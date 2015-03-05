#Poly-icon

![Polymer](https://www.polymer-project.org/images/logos/p-logo.svg)


This is a example using polymer to create a web component to make a image, with a link and css filter.

## Contents
- [Set Up](#set-up)
- [Run Server] (#run-server)
- [Passing Parameters](#map-methods)

## Set up

**Install bower**

    npm install -g bower

**Install polymer**

    //Locate in the root's directory of repository and install dependencies
    bower install

## Run Server

**I use python <3**

    //Run a server o locate this repo in a server
    python -m SimpleHTTPServer

## Passing Parameters

**Use the component**

    <!DOCTYPE html>
    <html>
    	<head>
    		<!--Import script of web components -->
      		<script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
      		<!--Import the component poly-icon -->
      		<link rel="import" href="icono-poly.html">
    	</head>
    	<body>
    	
    		<!--Use it :) -->
    		<icono-poly></icono-poly>
    		
    		<!-- 
    			url : link to web site
    			image : image's url
    			filter : filter css to add
    			amount : accept % or px
    		-->
    		<icono-poly url="http://yeoman.io/"
    			image="http://www.w3schools.com/images/w3logotest2.png"
    			filter="grayscale"
    			amount="90%">
    		</icono-poly>
    	</body>
    </html>

