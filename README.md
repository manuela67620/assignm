/* Global Styling */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f0f2f5; /* Light gray background */
    color: #333; /* Dark text color for readability */
}

/* Header Styling */
header {
    background-color: #007bff; /* Primary blue */
    color: #fff;
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

header h1 {
    margin: 0;
    font-size: 2.5em;
    font-weight: 700;
}

header h2 {
    margin: 5px 0 0;
    font-size: 1.5em;
    font-weight: 400;
}

/* Link Styling */
a {
    color: #007bff; /* Primary blue */
    text-decoration: none;
    transition: color 0.3s ease;
}

a:hover {
    text-decoration: underline;
    color: #0056b3; /* Darker blue on hover */
}

/* Paragraph Styling */
p {
    margin: 15px 0;
    padding: 0 15px;
    font-size: 1em;
}

/* Form Styling */
form {
    max-width: 600px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff; /* White background */
    border-radius: 8px; /* Rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

label {
    display: block;
    margin: 10px 0 5px;
    font-weight: 600;
}

input[type="text"], input[type="email"] {
    width: calc(100% - 22px); /* Full width minus padding */
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    margin-bottom: 10px; /* Space below inputs */
}

button {
    padding: 10px 20px;
    background-color: #007bff; /* Primary blue */
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1em;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #0056b3; /* Darker blue */
}

/* Table Styling */
table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    background-color: #fff; /* White background for table */
    border-radius: 8px; /* Rounded corners */
    overflow: hidden; /* To clip the corners */
}

th, td {
    padding: 15px;
    text-align: left;
    border-bottom: 1px solid #ddd; /* Light gray border */
}

thead {
    background-color: #007bff; /* Primary blue */
    color: #fff;
}

tfoot {
    background-color: #f9f9f9; /* Light gray for footer */
    font-weight: 600;
}

/* Image Styling */
.container {
    text-align: center;
    margin: 20px 0;
}

.container img {
    max-width: 100%;
    height: auto;
    border-radius: 8px; /* Rounded corners */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

/* Text Section Styling */
.text {
    max-width: 600px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff; /* White background */
    border-radius: 8px; /* Rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.text h2 {
    margin-top: 0;
    font-size: 1.8em;
    font-weight: 700;
}

.text p {
    font-size: 1em;
    color: #555; /* Slightly lighter text color */
}
