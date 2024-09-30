# FOOD-ARM
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Arm</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #ff6347;
            color: white;
            padding: 20px;
            text-align: center;
        }
        main {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin: 10px 0 5px;
        }
        input {
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            padding: 10px;
            background-color: #ff6347;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff4500;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            padding: 10px;
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>
    <header>
        <h1>Food Arm</h1>
        <p>Your gateway to delicious meals!</p>
    </header>

    <main>
        <h2>Login</h2>
        <form action="#" method="post">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <button type="submit">Login</button>
        </form>
    </main>

    <footer>
        <p>&copy; 2024 Food Arm. All rights reserved.</p>
    </footer>
</body>
</html>
