<template>
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Piazzolla:wght@200&display=swap" rel="stylesheet">
  <div id="about">
    
<div class="wrapper">
  <div class="text">
<h5>Who we are.</h5>
<h3>About us</h3>

  </div>
  </div>


  
<div class="about-section">
<div class="inner-width">
	<h1>About Us</h1>
	<div class="border"></div>
	<br><br><br>
	<div class="about-section-row">
	<div class="about-section-col">
		<div class="about">
			<p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts.Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.

A small river named Duden flows by their place and supplies it with the necessary regelialia. It is a paradisematic country, in which roasted parts of sentences fly into your mouth.Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic life.</p>
			
		</div>
	</div>

	<div class="about-section-col">
		<div class="skills">
			<div class="skill">
				<div class="title">Web Design</div>
				<div class="progress">
					<div class = "progress-bar p1"><span>90%</span></div>
				</div>
			</div>
			<div class="skill">
				<div class="title">UI Design</div>
				<div class="progress">
					<div class = "progress-bar p2"><span>70%</span></div>
				</div>
			</div>

			<div class="skill">
				<div class="title">UX Design</div>
				<div class="progress">
					<div class = "progress-bar p3"><span>60%</span></div>
				</div>
			</div>
		</div>
	</div>

</div>
</div>

 </div>


 
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
  color:  white;
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




.about-section{
	width: 100%;
	background-color: #f1f1f1;
	padding: 40px 0;
}

.inner-width{
	max-width: 1000px;
	overflow: hidden;
	padding: 0 20px;
	margin:auto;
}

.about-section h1{
	text-align: center;
	font-size: 20px;
	text-transform: uppercase;
	color: #232d60;
}

.border{
	width: 100px;
	height: 4px;
	background-color: #232d60;
	margin: 10px auto;
}

.about-section-row{
	display: flex;
	flex-wrap: wrap;
}


.about-section-col{
	flex:50%;
}

.about{
	padding-right: 30px;
}

.about p{
	text-align: justify;
	margin-bottom: 20px;
	font-size: 17px;
}


.skills{
	padding-left: 30px;
}

.skill{
	margin-bottom: 10px;
}

.progress{
	width: 100%;
	height: 12px;
	background: #ddd;
	border-radius: 12px;
}

.progress-bar{
	height: 12px;
	background-color: #232d60;
	border-radius: 12px;


}


.p1{
	width: 90%
}

.p2{
	width: 70%;
}

.p3{
	width: 60%;
}

.progress span{
	float: right;
	margin-right: 6px;
	line-height: 13px;
	color: #fff;
	font-size: 12px;
}

@media screen and (max-width: 700px){
	.about-section-col{
		flex: 100%; 
		margin:10px 0;
	}

	.about, .skills{
		padding: 0;
	}

	.about{
		text-align: center;
	}
}




/*===========CONTACT FORM=========*/



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