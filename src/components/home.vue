<template>
    <body>
    <div class="main-Nav">
      <div class="coffee-hub">
        <h2>COFFEE HUB</h2>
        <img
          src="../assets/junkie.jpg"
          id="logo"
          alt=" COFFEE"
          style="width: 400px; height: 300px; border-radius: 4px"
        />
      </div>

      
    </div>

    <h3>Coffee junkie</h3>

    <br />
    <br />
    <img
      src="../assets/roast.jpg"
      width="90%"
      alt="kenyan roast coffee"
      style="width: 400px; height: 300px; border-radius: 4px"
    />
    <br />
    <br />
    <h1>FEATURED PRODUCTS</h1>
    <br />
    <br />
    <!--House blend-->
    <h2>House Blend Coffee</h2>
    <img src="../assets/Houseblend.jpg" alt="Blend coffee" />
    <p class="p">
      House Blend coffee from The Coffee Bean & Tea Leaf is one of our most
      popular coffees. To create our light roast House Blend we combine natural
      and washed Central and South American coffees. We choose our blends for
      brightness, flavor, and aromas that make for a smooth, satisfying cup of
      coffee that can be enjoyed all day long. House Blend is available in both
      whole beans and ground coffee options. House Blend coffee from The Coffee
      Bean & Tea Leaf is one of our most popular coffees. To create our light
      roast House Blend we combine natural and washed Central and South American
      coffees. We choose our blends for brightness, flavor, and aromas that make
      for a smooth, satisfying cup of coffee that can be enjoyed all day long.
      House Blend is available in both whole beans and ground coffee options.
    </p>
    <h3>
      <a href="https://www.uticacoffeeroasting.com" target="_blank">Details</a>
    </h3>
    <!--KOFINAF-->
    <h2>Kofinaf coffee</h2>
    <img src="../assets/kofinaf.jpg" alt="kofinaf" />
    <p class="p">
      Kofinaf is available in both whole beans and ground coffee options.
      Kofinaf coffee from The Coffee Bean & Tea Leaf is one of our most popular
      coffees. To create our light roast Kofinaf we combine natural and washed
      Central and Kenya highlands coffees. We choose our blends for brightness,
      flavor, and aromas that make for a smooth, satisfying cup of coffee that
      can be enjoyed all day long. House Blend is available in both whole beans
      and ground coffee options.
    </p>
    <h3>
      <a href="https://www.uticacoffeeroasting.com" target="_blank">Details</a>
    </h3>

    <br />
    <br />
    <br />
    <br />
    <p>copyright&copy;2022</p>
    <h3><a href="#logo">Back To Top</a></h3>
  </body>
</template>
<style scoped>
    body {
      display: flex;
      align-items: center;
      justify-items: center;
      margin: auto;
      text-align: center;
      flex-direction: column;
      background-color: bisque;
    }
    .navs {
      display: flex;
      align-items: center;
      justify-items: center;
      margin: auto;
      flex-direction: row;
      background-color: rgb(217, 155, 155);
      padding: 10px;
      border-radius: 2px;
      color: white;
      list-style: none;
      position: fixed;
      top: 0px;
      right: 0px;
      gap: 4px;
    }
    .coffee-hub {
      display: flex;

      align-items: center;
      justify-items: center;
      margin: auto;
      flex-direction: column;
      list-style: none;
    }
    .main-Nav {
      display: flex;
      align-items: end;
      position: relative;
      justify-items: end;
      margin: auto;
      flex-direction: row;
      list-style: none;
      gap: 15px;
    }
    .li a {
      text-decoration: none;
      color: white;
      padding: 5px;
    }
    h2 {
      font-size: xx-large;
      font-family: Verdana, Geneva, Tahoma, sans-serif;
    }
    .p {
      max-width: 100px auto;
      width: 300px;
      text-align: start;
    }
  </style>