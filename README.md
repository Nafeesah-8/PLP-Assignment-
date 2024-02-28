<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Image_links</title>
    <style>
      header {
        border-bottom: 1px solid;
        padding: 10px;
        margin: 0 -10px;
        background-color: blanchedalmond;
      }
      nav a {
        margin: 10px;
        text-decoration: none;
      }
      nav {
        text-align: right;
      }
      .tech {
        width: 50%;
        text-align: center;
      }
      .tec {
        text-align: center;
      }
      main {
        padding: 0 3%;
      }
      .section2 {background-color: blanchedalmond; margin: 0 -15px;}
      .grid-container {display:grid;
    padding: 20px; gap: 10px;}
    .grid {text-align: center;}
    .grid1 {grid-column: 1;
    grid-row: 1 / span 2;}
    .grid2 {grid-column: 2; grid-row: 1;}
    .grid3 {grid-column: 2; grid-row: 2;}
    @media (max-width: 760px) {
        .grid1 {grid-column: 1;
        grid-row: 1;}
        .grid2 {grid-column: 1;
        grid-row: 2;}
        .grid3 {grid-column: 1;
        grid-row: 3;}
    }
    #Menu {padding: 20px;}
    footer {text-align: center; background-color: gray; margin: 0 -15px;}

    </style>
  </head>
  <body>
    <header>
      <nav>
        <a href="#Home">Home</a>
        <a href="#Gallery">Gallery</a>
        <a href="#Menu">Menu</a>
      </nav>
    </header>
    <main>
      <section>
        <h3>Home</h3>
        <p>
          Welcome to the world of technology, explore the exciting world of technology.
          <br />
          <br />Technology refers to the application of scientific knowledge and innovations to practical purposes,
          often in the development of tools, machinery, systems, and processes to solve problems or achieve specific goals.
          Technology plays a crucial role in various aspects of modern life, influencing communication, transportation, healthcare, entertainment, and many other fields.
        </p>
        <p class="tec">
          <img
            class="tech"
            src="https://en.m.wikipedia.org/wiki/Technology"
            alt="Technology"
          />
          <br />Word of technology
        </p>
      </section>
      </main>
      <section class="section2" id="Gallery"> <br>
        <h3 style="padding: 0 30px";>Gallery</h3>
        <p style="padding: 0 30px";> Nature refers to the natural world and everything in it, including living and non-living things.
        It encompasses the physical, biological, and material elements of the Earth, such as landscapes, plants, animals, air, water, and weather.</p>
            <div class="grid-container" style="padding: 30px">
                <div class="grid1 grid"> <img src="https://picjumbo.com/tremendous-mountain-peak-krivan-in-high-tatras-slovakia/" style="max-width: 100%; height: 100%;"> </div>
                <div class="grid2 grid"> <img src="https://picjumbo.com/download/?d=beautiful-nature-scenery-smartphone-wallpaper-free-photo.jpg&n=beautiful-nature-scenery-smartphone-wallpaper&id=1" style="max-width: 100%; height: auto;";> </div>
                <div class="grid3 grid"> <img src="https://www.pexels.com/photo/brown-wooden-house-surrounded-by-green-trees-1172064/" style="max-width: 100%; height: auto;";> </div>
            </div>
            <p style="text-align: center;"> Beauty of nature</p> <br>
      </section>
      <section id="Menu">
        <h3> Menu</h3>
        <p>Consuming healthy food is crucial for maintaining overall well-being and promoting optimal physical and mental health.
        A healthy food should contain fruits and vegetables,lean proteins, whole grains, healthy fats, hydration e.t.c.</p>
        <ol>
            <li><a href="https://www.medicalnewstoday.com/articles/290814#benefits" alt="Water" title="External link" target="_blank">Water</a></li>
            <li><a href="https://www.onlyfoods.net/category/vegetables" alt="Vegetable" target="_blank" title="External link"> Vegetable</a> </li>
            <li><a href="https://unsplash.com/photos/green-and-red-apples-on-white-plastic-container-P2X7NDx_GP0" alt="Apple" target="_blank" title="External link"> Apple</a> </li>
        </ol>
      </section>
  </body>
  <footer>
    <p style="padding: 15px 0;"> Alright reserve|| Kuforiji Nafisat</p>
  </footer>
</html>
