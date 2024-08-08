<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One Page Website</title>
    <style>
        /* General page styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f7; /* Light background color */
        }

        /* Header styling */
        .header {
            background-color: #007bff; /* Header background color */
            color: white;
            padding: 120px 0;
            text-align: center;
            position: relative;
        }

        /* Header main text styling */
        .header h1 {
            font-size: 36px; /* Increased font size */
            margin: 0;
        }

        /* Header secondary text styling */
        .header p {
            font-size: 14px; /* Smaller font size for secondary text */
            margin: 5px 0 15px; /* Space below the secondary text */
        }

        /* Navigation menu styling within the header */
        .menu {
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }

        .menu button {
            background-color: #3399ff; /* Slightly lighter than header */
            border: none;
            padding: 14px 20px;
            margin: 5px;
            color: white;
            text-align: center;
            text-decoration: none;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .menu button:hover {
            background-color: #0056b3; /* Darker shade on hover */
        }

        /* Content section styling */
        .content {
            padding: 20px;
            text-align: center;
            color: #333;
            margin-top: 20px; /* Vertical space below the header */
        }

        /* Footer styling */
        .footer {
            background-color: #007bff;
            color: white;
            padding: 10px 0;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <div class="header">
        <h1>Structure in Prime Gaps - Formalized</h1>
        <h2>A formalization in LEAN 4</h2>
        <!-- Navigation Menu inside the Header -->
        <div class="menu">
            <button onclick="alert('Blueprint')">Blueprint</button>
            <button onclick="alert('Documentation')">Documentation</button>
            <button onclick="alert('Paper')">Paper</button>
            <button onclick="alert('View on GitHub')">View on GitHub</button>
        </div>
    </div>

    <!-- Content Section -->
    <div class="content">
        <h2>Welcome!</h2>
        <p>This is a simple one-page website with a horizontal menu.</p>
    </div>

    <!-- Footer Section -->
    <div class="footer">
        <p>© 2024 My One Page Website</p>
    </div>

</body>
</html>
