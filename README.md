<!DOCTYPE html>
<html>
<head>
	<title>CALL CONTACT</title>
	<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body>
<style type="text/css">
		.grid-container {
  display: grid;
  grid-template-columns: 240px 1fr;
  grid-template-rows: 50px 1fr 50px;
  grid-template-areas:
    "sidenav header"
    "sidenav main"
    "sidenav footer";
  height: 100vh;
}

/* Give every child element its grid name */
.header {
  grid-area: header;
  background-color: #648ca6;
}

.sidenav {
  grid-area: sidenav;
  background-color: #394263;
}

.main {
  grid-area: main;
  background-color: #8fd4d9;
}

.footer {
  grid-area: footer;
  background-color: #648ca6;
}
.header, .footer {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 16px;
    background-color: #648ca6;
  }
</style>

<header class="header">
  <div class="header__search"></div>
  <div class="header__avatar"></div>
</header>

<footer class="footer">
  <div class="footer__copyright"></div>
  <div class="footer__signature"></div>
</footer>
</style>
<style>
  .sidenav {
    display: flex; /* Will be hidden on mobile */
    flex-direction: column;
    grid-area: sidenav;
    background-color: #394263;
  }
  .sidenav__list {
    padding: 0;
    margin-top: 85px;
    list-style-type: none;
  }
  .sidenav__list-item {
    padding: 20px 20px 20px 40px;
    color: #ddd;
  }
  .sidenav__list-item:hover {
    background-color: rgba(255, 255, 255, 0.2);
    cursor: pointer;
  }
  img {
    border-radius: 100%;
    padding: 16px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
</style>


<aside class="sidenav">
  <ul class="sidenav__list">
  	<img src="1539941987170.jpg" alt="Avatar" style="width:300px;height:300px;">
    <li class="sidenav__list-item">Rozaan Muhadzdzab Hanif Azhzhorif</li>
    <li class="sidenav__list-item">Univerity : MERCUBUANA JAKARTA</li>
    <li class="sidenav__list-item">Phone Number : 0126549165</li>
    <li class="sidenav__list-item">Address	: jl. jalanin aja dulu</li>
    <li class="sidenav__list-item">Types : HUMAN</li>
  </ul>
</aside>
<style>
  .main-header {
    display: flex;
    justify-content: space-between;
    margin: 20px;
    padding: 20px;
    height: 150px; /* Force our height since we don't have actual content yet */
    background-color: #e3e4e6;
    color: slategray;
  }
  <style>
  .main-overview {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(265px, 10fr)); /* Where the magic happens */
    grid-auto-rows: 94px;
    grid-gap: 20px;
    margin: 20px;
  }
  
  .overviewcard {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
    background-color: #d3d3;
  }
</style>

<div class="main-overview">
  <div class="overviewcard">
    <div class="overviewcard__icon">Competent Here</div>
    <div class="overviewcard__info">>>>></div>
  </div>
  <div class="overviewcard">
    <div class="overviewcard__icon">Competent Here</div>
    <div class="overviewcard__info">>>>></div>
  </div>
  <div class="overviewcard">
    <div class="overviewcard__icon">Competent Here</div>
    <div class="overviewcard__info">>>>></div>
  </div>
  <div class="overviewcard">
    <div class="overviewcard__icon">Competent Here</div>
    <div class="overviewcard__info">>>>></div>
  </div>
</div>
<style>
  .main-cards {
    column-count: 2;
    column-gap: 20px;
    margin: 20px;
  }
  
  .card {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    background-color: #82bef6;
    margin-bottom: 20px;
    -webkit-column-break-inside: avoid;
    padding: 24px;
    box-sizing: border-box;
  }
  /* Force varying heights to simulate dynamic content */
  .card:first-child {
    height: 485px;
  }
  .card:nth-child(2) {
    height: 200px;
  }
  .card:nth-child(3) {
    height: 265px;
  }
</style>

<div class="main-cards">
  <div class="card">karate</div>
  <div class="card">story telling</div>
  <div class="card">wushu</div>
</div>
</style>
 

</body>
</html>
