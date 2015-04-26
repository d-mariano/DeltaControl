<html>
<head>
<meta charset='utf-8'>
<meta http-equiv="X-UA-Compatible" content="chrome=1">
<link rel="stylesheet" type="text/css" href="https://github.com/d-mariano/DeltaControl/tree/gh-pages/stylesheets/stylesheet.css" media="screen">
<link rel="stylesheet" type="text/css" href="https://github.com/d-mariano/DeltaControl/tree/gh-pages/stylesheets/pygment_trac.css" media="screen">
<link rel="stylesheet" type="text/css" href="https://github.com/d-mariano/DeltaControl/tree/gh-pages/stylesheets/print.css" media="print">
<title>Deltacontrol by d-mariano</title>
</head>
<body>
<header>
<div class="container">
<h1 align="center">Delta Laser</h1>
<h2 align="center">Server Repository</h2>
<section id="downloads">
<p align="center">
<a href="https://github.com/d-mariano/DeltaControl/zipball/master" class="btn">Download as .zip</a>
<a href="https://github.com/d-mariano/DeltaControl/tarball/master" class="btn">Download as .tar.gz</a>
<a href="https://github.com/d-mariano/DeltaControl" class="btn btn-github"><span class="icon"></span>View on GitHub</a>
</p>
</section>
</div>
</header>
<div class="container">
<section id="main_content">
<h2>
<a id="welcome" class="anchor" href="#welcome" aria-hidden="true"><span class="octicon octicon-link"></span></a>Welcome</h2>
<p>The major goal for DeltaControl is to relay commands from a mobile device to a control system that manipulates the motors and carriages on a delta robot via G-code. Generally, some sort of device that is capable of running Python and has a USB port is required to run the server. There are libraries needed from the <a href="https://github.com/kliment/Printrun">Printrun</a> open-source package for this server to run. A robot controlled with a RepRap (Marlin, Repetier, etc) firmware loaded board is required. In our case, we have an Arduino Mega with a RAMPS (Reprap Arduino Mega Pololu Shield) and Marlin firmware controlling the 3 stepper motors of a delta robot. The RAMPS has an SD attachment, it is optional to use one of these for storing routines. Which routines will be executed depends on the commands received from the client communicating with the DeltaControl server. The DeltaControl server will recognize certain phrases/commands the client sends and load and execture the appropriate G-code file on the SD card.</p>
</section>
</div>
</body>
</html>
