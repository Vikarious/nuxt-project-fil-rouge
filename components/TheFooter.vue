<template lang="">
  <div>
    <footer>
      <div class="logo-footer">
        <img
          src="~/static/logoR&C.png"
          alt="logo-R&C"
          height="60px"
          width="60px"
        />
      </div>

      <nav class="bottom-nav">
        <a href="#">About</a>
        <a href="#">Terms of Use</a>
        <a href="#">Contact</a>
      </nav>

      <div class="logo-social">
        <a href="https://github.com/Vikarious/nuxt-project-fil-rouge" target="_blank"
          ><img
            src="~/static/GitHub-Mark-120px-plus.png"
            alt="logo-github"
            height="30px"
            width="30px"
        /></a>
      </div>
    </footer>
  </div>
</template>
<script>
export default {}
</script>
<style lang="scss">
footer {
  background-color: #575757;
  display: flex;
  flex-direction: column;
  margin-top: 25px;
}

.logo-footer {
  display: flex;
  justify-content: center;
  padding-top: 10px;
  padding-bottom: 10px;
}

nav.bottom-nav {
  height: 50px;
  display: flex;
  background-color: #575757;
  color: #fff;
  justify-content: space-around;
}

nav.bottom-nav > a {
  color: #fff;
  text-decoration: none;
}

.logo-social {
  // background-color: #575757;
  display: flex;
  justify-content: center;
}
</style>
