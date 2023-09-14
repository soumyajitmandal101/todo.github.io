# todo.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMDB Clone</title>
    <link rel="stylesheet" href="imdb.css">
</head>
<body>
    <!-- navigation bar which containes home-button, search-box and goto-favourites-button -->
    <header id="navigation-bar">

        <!-- home-button which redirect user to home page -->
        <button id="home-button" class="text-icon-button">
            <img src="./res/home-icon.png">
            <span>Home</span>
        </button>

        <!-- search box -->
        <input type="text" id="search-box">

        <!-- goto-favourites-button redirect user to the favourites movie page -->
        <button id="goto-favourites-button" class="text-icon-button">
            <img src="./res/favourites-folder.png">
            <span>favourite Movies</span>
        </button>

    </header>


    <main id="movie-card-container">

        <!-- movie card -->
<!-- 
        
        <div class="movie-card" id="">
            <img src="./res/the-marcian-movie-poster.jpg" alt="movie poster" class="movie-poster">
            <div class="movie-title-container">
                <span>The Martian</span>
                <div class="rating-container">
                    <img src="./res/rating-icon.png" alt="">
                    <span>8.1</span>
                </div>
            </div>
            <button class="add-to-favourite-button text-icon-button" data-id="" onclick="">
                <img src="./res/favourites-icon.png">
                <span>Make favourite</span>
            </button>
        </div>
     -->



    </main>

    <script src="imdb.js"></script>
</body>
</html>
