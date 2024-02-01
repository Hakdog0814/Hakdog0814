<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Valentine's Proposal</title>
</head>

<body>
    <div class="container">
        <div class="Mainprompt">
            <img class="image" src="c:\Users\Nicole Gotengco\Documents\html\catflower.jpg"></img>
            <h1 class="hh" id="name">Hey beautiful!</h1>
            <p class="pp" id="question">Will you be my Valentine?</p>
            <div class="buttons">
                <button id="no-button" onclick="showMessage('No')">No</button>
                <button onclick="showMessage('Yes')" id="yesButton">Yes</button>
            </div>
            <div class="hidden-message" id="no-message">
                <p>Nice try, but you can't escape that easily!</p>
            </div>
            <div class="hidden-message" id="yes-message">
                <p>YAY! See you on the 14th, babygirl.</p>
            </div>
        </div>
    </div>
    <script src="script.js"></script>
</body>

</html>
