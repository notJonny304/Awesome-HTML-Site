

<!DOCTYPE html>
<html>
<head>

    <title>notJonny.com</title>
<link rel="icon" type="image/png" href="https://static.vecteezy.com/system/resources/thumbnails/013/758/877/small_2x/abstract-circle-logo-with-holes-illustration-in-trendy-and-minimal-style-png.png">


      <link rel="stylesheet" href="https://www.w3schools.com/w3css/5/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src='https://kit.fontawesome.com/a076d05399.js' crossorigin='anonymous'></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
     <link href="fonts.googleapis.com" rel="stylesheet">
     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
     <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Spectral">
          <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Orbitron">
            <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sekuya">          <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Arial Rounded">
      <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Nixie One"> 
      <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lora"><link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Cormorant Garamond">
 <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Crimson Text"> <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=IBM Plex Mono"> <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Cutive Mono"><style>
  

.h321 {
    font-size: 5rem;
    font-family: Arial Black, sans-serif;
    /* transition: font-size 0.3s ease, text-shadow 0.3s ease; Removed transition */
    color: #00FFFF;
    text-align: center;
    /* Initial text shadow */
    text-shadow: 1px 1px 0 #0000ff, 2px 2px 0 #0000e6, 3px 3px 0 #0000cc, 4px 4px 0 #0000b3, 5px 5px 0 #000099, 6px 6px 0 #000080, 7px 7px 7px #3333ff;
}



.clipped-image {
  
  clip-path: inset(200px 0 200px 0);
  
  width: 100%;
  display: block;
position:relative;
top:-200px; 
}
.outlined-text{
  font-size: 4rem;
  color: transparent;
  -webkit-text-stroke: 1px white;
  text-shadow: -9px -9px  white;
  font-weight: 600; font-family: Times New Roman;
  text-transform: uppercase;
}
  :root {
    --primary-color: #212121;
    --background-color: #111;
    --font: sans-serif;
    --info-bg: #333; 
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    background: var(--background-color);
   
  
}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-image: url(https://images.unsplash.com/photo-1659469377768-4f42f2f091c5?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8ZGFyayUyMGdyYWRpZW50fGVufDB8fDB8fHww&fm=jpg&q=60&w=3000);
}

/* Style the buttons inside the tab */
.tab button {
  background-color: black;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
  color:#39FF14
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: orange;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: red;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
   -webkit-animation: fadeEffect 1s;
  animation: fadeEffect 1s;

}
@-webkit-keyframes fadeEffect {
transition: opacity 0.5s ease-in-out; /* Smooth transition for opacity */
    position: absolute; /* Position all content in the same spot for seamless transition */
    padding: 20px;
    border: 1px solid #ccc
}

@keyframes fadeEffect {
  from {opacity: .8;}
  to {opacity: 1;}
}
.btn {
  background-color: black;
  border: none;
  color: white;
  padding: 5px 13px;
  text-align: center;
  font-size: 16px;
  margin: 4px 2px;
  opacity: 0.7;
  transition: 0.3s;
  color:#FF007F

  
}
.btn:hover {opacity: 1.2;   transform: scale(1.1);}
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
.glow {
  font-size: 80px;
  color: #fff;
  text-align: center;
  animation: glow 1s ease-in-out infinite alternate;
}

@-webkit-keyframes glow {
  from {
    text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #e60073, 0 0 40px #e60073, 0 0 50px #e60073, 0 0 60px #e60073, 0 0 70px #e60073;
  }
  
  to {
    text-shadow: 0 0 20px #fff, 0 0 30px #ff4da6, 0 0 40px #ff4da6, 0 0 50px #ff4da6, 0 0 60px #ff4da6, 0 0 70px #ff4da6, 0 0 80px #ff4da6;
  }
}
.neon-text {
    font-size: 4rem;
    color: #fff;
    text-shadow: 0 0 5px #ff005e, 0 0 10px #ff005e, 0 0 20px #ff005e, 0 0 40px #ff005e, 0 0 80px #ff005e;
}

@keyframes glow {
    0% {
        text-shadow: 0 0 5px #ff005e, 0 0 10px #ff005e, 0 0 20px #ff005e, 0 0 40px #ff005e, 0 0 80px #ff005e;
    }
    100% {
        text-shadow: 0 0 10px #00d4ff, 0 0 20px #00d4ff, 0 0 40px #00d4ff, 0 0 80px #00d4ff, 0 0 160px #00d4ff;
    }
}
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #ddd;
}

.dropdown:hover .dropdown-content {
  display: block;
}
.dropdown {
  float: left;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}
.glow-on-hover {
    width: 220px;
    height: 50px;
    border: none;
    outline: none;
    color: #fff;
    background: #111;
    cursor: pointer;
    position: relative;
    z-index: 0;
    border-radius: 10px;
}

.glow-on-hover:before {
    content: '';
    background: linear-gradient(45deg, #ff0000, #ff7300, #fffb00, #48ff00, #00ffd5, #002bff, #7a00ff, #ff00c8, #ff0000);
    position: absolute;
    top: -2px;
    left:-2px;
    background-size: 400%;
    z-index: -1;
    filter: blur(5px);
    width: calc(100% + 4px);
    height: calc(100% + 4px);
    animation: glowing 20s linear infinite;
    opacity: 0;
    transition: opacity .3s ease-in-out;
    border-radius: 10px;
}

.glow-on-hover:active {
    color: #000
}

.glow-on-hover:active:after {
    background: transparent;
}

.glow-on-hover:hover:before {
    opacity: 1;
}

.glow-on-hover:after {
    z-index: -1;
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    background: #111;
    left: 0;
    top: 0;
    border-radius: 10px;
}

@keyframes glowing {
    0% { background-position: 0 0; }
    50% { background-position: 400% 0; }
    100% { background-position: 0 0; }
}
.rain {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: repeating-linear-gradient(
    0deg,
    rgba(0, 255, 0, 0.1) 0,
    rgba(0, 255, 0, 0.2) 2px,
    transparent 4px
  );
  animation: rain 10s linear infinite;
  z-index: 1; /* Place it behind the text */
}

/* Animation for the rain effect */
@keyframes rain {
  0% {
    transform: translateY(-100%);
  }
  100% {
    transform: translateY(100%);
  }
}

/* Glitch effect for the text */
.hover-underline {
  font-size: 2rem;
  color: #ffffff;
  position: relative;
  display: inline-block;
}

.hover-underline::after,
.hover-underline::before {
  content: '';
  position: absolute;
  width: 100%;
  height: 2px;
  background: linear-gradient(to right, #ff0000, #00ffff);
  bottom: -5px;
  left: 0;
  transform: scaleX(0);
  transform-origin: right;
  transition: transform 0.4s ease-out;
}

.hover-underline::before {
  top: -5px;
  transform-origin: left;
}

.hover-underline:hover::after,
.hover-underline:hover::before {
  transform: scaleX(1);
}
.container {
	width: 100%;
	height: 100%;
	display: grid;
	place-items: center;
	overflow: hidden;
}

.title {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
}
.title h1 {
	font-size: 25vmin;
	font-weight: 900;
	font-family: "Montserrat", sans-serif;
	color: black;
}


main {
  transition: all 0.5s;
  -webkit-text-stroke: 4px #d6f4f4;
  font-variation-settings: "wght" 900, "ital" 1;
  font-size: 15rem;
  text-align: center;
  color: transparent;
  font-family: "Meta", sans-serif;
  text-shadow: 10px 10px 0px #07bccc,
    15px 15px 0px #e601c0,
    20px 20px 0px #e9019a,
    25px 25px 0px #f40468,
    45px 45px 10px #482896;
  cursor: pointer;
}
.drop
main:hover {
  font-variation-settings: "wght" 100, "ital" 0;
  text-shadow: none;
}
.notJonny {
    background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background for content */
    padding: 20px;
    border-radius: 8px;
    text-align: center;
}
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
.glitch-button {
  position: relative;
  background-color: #333;
  color: #fff;
  padding: 15px 30px;
  font-family: 'Arial', sans-serif;
  font-size: 24px;
  border: none;
  overflow: hidden; /* Hide overflowing pseudo-elements */
  cursor: pointer;
}

.glitch-button span {
  position: relative;
  z-index: 2; /* Ensure text is above glitch layers */
}

/* Pseudo-elements for glitch effect */
.glitch-button::before,
.glitch-button::after {
  content: 'Click Me'; /* Duplicate button text */
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #333; /* Match button background */
  color: #ff00ff; /* Glitch color 1 (e.g., magenta) */
  overflow: hidden;
  clip-path: inset(0 0 0 0); /* Initially fully visible */
}

.glitch-button::after {
  color: #00ffff; /* Glitch color 2 (e.g., cyan) */
}

/* Glitch animation on hover */
.glitch-button:hover::before {
  animation: glitch-before 0.4s infinite alternate;
}

.glitch-button:hover::after {
  animation: glitch-after 0.4s infinite alternate;
}

/* Keyframe animations for glitch effect */
@keyframes glitch-before {
  0% {
    transform: translate(0, 0);
    clip-path: inset(0 0 0 0);
  }
  20% {
    transform: translate(-2px, 2px);
    clip-path: inset(10% 0 10% 0);
  }
  40% {
    transform: translate(2px, -2px);
    clip-path: inset(20% 0 20% 0);
  }
  60% {
    transform: translate(-1px, 1px);
    clip-path: inset(30% 0 30% 0);
  }
  80% {
    transform: translate(1px, -1px);
    clip-path: inset(40% 0 40% 0);
  }
  100% {
    transform: translate(0, 0);
    clip-path: inset(0 0 0 0);
  }
}

@keyframes glitch-after {
  0% {
    transform: translate(0, 0);
    clip-path: inset(0 0 0 0);
  }
  25% {
    transform: translate(3px, -3px);
    clip-path: inset(5% 0 5% 0);
  }
  50% {
    transform: translate(-3px, 3px);
    clip-path: inset(15% 0 15% 0);
  }
  75% {
    transform: translate(2px, -2px);
    clip-path: inset(25% 0 25% 0);
  }
  100% {
    transform: translate(0, 0);
    clip-path: inset(0 0 0 0);
  }
}
.futuristic-button {
  background-color: #1a1a2e; /* Dark background */
  color: #e0e0e0; /* Light text color */
  border: none;
  padding: 15px 30px;
  font-size: 18px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  cursor: pointer;
  position: relative;
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 255, 255, 0.5); /* Initial subtle glow */
  transition: all 0.3s ease;
}

.futuristic-button::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(0, 255, 255, 0.3), transparent);
  transition: all 0.7s ease;
}

.futuristic-button:hover {
  box-shadow: 0 0 20px rgba(0, 255, 255, 0.8), 0 0 40px rgba(0, 255, 255, 0.6); /* Enhanced glow on hover */
  transform: translateY(-2px); /* Slight lift on hover */
}

.futuristic-button:hover::before {
  left: 100%; /* Animate gradient across the button */
}

.futuristic-button:active {
  transform: translateY(0); /* Return to original position on click */
  box-shadow: 0 0 10px rgba(0, 255, 255, 0.5);
}
.neon-green-text {
  font-family: 'Arial Black', sans-serif; /* Choose a bold, impactful font */
  font-size: 60px;
  color: #00ff00; /* Bright neon green base color */
  text-align: center;
  text-shadow:
    0 0 5px #00ff00,    /* Inner, subtle glow */
    0 0 10px #00ff00,   /* Medium glow */
    0 0 20px #00ff00,   /* Stronger glow */
    0 0 40px #00ff00;   /* Widest, most diffused glow */
}
#container {
  color:#999;
  text-transform: uppercase;
  font-size:36px;
  font-weight:bold;
  padding-top:200px;  
  position:fixed;
  width:100%;
  bottom:45%;
  display:block;
}

#flip {
  height:50px;
  overflow:hidden;
}

#flip > div > div {
  color:#fff;
  padding:4px 12px;
  height:45px;
  margin-bottom:45px;
  display:inline-block;
}

#flip div:first-child {
  animation: show 5s linear infinite;
}

#flip div div {
  background:#42c58a;
}
#flip div:first-child div {
  background:#4ec7f3;
}
#flip div:last-child div {
  background:#DC143C;
}

@keyframes show {
  0% {margin-top:-270px;}
  5% {margin-top:-180px;}
  33% {margin-top:-180px;}
  38% {margin-top:-90px;}
  66% {margin-top:-90px;}
  71% {margin-top:0px;}
  99.99% {margin-top:0px;}
  100% {margin-top:-270px;}
}
.loading-bar-container {
  width: 100%;
  height: 10px;
  background-color: #f0f0f0;
  border-radius: 5px;
  overflow: hidden; /* Hide overflow for the progress bar */
  display: none; /* Initially hide the loading bar */
}

.loading-bar {
  height: 100%;
  width: 0%; /* Start with 0% width */
  background-color: #4CAF50; /* Green color for the progress */
  border-radius: 5px;
  transition: width 0.5s ease-in-out; /* Smooth transition for width changes */
}

/* Optional: Add a class for active loading state */
.loading-active .loading-bar-container {
  display: block; /* Show the loading bar when active */
}
.matrix-container {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    z-index: 2; /* Ensure it stays above the rain effect */
}

.matrix-text {
    color: #0f0;
    font-size: 70px; /* Changed to 70px */
    font-family: 'Courier New', monospace; /* Changed to Courier New */
    position: relative;
    text-shadow: 0 0 10px #0f0, 0 0 20px #0f0, 0 0 30px #0f0;
    z-index: 2; /* Ensure it stays above the rain effect */
}

.matrix-text::before {
    content: attr(data-text);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    animation: glitch 2s infinite;
    clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
    transform: translate(-2px, -2px);
    color: #0f0;
    text-shadow: 0 0 5px #0f0, 0 0 15px #0f0;
}

.rain {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: transparent; /* Ensures no background for the rain effect itself */
    animation: rain 10s linear infinite;
    z-index: 1; /* Place it behind the text */
}

/* Animation for the rain effect */
@keyframes rain {
    0% { transform: translateY(-100%); }
    100% { transform: translateY(100%); }
}

/* Glitch effect for the text */
@keyframes glitch {
    0%, 100% {
        clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
        transform: translate(0);
    }
    33% {
        clip-path: polygon(0 0, 100% 0, 100% 15%, 0 15%);
        transform: translate(-5px, -5px);
    }
    66% {
        clip-path: polygon(0 85%, 100% 85%, 100% 100%, 0 100%);
        transform: translate(5px, 5px);
    }
}
.neon-pink-text {
  font-family: 'Arial', sans-serif; /* Or a suitable neon-style font */
  font-size: 3em; /* Adjust size as needed */
  color: #fff; /* Base text color, white for a bright glow */
  text-shadow: 
    0 0 5px #ff00ff, /* Bright pink glow */
    0 0 10px #ff00ff,
    0 0 20px #ff00ff,
    0 0 40px #ff00ff,
    0 0 80px #ff00ff,
    0 0 90px #ff00ff; /* Deeper glow */
  animation: neonGlow 1.5s ease-in-out infinite alternate; /* Animation details */
}

@keyframes neonGlow {
  from {
    text-shadow: 
      0 0 5px #ff00ff, 
      0 0 10px #ff00ff, 
      0 0 20px #ff00ff, 
      0 0 40px #ff00ff;
  }
  to {
    text-shadow: 
      0 0 10px #ff00ff, 
      0 0 20px #ff00ff, 
      0 0 40px #ff00ff, 
      0 0 80px #ff00ff, 
      0 0 90px #ff00ff,
      0 0 100px #ff00ff;
  }
}
.glowin.blue.and.black {
    /* Set the text color and background */
    color: #fff; /* White text for contrast */
    background-color: #000; /* Black background as requested */
    font-family: 'Arial', sans-serif; /* Example font, 'Satisfy' font would need to be linked */
    font-size: 72px; /* Large font size */
    text-align: center;
    padding: 20px;
    
    /* Apply the blue glowing effect */
    text-shadow: 
        0 0 10px #00bfff,  /* Inner glow */
        0 0 20px #00bfff,  /* Medium glow */
        0 0 30px #00bfff,  /* Outer glow */
        0 0 40px #00bfff,
        0 0 50px #00bfff,
        0 0 60px #00bfff,
        0 0 70px #00bfff;
}
.neon-green-text {
    color: #39ff14; /* Bright neon green for the text */
    font-size: 5em;
    text-align: center;
    text-shadow:
        0 0 7px #39ff14,   /* Inner glow */
        0 0 10px #39ff14,  /* Medium glow */
        0 0 21px #39ff14,  /* Larger glow */
        0 0 42px #0f0,     /* Wider, slightly different shade of green for depth */
        0 0 82px #0f0,
        0 0 92px #0f0,
        0 0 102px #0f0,
        0 0 151px #0f0;
}
.glitch-text {
  position: relative;
  font-family: 'monospace', sans-serif; /* Use a monospace or futuristic font */
  color: #fff;
}

.glitch-text::before,
.glitch-text::after {
  content: attr(data-text); /* Use data-text attribute for content */
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.glitch-text::before {
  left: 2px;
  text-shadow: -2px 0 #ff00c1; /* Red glitch */
  animation: glitch-anim-1 2s infinite alternate-reverse;
}

.glitch-text::after {
  left: -2px;
  text-shadow: 2px 0 #00ffff; /* Cyan glitch */
  animation: glitch-anim-2 2s infinite alternate-reverse;
}

@keyframes glitch-anim-1 {
  0% { transform: translate(0); }
  20% { transform: translate(-2px, 2px); }
  40% { transform: translate(-2px, -2px); }
  60% { transform: translate(2px, 2px); }
  80% { transform: translate(2px, -2px); }
  100% { transform: translate(0); }
}

@keyframes glitch-anim-2 {
  0% { transform: translate(0); }
  20% { transform: translate(2px, -2px); }
  40% { transform: translate(2px, 2px); }
  60% { transform: translate(-2px, -2px); }
  80% { transform: translate(-2px, 2px); }
  100% { transform: translate(0); }
}
.awesome-buzz-effect {
    position: relative;
    font-family: monospace; /* Glitch effects often work well with techy/mono fonts */
    font-size: 4rem;
    color: white;
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #FF00FF, 0 0 20px #FF00FF; /* Optional neon glow */
    animation: buzz-animation 1s infinite alternate; /* Main buzz/shake */
}

/* Create distorted layers with pseudo-elements */
.awesome-buzz-effect::before,
.awesome-buzz-effect::after {
    content: attr(class="awesome-buzz-effect"); /* Use the text content */
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: transparent;
    overflow: hidden;
}

.awesome-buzz-effect::before {
    left: 2px;
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #00FFFF, 0 0 20px #00FFFF;
    clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%); /* Clip to top third */
    animation: buzz-top 1s infinite alternate-reverse;
}

.awesome-buzz-effect::after {
    left: -2px;
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #FF00FF, 0 0 20px #FF00FF;
    clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%); /* Clip to bottom third */
    animation: buzz-bottom 1.5s infinite alternate-reverse;
}

/* Main shake animation */
@keyframes buzz-animation {
    0%, 100% {
        transform: translateX(0);
    }
    10% {
        transform: translateX(-1px);
    }
    90% {
        transform: translateX(1px);
    }
}

/* Top layer distortion */
@keyframes buzz-top {
    0% {
        transform: translate(0, 0);
    }
    100% {
        transform: translate(5px, -5px);
    }
}

/* Bottom layer distortion */
@keyframes buzz-bottom {
    0% {
        transform: translate(0, 0);
    }
    100% {
        transform: translate(-5px, 5px);
    }
}
.hologram-container {
  position: relative;
  perspective: 1000px;
}

.hologram-text {
  font-family: 'Courier New', monospace;
  font-size: 4rem;
  font-weight: bold;
  color: #0ff;
  text-shadow: 
    0 0 10px #0ff,
    0 0 20px #0ff,
    0 0 30px #0ff;
  animation: float 3s ease-in-out infinite alternate;
  position: relative;
  z-index: 2;
}

.hologram-glitch {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: 
    linear-gradient(0deg, transparent 45%, rgba(0, 255, 255, 0.2) 50%, transparent 55%),
    linear-gradient(90deg, transparent 45%, rgba(0, 255, 255, 0.2) 50%, transparent 55%);
  background-size: 10px 10px;
  animation: glitch 0.5s linear infinite;
  opacity: 0.7;
  z-index: 1;
}

/* Scan lines */
.hologram-container::before {
  content: '';
  position: absolute;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
 

  pointer-events: none;
}

@keyframes float {
  0% { transform: translateY(0) rotateX(20deg); }
  100% { transform: translateY(-20px) rotateX(20deg); }
}

@keyframes glitch {
  0% { background-position: 0 0; }
  100% { background-position: 20px 20px; }
}

.matrix-container {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    z-index: 2; /* Ensure it stays above other elements if any */
}

.matrix-text {
    color: #0f0;
    font-size: 80px;
    font-family: monospace;
    position: relative;
    text-shadow: 0 0 10px #0f0, 0 0 20px #0f0, 0 0 30px #0f0;
    z-index: 2; /* Ensure it stays above other elements if any */
}

.matrix-text::before {
    content: attr(data-text);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    animation: glitch 2s infinite;
    clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
    transform: translate(-2px, -2px);
    color: #0f0;
    text-shadow: 0 0 5px #0f0, 0 0 15px #0f0;
}

/* Glitch effect for the text */
@keyframes glitch {
    0%, 100% {
        clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
        transform: translate(0);
    }
    33% {
        clip-path: polygon(0 0, 100% 0, 100% 15%, 0 15%);
        transform: translate(-5px, -5px);
    }
    66% {
        clip-path: polygon(0 85%, 100% 85%, 100% 100%, 0 100%);
        transform: translate(5px, 5px);
    }
}
section {
    width: 100%;
    max-width: 2400px;
    height: 100vh;
    margin: 0 auto; /* Changed from 100vh auto 0 to 0 auto */
    display: flex;
    flex-direction: column;
}

section:nth-child(odd) {
    align-items: flex-end;
}

section:first-child {
    /* This rule can likely be removed if all sections should have 0 margin-top */
    margin-top: 0; /* Changed from 30vh to 0 (or remove the entire selector) */
}

.text-wrapper {
    margin: 6rem 4rem;
    padding: 1px;
    width: 100%;
    max-width: 1000px;
    position: sticky;
    top: 6rem;
}

/* The rest of the styles are for the background-clip effect and remain the same */

.fade-from-left{
    background: linear-gradient(to top left, transparent 50%, var(--text-color) 60%, var(--text-color) 0) left bottom 25vh / 100vw 30vh fixed no-repeat, linear-gradient(to top, transparent 55%, var(--text-color) 0) left bottom 0vh / 100vw 100vh fixed no-repeat;
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
}

.fade-from-top{
    background: linear-gradient(to top, transparent 27%, var(--text-color) 40%, var(--text-color) 0) left bottom 0vh / 100vw 100vh fixed no-repeat;
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
}

.fade-from-right{
    background: linear-gradient(to top right, transparent 50%, var(--text-color) 60%, var(--text-color) 0) left bottom 25vh / 100vw 30vh fixed no-repeat, linear-gradient(to top, transparent 55%, var(--text-color) 0) left bottom 0vh / 100vw 100vh fixed no-repeat;
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
}

.fade-from-top-dots{
    background: url( data:image/svg+xml,%3Csvg xmlns= http://www.w3.org/2000/svg width= 4 height= 4 viewBox= 0 0 4 4 %3E%3Cpath fill= %23ffffff fill-opacity= 0.8 d= M1 3h1v1H1V3zm2-2h1v1H3V1z %3E%3C/path%3E%3C/svg%3E ), linear-gradient(to top, transparent 27%, var(--text-color) 40%, var(--text-color) 0) left bottom 0vh / 100vw 100vh fixed no-repeat;
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
}

.ywwqjowihojqdnw{
  width: 35px;
  height: 5px;
  background-color: black;
  margin: 6px 0;
}
   .outer {
    max-width: 900px;
    width: 100%;
    margin: 0 auto;
}
/* Timeline Container */
.timeline {
  background: #212121;
  margin: 20px auto;
  padding: 20px;
  width:100%
}

/* Card container */
.card {
  position: relative;
   width:100%
}

/* setting padding based on even or odd */
.card:nth-child(odd) {
  padding: 30px 0 30px 30px;
}
.card:nth-child(even) {
  padding: 30px 30px 30px 0;
}
/* Global ::before */
.card::before {
  content: "";
  position: absolute;
  width: 50%;
  border: solid orangered;
}

/* Setting the border of top, bottom, left */
.card:nth-child(odd)::before {
  left: 0px;
  top: -4.5px;
  bottom: -4.5px;
  border-width: 5px 0 5px 5px;
  border-radius: 50px 0 0 50px;
}

/* Setting the top and bottom to "-5px" because earlier it was out of a pixel in mobile devices */
@media only screen and (max-width: 400px) {
  .card:nth-child(odd)::before {
    top: -5px;
    bottom: -5px;
  }
}

/* Setting the border of top, bottom, right */
.card:nth-child(even)::before {
  right: 0;
  top: 0;
  bottom: 0;
  border-width: 5px 5px 5px 0;
  border-radius: 0 50px 50px 0;
}

/* Removing the border if it is the first card */
.card:first-child::before {
  border-top: 0;
  border-top-left-radius: 0;
}

/* Removing the border if it is the last card  and it's odd */
.card:last-child:nth-child(odd)::before {
  border-bottom: 0;
  border-bottom-left-radius: 0;
}

/* Removing the border if it is the last card  and it's even */
.card:last-child:nth-child(even)::before {
  border-bottom: 0;
  border-bottom-right-radius: 0;
}

/* Information about the timeline */
.info {
  display: flex;
  flex-direction: column;
  background: #333;
  color: gray;
  border-radius: 10px;
  padding: 10px;
}

/* Title of the card */
.title {
  color: orangered;
  position: relative;
}

/* Timeline dot  */
.title::before {
  content: "";
  position: absolute;
  width: 13px;
  height: 13px;
  background: white;
  border-radius: 999px;
  border: 3px solid orangered;
}

/* text right if the card is even  */
.card:nth-child(even) > .info > .title {
  text-align: right;
}

/* setting dot to the left if the card is odd */
.card:nth-child(odd) > .info > .title::before {
  left: -45px;
}

/* setting dot to the right if the card is odd */
.card:nth-child(even) > .info > .title::before {
  right: -45px;
}
.huswh {
  font-size: 35px;
position:relative; top:-5px;
  color: #e0ffff; 
  text-align: center;
  font-family: 'Courier New', Courier, monospace;
  font-weight: bold;
  text-shadow: 
    0 0 5px #fff,          
    0 0 10px #0ff,        
    0 0 20px #0ff,         
    0 0 40px #00ffff,      
    0 0 80px #00ffff;      
  letter-spacing: 2px;     
}
</style>
</head>
<body>


<div class="tab" style="height:60px">
  <button class="tablinks" onclick="openCity(event, 'Homepage')" id=defaultOpen style="height:60px" >
<i class="material-icons" style="font-size:17px;">home</i><span style="margin-left:4px;position:relative;top:-2px">Homepage</span></button>
   <button class="tablinks" onclick="openCity(event, 'Profiles') "style="position:relative;top:-3px;height:60px">
<i class='fas fa-user-circle'></i><span style="margin-left:4px;position:relative;top:-1px">Profiles</span></button>
  <button class="tablinks" onclick="openCity(event, 'myJourney')" style="position:relative;top:-3px;height:60px;position:relative;top:-.5px" ><span><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-globe" viewBox="0 0 16 16">
  <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8m7.5-6.923c-.67.204-1.335.82-1.887 1.855A8 8 0 0 0 5.145 4H7.5zM4.09 4a9.3 9.3 0 0 1 .64-1.539 7 7 0 0 1 .597-.933A7.03 7.03 0 0 0 2.255 4zm-.582 3.5c.03-.877.138-1.718.312-2.5H1.674a7 7 0 0 0-.656 2.5zM4.847 5a12.5 12.5 0 0 0-.338 2.5H7.5V5zM8.5 5v2.5h2.99a12.5 12.5 0 0 0-.337-2.5zM4.51 8.5a12.5 12.5 0 0 0 .337 2.5H7.5V8.5zm3.99 0V11h2.653c.187-.765.306-1.608.338-2.5zM5.145 12q.208.58.468 1.068c.552 1.035 1.218 1.65 1.887 1.855V12zm.182 2.472a7 7 0 0 1-.597-.933A9.3 9.3 0 0 1 4.09 12H2.255a7 7 0 0 0 3.072 2.472M3.82 11a13.7 13.7 0 0 1-.312-2.5h-2.49c.062.89.291 1.733.656 2.5zm6.853 3.472A7 7 0 0 0 13.745 12H11.91a9.3 9.3 0 0 1-.64 1.539 7 7 0 0 1-.597.933M8.5 12v2.923c.67-.204 1.335-.82 1.887-1.855q.26-.487.468-1.068zm3.68-1h2.146c.365-.767.594-1.61.656-2.5h-2.49a13.7 13.7 0 0 1-.312 2.5m2.802-3.5a7 7 0 0 0-.656-2.5H12.18c.174.782.282 1.623.312 2.5zM11.27 2.461c.247.464.462.98.64 1.539h1.835a7 7 0 0 0-3.072-2.472c.218.284.418.598.597.933M10.855 4a8 8 0 0 0-.468-1.068C9.835 1.897 9.17 1.282 8.5 1.077V4z"style="position:relative;top:5px"style/>
</svg><span style="margin-left:4px;position:relative;top:-2.1px">My Journey</span></span></button>
  <button class="tablinks" onclick="openCity(event, 'Paris')" style="position:relative;top:-3px;height:60px" >   <span class="material-icons" style="font-size:19px;position:relative; top:4px">desktop_windows</span><span style="margin-left:4px"> Gallery</span></button>
  <button class="tablinks" onclick="openCity(event,'Info')" style="position:relative;top:-3px;height:60px;position:relative"> About Us</button>
     <button class="tablinks" onclick="openCity(event, 'Contact')"style="position:relative;top:-3px;height:60px;position:relative"">Contact</button>

</div>
  
<div id="Homepage" class="tabcontent" style="height:700px; border-bottom:none;background-image: url(data:image/jpeg;base64,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)">
<h1 class="neon-text" style="font-size:55px;font-family:Courier New;text-align:center;font-weight:550">
notJonny's Awesome HTML Site</h1>





<h2 class="huswh"
>

Not sure which project is best? Here are some ideas!






</h2>

   
 <div class="row"style="position:relative;top:10px" >
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7auMssyLgJgUwqBew8nYRY_RoABxwamYgSw&s" width="180" height="300" alt="Google Logo" alt="Snow" style="width:100%;height:250px">
  </div>
  <div class="column">
    <img src="data:image/jpeg;base64,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" alt="Forest" style="width:100%;margin-left:9px;height:250px">
  </div>
  <div class="column">
    <img src="data:image/jpeg;base64,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" alt="Mountains" style="height:250px;margin-left:14px;width:95%">
  </div>
  </div>
  <a href="https://docs.google.com/document/d/1oWycSjjtCSOlB0_-A8_8fTs5N6a6dH8CexyUJWZkL1Q/edit?tab=t.0"><button class="btn" style="font-size:28px;width:360px;margin-left:12px;height:80px;position:relative; top:15px"><span style="color:#FF007F;border-radius: 15px; padding: 10px 20px; position:relative;">My Awesome Stories</span>   </button></a><a href="https://sites.google.com/students.wcpss.net/the-deviant-studio"><button class="btn" style="margin-left:60px;font-size:28px;width:370px;height:80px;color:#FF007F;position:relative;top:15px"><span>Our Google Site!</span></button></a>  <a href="https://www.youtube.com/@812333"style=""><button class="btn" style="margin-left:29px;font-size:28px;width:380px;height:80px;position:relative; top:15px;font-size:19px"><span style="color:#FF007F;margin-right:9px;border-radius: 15px; padding: 10px 20px; position:relative;font-size:21px">Our Awesome Youtube Channel!</span>   </button></a>
 
</div>
  

<div id="myJourney" class="tabcontent"  style=" height: auto;background-image: url(data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBwgHBgkIBwgKCgkLDRYPDQwMDRsUFRAWIB0iIiAdHx8kKDQsJCYxJx8fLT0tMTU3Ojo6Iys/RD84QzQ5OjcBCgoKDQwNGg8PGjclHyU3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3N//AABEIAJQA7AMBIgACEQEDEQH/xAAbAAACAwEBAQAAAAAAAAAAAAADBAACBQEGB//EAD4QAAEDAwIDBAgFAgUEAwAAAAECAxEABCESMSJBUQUTYXEUIzKBkaHB8EJSsdHhYvEVM0NygiSiwvI0kuL/xAAZAQADAQEBAAAAAAAAAAAAAAABAgMABAX/xAAnEQACAgMAAQMEAgMAAAAAAAAAAQIRAxIhMQQiQRNRocGx4WFxgf/aAAwDAQACEQMRAD8A+KtJClgEwOtEebShaghYWAcKA3oaauMmmrpJ+TraCo4BptdophCC6lQChIkRNAZcKDjFOXV65dIbS6sqDadKJ5DpQd2Sm5WvsAZY75zSgEknAHOo4ytlwocBBHUbUSyfctXQ40pSVgyCOtdurhdxcKccJUpRkqO5NMr2Fblt/gClI6E+6rAAiQnH+2ugACTt5VdhClJ0hKTPhTmbOKLXcxpPeSIMVHNGk6EkVbuFKySBV0WhUpKQrcxtWBaFw2s7IUfIV0Nq20Knyp5hpwaQFJzpjHU1QhzvWwVCViZj+o0QbCiW1K9lJPkKndqzwnGTjanGm1pW8lCkgpOZE7Ghk6XXJIkyn5/xWBswaGHFfgX8DRFWNwmZackctJrSsXG1rKV853TW1208hpCVMuNrUpPFw/D4VKWTWSRzT9TKM1GvJ41bLiRKm1gbZSaH7vlT9xdOEBBAiccP31oDbCnEapiTiqp2dUZOulYB2TP/ABrunoif+NWIIYnGCOXhRCyoAr4cAcvOgwWLqSCk8P8A20AoP5T8KbDajMBOIG3jVS0omJGI5VgqQsUFJGoEeYrpKelXeBBSkkZJ5RVS140ClgsRtVCJ2BopbjnXEgpOCKAyYEjNVIo5CpnFDVIoDJgTVYohFVNAdMOGzA4TXdMcjW+eynW+zmblRRodMJzn4VjugoI2pIZFLwc0Myn4Ae6rhJgEjFV1bzzoiXSE6cRFVHZ0RIx8q5B1GAfhVkuKUYgD+aOhCyVGQBk0yFboEhCycJUfdWr2ZYC6ASlKisk4AnEfvVuz2XnW0lCmwJjM+FafYbjtu2l5lSEnUUyZmYmo5ZNL2nHnyyUXqZXaFtbNKASlQIImR4GfnFLMLtEmHgf/AK/z51q37a7gqcKmc5iD0msk2iypUKEBSQRHUH9qbG249Gwtyh7mdQGVuS2hcSJhPKf2oymrfQ3DLoUBxHuz4fWfiKqyjR3aCQFqAIBSZO9OIZdDK1akhKUgkKSrNP4GboQLaC696tYBPBKfGrNoa70KW0spmTwHI1D6TTgZIMr0iTj1as8X1oTq3bdCSe7ziM4zP0rWDa+DPfMNKhplxIg57sjp9ar2heIcCdKFJQFHdBAjH80qvtF1RgpTEEZ5TFUcuHLlttkpSAVYPj9mhrXWTWL3W0Rblqpc6DHl4edDPckcCTPLG2BTF12Y5bOaC4lRgxAOcA/Wu21i6pfCsJ8c/lB+tNyrKJpK0yOItPRVaEKDkyCU0f0JnS3qYdE6JBbO3P602eznWUDvXQpJjAJ5yPoa1HX3EpAOhQ0ge6CPrUJZKOSfqKdLp5ZNmiW4bXqhMjQcmTQn7dLZy2tOOafGvUpd1OBxSm0rMcj1J+prM7QClqWsmSc+yrmaMcjbofH6hylTPOOpgiAT7qpB5J+VOXCSNQAGOgIoE6RgyfLNWO9PgEyNwfhXe7JmdxVtSlqA2M4mm2WlKdIBExvSydBlKkKejrjY/ChqaIxXtezOzO/aWC8ygji45zwgj6V569ZLbhAKcRn3VCOZSlSIY/UqUnFfBhlJJ2qpBB2NaVs02u4SHlBKT7RjaqXjSEXCwwsKbB4SRvVNu0dSydoMbslDaJOnGJpZZQpaZriErcKMVFJUkokZrRio+BYxS8EhudvlVghKthPurqQqTt9zRGlrbUSAmfHzqhmR1iGQsIIkxkGuNJUTud84p68vXnLRDLiEhCVbifH+aonvWlL1aAZVMzv9igm/kncqHbG2KoAUoAnkkwKds27VIAeKzxnbVtHh7/vNDsO1X2k92jukxni1eH7Ve1vHrVIQlTRE/imT8KlJOzimptsz31W+uE641CBKs8J/j+1cWm1KkhoOAYmSrPT5T9Kq9duNvoWUIJBCoyMgR9aZ7NeuLhxCW2mvV6EcRVmAen+39qrVI6FyNlWW7VRQtYXhtucL3zOY8vpTCfQA0dfe6lI4J7yJ1qj5aPnzp2ybvko0IRbAJSjBUvYFX8/So/a36gyhabcFsDAUr8Ok/oE7ePOkvpB5I3Tf5MlS7dN1bqUpfo+s6/aHDq+O3Sq33oi3EeikqydR4o3G08t6bvrG7Qu3Yc7oErUhOkmJmMz9++qr7LulIKlKb0oSpUZGBnp0prQ6nHzZQ/4XqXpVqBK9IKV9eH3x/NVcaYWSUICc7BKqbb7FvUpWEqZPEoEEnkY6c6KbW4bdUzob1GYOtUTI8PEVm0I5xv2v8ia0srhxXw0rM461xn0ecHhKzCgF/lGPvrRT36bzuilBhsq0azG2/nVre2urZrWkNKCVqwVKxKE/RQrN8CnzoxdP2SLT1OtLmInXBHLfw+e1Ht3rJTLYdCyvg1QlcR+Ll51n9pel3Fmp9xLQQkIEJJk6hqG/+/8AaiMXl4xbttpS0pK0NjJUDCgR+/lU3C0SeJNBlP8AZ6W28L1QnVIVk8/n05bVm+kW/eud73hRq4PawnP8Ud969uUpuXAzxhLgAKtiY+/lSTq7i4gENjVGc9RTxjSKwxJALk2ikqLYVMH833v8qWQlpbaICtUSrenHGX22HNWgpKCTk9Vfz8qVtbpTAgJSeWT76c6kqjws0wzqVqBgeB8KK02kOE5EJ8d6bsnC4VICUQtKk5nAMftTN2wu0eUoBGpQkpyRnNSlPtEJZfdqxd27ZbSQ3qTMiZV0/tWa860syqfielS5fUomdPTn0ik1vqxgYrKCXS2PEl0EtRC8E0NZCjJJqylSZNVJmno60jZ7NuLVlC+9Z70lvSk6o0q60i9xrB5UFoqUoeFNSpTiAobTSKCTbIaqMmziEpJGT45PWm7dhhbkFagmCTufxD6VxT06RoTgR8x+1aHZt+WHVFLCF6xG+2ZrSk64SyTko8QteWzAcSG1ko1nkdsdffVblpnRKFSozJJMbV6e7Sl+xQ8pDQ0qkJmTzP1PnWf2op9Nv3KmmwEKOypOMZ+dJjy7HJj9TvwwVulsbEHwUaOt9JSFCVEq9kLVPjVO0ErMrWgJ4oMK+NNMekMvBQbbMaRGrqkQa6WkdTa1svbM2bpSp9fEciCoxjAovZbNsHnC464lIdToIJEphe8f8fiaZslPrcbPcNSpxKcOcyhX7/Kmey0KIccSxq1OpcxiCNWP+6pSlRy5Muqdgkos8xcvg8EcS8ZM8vL6URluxLTf/UvFwJH41xP/ALT7qOm5cY4BbTASOedJ/mu2l73Q7vuBgadzPtKP/kR7qRPhzPI9WZvaDSS4k2zrqkpUsgqKiRxGDnrg0o4bkzK3TvJk++vXt27l2kqDQBcJG+OJWr60K4buEJf0stEEOH/M5GSfPE/CjHInxCQ9Wm9TyPf3Ikd47mQRqPPemLNet9z0t10QgnJUDOPpNPBt5XaV6pLKNYC9YUrAM8utcc7Qdt+1H31st69ITpkwMg+/b4GKpZ1734Qke6/xBwhxXd92YVxT7P70zFmWiFPuateOJcf5aflOr4DlVD2ov01Vz3KQS3o0aj0ia0ez3AbV65hoaSDoK8mE6aWTpAlNwSbRj9oC29G027zixKMFSs7+6Y01dlNkW2g88vUW0xK1gaoMe6Y2od12gXLdy37lI1aJIP5UgfQfOtJ5q9dbZ9QzkNoBDnXHTHtCiUcmkk/0IrT2aW1JbuHCeHQFKVtr6eUn9KR9QEe2qRGNSuppnU++6xcBtsAQQAYnUY930obtw406ha2kccEcXRc0UqKqxW5U33bmlxc6TAKj+Yf/AKodmm2k+kE7Ygmm33S6lcttiUFGF/1BX0/WhISsW7cISZBgz0NMil8oZYdtG1KIkHSYyd65eXLDmvSowCoAyduVJOrdI7vSMEjf760JbqzMpGZ59RNI4K7FWJXZR8Nzv8z0pd1LY9mTTMOOn2Rv16/3pg9nq7vjAHjNFui26j5MopRHvqhCetNPoUhWkDHn99KWUhSjyrJl4u0Wa0jcmjhaZBBMTuaEnUAMdOdWOpKmyUgRgDrWEasYKmuCF7nNaNou2CuJ1QGncKjn5dKylEk5AHvojStOrSIURE6q2vCU8dqj0huLFSCDcqkJ/NOem3l50jePtOFRFwtWCqFK3NZSkrSDtAk48IqBBcSTpGATM8qEcaXSMfTxj2y76woQHFK4pgmeVOWBt1vI9Ku3Et7H1kfhA3z4/Cs9bC20kqiAYnxia0l3LhASbcTj/U6J09Ko1ZSa9tIdtXLZKm4vV6Q6n/UiBBz+nxitXs64s2kpBudIIRqGvmUnV8CBWXY3Fwh1tYYBIIGkOxukjpj2q0mry6aKJs2wVpTpCXo2gdOUe6TvUZR6cGbHsqf8oIVdnrUom7M8MesjmZ5eVRA7NAQr0iVEAnjxOPDxPwmgi8um9E2iPWd2Uw94nw8fd41awuLott6LVBEJgl6J9Yrw6z8JrUQ+k6/tGwL61a7tti4ltSzrIVkCd/CkH7hpy6fQu6cDUe1r3kiR48/hSd27cPt2jfcpSVyEQ5JJJ8sUH/D7tZhIQTkjj9ry92aVRSJY/Txj2wgVbKvrr/qlpSW8K15WTEgmM5qPMdnKSpartSnCSSSufwmOXUAe+iWVpeWhcUWm1BbZT/mR/cHpzo7Tr5WvTap3Xu74I8PLz1GmZZNJ+1/kVNr2RI/6o6gcesHTy+9qDdOWqF92xdqKCQCdQ20q8OoT8aam4cWUi3T7azl7+hI6eXnTJevEp/8Ahowoie/ycJHTlge+PGt/sydNX3/qMLtMWvcabe5LhBEJKges8vLyJo7D1qq3QV9oOpcSlBA76AFAY5Yz8Kr2rcvPsLDlulCQW5hcxIKhiNoV7oAo7bt04hpwWyUpS0OLvoIGk8QxiAZ8KL6dPdVf8oy3FWyF6WbpwoCgE8UQJ3/WhENKcY9cpQ/ESfZzTl25cOPgqtkIIcSdIXgcRxt1EeFBZdd9JtT3SdX4Rq3z8qf4LK6v9mkjs/sxVupTb5Luk6UhYgnly60hcW6G7dsF46tKpTq2M/WtR68eFspJYSgBsjV3k8wen9B+JNYF09rknapRUmyGNTcukuUWyW9TbxK9Sh7U4z/Hx8KQhMSHDOefKKOHCEEKggAwJiKEjBIAzH5tsVVKjujxDNuyg/6igqDz56f7UzfI7tuW3SoYiTRLB4Nq7xXIxGvNOdrOIFmhBbQFD8QMzNcuSb38HLPJL6iVHmbjTMlfITSpCJ3NP3SiqDoEQAM7/c0gZnauiPg74eCNnigk1p35s/Rbf0dSy9B7yTieUVl5JGIxRGwSQAn5+NFqxpRtp/YkqmrtrWFAya6DpVlPzq4OrASOZ3FMhWy6laidSzG0FQqpUpskJXAPLeiNqUgq4Sd9oqyp7sjus8WTE/eKIgAuKWCFrO85+FXDzntd4fOmnWXPQNRYAHee3Ip9aHUPAm0AOQMp6EkfI0NkLKaXwZ7VxcpbCkvrGkjAVnG1GZevndK03DsogA6ojpTDThDAb9FTqUsRhPT9cUTs1DqrZ7u7XUFOA6pSIynr0ED/AJ1rJOS6wSV3ylJ1XKhpAAKl7QZArjF3cNPBtdy8kJUEnSuIgz+pn31pMqdt0obcsgSQ2JlOSCRFZms3L9u223CkSgjAniUrfwB+VL5Jxe12jQWoFxk+lq4FHQe9BKeLl40dLxBn01wb7PCgXDi7YpQttxOpRTBKDnVnlV1rKUrJZc0o1bqSYCVQfPJFAg434DuPq0Lm9dkoUQO+kHbFGbTbmSrtN0ElQPrOsTy8BSoaVdMIdLDikmSjKRjHSpcdnuNO6SyUAnSBIyenzFBknSVWHfUyjjb7Sc1yf9TqnP6JoOtK0HV2m7r1bd5/QPrPwoVx2Xc6u7QwEqM5Dg5AGPmKUV2fcNtFxSYbSQCdW2x/8h8aySHgoV5Ge0mbf0NWi+U4vh9WVztgY8o8qAhyFMJ9OdShQbBhfsg7/CnUn0y3NszbDvVaOIx+FIBz5j50o/2JdcJSgK16R7Q3Vy38vjRVD45RXtkwTncm2Ss3qi4Qg6e85yP0k/CkkqhTR74zIAVr2zVhYuOqbSlBJdAIMgSDOfDY1FnuVpa0qSsHTkp3nPKmOpL4CPP6m3fXrgJMAuTPEMfNVLNJt3Gipx2CUkxPOaDdKSSAkZEzkH9KEh0AJBQCB86Oo8YcCnuiNPfECT060ElKXjpcMRNFJ7wFaWxpg4x4ftQFKPeq4RtRoqkMBxM6+8hwT+k/rVr58KAh1S9tzS2ohR4R9ihOKITtnFI4dBpbR1bkgSo8qAd/aNWJkDh+dUJHSiWRUEzvREuKBwqohIJTjejpQYHBnH60LM2ijaiqZM/CiJJB4Z+VRUJx3Y8dqqFDUrA8qZCPpbvVg+1vXUuukzrME/rXEKSFE6RB5SKKXm/yT446CiAfZduXGO5ccV3WqQPHrWg8+6FJK7lSlAk4QnciP0JrM/xBo2aWUshKwqe8gTFaDF6204kuWmseGn8oH0+fWpNO7OScJXYS1C1+y+sKSdaeEbgQD8zVbcuMIcS3dd0O9QIlOxBk58Up+4o9j2g0yO7XZalKOCAn8v3/AHpBpwqW676PLYeB0kpEbynP+5PyrK2yUYzb6ONKLndqd7QOrSgjKMGSfjIpeyZZNy84bzuy24NK5AkE5NVZuGWGgp201erRnh8c/fvoFvd27Tzi128oW4FhIAwJ2zTJMpGLp0HvHVuLt1O3PeFSlEklPCde/wBc07dJQLd5Sb7WshyUynMrE/Hesl64ZWWi21pLZMyBnikfLGadX2jZHSpNmICyY0jI1AgfDFanRnF/CLWV6+ltDYcOgAgDHPetu3fTcIl93IOoKIAyaRtbtt1SnW+zytCm1ZGjMET+nLOcU4ntRkgRYAiTng5R9CB+malNX4ODPByfEEvVlt3gvZMq/En8o/t7qAUtvskO3oIKttSc8Cf2j/j1oF3cJUrUbIiNWeHmj+CfjXGrhvulE2JMK9rgxKE/XPTi61kqQYYnqjRatmrdwG2uBIROoEH7xB99ZV9f3SCAh88JBTIGCDg0zfXBFprTaFtPDxnT49PMD3Zqi7hC0NuehH2UgHg3IIHzIOffSxTuxcUJbbPp59y7uGykocjQAE4GAJI/U/Gua1up1uukqPORvTF28044Ci20zpiIwZUf0I36UutMSTbmDtt1NdKPUVC60BZTqXHUyOooNw02hSglcxPMU2pScRb9eQ6g/T50u+tJKiGwnfkKNlY2VQfVphzSCVDl4UNzDpAUdvDpVEtqWOETiuwUSSjlWHVE1ScrPyoThminBPB9xQljG0bUBkVO8aj8qoqAd6uo/wBIrgnkmlY6GbZnW6hOoZp5yzU04lJUBB3jxrMZc0KBpty4W4UlfMVJ7WQmp7cL+jkrV6z3xQTb+sUCffTdikFwBYwTTvaSbNt5wMalAoAEjINH6naJfUalqYa2gmYM4qyWhJlUb/KuvaZMNq58qitPEdBAMwYq5e2yKbCW9aVDBFNpU4SJe+MdKTWUFPCkg6vlRtbWue5JT5CsLIKl5wnvC5xAgAY6Gr2y3got94QlStSsAnl+w+FDWttSQUsKAxnSK60ptzCUKORsgVhGuBwsPS0txZQAEYAGASRUFo3wcZBMSDECSBXW0hCVK7hyIElTYwKC/buKhSGVgH+nHhQQiffI0xYNuaQp8IkiSSMcUda7c9ntNKdCH0ygEwY6THxwaTtAAtaVsKWRAgDbNOsOsNsPJXarktKhUDhO0+GSM/vWdpgakn5C2JdNqUtXIA7tfCQNt+dEhaX1MqugEp1GYGfZ/j4VXsntSxtGgm4te8WAoHA5xAoFxfWT18t1NvpQQYTA8P5pa9z4S1k5Na8+40Qt1JUq8GT0T0oSnFtsnRdJIKvZhOTpH0A+FZy3mCrDcYOwHT96IlbJIWGFKTMTpxOkfX9aah1jHr19wWakC67xJKQUQPH9p99URcPFtoC5gJSgpSAmcZA+IpF1TfckBohcJyYGwAPzBPvrjKmgj1jJVlBJAGw3HvoKNDLGkixkEAPpIEQceO1UddXpjvtUeXWghSQniRJETtXFOtEABGYztTIrqWK1wPWfp98qGoqIOpU77iuJcbknQflULrXHKNxj6Vh0iqCUtiFdfpXJKlGVddxVApIHEJxUKkk4TWYxdKNRJ1DY/pXXGsDiH2K6yUhQ1JMVrWbdrcJDaobUfxr2qOSevSWSenTFda0xxCllTO5rT7QDSFlKcjqOdZiimdqMZWi+KVo4lVEKydI1YFLg1bHjRKNDrbxSRB59KuXSpxRK/IkUiPfV0kA5k0UkScF5GZUSTrFc1KKNJz7qCFJ6VcqTHCI86YFFzEn9quDA/ihqWnRABmrJU3+JPyogaNbsyyXeqS2FhKSJ9kHYEx8qG0whpTnrfWpeCRwzPtZ++tIIfKDDYiutqRu4gklSSMTjP8UtOyWkrfeHpLRhdxblTj7aR3aMaeWefxpO+uHGvVApKUCBCRnEfpjypRi7YQEhLRxAVw/zVVvoWpJU0oyQcjlOaRRakc8cUt7fgE0+6FrUFAKUZ28aabS4tD0vJGlChGncbxvj2RSduW0uLDjciRAjbNVe0KWENJg7QOfSqvp062xhy0CEAhyeIj2envoQZCnSjVEc6CtK0HStJEHpRTETpIPMxRSo1NBW7QKVBdA328p+tcYC1NlKVgDV03x/FU1IkhIk7+zVkrZQQXEkjoEfzWB0puSNUyeYFGZZW4ABtI/CKWccaI9WkgwNxzjPzrU7MvbFnSbhgrgpnA2ETz86Vt0CbklaRmPoLYiMnfAoKU8Te2fGj3jgcXKcUAKQkpJG2/jRTKRuiy0FJgEfD3fWqFE7kR5V1xbZUClOOeKoVInbFYdWcUkJGDNUq6lonANCM0BkGSr7iiJfKJg0mZ8amo0klZtLDPr1ZKppUnNWUomhE0EqKRjSIKsKlSiFl0qJq1SpRFZ0VapUphWWqCpUogLpMKBqwcUmCOgqVKIrLIcI2jiMmrB9eBjhGMVKlYRlFqKlFROSSTXUEpKVg8QMg+WalSsEs66p1WpUSDy+/Cq94egqVKJjoXxnA2qi1ExJ5VKlAxWoSZqVKwTknWBXF712pQGKHeoalSswooa7yqVKUJQqIFUJqVKA6K1w1KlAZH//2Q==); height: 2000px">

    <div class="notJonny">
<main style="font-style:oblique;font-size:80px">My Journey</main>
</div>
 
 
 <section>
<div class="text-wrapper" style="--text-color: #fff; position:relative; top: 150px; margin-left:20px;max-width:1100px  ">
  <h1 class="fade-from-left;"style="background-clip: text;color: black; text-shadow:-1px -1px 0 #fff,   1px -1px 0 #fff,-1px  1px 0 #fff,1px  1px 0 #fffF;font-family:Crimson Text;font-size:30px;font-weight:900 ;position:relative;top:-200px">Chapter One: The Start of my Writing Addiction
  </h2></h1>
  <p class="fade-from-left" style="width: 100%; font-family:spectral; font-size:19px;position:relative;top:-200px ">I started writing stories online in 4th Grade. Before, I only used the computer for gaming or occasionally writing essays for school. I had wrote a few short stories on paper, but without the help of a computer, my stories didn't go very far. This all changed, however, when I went to a writing camp over the summer after 3rd Grade with my friend Vincent. There, I was introduced to typing stories on a computer. <br><br>I remember coming up with a character named Wyatt Plague. It was about a nerdy kid who's dad kept on making him excersize. He was invited to join a battalion that belonged to a differenmt multiverese, provided he complete a quest. He meets Willow, a knowledgeble girl who knows about the different dimensions and helps his quest. I'm not going to spoil more than that, but it was still a good start. I was obsessed in typing he story, and all through summer I worked tirelessly. But with school started and my schedule overflowing with classes, sports, and schoolwork, I lost my enthusiasm for writing stories. And even when I did have free time, I barely wrote anything on it. I tried telling myself I was still typing, even though I barely typed fifty words a month. Then, one day, two of my friends came to save the day. </p>
<h1 class="fade-from-left"style="color: black; text-shadow:-1px -1px 0 #fff,   1px -1px 0 #fff,-1px  1px 0 #fff,1px  1px 0 #fffF;font-family:Crimson Text;font-size:30px;font-weight:900 ;position:relative;top:-200px">Chapter Two: The Rise of HFSNBW </h1>
<p class="fade-from-left" style="width: 100%; font-family:spectral; font-size:19px;position:relative;top:-200px ">Sean and Hao, later known as theGenius9 and PokeGod7, were sitting at a reccess table with a wrinkled paper in front of them and a pencil in their hands. I already knew Sean, who was one of my friends, but I barely knew Hao. I looked over to see what they were drawing and I was instantly confused. All I saw on that paper was meaningless scribbles. But then they explained what they were creating to me. I think the first project they showed me was a poem about hot messes formatted like a hot mess! There were scribbles and hand-drawn rips eveywhere, the handwriting was abmyssal and all over the place, which fit the poem perfectly. At first I thought they were idiotic or at the very best disorganized; now I know they're really creative geniuses. They invited me to there club, and I showed them my stories. Like I said, my stories were pretty terrible at the time, but my friends were extremely supportive. They edited my stories and gave me advice, and we started getting along really well. Theys started creating their own stories, and I dove deeper and deeper into their club.</p></div>  
</section>
<section>
<p>
  
  
  
  
  </p>
</section>
  In the second quarter of 4th Grade,  </p>
</div>
<div id="Profiles" class="tabcontent">
  
  <h3 style="font-damilyuj9">The Deviant Members </h3>
  <p>Tokyo is the capital of Japan.</p>

 
    <div class="timeline" style="width:100%">
    
        <div class="card" style="" >
            <div class="info" style="max-width:900px">
                <h3 class="title" style="position:relative; top:18px;"><span style="position:relative; top:-9px;font-family:Crimson Text">HFSNBW is Founded</span></h3>
                <p style="font-family:Spectral;position:relative;top:-11px">In 4th Grade Sean and Hao founded the AA Honors to annoy people that they didn't like. At first, it was only them two messing, but soon they started recuriting more and more members from Mr. Simonds class. They also change their name to "HFSNBW", which stood for "Heck Frick Sigma not bad words", to protest against the girls calling them out for saying heck, frick and, sigma. </p>
            </div>
        </div>
        <div class="card"style="">
            <div class="info" style="margin-left:452px;max-width:900px">
                <h3 class="title" style="position:relative; top:9px;"><span style="position:relative; top:-9px;font-family:Crimson Text;margin-right:32px">Obtuse Honors is  Founded to Rival HFSNBW</span></h3>
                <p style="font-family:spectral;position:relative;top:-15px;max-width:900px ">After HFSNBW was founded, an enemy club called Obtuse Honors was founded by Adam Luicano to try and overthrow HFSNBW. Both clubs started recruting more and more members, and they had regular "Blooket Wars," to see which one was better at Blooket. This was around the same time when notJonny(Me), one of the most Prominent members joined. But because I wasn't in the class the Blooket Wars took place in, I couldn't participate, and Obtuse Honors won the Blooket Wars by forfeit. (See "My Journey" for more Information on how I joined.) </p>
            </div>
        </div>
        <div class="card" style="border-radius: 50%">
            <div class="info" style="">
 <h3 class="title" style="position:relative; top:11px"><span style="position:relative; top:-9px;font-family:Crimson Text">Deviant Minds is Founded</span></h3>
                <p style="position:relative; top:-14px;font-family:Spectral;">notJonny founded Deviant Minds in 5th Grade to slowly take down HFSNBW and Obtuse Honors. In 5th Grade, both clubs were weakened as many club members left over the summer. And Deviant Minds was quickly gaining power. The three founders, notJonny, Quetz, and Vinsconte, started mass recrutuiting and making many new projects. And soon Deviant Minds began taking over HFSNBW and Obtuse Honors. Then, Sean, Haven, and Vincent, one of Deviant Minds' own founders, created a rebellion called Tree(4)ce. Deviant Minds' was in trouble, and so we allied with the remaining founder of HFSNBW, PG7, to take down Tree(4)ce. Finally, the major wars ended, and the clubs merged into Deviant Studios. </p>
            </div>
        </div>
        <div class="card" style="border-width:750px">
            <div class="info"style="margin-left:452px;max-width:900px">
                 <h3 class="title" style="position:relative; top:8px"><span style="position:relative; top:-9px; font-family:Crimson Text">The Shadow Arc</span></h3>
                <p style="position:relative; top:-14px;font-family:Spectral;">After the War of Factions ended, HFSNBW was now known as Deviant Studios.  But, as the most mischievous club member of the Deviant Studio, notJonny was getting bored. There was always something to do in the War of the Factions. But now, with nothing left to conquer notJonny was getting bored. Luckily, theGenius9, the captain (soon to be former captain) of the Deviant Studio had made a group chat for Deviant Studios to share our ideas. And, as the troublemaker notJonny was (and still is), he decided to cause some chaos. His plan was simple: pretend that the group chat got leaked and somebody had broken into it. He changed <span style="font-style:italic">everything</span>, from his username to his personality and the way he talked. He impersonated other people and lied about himself, all with HFSNBW (or Deviant Studios, it's confusing) having no idea who the mysterious stalker was. Each time theGenius9 and the othe members began to catch on, notJonny covered up his tracks perfectly, through calculated manipulation and alt accounts. And it got even crazier when he pulled out his secret weapon: his friend Wynn. He convinced him to help him with his plan of throwing HFSNBW into chaos. All was going perfectly well for notJonny and his plan was seemingly unstoppable...until he made a mistake that leaked his entire identity. </p>
            </div>
        </div>
        <div class="card" style="width:100%">
            <div class="info"style="width:100%">
               <h3 class="title" style="position:relative; top:11px; font-size:25px"><span style="position:relative; top:-9px;font-family:Crimson Text; transform: scaleX(1.9);font-size:28px">Peace (finally)</span></h3>
                  <p style="position:relative;top:-16px;font-family: spectral;font-size:15px;width:100%">                  <p style="position:relative;top:-16px;font-family: spectral;font-size:15px;width:100">Shadow seemed unstoppable. None of the members of HFSNBW knew what to do. But theGenius9 decided to go on Wyatt PLague for no reason. He check the version history, and he saw a name that he had never heard of before: "Wynn Zhang." He traced teh edits to a new tab created by notJonny, called "chat." It seemed to be a private chat for notJonny and his mysterious friend, but theGenius9 still investigated their messaged. He looked into past versions to find a message that was deleted right after it was created: a chat. TheGenius9 quickly copied the chat code and pasted it itno his browser. As notJonny didn't expect anybody to find out about his chat, he put minimum security, and theGenius9 easily entered the chat. He saw all of notJonny's plans for the future, giving him undeniable evidence that notJonny was guilty. NotJonny gave away his identity and his friend's identity (who was in a completely different school.) Luckily for notJonny, because he was one of the most prominent members of HFSNBW, he was forgiven and welcomed back into the club. </p></p>
            </div>
        </div>
          <div class="card" style="width:100%;">
            <div class="info"style="">
               <h3 class="title" style="position:relative; top:11px; font-size:25px"><span style="position:relative; top:-9px;font-family:Crimson Text; transform: scaleX(1.9);font-size:28px">The Great Proxy Hunt(Present) </span></h3>
                  <p style="position:relative;top:-16px;font-family: spectral;font-size:15px;width:100%">The Origin of the Great Proxy Hunt happened way before HFSNBW was ever founded. A 2nd Grader named Harrison managed to acquire the link of a proxy, a website that allows you to use any website unblocked. At the time, people in the school were using the district's computers, which blocked many websites. Proxies completely bypassed the blocking. They were like their own Googles, except with no restraints. NotJonny (still Jonathan at the time) managed to convince Harrison to give him the proxy. From their, NotJonny used that proxy to find loads and loads more proxies, and gave them away for power and friends. But after a year, many of the proxies that NotJonny had once possessed had been blocked. By 4th Grade, he had barely scraped together two proxy severs. But luckily, a new websites known as Nirbytes was created, with over 1000 proxy servers to use. Though many were blocked, notJonny had regained countless proxies. And then, one of his friends named Gavin, help him rise to his true power. Gavin sent him a document call "nyan cat hub", which had about <span style="font-style:italic;">100</span> proxies. This amount was incredibly large, even for notJonny, who only had about 30 proxies at the time. The Nyan Cat HUb also included HTML games, which he used in his unblocked games site. The Nyan Cat Hub made notJonny regain his passion for finding proxies. He continued to search for ways to unblock websites and other things. This led to him and theGenius9, another proxy hunter, to create "the hab," a document where they kept their proxy servers. They shared them to a tiny group of people and barely used them, because they knew the power proxies possessed.</p>
            </div>
        </div>
        
        
    </div>
    
</div>


<div id="Paris" class="tabcontent" style="background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-kYUlHLB9Uy1apdb89QfFfETTUYH740jztg&s');background-repeat: no-repeat; background-attachment: fixed; background-size: cover; ">
<div class="clipped-image"> <img src="data:image/jpeg;base64,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" alt="Description of the image"style="height:800px;position:relative; ">

</div>
<p class="outlined-text" style="font-size:12rem; position:relative;top:-700px;margin-left:50px;font-family:Times New Roman">
  SHOWCASE
</p>   <div style="position:relative;top:-540px"> 
<button class="glow-on-hover" type="button"  onclick="scrollToElement('section1')"style="height:70px; font-size:30px;width:400px;font-family:Courier New">AWESOME STORIES!</button> <button class="glow-on-hover" type="button"  onclick="scrollToElement('section2')"style="height:70px; font-size:30px;width:400px;font-family:Courier New">UNBLOCKED GAMES</button>
<button class="glow-on-hover" type="button"  onclick="scrollToElement('section3')"style="height:70px; font-size:30px;width:400px;font-family:Courier New">HTML WEBSITES!</button>
       
    



<br><br><br><br><br><br><br><br><br>
<div id="section1" style="height:500px; background-image: url(data:image/jpeg;base64,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);background-repeat: no-repeat; background-size: cover; height:800px;">

  <div class="hologram-container">
  <div class="hologram-text" style="background-color: transparent;text-align:center;font-size:60px;position-relative;top:60px;">Awesome Stories</div>
<p style="color:white;font-family:Spectral;font-size:21px;position:relative;top:60px;margin-left:12px">
Some of Deviant Studios' largest projects are our stories. All of our members have either edited or wrote a story. Some of the Story Creators are notJonny, who created notJonny's Awesome Stories, theGenius9, the owner of theGenius9's Horrible Stories. Other creators include, Quetz, PokeGod7, and IamSigma. The story community was started by notJonny, who went to Young Writer's Institute as a rising 4th grader. In the Young Writer's Institute, he created his first digital story: Wyatt Plague and the Land of Time. The story was very different from what it is now. At the time, Wyatt was in a world with different lands: pirates, technology, magic, and much more. The book made its way into HFSNBW, which just started at the time. The club members loved it, and started creating their own stories. <p>TheGenius9 was second to create a story, a collab with S7C which he called "Scrambled." It was about a person who wanted to compete in professianal cubing. He changed it drastically many times, changing it to a story many included club members as 20-year-olds, including himself, PokeGod7, and notJonny. Scrambled continued evolving and theGenius9 created more and more stories. <p>Meanwhile, PokeGod7 was working on his own story, Percy Klang. It was kind of a Harry Potter rip-off, but it was getting better. He changed the character's name from Percy Klang to Jack Cropman (<span style="font-style:italic">questionable</span> name choice), and made the story much more engaging. But he then created his greatest creation yet: The War of School. And though I greatly despise his choosing of the name "Jonathan", (I despise all his name choices, but this one I had a special hatred for) the story really took off.  At 2026 February 1st, he holds the second longest story in the Deviant Universe, surpassing theGenius9 even though PG7 started mcuh later.</p>
</div></div>
<div id="section2" style="height:1000px;background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3mnYGJmQUlr4ogymA5-YIbC3Dy-ubD1EAFg&s');background-size:cover;">
HELLO
</div>
</div>
<div id="section3" style="position:relative;top:-540px;height:1000px;background-image:url(data:image/jpeg;base64,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);background-size: cover; background-position: center; background-repeat: no-repeat;">
  <div class="hologram-container"  style="background-color: transparent">
  <div class="hologram-text" style="background-color: transparent;text-align:center;font-size:63px;position-relative;top:22px;">HTML Sites</div>
<p style="color:white;font-family:Spectral;font-size:20px;text-indent:18px">
I started coding HTML when</p>
</div></div></div>

</div>
<div id="Info" class="tabcontent" >

<div style="background-size: 1238px 260px; height:260px;width:1238px;background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRCQqV4bwn78USUtoPZ7j2vMk7KCCGvQ5Bq-w&s');">   <h1 class="h321"style="font-weight: 400"><span style="font-size:70px;position:relative;top:80px;font-weight: 580;font-family:Nixie One;transform: scaleX(0.7);margin-left:50px">Unleash Your Creativity</span></h1></div>
<div style="height:420px;background-image: linear-gradient(45deg, #301934, blue)"><h1 style="color:white;font-family:Cutive Mono;position:relative;top:20px;margin-left:4px;text-indent:10px;font-size:50px">Bold Origins</h1>
<p style="font-size:18px;color:white; margin-left:13px; width:780px;font-family:IBM Plex Mono;top:15px;position:relative"> The Deviant Universe was created for many purposes, but one of the biggest goals of the D.U is to create amazing projects to share with friends. In the beginning, we started tiny, with twenty page stories and nothing else. The Deviant Universe is a creative group of writers, coders, video creators, and designers, working together to create amazing prjects. We love improving ourselves and learning new things along the way. The Deviant Universe was also created for a way for students to have fun in school. We all know that school is dull and boring, and the members of the Deviant Universe know that just as well as anyone else. So we created a cub that allows you to have fun at school, even if it means bending the rules a tiny bit. We love exploring the internet for new things to create and always welcome new members. </p>
<img src="data:image/jpeg;base64,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" alt="Moon"style="position:relative;top:-362px;margin-left:820px;height:380px">
</div>
<div style="height:530px;background-image: linear-gradient(45deg, #00FFFF, violet);"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTvxFdLfJ7MbgpWcE8WRPaJzLbF61HENguyAw&s" alt="controller"style="position:relative;top:15px; height:480px;margin-left:14px">
<div style="position:relative; top:-480px;margin-left:515px;"><h1 style="font-family:Cutive Mono;font-size:50px"> Our Missions </h1><p style="font-family:IBM Plex MOno;font-size:15px; top:-10px;position:relative">In the Deviant Studio, we have many goals for the future. When AA, the starting point of the Deviant Universe was created, the main goal was to annoy Ariana and a group of friends she had, and the projects they created mostly involved plans to annoy her. Then, notJonny joined and changed everything. At that time, AA was almost finished evolving into HFSNBW, after Ariana has left the school. NotJonny joined HFSNBW after Obtuse Honors had declared war on HFSNBW. At the time, HFSNBW's goal was to beat Obtuse Honors in their club war. HFSNBW's only projects were little drawings on paper. And thought they had a mound and mounds of mini platformer levels, protests, and a bunch of other random projects they had made on paper. The problem was, these problems were disorganized and the members most usually forgot about and ended up in their classroom recycling bin. But notJonny showed them one of his projects that changed <span style="font-style:italic">everything.</span> At the time, notJonny had started a story called "Wyatt Plague," and though it was short, it was the biggest project HFSNBW had ever seen. Soon, many members dedicated themselves to creating amazing  projects. But notJonny wasn't content. He had a new mission: become the leader. He was one of the top members at the time, but not the ultimate leader. He became the most powerful member by bribing theGenius9 with proxies. Now Deviant Universe is all about creating projects and publishing them online, finding new interesting new websites.  </p></div>
</div>
<div style="height: 640px;background-color:white">
<img src="data:image/jpeg;base64,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"style="height:600px;width:430px;margin-left:10px;position:relative;top:20px" >
<h1 style="font-family:Cutive Mono;font-size:50px;color:black;margin-left:475px;position:relative;top:-600px"> Our Spotlight</h1>
  <p style="margin-left:475px;position:relative;top:-603px;font-family:IBM Plex Mono; font-size:16px">In the Deviant Studio, we have many dedicated members who love creating projects. Some of the longest term projects include Wyatt Plague and the Land of Time by notJonny& Quetz, which was 51000 words as of 2026 January 24th, notJonny's Awesome HTML Site (which is this!), theGenius9's Horrible Stories, with many "Horrible" stories (I actually think they're quite intereseting to read) the War of School by PokeGod7, Vincent's Video Game Arcade taht he coded on Replot, and PG7's rubix cube scrambler on Python. Other projects can include the Deviant Universe Blog, and our Canva Website. The leader for the longest and longest-lasting story is Wyatt Plague, at 51000 words, followed by PG7's War of School, at 19000 words. At the time I am writing this, I am also creating an unblocked games site on google sites. (You can play the games at <a href="https://sites.google.com/students.wcpss.net/notjonnysunblockedgames/home">notJonny's Unblocked Games Hub</a> now! We have also created a document called "The Hab," that holds many game's HTML codes, along with many other links we can use to unblock websites.) PokeGod7 has created countless things on Canva, including desk mats, posters, and logos. Quetz has made many logos on Canva, including animated ones. He has also created a trading card for himself. TheGenius9 created AI-Generated image collages, along with many other projects. I've created our Canva websites, my own trading card (work in progress) and manyshort videos on Canva. We also use Adobe for designing profile pictures, and occasionally Google Sites for websites that would be hard to code (Like unblocked game websites!).</p></div>
<div class="matrix-container">
    <div class="matrix-text" data-text="How to Join">How to Join</div><div class="rain"></div>
</div><h1 class="neon-green-text" style="text-align:center;font-size:27px;font-weight:normal;font-family:Courier New;position: relative; top: -40px;">To Join, Contact the Founders or Fill out this Google Form!</h1>
    <h1 class="glitch-text" data-text="Want Cool CSS Effects Like These?">Want Cool CSS Effects Like These?
<div class="container">
    <h1 class="awesome-buzz-effect">Awesome Buzz Effect</h1>
   <h1> Credits: Thank you to Ashish Ranjan for the Floating Holographic Blue text effects in the tab, "My Awesome Project Pool". Thank you to Emadamerho Nefe for the Neon Green Matrix Text Animation and the Neon Blue and Red Text effects. Thank you to Gayane Gasparyan for the text effect I used for the headers I used for Info,My Projects, and My Journey.
  </h1>
<section>
<div class="text-wrapper" style="--text-color: #fff; ">
  <h1 class="fade-from-left;"style="margin-left:-50px">Asset uploading is a PRO feature</h1>
  <p class="fade-from-left" style="width: 2000px; margin-left:-50px">As a PRO member, you can drag-and-drop upload files here to use as resources. Images, Libraries, JSON data... anything you want. You can even edit them anytime, like any other code on CodePen.</p>
</div>  
</section>
<section>
<p>
  
  
  
  
  </p>
</section>

</section></div></div></div></div>
<div id="Contact" class="tabcontent"style="background-color:white">
  <h3>Tokyo</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>
</body>


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
document.getElementById("defaultOpen").click();
 function scrollToElement(elementId) {
    const targetElement = document.getElementById(elementId);
    if (targetElement) {
        targetElement.scrollIntoView({
            behavior: 'smooth', // Optional: for smooth scrolling
            block: 'start'      // Aligns the top of the element with the top of the viewport
        });
    }
}
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}

</script>
   

</html> 

































