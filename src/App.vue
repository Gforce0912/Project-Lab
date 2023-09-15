<template>
      <header class="main-header">
        <div class="layers">
          <div class="layer__header">
            <div class="layers__caption">{{ firstText }}</div>
            <div class="layer__ti">{{ secondText }}</div>
          </div>
        </div>
      </header>
      <div class="layer layers__base" style="background-image: url(img/basic.png);"></div>
          <div class="layer layers__midle" style="background-image: url(img/midle.png);"></div>
          <div class="layer layers__front" style="background-image: url(img/Srr.png);" ></div>
      <article class="main-article">
        <div class="main-article__contenft">
          <h2 class="main-article__header">
            {{ articleH2 }}
          </h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi quisquam quaerat nobis nesciunt consequuntur dolorem dicta, ipsam nostrum illum non quasi incidunt quis tempora maxime neque itaque fugit repellendus obcaecati quos similique!</p>
        </div>
        <div class="copy">Project Lab</div>
      </article>
</template>

<script>
  export default {
      data() {
        return{
          firstText: "Test projectfor Project Lab",
          secondText: "My project",
          articleH2: "Help me, i'm very tired",
        }
      }
    }
</script>

<style>
@import url('https://fonts.googleapis.com/css2? Family= Irish+Grover & Family= Kanit:wght@200;400 & display=swap');
*{
font-family: 'Irish Grover', cursive;
color: white;
margin: 0;
padding: 0;
box-sizing: border-box;
}
/* :root{

} */
  body{
    background: url(img/background.png);
    line-height: 1.55;
  }
  .main-header{
    position: relative;
  }
  .layers{
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .layer{
    height: 100%;
    width: 100%;
    position: absolute;
    background-size: cover;
    background-position: center;
  }
</style>
