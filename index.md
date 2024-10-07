
# Welcome to AP Computer Science Principles

<div style="background-color: #da95f5; padding: 20px; border-radius: 15px;">
  <h2 style="color: black;">AP CSP Students  Click Here!</h2>
  <p style="color: black;"> To properly prepare and excell in this class, there are many resources avaialable to you. Click on the button below ! </p>
  <button onclick="window.location.href='https://apcentral.collegeboard.org/courses/ap-computer-science-principles';">College Board!</button>
</div>

<p> </p>
<div style="background-color: #da95f5; padding: 20px; border-radius: 15px;">
  <h2 style="color: black;">Programming Help</h2>
  <a href="https://www.w3schools.com/css/">
    <button class="block"><b>CSS Help</b></button>
  </a>
  <p> </p>
  <a href="https://www.w3schools.com/html/">
    <button class="block"><b>HTML Help</b></button>
  </a>

  <p style="color: black;"> Use the links above to navigate to the programming language of your choosing! </p>
</div>

<p> </p>

<style>
  /* Ensure the 'Games' button is a big rounded square with a purple background */
  .games-menu {
    display: inline-block;
    background-color: #da95f5 !important; /* Purple background */
    padding: 15px 30px;
    border-radius: 25px;
    color: black !important; /* Text color */
    font-size: 18px;
    text-align: center;
    cursor: pointer;
    text-decoration: none;
  }

  /* Dropdown menu container */
  .dropdown-menu {
    display: none;
    position: absolute;
    background-color: #da95f5 !important; /* Purple background */
    border-radius: 10px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    padding: 10px;
    top: 100%;
    left: 0;
    z-index: 1000;
  }

  /* Dropdown menu links */
  .dropdown-menu a {
    display: block;
    color: black !important; /* Text color */
    padding: 10px;
    text-decoration: none;
    border-radius: 5px;
    font-size: 16px;
  }

  /* Dropdown menu link hover effect */
  .dropdown-menu a:hover {
    background-color: #C8A2C8 !important; /* Hover background color */
    color: black !important; /* Hover text color */
  }

  /* Show dropdown menu when 'Games' button is clicked */
  .games-menu.active + .dropdown-menu {
    display: block;
  }
</style>

<!-- Add this HTML to your index.md file where you want the menu to appear -->
<div class="dropdown">
  <a href="#" class="games-menu">Games</a>
  <div class="dropdown-menu">
    <a href="https://vibha1019.github.io/vibha_mandayam/navigation/calculator.html">Calculator</a>
    <a href="https://vibha1019.github.io/vibha_mandayam/navigation/cookie_clicker.html">Cookie Clicker</a>
    <a href="https://vibha1019.github.io/vibha_mandayam/navigation/snake.html">Snake Game</a>
    <a href="https://vibha1019.github.io/vibha_mandayam/navigation/binary_calculator.html">Binary Calculator</a>
    <a href="https://vibha1019.github.io/bc_game/index.html"> Bulls and Cows Game</a>
  </div>
</div>

<script>
  // Toggle dropdown menu visibility
  document.querySelector('.games-menu').addEventListener('click', function(e) {
    e.preventDefault();
    this.classList.toggle('active');
  });
</script>

<p> </p>
<table style="background-color: #da95f5;">
    <tr>
        <td><a href="{{site.baseurl}}/github/pages/3_3_hacks"> 3.3 Hacks </a></td>
        <td><a href="{{site.baseurl}}/github/pages/3_5_hacks"> 3.3 Hacks </a></td>
    </tr>
</table>


