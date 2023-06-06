
<body>
<script>
 import button from '/src/button.svelte'
 </script>
 <head>
  <link rel="icon" type="image/svg+xml" href="static\assets\iconk.png"/>
  <title>Keagan Bush</title>
</head>
<main>
<body>

</body>



  <div class="navbar">
    <nav>
      <ul>
        <li><a href="/">home</a></li>
		<li><a href="/about">about</a></li>
   	 	<li><a href="/contact">contact</a></li>
      </ul>
    </nav>
  </div>


  <h1>Hi, I'm Keagan Bush. <ml>YOUR NEW AND INNOVATIVE DEVELOPER</ml></h1>
  <h2>Welcome to my site, here you will find
    everything you need to know about me and my work experince <br/>
     From contact details to my resume, feel free
      to browse.</h2>

<pic1><img src = '.\assets\character.png' alt = 'man' height = 500px></pic1>
<pic2><img src = '.\assets\sitting.png' alt = 'man' height = 300px></pic2>
  
<a href=".\assets\KJB.pdf" download="Resume">
  <button>Download My Resume</button>
</a>


<a href="https://youtu.be/dQw4w9WgXcQ">
  <rickbutton>Find out more</rickbutton>
</a>
  

</main>
<lk>
<footer><a href="/nothing" style="color: white;">Nothing to see here</a></footer>
</lk>

<style>
	:root {
  font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.5;
  font-weight: 400;

  color-scheme: none;
  color: rgba(255, 255, 255, 0.87);

  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-text-size-adjust: 100%;
}

body {
  margin: 0;
  display: flex;
  place-items: center;
  min-width: 320px;
  min-height: 150vh;
  background-image: linear-gradient(#D4AF37,gray,gray , black);

}

pic1 {
  position: absolute;
  top: 300px;
  left:1000px;

}

pic2 {
  position: absolute;
  top: 500px;
  left:100px;
}



h1 {
  font-size: 2.5em;
  line-height: 1.2;
  color: white;
  position: absolute;
  top:200px;
  left:100px;
}

h2 {
  font-size: 1.3em;
  line-height: 1.0;
  color: #c7c67b;
  position: absolute;
  top:300px;
  left:100px;
}

ml {
  color:#D4AF37;
  font-size: 0.9em;
 
 }



button {

  position: absolute;
  top: 410px;
  left:100px;
  }

  rickbutton {

    position: absolute;
    top: 45px;
    right:100px;
    }


    .navbar {
      background-image:linear-gradient(grey, lightgray);
      width:800px;
      border-radius :10px;
      float: left;
      position:absolute;
      top:40px;
      left:350px;
        
        }
      
    
      
    
    .navbar ul li {
      float: left;
      width: 100px;
      height :58px;
      line-height:40px;
      margin-left:100px;
      list-style:none;

      }
      
    .navbar ul li a {
      display:block;
      color: white;
      text-align: center;
      text-decoration:none;
      text-transform: uppercase;
      padding:0px 10px px 10px;
    
      }
      
    .navbar ul li a:hover {
      background-color: #D4AF37;
      border-radius:10px;
      
      
      }

      .aboutbar {
        background-image:linear-gradient(grey, lightgray);
        width:580px;
        border-radius :10px;
        float: left;
        position:absolute;
        top:40px;
        left:450px;
          
          }
        
      
        
      
      .aboutbar ul li {
        float: left;
        width: 100px;
        height :58px;
        line-height:40px;
        margin-left:100px;
        list-style:none;
  
        }
        
      .aboutbar ul li a {
        display:block;
        color: white;
        text-align: center;
        text-decoration:none;
        text-transform: uppercase;
        padding:0px 10px px 10px;
      
        }
        
      .aboutbar ul li a:hover {
        background-color: #D4AF37;
        border-radius:10px;
      }
        
  h1 {text-align: left;}
  h2 {text-align: left;}

  button {
  border-radius: 8px;
  border: 1px solid transparent ;
  padding: 0.6em 1.2em;
  font-size: 1.5em;
  font-weight: 700;
  font-family: inherit;
  background-color: #D4AF37;
  cursor: pointer;
  transition: border-color 0.25s;
  color: white;

}
button:hover {
background-color: grey;
border:none;
color: rgb(255, 255, 255);
box-shadow: 0px 5px 25px rgba(216, 194, 20, 0.9);

}
rickbutton{
border-radius: 8px;
  border: 1px solid transparent ;
  padding: 0.6em 1.2em;
  font-size: 1.5em;
  font-weight: 700;
  font-family: inherit;
  background-color: #D4AF37;
  cursor: pointer;
  transition: border-color 0.25s;
  color: rgb(255, 255, 255);

}

rickbutton:hover {
background-color: grey;
border:none;
color: rgb(255, 255, 255);

}

footer {
  position: absolute;
  text-align: center;
  padding:30px;
  background-color: rgb(0, 0, 0);
  color: rgb(253, 252, 252);
  width:96%;
  float:left;
  bottom:-400px;
  left:0px;
}


</style>
</body>