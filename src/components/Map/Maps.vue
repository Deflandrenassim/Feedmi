<template>
  <div>

  
 <h4>{{ reseau }} </h4>
  <!--  <div class="background">
  <div class="container-logo">
      <div class="logo">
        <i class="fa-brands logos fa-instagram"></i>
        <i class="fa-brands logos fa-facebook"></i>
        <i class="fa-brands logos fa-github"></i>
        <i class="fa-brands logos  fa-twitter"></i>
     </div>
  </div>
  </div> -->


<svg class="svg" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Calque_1" x="0px"
     y="0px" viewBox="0 0 1300 550" style="enable-background:new 0 0 1300 550;" xml:space="preserve">


    <path class="st1" fill="#00cba9" fill-opacity="1" d="M 0 250 C 600 450 650 100 1300 250 L 1300 550 L 0 550 L 0 250">
		<animate
                attributeName="d"
                dur="5s"
				begin="1s"
                values="M 0 250 C 600 450 650 100 1300 250 L 1300 550 L 0 550 L 0 250;
                M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250;
				M 0 250 C 600 450 650 100 1300 250 L 1300 550 L 0 550 L 0 250"
                repeatCount="indefinite"
        />
	</path>


	<path class="st1" fill="#00cba9" fill-opacity="1" d="M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250">
		<animate
                attributeName="d"
                dur="5s"
                values="M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250;
                M 0 250 C 600 450 650 100 1300 250 L 1300 550 L 0 550 L 0 250;
				M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250"
                repeatCount="indefinite"
        />
	</path>

	<path class="st1" fill="#00cba9" fill-opacity="1" d="M 0 250 C 950 350 950 150 1300 250 L 1300 550 L 0 550 L 0 250">
		<animate
                attributeName="d"
                dur="5s"
				begin="2s"
                values="M 0 250 C 950 350 950 150 1300 250 L 1300 550 L 0 550 L 0 250;
                M 0 250 C 350 150 350 350 1300 250 L 1300 550 L 0 550 L 0 250;
				M 0 250 C 950 350 950 150 1300 250 L 1300 550 L 0 550 L 0 250"
                repeatCount="indefinite"
        />
	</path>

	<path class="st1" fill="#00cba9" fill-opacity="1" d="M 0 250 C 350 150 350 350 1300 250 L 1300 550 L 0 550 L 0 250">
		<animate
                attributeName="d"
                dur="5s"
                values="M 0 250 C 350 150 350 350 1300 250 L 1300 550 L 0 550 L 0 250;
                M 0 250 C 950 350 950 150 1300 250 L 1300 550 L 0 550 L 0 250;
				M 0 250 C 350 150 350 350 1300 250 L 1300 550 L 0 550 L 0 250"
                repeatCount="indefinite"
        />
	</path>

</svg>

  </div>
</template>

<script>
export default {
    name:'Maps'
}
</script>

<style scoped>

.container-logo{
  display: flex;
  flex-direction: column;
  justify-content: center;

}
.logo{
  display: flex;
  justify-content: space-around;
position: absolute;
    bottom : -100px;
}






</style>