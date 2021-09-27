<div class="container">
  <div class="title">
    <div class="italic">Take earth to it's next level</div>
    <div class="test">
      Help us to improve the world we live in by supporting our projects or
      creating helpful projects for your community
    </div>
    <div class="actions">
      <button class="box2">SEE PROJECTS</button>
      <button class="box3">HELP YOUR COMMUNITY</button>
    </div>
  </div>

  <div class="gradient" />
  <div class="water" />
  <div class="clouds" />
  <div class="forest" />
  <div class="flamingo" />
  <div class="people" />
</div>

<style>
  div.container {
    position: relative;
    height: 100%;
    width: 100%;
  }

  div.title {
    width: 470px;
    align-items: center;
    flex-direction: column;
    padding: 0 30px;
    justify-content: center;
    display: flex;
    height: 100%;
    word-wrap: break-word;
  }

  div.italic {
    font-family: 'Old Standard TT';
    font-style: italic;
    font-size: 40px;
  }

  div.test {
    font-family: 'Montserrat';
    font-weight: 200;
    font-size: 22px;
  }

  div.actions {
    display: flex;
    align-items: flex-end;
    width: 100%;
    justify-content: space-evenly;
    height: 30%;
  }

  div.gradient {
    height: 700px;
    width: 700px;
    top: -100px;
    right: -190px;
    border-radius: 50%;
    background: linear-gradient(#2baa83, #b3dc7c);
    z-index: -10;
    background-size: cover;
    position: absolute;
  }

  div.clouds {
    height: 400px;
    width: 400px;
    top: -100px;
    right: 250px;
    border-radius: 50%;
    background: url(clouds.jpg);
    z-index: 0;
    background-size: cover;
    position: absolute;
  }

  div.water {
    height: 400px;
    width: 400px;
    top: 100px;
    right: 135px;
    z-index: 2;
    border-radius: 50%;
    background: url(water.jpg);
    background-size: cover;
    position: absolute;
  }

  div.forest {
    height: 700px;
    width: 700px;
    bottom: -150px;
    right: -200px;
    border-radius: 50%;
    z-index: -2;
    background: url(forest.jpg);
    background-size: cover;
    position: absolute;
  }

  div.flamingo {
    height: 300px;
    width: 300px;
    bottom: 0;
    right: 260px;
    border-radius: 50%;
    z-index: 3;
    background: url(flamingo.jpg);
    background-size: cover;
    background-position: center;
    position: absolute;
  }

  div.people {
    height: 260px;
    width: 260px;
    bottom: 200px;
    right: 400px;
    border-radius: 50%;
    z-index: 2;
    background: url(people.jpg);
    background-size: cover;
    background-position: center;
    position: absolute;
  }

  .box2 {
    background-image: linear-gradient(black, black),
      linear-gradient(black, black), linear-gradient(black, black);
    background-repeat: no-repeat;
    background-size: 100% 3px, 3px 100%, 30% 3px;
    background-position: left bottom, right bottom, right top;
    height: 36px;
    width: auto;
    min-width: 160px;
    color: black;
    text-decoration: unset;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    transition: background-size 1s ease;
  }

  .box2:hover {
    background-image: linear-gradient(black, black),
      linear-gradient(black, black), linear-gradient(black, black);
    background-repeat: no-repeat;
    background-size: 100% 3px, 3px 100%, 100% 3px;
    background-position: left bottom, right bottom, right top;
  }

  .box3 {
    background-image: linear-gradient(#2baa83, #2baa83),
      linear-gradient(#2baa83, #2baa83), linear-gradient(#2baa83, #2baa83);
    background-repeat: no-repeat;
    background-size: 80% 3px, 3px 0, 80% 3px;
    background-position: right bottom, right bottom, left top;
    height: 36px;
    width: auto;
    min-width: 160px;
    color: black;
    text-decoration: unset;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    transition: background-size 1s ease;
  }

  .box3:hover {
    background-image: linear-gradient(#2baa83, #2baa83),
      linear-gradient(#2baa83, #2baa83), linear-gradient(#2baa83, #2baa83);
    background-repeat: no-repeat;
    background-size: 100% 3px, 3px 0, 100% 3px;
    background-position: right bottom, right bottom, left top;
  }
</style>
