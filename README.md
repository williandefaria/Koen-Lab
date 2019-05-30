## Welcome to the Koen Lab
<head>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}

/* Set height of body and the document to 100% */
body, html {
  height: 100%;
  margin: 0;
  font-family: Helvetica;
}

/* Style tab links */
.tablink {
  background-color: #f1f1f1;
  color: black;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #fff;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: black;
  display: none;
  padding: 100px 20px;
  height: 100%;
}

#Home {background-color: white;}
#News {background-color: white;}
#Contact {background-color: white;}
#About {background-color: white;}
</style>
</head>
<body>

<button class="tablink" onclick="openPage('Home', this, '#bbb')">Home</button>
<button class="tablink" onclick="openPage('People', this, '#bbb')" id="defaultOpen">People</button>
<button class="tablink" onclick="openPage('Publications', this, '#bbb')">Publications</button>
<button class="tablink" onclick="openPage('News', this, '#bbb')">News</button>
<button class="tablink" onclick="openPage('Contact Us', this, '#bbb')">Contact Us</button>

<div id="Home" class="tabcontent">
  <h3>Home</h3>
  <p>Welcome to the Koen Lab</p>
</div>

<div id="People" class="tabcontent">
  <h3>People</h3>
  <p>
  <ol>
  <li>Dr. Joshua Koen</li>
  <li>Morgan Foley</li>
  <li>Nicholas Yeh</li>
  <li>Willian Defaria</li>
  <li>Sydney Habermann</li>
  </ol>
  </p> 
</div>

<div id="Publications" class="tabcontent">
  <h3>Publications</h3>
  <p>Home is where the heart is..</p>
</div>

<div id="News" class="tabcontent">
  <h3>News</h3>
  <p>Who we are and what we do.</p>
</div>

<div id="Contact Us" class="tabcontent">
  <h3>Contact Us</h3>
  <p>Get in touch, or swing by for a cup of coffee.</p>
</div>


<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
</body>
</html> 

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

