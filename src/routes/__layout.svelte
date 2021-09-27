<nav>
  <div>
    <img src="earth2.0.svg" alt="Logo" />
    <a href="/">HOME</a>
    <a href="/about">ABOUT</a>
    <a href="/projects">PROJECTS</a>
  </div>
  <div>
    <a href="/" class="box">DONATE</a>
  </div>
</nav>

<slot />

<style>
  .container:before {
    content: '';
    position: absolute;
    top: -1px;
    right: -1px;
    transform: translate(50%, -50%);
    width: 700px;
    height: 700px;
    border-radius: 50%;
    background: linear-gradient(#2baa83, #b3dc7c);
    mix-blend-mode: darken;
  }
  nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 20px;
  }

  nav div {
    display: flex;
    align-items: center;
  }

  nav img {
    margin-right: 20px;
    height: 36px;
  }

  nav a {
    font-family: 'Montserrat';
    font-weight: bold;
    margin: 0 20px;
    text-decoration: none;
    color: black;
  }

  .box {
    background-image: linear-gradient(black, black),
      linear-gradient(black, black), linear-gradient(black, black);
    background-repeat: no-repeat;
    background-size: 100% 3px, 3px 100%, 30% 3px;
    background-position: left bottom, left bottom, left top;
    height: 36px;
    width: 160px;
    color: black;
    text-decoration: unset;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    transition: background-size 1s ease;
  }

  .box:hover {
    background-image: linear-gradient(purple, purple),
      linear-gradient(purple, purple), linear-gradient(purple, purple);
    background-repeat: no-repeat;
    background-size: 100% 3px, 3px 100%, 100% 3px;
    background-position: left bottom, left bottom, left top;
  }
</style>
