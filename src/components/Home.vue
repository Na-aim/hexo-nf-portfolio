<template>
  <div class="space">
  <img src="https://i.postimg.cc/wBxQwLvD/workwork.png" />
  <svg
    width="380px"
    height="500px"
    viewBox="0 0 837 1045"
    version="1.1"
    xmlns="http://www.w3.org/2000/svg"
    xmlns:xlink="http://www.w3.org/1999/xlink"
    xmlns:sketch="http://www.bohemiancoding.com/sketch/ns"
  >
    <g
      id="Page-1"
      stroke="none"
      stroke-width="1"
      fill="none"
      fill-rule="evenodd"
      sketch:type="MSPage"
    >
      <path
        d="M78.5,529 L147,569.186414 L147,648.311216 L78.5,687 L10,648.311216 L10,569.186414 L78.5,529 Z"
        id="Polygon-2"
        stroke="#AFDBF5"
        stroke-width="6"
        sketch:type="MSShapeGroup"
      ></path>
      <path
        d="M773,186 L827,217.538705 L827,279.636651 L773,310 L719,279.636651 L719,217.538705 L773,186 Z"
        id="Polygon-3"
        stroke="#89CFF0"
        stroke-width="6"
        sketch:type="MSShapeGroup"
      ></path>
      <path
        d="M639,529 L773,607.846761 L773,763.091627 L639,839 L505,763.091627 L505,607.846761 L639,529 Z"
        id="Polygon-4"
        stroke="#6CA0DC"
        stroke-width="6"
        sketch:type="MSShapeGroup"
      ></path>
      <path
        d="M281,801 L383,861.025276 L383,979.21169 L281,1037 L179,979.21169 L179,861.025276 L281,801 Z"
        id="Polygon-5"
        stroke="#6495ED"
        stroke-width="6"
        sketch:type="MSShapeGroup"
      ></path>
    </g>
  </svg>

  <div class="content">
    <span class="hi"> Hi there... </span>
    <h1>I am <span> Na-aim Fredericks </span></h1>
    <p class="info">I am an aspiring web developer<br>ui designer </p>
    <p class="text"></p>
  </div>

	
		<div class="up">
			<div class="hexa-social">
				<a href="" target="_blank">
					<i class="fab fa-linkedin-in"></i>
				</a>
			</div>
			<div class="hexa-social">
				<a href="" target="_blank">
					<i class="fab fa-github"></i>
				</a>
			</div>
      <div class="hexa-social">
				<a href="" target="_blank">
					<i class="fab fa-codepen"></i>
				</a>
			</div>
		</div>
	
  
  </div>
</template>
   
   <script>
export default {};
</script>
   
   <style scoped>

   .space{
    padding-top: 100vh;
   }

   /* style for the icons */

.hexa-social {
	height: 40px;
	width: 90px;
	background: #222;
	position: relative;
	float: left;
	margin-right: 5px;
	cursor: pointer;
	transition:all ease .3s;
}
.hexa-social i {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    font-size: 30px;
		color: var(--main-color);
}

.hexa-social:before {
	position: absolute;
	bottom: 100%;
	content: '';
	height: 0;
	width: 0;
	border-width: 0 45px 30px 45px;
	border-style: solid;
	border-color: #222 transparent;
	transition:all ease .3s;
	-webkit-transition:all ease .3s
}

.hexa-social:after {
	position: absolute;
	top: 100%;
	content: '';
	height: 0;
	width: 0;
	border-width: 30px 45px 0 45px;
	border-style: solid;
	border-color: #222 transparent;
	transition:all ease .3s;
	-webkit-transition:all ease .3s
}



.up {
	position: absolute;
  top: 78%;
  left: 50%;
  margin-top: -100px;
  margin-left: 10px;
}




/*
* Hover
* */
.hexa-social:hover{
	background-color: #000;
}

.hexa-social:hover:before, .hexa-social:hover:after {
	border-color: #000 transparent;
} 

   /* end style for icons */


.content {
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -100px;
  margin-left: 10px;
}

.content .hi {
  font-size: 26px;
  color: var(--main-color);
}

.content h1 {
  font-size: 66px;
  color: aliceblue;
}

.content span {
  color: var(--main-color);
}

.content .info {
  font-size: 26px;
  color: aliceblue;
  padding: 8px;
}

.content .text {
  font-size: 18 px;
  color: #666;
  padding: 8px;
}

img {
  /* position: fixed; */
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -232px;
  margin-left: -665px;
  width: 250px;
  height: 260px;
}
svg {
   /* position: fixed; */
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -250px;
  margin-left: -710px;
}

img {
  animation: float 1s infinite ease-in-out alternate;
}
#Polygon-1,
#Polygon-2,
#Polygon-3,
#Polygon-4,
#Polygon-4,
#Polygon-5,
#Polygon-6 {
  animation: float 1s infinite ease-in-out alternate;
}
#Polygon-2 {
  animation-delay: 0.2s;
}
#Polygon-3 {
  animation-delay: 0.4s;
}
#Polygon-4 {
  animation-delay: 0.6s;
}
#Polygon-5 {
  animation-delay: 0.8s;
}


@keyframes float {
  100% {
    transform: translateY(20px);
  }
}
@media (max-width: 450px) {
  img {
    position: absolute;
    top: 48%;
    left: 57.3%;
    margin-top: -250px;
    margin-left: -190px;
  }
  svg {
    position: absolute;
    top: 50%;
    left: 50%;
    margin-top: -250px;
    margin-left: -190px;
  }
  .content {
    top: 50%;
    left: 50%;
    margin-top: -100px;
    margin-left: -250px;
    text-align: center;
  }
  .content h1 {
    font-size: 44px;
    color: aliceblue;
  }
  .content .info {
    font-size: 22px;
    color: aliceblue;
  }
  #Polygon-3, #Polygon-4, #Polygon-5 {
  display:none;
}
.up {
  
    top: 80%;
    left: 70%;
    margin-top: -100px;
    margin-left: -250px;
    
}
}
</style>