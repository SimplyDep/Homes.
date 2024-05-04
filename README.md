<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roblox Homepage</title>
    <style>
        body {
            background-color: #2a2a3e; /* Dark grey with a hint of purple */
            color: #ffffff; /* White text color */
            font-family: Arial, sans-serif;
        }
        #header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }
        #logo {
            font-size: 24px;
            font-weight: bold;
        }
        #profile {
            display: flex;
            align-items: center;
        }
        #profile img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 10px;
        }
        #simplybucks {
            margin-right: 10px;
        }
        #friends {
            margin-top: 20px;
        }
        #games {
            margin-top: 20px;
        }
        .category {
            margin-bottom: 20px;
        }
        .category-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .game-image {
            width: 100px;
            height: 100px;
            background-color: #4b4b4b; /* Dark grey for game images */
            margin-right: 10px;
            margin-bottom: 10px;
            display: inline-block;
        }
        .friend-icon {
            width: 50px;
            height: 50px;
            background-color: #8a8a8a; /* Light grey for friend icons */
            border-radius: 50%;
            margin-right: 10px;
            display: inline-block;
        }
        #important {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div id="header">
        <div id="logo">Simplyland</div>
        <div id="profile">
            <span id="simplybucks">SimplyBucks: 0</span>
            <img src="profile-picture.jpg" alt="Profile Picture">
        </div>
    </div>

    <div id="friends" class="category">
        <div class="category-title">Friends</div>
        <div class="friend-icon"></div>
        <div class="friend-icon"></div>
        <div class="friend-icon"></div>
        <!-- Add more friend icons as needed -->
    </div>

    <div id="games" class="category">
        <div class="category-title">Games</div>
        <div class="game-image"></div>
        <div class="game-image"></div>
        <div class="game-image"></div>
        <!-- Add more game images as needed -->
    </div>

    <div id="important">
        <p>©2024 Simplyland Corporation</p>
    </div>
</body>
</html>
