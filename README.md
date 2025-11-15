# form.html
html css code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>formm</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #92bde2;
        
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            text-decoration: aqua double underline;
            animation: MYMOVE 3s infinite alternate;
    

        }
            @keyframes MYMOVE {
                from {color: #ee8b39;}
                to {color: #246161;}
            }
           
        
        form {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        input[type="text"],
        input[type="email"],
        input[type="password"] {
            width: calc(100% - 20px);
            padding: 10px;
            margin-bottom: 15px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1> Welcome to TIYA </h1>
    <form action="tiya.html">
        <div class="ab">
        <br>
        <label for="name">Name:</label>
        <input type="text" name="name" placeholder="Enter your name" required>
        <br>
        <br>
        <label for="email">Email:</label>
        <input type="email" name="email" placeholder="Enter your email" required>
        <br><br>
        <label for="password">Password:</label>
        <input type="password" name="password" placeholder="Enter your password" required>
        <br><br>
        <label for="address">Address:</label>
        <input type="text" name="address" placeholder="Enter  address" required>
        <br><br>
        <label for="phone">Phone Number:</label>
        <input type="text" name="phone" placeholder="Enter your phone number" required>
        <br><br>
        <input type="submit" value="Submit">
        </div>

            


    </form>
</body>
</html>
