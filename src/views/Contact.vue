<template>
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <div class="page">

<div class="wrapper">
  <div class="text">
<h5>Contact.</h5>
<h3>Get in touch with us</h3>

  </div>
  </div>

<br><br><br><br><br>

<div class="contact-section">
	<div class="inner-width">
		<h1>Get in Touch</h1>
		<input type="text" class="name" placeholder="Your Name">
		<input type="email" class="email" placeholder="Your Email">
		<textarea rows="1" placeholder="Message" class="message"></textarea>
		<button>Get in Touch</button>
	</div>
</div>




<div class="contact-wrapper">
	
	<div class="contact-info">
		<div class="card">

			<i class="material-icons" id="card-icon">mail</i>
			<p>designs@gmail.com</p>

	</div>

	<div class="card">

			<i class="material-icons" id="card-icon">phone</i>
			<p>+233 234 324 4354</p>

	</div>


	<div class="card">

			<i class="material-icons" id="card-icon">map</i>
			<p>Osu, New Street, Accra, Ghana</p>

	</div>
</div>

</div>






    </div>
</template>


<style scoped>


.wrapper{
  background:linear-gradient(to right, #283048, #859398);
  width:100%;
  height: 60vh;
}

.wrapper .text{
  text-align:center;
  color:white;
  padding-top:8%;
  letter-spacing: 5px;
  line-height: 50px;
}

.text h3{
  font-size: 35px;
  font-weight: 900;
font-family: 'Piazzolla', serif;
}

button{
  background: none;
	color: #70a1ff;
	border:1px solid #70a1ff;
	padding: 12px 40px;
	border-radius: 8px;
	text-transform: uppercase;
	font-size: 14px;
	transition: 0.4s linear;
	cursor: pointer;
  margin-top:2%;
}



.contact-section{
	background: #313840;
	padding: 80px 0;
	text-align: center;
}

.contact-section .inner-width{
	max-width: 600px;
	margin: auto;
	padding: 0 20px;
}

.contact-section .inner-width h1{
	font-size: 20px;
	color: white;
	margin-bottom: 40px;
	text-transform: uppercase;
	letter-spacing: 4px;
	font-weight: 400;
}

.contact-section .name, .email, .message{
	background: none;
	border: none;
	outline: none;
	border-bottom: 1px solid;
	color: #888;
	padding: 10px 6px;
	font-size: 14px;
	margin-bottom: 40px;

}

.contact-section .name{
	float: left;
	width: 270px;
}


.contact-section .email{
	float: right;
	width: 270px;
}



.contact-section .message{
	min-width: 100%;
	max-width: 100%;
}

.contact-section button{
	background: none;
	color: #70a1ff;
	border:1px solid #70a1ff;
	padding: 12px 40px;
	border-radius: 8px;
	text-transform: uppercase;
	font-size: 14px;
	transition: 0.4s linear;
	cursor: pointer;
}

.contact-section button:hover{
	background: #70a1ff;
	color: #fff;
}

@media screen and (max-width: 600px){
	.name, .email{
		width: 100%;
	}
}



.contact-wrapper{
	background-color: #f1f1f1;
	min-height: 50vh;
	display: flex;
	align-items: center;
	justify-content: center;


}

.contact-info{
	display: flex;
	width: 100%;
	max-width: 1200px;
	align-items: center;
	justify-content: center;
	padding: 0 20px;
}


.card{
	background-color: #2f3542;
	padding: 0 20px;
	margin:0 10px;
	width: calc(33% - 20px);
	height: 200px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	color: #fff;
	cursor: pointer;
}

.card i{
	font-size: 28px;
	
	width: 60px;
	height: 60px;
	text-align: center;
	line-height: 60px !important;
	border-radius: 50%;
	transition: 0.3s linear;
}

.card:hover #card-icon{
	background: none;
	color: #ff6348;
	transform:scale(1.6);
}

.card p{
	margin-top: 20px;
	font-weight: 200;
	letter-spacing: 2px;
	min-height: 0;
	opacity: 0;
	transition: 0.3s linear;
}

.card:hover p{
max-height: 40px;
opacity: 1;
}


@media screen and (max-width: 800px){
	.contact-info{
		flex-direction: column;
	}

	.card{
		width: 100%;
		max-width: 300px;
		margin: 10px 0;
	}
}


</style>