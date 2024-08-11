<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback Form</title>
    <style>
          body {
            font-family: Arial, sans-serif;
            background-image: url('https://www.transparenttextures.com/patterns/white-diamond.png');
    /* Subtle diamond texture */
    background-color: #b296ef; /* Light pastel pink background */
    background-repeat: repeat;
    color: #1d1352; 
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }


        .feedback-container {
            background-color: #00ffcc;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 10px 15px rgba(0, 0, 0.1, 1);
            width: 80%;
        }

        h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 96%;
            padding: 1%;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 3px;
        }

        button {
            width: 96%;
            padding: 10px;
            background-color: #4609be;
            color: white;
            border: none;
            border-radius: 3px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #30075c;
           
        }
        

        #responseMessage {
            margin-top: 15px;
            text-align: center;
            color: #4200d0;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="feedback-container">
        <h2>Send Message to Us</h2>
        <form id="feedbackForm" action="https://api.web3forms.com/submit" method="POST">
            <input type="hidden" name="access_key" value="e67a582a-29ba-4180-a6ed-41d174937780">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="feedback">Message:</label>
            <textarea id="feedback" name="feedback" rows="4" required></textarea>

            <button type="submit">Submit</button>
        </form>
        <div id="responseMessage"></div>
    </div>

</body>
</html>
