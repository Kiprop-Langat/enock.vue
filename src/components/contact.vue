<template>
    <main class=" flex justify-center items-center flex-col">
    

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
      src="@/assets/roast.jpg"
      width="90%"
      alt="kenyan roast coffee"
    />
    <br />
    <br />
    <h1>Contact Us</h1>
    <br />
    <form action="https://formspree.io/f/mgeqpwwk" method="POST" class=" p-5 rounded-md   bg-gray-200  border-emerald-200 border-dotted">
      <!--name-->
      <label for="Name">Name</label>
      <input type="text" name="name" id="name" />
      <br />
      <br />
      <!--  email-->
      <label for="email">email</label>
      <input type="text" name="email" id="email" />
      <br />
      <br />
      <!--Description-->
      <p>Description</p>
      <textarea
        name="Desciption"
        id=""
        cols="30"
        rows="10"
        placeholder="Your description"
      ></textarea>
      <button class=" px-5 py-3 bg-indigo-600 text-white mt-2 flex justify-center mx-auto items-center rounded-md">Send-)</button>
    </form>
    <br />

    <br />
    <br />
    <br />
    <br />
    <p>copyright&copy;2022</p>
    <h3><a href="#logo">Back To Top</a></h3>
  </body>
    </main>
</template>
<style scoped>
body {
  display: flex;
  align-items: center;
  justify-items: center;
  margin: auto;
  text-align: center;
  flex-direction: column;
  
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