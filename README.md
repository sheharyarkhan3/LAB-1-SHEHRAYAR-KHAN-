# LAB-1-SHEHRAYAR-KHAN-

@import url('https://fonts.googleapis.com/css2?family=Ubuntu&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Varela+Round&display=swap');
body{
    background-color: #3C3837;
}

*{
    margin: 0;
    padding: 0;
}

nav{
    font-family: 'Ubuntu', sans-serif;
}

nav ul{
    display: flex;
    align-items: center;
    list-style-type: none;
    height: 65px;
    background-color: black;
    color: white;
}

nav ul li{
    padding: 0 12px;
}
.brand img{
    width: 44px;
    padding: 0 8px;
}

.brand {
    display: flex;
    align-items: center;
    font-weight: bolder;
    font-size: 1.3rem;
}

.container{
    min-height: 72vh;
    background-color: black;
    color: white;
   font-family: 'Varela Round', sans-serif;
   display: flex;
   margin: 23px auto;
   width: 85%;
   border-radius: 12px;
   padding: 34px;
   background-image: url('bg.jpg');
}

.bottom{
    position: sticky;
    bottom: 0;
    height: 100px;
    background-color: black;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column; 
}

.icons{
    margin-top: 14px;
    display: flex;
    justify-content: flex-start 
}
.icons i{
    cursor: pointer;
}

#myProgressBar{
    width: 80vw; 
    cursor: pointer;
}

.songItemContainer{
    margin-top: 74px;
}

.songItem{
    height: 50px;
    display: flex;
    background-color: white;
    
    color: black;
    margin: 12px 0;
    justify-content: space-between;
    align-items: center;
    border-radius: 34px;
}

.songItem img{
    width: 43px;
    margin: 0 23px;
    border-radius: 34px;
}

.timestamp{
    margin: 0 23px;
}

.timestamp i{
    cursor: pointer;
}

.songInfo{
    position: absolute;
    left: 10vw;
    font-family: 'Varela Round', sans-serif;
}

.songInfo img{
    opacity: 0;
    transition: opacity 0.4s ease-in;
}

@media only screen and (max-width: 1100px) {
    body {
      background-color: red;
    }
  }

/* Search bar */
#searchBar {
    width: 100%;
    padding: 10px;
    margin: 20px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
    font-size: 16px;
}

#volumeSlider {
    width: 200px;
    margin-left: 900px;
    background-color: white; /* Added this line */

    }
/*Comment section*/

.commentsSection {
    margin-top: 20px;
}

#commentInput {
    width: 100%;
    height: 60px;
    margin-bottom: 10px;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
    font-size: 16px;
}

#addComment {
    display: inline-block;
    padding: 10px 20px;
    margin-bottom: 20px;
    border: none;
    border-radius: 5px;
    background-color: #1DB954;
    color: white;
    cursor: pointer;
}

