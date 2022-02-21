<template>
  <div>
    <body>
      <TheHeader />
      <!-- video-lightbox -->
      <div id="lightbox">
        <div class="box">
          <div class="topbar">
            <button id="hide_video">Close</button>
          </div>
          <div id="wrapper">
            <div id="ytplayer"></div>
          </div>
        </div>
      </div>

      <main>
        <!-- Editor's Pick -->
        <h2>Editor's Pick</h2>
        <div class="container-1">
          <img
            class="show_video poster"
            data-video-id="JfVOs4VSpmA"
            alt="click to see video"
            src="https://img.youtube.com/vi/JfVOs4VSpmA/mqdefault.jpg"
          />
          <div class="container-1-txt">
            <h3>Spider-Man: No Way Home</h3>
            <p>Film descriptions Lorem ipsum dolor sit amet</p>
          </div>
        </div>

        <div class="container-1">
          <img
            class="show_video poster"
            data-video-id="TJFVV2L8GKs"
            alt="click to see video"
            src="https://img.youtube.com/vi/TJFVV2L8GKs/mqdefault.jpg"
          />
          <div class="container-1-txt">
            <h3>The Witcher</h3>
            <p>Film descriptions Lorem ipsum dolor sit amet.</p>
          </div>
        </div>

        <div class="container-1">
          <img
            class="show_video poster"
            data-video-id="E3Huy2cdih0"
            alt="click to see video"
            src="https://img.youtube.com/vi/E3Huy2cdih0/mqdefault.jpg"
          />
          <div class="container-1-txt">
            <h3>Elden Ring</h3>
            <p>Film descriptions Lorem ipsum dolor sit amet.</p>
          </div>
        </div>

        <div class="container-1">
          <img
            src="~/static/8cec4dbb2e0faa8ff7f26279023bbaaa-250h.jpg"
            alt="film-poster"
            height="100px"
            width="100"
            class="poster"
          />
          <div class="container-1-txt">
            <h3>Film Title</h3>
            <p>Film descriptions Lorem ipsum dolor sit amet.</p>
          </div>
        </div>

        <!-- New and Notable -->
        <h2>New And Notable</h2>
        <nav class="nav-notable">
          <a href="#GAMES">Game</a>
          <a href="#MOVIES">Movies</a>
          <a href="#TELEVISION">Television</a>
          <a href="#MUSICS">Musics</a>
        </nav>
        <div class="scroll-h">
          <img
            src="~/static/8f095626844483d6c09f87bf7b9cf0bf-250h.jpg"
            alt="film-poster"
          />
          <img
            src="~/static/8f095626844483d6c09f87bf7b9cf0bf-250h.jpg"
            alt="film-poster"
          />
          <img
            src="~/static/8f095626844483d6c09f87bf7b9cf0bf-250h.jpg"
            alt="film-poster"
          />
          <img
            src="~/static/8f095626844483d6c09f87bf7b9cf0bf-250h.jpg"
            alt="film-poster"
          />
          <img
            src="~/static/8f095626844483d6c09f87bf7b9cf0bf-250h.jpg"
            alt="film-poster"
          />
        </div>

        <section class="flexbox-big-container">
          <section class="row-wrap1">
            <!-- Game Review Score -->
            <section class="gameScore">
              <h2>Games Review Score</h2>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>Game Title</h3>
                  <p>Release date</p>
                </div>
                <div class="green-score"><p>90</p></div>
              </div>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>Game Title</h3>
                  <p>Release date</p>
                </div>
                <div class="yellow-score"><p>55</p></div>
              </div>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>Game Title</h3>
                  <p>Release date</p>
                </div>
                <div class="red-score"><p>15</p></div>
              </div>
              <div class="button-view">
                <button class="blackButton" type="button">View More</button>
              </div>
            </section>

            <!-- Movies Review Score -->
            <section class="movieScore">
              <h2>Movies Review Score</h2>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>Movie Title</h3>
                  <p>Release date</p>
                </div>
                <div class="green-score"><p>90</p></div>
              </div>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>Movie Title</h3>
                  <p>Release date</p>
                </div>
                <div class="yellow-score"><p>55</p></div>
              </div>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>Movie Title</h3>
                  <p>Release date</p>
                </div>
                <div class="red-score"><p>15</p></div>
              </div>
              <div class="button-view">
                <button class="blackButton" type="button">View More</button>
              </div>
            </section>
          </section>

          <section class="row-wrap2">
            <!-- TV Show Score Review -->
            <section class="tvScore">
              <h2>TV Show Review Score</h2>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>TV Show Title</h3>
                  <p>Release date</p>
                </div>
                <div class="green-score"><p>90</p></div>
              </div>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>TV Show Title</h3>
                  <p>Release date</p>
                </div>
                <div class="yellow-score"><p>55</p></div>
              </div>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>TV Show Title</h3>
                  <p>Release date</p>
                </div>
                <div class="red-score"><p>15</p></div>
              </div>
              <div class="button-view">
                <button class="blackButton" type="button">View More</button>
              </div>
            </section>

            <!-- Music Score Review -->
            <section class="musicScore">
              <h2>Music Review Score</h2>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>Music Title</h3>
                  <p>Artist | Release date</p>
                </div>
                <div class="green-score"><p>90</p></div>
              </div>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>Music Title</h3>
                  <p>Artist | Release date</p>
                </div>
                <div class="yellow-score"><p>55</p></div>
              </div>

              <div class="flexbox-container-2">
                <div class="item">
                  <h3>Music Title</h3>
                  <p>Artist | Release date</p>
                </div>
                <div class="red-score"><p>15</p></div>
              </div>
              <div class="button-view">
                <button class="blackButton" type="button">View More</button>
              </div>
            </section>
          </section>
        </section>
      </main>
      <TheFooter />
    </body>
  </div>
</template>

<script>
import TheHeader from '~/components/TheHeader.vue'
import TheFooter from '~/components/TheFooter.vue'
export default {
  name: 'IndexPage',
  components: { TheHeader, TheFooter },
}
</script>

<style lang="scss">
@font-face {
    font-family: 'Proxima Nova';
    src: local('Proxima Nova'),
    url(~assets/Proxima/ProximaNova-Regular.otf) format("truetype");
    }

html {
    font-family: 'Proxima Nova';
}

body {
  background-color: #fff;
  font-family: 'Proxima Nova';
  margin: 0;
  padding: 0;
}

h1 {
  width: 180px;
  font-size: 22px;
  padding-left: 5px;
}

h2 {
  text-decoration: underline 2px;
  margin-left: 15px;
}

h3 {
  height: 10px;
  margin-top: 0;
}

.container-1 {
  display: flex;
  margin-bottom: 25px;
  margin-left: 10px;
}

.container-1-txt {
  display: flex;
  flex-direction: column;
  margin-left: 5px;
}

.container-1-txt > p {
  color: #333333;
  padding-top: 30px;
}

.poster {
  border-radius: 10px;
  width: 100px;
}

.scroll-h {
  display: flex;
  width: 100%;
  overflow-x: auto;
}
.scroll-h > img {
  margin: 10px;
  border-radius: 10px;
}

.nav-notable {
  display: flex;
  justify-content: space-around;
}

.nav-notable > a {
  text-decoration: none;
  color: #0047ff;
}

.green-score {
  background-color: #48b80f;
  color: #fff;
  height: 50px;
  width: 50px;
  border-radius: 10px;
  text-align: center;
  margin-right: 15px;
}

.yellow-score {
  background-color: #ffb300;
  color: #fff;
  height: 50px;
  width: 50px;
  border-radius: 10px;
  text-align: center;
  margin-right: 15px;
}

.red-score {
  background-color: #ff2929;
  color: #fff;
  height: 50px;
  width: 50px;
  border-radius: 10px;
  text-align: center;
  margin-right: 15px;
}

.flexbox-container-2 {
  display: flex;
  flex-direction: row;
}

.item {
  flex-direction: column;
  /* width: 280px; */
  width: 80%;
  margin-left: 15px;
}

.item > p {
  font-size: 15px;
  color: #333333;
}

.blackButton {
  background-color: #111;
  color: #fff;
  border-color: #111;
  border-radius: 8px;
  width: 80%;
  height: 45px;
  text-transform: capitalize;
  font-size: large;
}

.button-view {
  display: flex;
  justify-content: center;
}

#lightbox {
  display: none;
  align-items: center;
  justify-content: center;
  position: fixed;
  background: #0007;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 10;
}

#hide_video {
  display: inline-block;
  border-radius: 4px;
  background-color: #ffffff;
  border: none;
  color: #000;
  text-align: center;
  font-size: 20px;
  padding: 0 10px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}

.topbar {
  display: flex;
  justify-content: flex-end;
  width: 100%;
  height: 50px;
}

.box {
  position: relative;
  padding: 10px;
  background: #000;
  border-radius: 10px;
  width: 60%;
}

#wrapper {
  position: relative;
  padding-bottom: 56.25%; /* 16:9 */
  padding-top: 25px;
  height: 0;
}

#wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.videos {
  display: flex;
  flex-direction: row;
}

@media screen and (min-width: 800px) {
  main {
    margin-left: 20%;
    margin-right: 20%;
  }

  .flexbox-big-container {
    display: flex;
    flex-direction: column;
  }

  .row-wrap1 {
    display: flex;
    flex-direction: row;
    justify-content: center;
    justify-content: space-evenly;
  }

  .row-wrap2 {
    display: flex;
    flex-direction: row;
    justify-content: center;
    justify-content: space-evenly;
  }

  .musicScore,
  .tvScore,
  .movieScore,
  .gameScore {
    width: 50%;
  }

  .container-1 {
    width: 100%;
    img {
      width: 180px;
      height: 180px;
      margin-right: 10%;
    }
  }

  .searchbar {
    display: flex;
    background-color: #111;
    border: 1px solid;
    border-radius: 5px;
    border-color: #fff;
    width: 300px;
    margin-right: 5px;
    color: #fff;
    font-weight: bold;
    opacity: 1;
  }
}
</style>
