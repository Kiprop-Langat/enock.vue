<template>
    
  <body>
    <div class="main-Nav">
      <div class="coffee-hub">
        <h2>COFFEE HUB</h2>
        <img
          src="@/assets/junkie.jpg"
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
      src="@/assets/roast.jpg"
      width="80%"
      alt="kenyan roast coffee"
      style="width: 400px;height:300px; border-radius: 4px"
    />
    <br />
    <br />
    <h1 >Our stores</h1>
    <br />
    <br />
    <br />
    <table style="border: 5px solid black; border-spacing: 25px">
      <!--City-->
      <tr>
        <th>city</th>
        <th>Chicago</th>
        <th>New York</th>
        <th>Los Angeles</th>
      </tr>
      <!--end of city-->
      <!--orders-->
      <tr>
        <td>Orders</td>
        <td>200</td>
        <td>125</td>
        <td>400</td>
      </tr>
      <!--Profit-->
      <tr>
        <td>Profit</td>
        <td>$ 10,000</td>
        <td>$ 20,000</td>
        <td>$ 30,000</td>
      </tr>
      <!--end of profit-->
    </table>

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
  position: relative;
  width: 960px;
  text-align: center;
  flex-direction: column;
  overflow-x: hidden;
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