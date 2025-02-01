<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QUIZ 1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="main">
        <button class="show-btn">Show All Tasks</button>
        <div class="search">
            <input class="search-area" type="text" placeholder="Search User ID">
            <input class="search-btn" type="submit" value="Search">
        </div>
        <div class="task-container" style="display: none;">
            <h1 class="task-title"></h1>
            <h3 id="user-id"></h3>
            <h3 class="status"></h3>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
