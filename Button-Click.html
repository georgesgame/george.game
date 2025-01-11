<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button Click</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            margin: 0;
            background-color: #f0f0f0;
        }
        .button {
            position: absolute;
            padding: 20px 40px;
            font-size: 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }
        #score {
            font-size: 24px;
            font-weight: bold;
            margin-top: 20px;
        }
        #points-bar {
            width: 100%;
            background-color: #ddd;
        }
        #points {
            height: 30px;
            width: 0;
            background-color: #4CAF50;
        }
    </style>
</head>
<body>

<h1>Click the Button to Earn Points!</h1>

<div id="score">Score: 0</div>
<div id="points-bar">
    <div id="points"></div>
</div>

<button class="button" id="gameButton" onclick="buttonClicked()">Click me!</button>

<script>
    let score = 0;
    let gameButton = document.getElementById("gameButton");
    let scoreDisplay = document.getElementById("score");
    let pointsBar = document.getElementById("points");
    let inactivityTimer; // Timer for the 3-second inactivity period
    let redButtonTimer; // Timer for the 3-second waiting period for the red button to turn green
    let isRedButton = false; // To track if the button is red
    let waitingForGreen = false; // To track if we are in the waiting period for the red button to turn green

    // Function to handle button click
    function buttonClicked() {
        if (isRedButton) {
            if (waitingForGreen) {
                // If it's red and still in the waiting period, do nothing
                console.log("Wait for the button to turn green!");
                return;
            } else {
                // If it's red and clicked after it has turned green, increment score
                score += 10;
                scoreDisplay.innerText = "Score: " + score;
                updatePointsBar();
                moveButton(); // Move the button
                resetTimer(); // Reset the inactivity timer
            }
        } else {
            // If it's the "Click Me!" button (green), increment the score
            score += 10;
            scoreDisplay.innerText = "Score: " + score;
            updatePointsBar();
            moveButton();
            resetTimer(); // Reset the inactivity timer
        }
    }

    // Function to move the button to a random position
    function moveButton() {
        let x = Math.random() * (window.innerWidth - 100); // Width of the button
        let y = Math.random() * (window.innerHeight - 100); // Height of the button
        gameButton.style.left = x + "px";
        gameButton.style.top = y + "px";

        // Randomly decide whether the button should be red (25% chance)
        maybeTurnRed();
    }

    // Function to update the points bar based on score
    function updatePointsBar() {
        let percentage = (score / 1000) * 100; // Max score of 1000
        pointsBar.style.width = "100%";
        points.style.width = percentage + "%";
    }

    // Function to reset the inactivity timer (3 seconds countdown)
    function resetTimer() {
        clearTimeout(inactivityTimer); // Clear any existing timers
        inactivityTimer = setTimeout(handleInactivity, 3000); // Check for inactivity after 3 seconds
    }

    // Function to handle inactivity (3 seconds with no click)
    function handleInactivity() {
        // Reset the score after 3 seconds of inactivity
        score = 0;
        scoreDisplay.innerText = "Score: " + score;
        updatePointsBar();
        moveButton(); // Move the button after losing points
        resetTimer(); // Reset inactivity timer after losing points
    }

    // Function to potentially turn the button red with a 25% chance
    function maybeTurnRed() {
        if (Math.random() < 0.25) { // 25% chance
            isRedButton = true;
            waitingForGreen = true;
            gameButton.textContent = "Wait for 3 seconds!";
            gameButton.style.backgroundColor = "red"; // Change color to red

            // Start the timer to wait 3 seconds for it to become green
            redButtonTimer = setTimeout(turnGreen, 3000);
        } else {
            isRedButton = false;
            waitingForGreen = false;
            gameButton.textContent = "Click me!";
            gameButton.style.backgroundColor = "#4CAF50"; // Green color
        }
    }

    // Function to turn the button green after 3 seconds
    function turnGreen() {
        waitingForGreen = false;
        gameButton.textContent = "Click me!";
        gameButton.style.backgroundColor = "#4CAF50"; // Green color
        resetTimer(); // Reset inactivity timer
    }

    // Initialize button position and start the inactivity timer
    moveButton(); // Spawn the first button with a random position and color
    resetTimer(); // Start the inactivity timer

</script>

</body>
</html>
