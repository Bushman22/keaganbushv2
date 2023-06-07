<script>

    import { bubble, object_without_properties, resize_observer_border_box } from "svelte/internal";
    
</script>

<div class ="webContainer">

 <head>
  <link rel="icon" type="image/svg+xml" href="static\assets\iconk.png"/>
  <title>Keagan Bush</title>
</head>
<main>


  <div class="navbar">
    <nav>
      <ul>
        <img src="/logo.png" alt="logo" height = 50px>
        <li><a href="/">home</a></li>
		    <li><a href="/about">about</a></li>
   	 	  <li><a href="/contact">contact</a></li>
        <li><a href="https://youtu.be/dQw4w9WgXcQ">More</a></li>
        <img src="/logo.png" alt="logo" height = 50px>
      </ul>
    </nav>
  </div>


  <div class ="wording1">
  <h1>Hi, I'm Keagan Bush<br/>
   <ml>YOUR NEW AND INNOVATIVE DEVELOPER</ml></h1>
</div>

  <div class ="wording2">

  <h2 >Welcome to my site, here you will find
    everything you need to know about me<br/>
    You will find my work experience, contact details and my resume<br/>
      Feel free to browse</h2>
  </div>

<div class ="resume">
  <button><a style=text-decoration:none; href="./assets/KJB.pdf" download>Download my resume</a></button>
  </div>
<div class ="horizon">
  <img src = '.\assets\city.png' alt = 'city' width = 100%>

</div>

</main>

<lk>
</lk>

<style>

:root {
  font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.5;
  font-weight: 400;

  color-scheme: none;
  color: black;
  background:#99BADD;
  

  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-text-size-adjust: 100%;
}

.wording1{
text-align:center;
padding:50px;
background: none;
font-size:20px;
}

.wording2{
text-align:center;
padding:4px 40px;
text-transform:uppercase;
background: none;
font-size:18px;
color:black;
}

.resume{
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 100px ;
}

.horizon{
  display: flex;
  align-items: center;
  justify-content: center;
}
a {

  color: white
}



ml {
  color:#202A44;
  font-size: 45px;
  
 }


    * {
      margin:0;
      box-sizing:border-box;
    }

    .navbar {
      background: black;
      
        }
      
    
    .navbar ul{
       list-style-type:none;
       padding: 30px;
      }
    .navbar li {
    border: 2px solid black;
    border-radius:10px;
    margin-left:20px;
    margin-right:20px;
    padding: 10px 30px 10px 30px;

      }
      
    .navbar a {
      display:Block;
      color: white;
      text-decoration:none;
      text-transform: uppercase;
      font-weight:500;
    
      }

    
      


      @media screen and (min-width:700px){
        .navbar ul {
        display:flex;
        justify-content: center;}
        button { display:flex;}
        

      }
        
  

  button {
    border-radius: 10px;
  border: 1px solid transparent ;
  padding: 0.6em 1.2em;
  font-size: 1.5em;
  font-weight: 700;
  font-family: inherit;
  background-color: black;
  cursor: pointer;
  transition: border-color 0.25s;
  color: white;
  text-decoration:none;


}
button:hover {
background-color: grey;
border:none;
color: rgb(255, 255, 255);
box-shadow: 0px 5px 25px black;
}

</style>
</div>
