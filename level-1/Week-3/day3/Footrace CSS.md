```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foot Race Signup</title>
    <style>
        body {
            font-family: Arial, sans-serif; /* Sets the font for the page */
            margin: 20px; /* Adds margin around the body content */
        }

        .container {
            width: 100%; /* Full width */
            max-width: 600px; /* Maximum width */
            margin: auto; /* Centers the container */
            padding: 20px; /* Padding inside the container */
            box-shadow: 0 0 10px rgba(0,0,0,0.1); /* Shadow around the container */
        }

        h2 {
            text-align: center; /* Centers the heading */
            margin-bottom: 20px; /* Space below the heading */
        }

        label {
            display: block; /* Makes the label take up the full width */
            margin-bottom: 5px; /* Space below each label */
        }

        input[type="text"],
        input[type="email"],
        input[type="number"],
        select {
            width: 100%; /* Makes the input fields take up 100% of their container's width */
            padding: 10px; /* Padding inside the input fields */
            margin-bottom: 20px; /* Space below each input field */
            box-sizing: border-box; /* Includes padding and border in the element's width and height */
        }

        .form-check {
            margin-bottom: 10px; /* Space below each radio button */
        }

        button {
            width: 100%; /* Makes the button take up the full width */
            padding: 10px; /* Padding inside the button */
            background-color: #007bff; /* Background color */
            color: white; /* Text color */
            border: none; /* No border */
            cursor: pointer; /* Pointer cursor on hover */
        }

        button:hover {
            background-color: #0056b3; /* Darker background on hover */
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Foot Race Signup Form</h2>
        <form>
            <label for="fullName">Full Name</label>
            <input type="text" id="fullName" required placeholder="Enter your full name">

            <label for="email">Email Address</label>
            <input type="email" id="email" required placeholder="Enter your email">

            <label for="age">Age</label>
            <input type="number" id="age" required placeholder="Enter your age">

            <label for="gender">Gender</label>
            <select id="gender" required>
                <option selected disabled>Choose...</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>

            <div class="form-check">
                <input class="form-check-input" type="radio" name="tshirtSize" id="small" value="small" required>
                <label class="form-check-label" for="small">Small</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="tshirtSize" id="medium" value="medium">
                <label class="form-check-label" for="medium">Medium</label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="tshirtSize" id="large" value="large">
                <label class="form-check-label" for="large">Large</label>
            </div>

            <button type="submit">Sign Up</button>
        </form>
    </div>
</body>
</html>

```