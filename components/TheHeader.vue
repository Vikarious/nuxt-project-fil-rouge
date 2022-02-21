<template lang="">
  <div>
    <header>
      <div class="logo-title">
        <nuxt-img src="~assets/logoR&C.png" alt="logo-R&C" height="50px" />
        <h1>Review&Critic</h1>
      </div>
      <div class="search-signup">
        <form action="/form/submit" method="GET">
          <input
            type="text"
            maxlength="20"
            class="searchbar"
            placeholder="Search here..."
          />
          <!-- <input type="submit" name="submit" class="submit" value="Search"> -->
        </form>
        <nuxt-img
          class="search-button"
          src="~/assets/img/buttons/seachButton.png"
          alt="search-button"
          height="20px"
        />
        <button class="sign-in" type="button">Sign In</button>
      </div>
    </header>

    <!-- dropdown menu -->
    <nav class="top-nav">
      <ul>
        <li class="nav-items nav-item-dropdown">
          <a class="dropdown-trigger" href="#GAMES">GAMES</a>
          <ul class="dropdown-menu">
            <li class="dropdown-menu-items"><a href="#">>Game Home<</a></li>
            <li class="dropdown-menu-items"><a href="#">New Releases</a></li>
            <li class="dropdown-menu-items"><a href="#">Coming Soon</a></li>
            <p>Best...</p>
            <li class="dropdown-menu-items"><a href="#">Games This Year</a></li>
            <li class="dropdown-menu-items">
              <a href="#">Games of All Time</a>
            </li>
            <li class="dropdown-menu-items"><a href="#">Games by Genre</a></li>
            <li class="dropdown-menu-items"><a href="#">New Games</a></li>
            <p>
              Platforms: <a href="#">PS5</a> <a href="#">XBOX</a>
              <a href="#">SWITCH</a>
            </p>
          </ul>
        </li>

        <li class="nav-items nav-item-dropdown">
          <a class="dropdown-trigger" href="#MOVIES">MOVIES</a>
          <ul class="dropdown-menu">
            <li class="dropdown-menu-items"><a href="#">>Movie Home<</a></li>
            <li class="dropdown-menu-items"><a href="#">In Theaters</a></li>
            <li class="dropdown-menu-items"><a href="#">Coming Soon</a></li>
            <p>Best...</p>
            <li class="dropdown-menu-items"><a href="#">Movie This Year</a></li>
            <li class="dropdown-menu-items">
              <a href="#">Movie of All Time</a>
            </li>
            <li class="dropdown-menu-items"><a href="#">Movie by Genre</a></li>
            <li class="dropdown-menu-items">
              <a href="#">Film Awards & Nominations</a>
            </li>
            <p>
              Streaming: <a href="#">Nextflix</a> <a href="#">Amazon</a>
              <a href="#">Hulu</a>
            </p>
          </ul>
        </li>

        <li class="nav-items nav-item-dropdown">
          <a class="dropdown-trigger" href="#TELEVISION">TELEVISION</a>
          <ul class="right-dropdown-menu">
            <li class="dropdown-menu-items"><a href="#">>TV Home<</a></li>
            <li class="dropdown-menu-items"><a href="#">TV Calendar</a></li>
            <li class="dropdown-menu-items"><a href="#">Coming Soon</a></li>
            <p>Best...</p>
            <li class="dropdown-menu-items">
              <a href="#">TV Show This Year</a>
            </li>
            <li class="dropdown-menu-items">
              <a href="#">TV Show of All Time</a>
            </li>
            <li class="dropdown-menu-items">
              <a href="#">TV Show by Genre</a>
            </li>
            <li class="dropdown-menu-items"><a href="#">New TV Show</a></li>
            <p>
              Streaming: <a href="#">Nextflix</a> <a href="#">Amazon</a>
              <a href="#">Hulu</a>
            </p>
          </ul>
        </li>

        <li class="nav-items nav-item-dropdown">
          <a class="dropdown-trigger" href="#MUSICS">MUSICS</a>
          <ul class="right-dropdown-menu">
            <li class="dropdown-menu-items"><a href="#">>Music Home<</a></li>
            <li class="dropdown-menu-items"><a href="#">New Releases</a></li>
            <li class="dropdown-menu-items"><a href="#">Coming Soon</a></li>
            <p>Best...</p>
            <li class="dropdown-menu-items">
              <a href="#">Albums This Year</a>
            </li>
            <li class="dropdown-menu-items">
              <a href="#">Albums of All Time</a>
            </li>
            <li class="dropdown-menu-items"><a href="#">Albums by Genre</a></li>
            <li class="dropdown-menu-items"><a href="#">New Albums</a></li>
          </ul>
        </li>
      </ul>
    </nav>
  </div>
</template>
<script>
export default {}
</script>
<style lang="scss">
header {
  height: 70px;
  display: flex;
  background-color: #111;
  color: #fff;
  align-items: center;
  justify-content: space-between;
}

.logo-title {
  display: flex;
  margin-left: 4px;
}

.search-signup {
  display: flex;
  margin-right: 4px;
  align-items: center;
}

.searchbar {
  display: none;
}

.search-button {
  padding-right: 0px;
}

.sign-in {
  background-color: #111;
  color: #fff;
  border: 1px solid;
  border-radius: 5px;
  border-color: #fff;
  font-size: large;
  width: 90px;
  height: 30px;
  margin-left: 10px;
  margin-right: 5px;
}

nav.top-nav {
  height: 30px;
  background-color: #111;
  color: #fff;
}

nav.top-nav > ul {
  justify-content: space-around;
  margin: 0;
  padding: 0;
}

nav.top-nav > ul,
li {
  display: flex;
  list-style: none;
  text-decoration: none;
}

nav.top-nav > ul > li > a {
  color: #fff;
  text-decoration: none;
}

.nav-item-dropdown {
  position: relative;

  &:hover > .dropdown-menu {
    display: block;
    opacity: 1;
  }

  &:hover > .right-dropdown-menu {
    display: block;
    opacity: 1;
  }
}

.dropdown-trigger {
  position: relative;

  &:focus + .dropdown-menu {
    display: block;
    opacity: 1;
  }

  &:focus + .right-dropdown-menu {
    display: block;
    opacity: 1;
  }

//   &::after {
//     content: "›";
//     position: absolute;
//     color: #ED3E44;
//     font-size: 24px;
//     font-weight: bold;
//     transform: rotate(90deg);
//     top: -5px;
//     right: -15px;
//   }
}

.dropdown-menu {
  background-color: #111;
  display: flex;
  flex-direction: column;
  text-align: left;
  position: absolute;
  top: 30px;
  // right: 0px;
  left: 0;
  display: none;
  opacity: 0;
  transition: opacity 0.5s ease;
  width: 200px;
  border-radius: 0 0 5px 5px;
  padding-bottom: 15px;
  a {
    color: #00fff0;
  }
  p {
    color: #fff;
  }
}

.right-dropdown-menu {
  background-color: #111;
  display: flex;
  flex-direction: column;
  text-align: left;
  position: absolute;
  top: 30px;
  right: 0;
  /* left: 0; */
  display: none;
  opacity: 0;
  transition: opacity 0.5s ease;
  width: 200px;
  border-radius: 0 0 5px 5px;
  padding-bottom: 15px;
  a {
    color: #00fff0;
  }
  p {
    color: #fff;
  }
}

.dropdown-menu-item {
  cursor: pointer;
  padding: 1em;
  text-align: center;

  /* // &:hover {
    //     background-color: darken(#ED3E44, 5%);
    // } */
}
</style>
