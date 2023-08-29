<template>
    <div>
        <div class="container mt-5 mb-5">
            <div class="row mt-5">
                <div class="col-12">
                    <h3 class="text-center tex">Our Partners</h3>
                </div>
            </div>
           <div class="row">
              <div class="col-12 container">
                <p class="text-center">We partner internationally recognized Pharmaceutical companies across the </p>
                    <p class="text-center">globe. The partners that trust us have huge value for their money. </p>
              </div>
           </div>


		</div>
       
           <div>
            <div class="slider-area">
		<h2>Our Clients</h2>
		<div class="wrapper">
			<div class="item"><img alt="" src="../assets/f1.png" class="img-fluid "></div>
			<div class="item"><img alt="" src="../assets/f2.png" class="img-fluid ml-5 mr-5 ml "></div>
			<div class="item"><img alt="" src="../assets/f3.png" class="img-fluid ml-5 mr-5 ml "></div>
			<div class="item"><img alt="" src="../assets/f4.png" class="img-fluid ml-5 mr-5 ml"></div>
			<div class="item"><img alt="" src="../assets/f5.png" class="img-fluid ml-5 mr-5 ml"></div>
            <div class="item"><img alt="" src="../assets/f6.png" class="img-fluid ml-5 mr-5 ml"></div>
            <div class="item"><img alt="" src="../assets/f7.png" class="img-fluid ml-5 mr-5 ml"></div>
		</div>
	</div>
           </div>
       
 
    </div>
 
</template>

<script>
export default {
name:'ourProject'
}
</script>

<style>

.ml{
    margin-right:200px !important;
	width:220.75px;
	height:60px;
}
.it{
    width:100px;
    height:100px;
}
@font-face {
  font-family: 'CustomFont'; /* Provide a name for your font */
  src: url('../assets/font/Millik\ Regular.otf') format('otf');
     
  font-weight: normal;
  font-style: normal;
}
 *{
	font:'CustomFont';
 }
.slider-area h2 {
	text-align: center;
	font-family: impact;
	font-size: 60px;
	font-weight: 500;
	text-transform: uppercase;
	letter-spacing: 2px;
	/* margin: 100px 0 30px 0; */
	color: #fff;
}
.wrapper {
	display: flex;
	width: inherit;
	margin: 0 auto;
	overflow: hidden;
    justify-content: center;
      align-items: center;
      height: 40vh;
	/* border-radius: 180px; */
	padding: 2.5rem;
	/* background: #ddd; */
	/* box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px; */
}
.item {
	animation: animate 25s alternate linear infinite;
}
.container:hover .item {
	animation-play-state: paused;
}
@keyframes animate {
	0% {
		transform: translate3d(0, 0, 0);
	}
	100% {
		transform: translate3d(-1100px, 0, 0);
	}
}
@media (max-width:767px) {
	.slider-area h2 {
		font-size: 30px;
	}
	.wrapper {
		width: 95%;
		border-radius: 0;
		padding: 0;
	}
}

  .tex{
    color:#18564C;
    font-family: 'Customfont';
    font-weight:bold;
  }
  @font-face {
  font-family: 'CustomFont'; /* Provide a name for your font */
  src: url('../assets/font/Millik\ Regular.otf') format('otf');
     
  font-weight: normal;
  font-style: normal;
}
 
</style>