<template>

  <div id="nav">

    <router-link to="/">Home</router-link> 
    <router-link to="/about">About</router-link>
    <router-link to="/contact">Contact</router-link>
	</div>


  <router-view/>
</template>

<style>

*{
margin:0;
padding: 0;
}


body{
font-family: 'montserrat', sans-serif;
font-size:20px;
margin-left:auto;
margin-right:auto;
}



#app {


}


#nav{
	 background:linear-gradient(to right, #283048, #859398);
	height:50px;
	text-align:center;
	padding-top:20px;
  
	
}


.lg{
  text-align: left;
}

#nav a {
  
  text-decoration: none;
  padding: 15px;
  color:white;
  font-size: 17px;
}

#nav a.router-link-exact-active {

}
</style>
