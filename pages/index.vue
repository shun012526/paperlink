<template>
  <div class="container">
    <div id="heading">
      <img src="image/heading.png" />
    </div>
    <div class="sns">
      <ul>
        <li class="twitter">
          <a
            href="http://twiter.com/share?url=https://paprlink.com/"
            target="_blank"
            ><img class="snsbtn" src="image/twitter_icon.png"
          /></a>
        </li>
        <li class="facebook">
          <a
            href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fpaperlink.jp%2F&amp;src=sdkpreparse"
            target="_blank"
            ><img class="snsbtn" src="image/facebook_icon.png"
          /></a>
        </li>
        <li class="line line-it-button">
          <a
            href="https://social-plugins.line.me/lineit/share?url=https%3A%2F%2Fpaperlink.jp%2F"
            ><img class="snsbtn" src="image/line_icon.png"
          /></a>
        </li>
      </ul>
    </div>
    <div id="main">
      <img src="image/main.png" />
    </div>
    <div class="sns">
      <ul>
        <li class="twitter">
          <a
            href="http://twiter.com/share?url=https://paprlink.com/"
            target="_blank"
            ><img class="snsbtn" src="image/twitter_icon.png"
          /></a>
        </li>
        <li class="facebook">
          <a
            href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fpaperlink.jp%2F&amp;src=sdkpreparse"
            target="_blank"
            ><img class="snsbtn" src="image/facebook_icon.png"
          /></a>
        </li>
        <li class="line">
          <a
            href="https://social-plugins.line.me/lineit/share?url=https%3A%2F%2Fpaperlink.jp%2F"
            ><img class="snsbtn" src="image/line_icon.png"
          /></a>
        </li>
      </ul>
    </div>
    <div id="footer">
      <img src="image/footer.png" />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* 共通 */
body {
  margin: 0;
  padding: 0;
}

#heading img,
#main img,
#footer img {
  width: 100%;
}

.sns li {
  list-style: none;
  display: inline-block;
  margin: 0 1vw;
}

@media (min-width: 960px) {
  body {
    margin: 0 25vw;
  }
  .sns ul {
    margin-left: 5vw;
    padding: 0;
  }
  .snsbtn {
    width: 10vw;
  }
}

@media (max-width: 960px) {
  .sns ul {
    margin-left: 7vw;
    padding: 0;
  }
  .snsbtn {
    width: 25vw;
  }
}
</style>
