## Welcome to the Koen Lab
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial;}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>
</head>
<body>

<h2>Tabs</h2>
<p>Click on the buttons inside the tabbed menu:</p>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Home')">Home</button>
  <button class="tablinks" onclick="openCity(event, 'People')">People</button>
  <button class="tablinks" onclick="openCity(event, 'Publications')">Publications</button>
  
</div>

<div id="Home" class="tabcontent">
  <h3>Home</h3>
  <p>This is the Koen Lab y'all</p>
</div>

<div id="People" class="tabcontent">
  <h3>People</h3>
  <p>Joshua Koen, Willian De Faria, Nick Yeh, Sydney Habermann</p> 
</div>

<div id="Publications" class="tabcontent">
  <h3>Publications</h3>
  <p>Psych</p>
</div>
<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>
   
</body>

<html lang="en-US"><head> <title> Koen Lab </title>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<title>Welcome to the Koen Lab </title>
<meta name="generator" content="Jekyll v3.8.5">
<meta property="og:title" content="Welcome to the Koen Lab">
<meta property="og:locale" content="en_US">
<meta name="description" content="Hello World!">
<meta property="og:description" content="Hello World!">
<link rel="canonical" href="https://williandefaria.github.io/Koen-Lab/">
<meta property="og:url" content="https://williandefaria.github.io/Koen-Lab/">
<meta property="og:site_name" content="Koen-Lab">
<script type="application/ld+json">
{"@type":"WebSite","headline":"Welcome to the Koen Lab","url":"https://williandefaria.github.io/Koen-Lab/","name":"Koen-Lab","description":"Hello World!","@context":"http://schema.org"}</script>
<!-- End Jekyll SEO tag -->

    <link rel="stylesheet" href="/Koen-Lab/assets/css/style.css?v=cc9aea1387902ee2ff66d876cb75a04ba2339984">
    <!--[if lt IE 9]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js"></script>
    <![endif]-->
  <style id="__web-inspector-hide-shortcut-style__" type="text/css">
.__web-inspector-hide-shortcut__, .__web-inspector-hide-shortcut__ *, .__web-inspector-hidebefore-shortcut__::before, .__web-inspector-hideafter-shortcut__::after
{
    visibility: hidden !important;
}
</style></head>
  <body>
   <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #4CAF50;
  color: white;
}
</style>
</head>
<body>

<div class="topnav"> 
        <a class="active" href="#home">Home</a>
        <a href="#Research">Research</a>
        <a href="#People">People</a>
        <a href="#Publications">Publications</a>
        <a href="#News">News</a>
        <a href="#Contact Us">Contact Us</a>
        </div>

<div style="padding-left:16px">
  <h2>Top Navigation Example</h2>
  <p>Some content..</p>
</div>
            <div class="wrapper">
      
      <section>
      <h2 id="welcome-to-the-koen-lab">Welcome to the Koen Lab</h2>
<hr>
Here in the Koen Lab we study Memory, Aging, and Cognition using electrophysiology (EEG/ERP), transcranial magnetic stimulation (TMS), functional magnetic resonance imaging, and eye tracking. Using these tools, we look to investigate what neural processes give rise to memory and how memory changes with age. 
<p>Here in the Koen Lab we study Memory, Aging, and Cognition using electrophysiology (EEG/ERP), transcranial magnetic stimulation (TMS), functional magnetic resonance imaging, and eye tracking. Using these tools, we look to investigate what neural processes give rise to memory and how memory changes with age.</p>
<p><img src="https://news.nd.edu/assets/253664/1000x562/dome_feature.jpg" alt="image"></p>

