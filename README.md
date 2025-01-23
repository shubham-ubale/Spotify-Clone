# Spotify-Clone
# HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify - Web Player: Music for everyone</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="icon" href="./logo.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="project.css">

</head>
<body>
    <div class="main">
        <div class="sidebar">
            <div class="nav">
                <div class="nav-option" style="opacity: 1;">
                    <i class="fa-solid fa-house"></i>
                    <a href="#">Home</a>
                </div>
                <div class="nav-option">
                    <i class="fa-solid fa-magnifying-glass"></i>
                    <a href="#">Search</a>
                </div>
            </div>
            <div class="library">
                <div class="options">
                    <div class="lib-option nav-option">
                        <img src="library_icon.png">
                        <a href="#">Your Library</a>
                    </div>
                    <div class="icons">
                        <i class="fa-solid fa-plus"></i>
                        <i class="fa-solid fa-arrow-right"></i>    
                    </div>
                </div>
                <div class="lib-box">
                    <div class="box">
                        <p class="box-p1"> Create your first playlist</p>
                        <!-- <br> -->
                        <p class="box-p2"> It's easy, we'll help you</p>
                        <!-- <br> -->
                        <button class="badge">Create playlist</button>
                    </div>

                    <div class="box">
                        <p class="box-p1"> Let's find some podcast to follow</p>
                        <!-- <br> -->
                        <p class="box-p2"> We'll keep you updated on new episodes</p>
                        <!-- <br> -->
                        <button class="badge">Create playlist</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="main-content">
            <div class="sticky-nav">
                <div class="sticky-nav-icons">
                    <img src="backward_icon.png">
                    <img src="forward_icon.png" class="hide">
                </div>

                <div class="sticky-nav-options">
                <button class="badge nav-item hide">Explore Premium</button>
                <button class="badge nav-item dark-badge"><i class="fa-regular fa-circle-down" style="margin-right: 5px;"></i>Install App</button>
                <i class="fa-regular fa-user"></i>
                </div>
            </div>
            
            <h2>Recently played</h2>
            <div class="cards-container">
                <div class="card">
                     <img src="card1img.jpeg"  class="card-img">
                     <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily updates of the most played..</p>
                  </div>
            </div>

            <h2 class="trend">Trending now near you</h2>
            <div class="cards-container">
                <div class="card">
                     <img src="card2img.jpeg"  class="card-img">
                     <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily updates of the most played..</p>
                  </div>

                  <div class="card">
                    <img src="card3img.jpeg"  class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                   <p class="card-info">Your daily updates of the most played..</p>
                 </div>

                 <div class="card">
                    <img src="card4img.jpeg"  class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                   <p class="card-info">Your daily updates of the most played..</p>
                 </div>

                 <div class="card">
                    <img src="card3img.jpeg"  class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                   <p class="card-info">Your daily updates of the most played..</p>
                 </div>

                 <div class="card">
                    <img src="card4img.jpeg"  class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                   <p class="card-info">Your daily updates of the most played..</p>
                 </div>
            </div>

            <h2 class="trend">Featured Charts</h2>
            <div class="cards-container">
                <div class="card">
                     <img src="card1img.jpeg"  class="card-img">
                     <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily updates of the most played..</p>
                  </div>

                  <div class="card">
                    <img src="card5img.jpeg"  class="card-img">
                    <p class="card-title">Top Songs - India</p>
                   <p class="card-info">Your daily updates of the most played..</p>
                 </div>

                 <div class="card">
                    <img src="card6img.jpeg"  class="card-img">
                    <p class="card-title">Top Songs - Global</p>
                   <p class="card-info">Your daily updates of the most played..</p>
                 </div>
            </div>

            <div class="footer">
                <div class="line"></div>
            </div>
            
        </div>
        <div class="music-player">
            <div class="albums">
                <img src="card3img.jpeg" class="al" style="border-radius: 5px;">

                <div class="lines">
                 <p class="daylight" style="font-weight: 700; margin-bottom: 5px; width: 78px;">Daylight </p>
                 <p style=" font-size: 0.7rem; opacity: 0.7;">David Kushner</p>
                </div>
                <!-- <p1>Daylight </p1>
                <p2>David Kushner</p2> -->

                <i class="fa-regular fa-heart"></i>

            </div>
            <div class="player">
                <div class="player-controls">
                    <img src="player_icon1.png" alt="" class="player-control-icon">
                    <img src="player_icon2.png" alt="" class="player-control-icon">
                    <img src="player_icon3.png" alt="" class="player-control-icon" style="height: 1.5rem; width: 1.5rem; opacity: 1;">
                    <img src="player_icon4.png" alt="" class="player-control-icon">
                    <img src="player_icon5.png" alt="" class="player-control-icon">
                </div>
                <div class="playback-bar">
                    <span class="curr-time">00.00</span>
                    <input type="range" min="0" max="100" class="progress-bar" step="1">
                    <span class="tot-time">03.33</span>
                </div>
            </div>  
            <div class="controls">
                <i class="fa-regular fa-circle-play"></i>
                <i class="fa-solid fa-microphone"></i>
                <i class="fa-solid fa-list-ul"></i>
                <!-- <i class="fa-regular fa-speakers"></i> -->
                <i class="fa-thin fa-speakers"></i>
                <i class="fa-solid fa-volume-high" style="margin-left: -5px;"></i>
                <input type="range" min="0" max="100" class="progress-bar" step="1" style="width: 8rem;">
            </div>
        </div>
    </div>
</body>
</html>



# CSS

* {
  font-family: "Montserrat", sans-serif;
  margin: 0;
  /* background-color: #000; */
  color: #fff;
  overflow: hidden;
}

.main {
  display: flex;
  height: 100vh;
  background-color: #000;
  /* margin: 2px; */
  padding: 0.5rem;
}

.sidebar {
  background-color:#000;
  width: 340px;
  border-radius: 1rem;
  margin-right: 0.5rem;
}

.main-content {
  background-color: #121212;
  flex: 1;
  border-radius: 1rem;
  overflow: auto;
  padding: 0 1.5rem 0 1.5rem;
}

.music-player {
  background-color: #000;
  position: fixed;
  bottom: 0;
  width: 100%;
  height: 72px;
}

a {
  text-decoration: none;
  
}

.nav {
  background-color: #121212;
  border-radius: 1rem;
  display: flex;
  flex-direction: column;
  justify-content:center;
  height: 100px;
  padding: 0.5rem 0.75rem;
}

.nav-option {
  line-height: 2.5rem;
  opacity: 0.7;
  padding: 0.5rem 0.75rem;
}

.nav-option:hover {
  /* line-height: 2.5rem; */
  opacity: 1;
}

.nav-option i {
    font-size: 1.25rem;
}

.nav-option a {
  font-size: 1rem;
  margin-left: 1rem;
}

.library {
  background-color: #121212;
  border-radius: 1rem;
  height: 100%;
  margin-top: 0.5rem;
  padding: 0.5rem 0.75rem;
}

.options {
  display: flex;
  justify-content: space-between;
  align-items: center;
  
}

.lib-option img {
  height: 1.25rem;
  width: 1.25rem;
  
}

.icons{
  font-size: 1.25rem;
  display: flex;
}

.icons i {
  opacity: 0.7;
  margin-right: 1rem;
}

.icons i:hover{
  /* font-size: 1.25rem; */
  opacity: 1;
}

.box {
  height: 8rem;
  background-color: #232323;
  border-radius: 0.75rem;
  margin: 2rem 0 1.75rem 0;
  padding: 0.75rem 1rem;
}

.box-p1 {
  font-size: 1rem;
  font-weight: 500;
  /* line-height: 3.5; */
   
}

.box-p2 {
  font-size: 0.85rem;
  opacity: 0.9;
  line-height: 3.5;

}

.badge {
  background-color: #fff;
  color: #000;
  border: none;
  border-radius: 100px;
  padding: 0.25rem 1rem;
  font-weight: 600;
  margin-top: 0.5rem;
  height: 2rem;
  width: fit-content;
}

.dark-badge {
  background-color: #000;
  color: #fff;
}

.sticky-nav {
  position:sticky;
  top: 0;
  background-color: #121212;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 0 1rem 0;
  z-index: 10;
}

.sticky-nav-icons {
  margin-left: 0.75rem;
}

.sticky-nav-options {
  display: flex;
  justify-content: center;
  align-items: center;
}

.nav-item {
  margin-right: 1 rem;
}

@media (max-width:1000px) {
  .hide {
    display: none;
  }
}

.card {
  background-color: #232323;
  width: 150px;
  border-radius: 0.5rem;
  padding: 1rem;
  margin-top: 1rem;
  margin-left: 1.5rem;
}

.cards-container {
  display: flex;
  /* justify-content: space-evenly; */
  flex-wrap: wrap;
}

.card-img {
  width: 100%;
  border-radius: 0.5rem;
}

.card-title {
  font-weight: 600;
  margin-top: 10px;
}

.card-info {
  font-size: 0.8rem;
  opacity: 0.5;
  padding: 10px 0 0 0;
}

.trend {
  margin-top: 1rem;
}

.footer {
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.line {
  width: 90%;
  height: 50%;
  border-top: 1px solid white;
  opacity: 0.4;
}

.music-player {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.albums {
  background-color: #000  ;
  width: 25%;
  display: flex;
  /* justify-content: space-aroun d; */
  align-items: center;
  margin-left: 5px;
  /* padding: ; */
}

.albums i {
  margin-left: 1rem;
  /* border-radius: 3rem; */
}

.lines {
  margin-left: 1rem;
  margin-right: 1rem;
}

.player {
  background-color: #000;
  width: 50%;
}

.controls {
  background-color: #000;
  width: 25%;
  display: flex;
  /* margin: 0 3rem 0 1rem; */
  /* justify-content: space-between; */
}

.controls i {
  display: flex;
  justify-content: space-between;
  margin: 0 0.5rem 0 0.5rem;
}

.al{
  height: 3.8rem;
  width: 3.80rem;
}

.player-control-icon {
  height: 1rem;
  width: 1rem;
  margin-right: 1rem;
  opacity: 0.7;
}

.player-controls {
  display: flex;
  justify-content: center;
  align-items: center;
}

.player-control-icon:hover {
  opacity: 1;
}

.playback-bar {
  display: flex;
  justify-content: center;
  align-items: center;
}

.progress-bar {
  width: 70%;
  appearance: none;
  background-color: transparent;
  cursor: pointer;
}

.progress-bar::-webkit-slider-runnable-track {
  background-color: #ddd;
  border-radius: 100px;
  height: 0.2rem;
}

.progress-bar::-webkit-slider-thumb {
  appearance: none;
  background-color: #17e763 ;
  height: 1rem;
  width: 1rem;
  border-radius: 50%;
  margin-top: -6px;
  font-weight: 700;
  opacity: 2;
}
