<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Complaint Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            padding: 20px;
        }
        .form-container {
            background-color: white;
            max-width: 500px;
            margin: auto;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px #ccc;
        }
        input, textarea, select {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            margin-bottom: 20px;
            border: 1px solid #a27676;
            border-radius: 5px;
        }
        label {
            font-weight: bold;
        }
        button {
            background-color: #0be9c7;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0277bd;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2>Complaint Registration Form</h2>
        <form action="#" method="post">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone">

            <label for="type">Complaint Type:</label>
            <select id="type" name="type" required>
                <option value="">--Select--</option>
                <option value="service">Service</option>
                <option value="product">Product</option>
                <option value="staff">Staff Behavior</option>
                <option value="other">Other</option>
            </select>

            <label for="message">Complaint Details:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Submit Complaint</button>
        </form>
    </div>
</body>
</html>
