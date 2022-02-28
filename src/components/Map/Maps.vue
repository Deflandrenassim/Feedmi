<template>
  <div>
<div class="map">
     
</div>


<svg class="svg" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Calque_1" x="0px"
     y="0px" viewBox="0 0 1300 550" style="enable-background:new 0 0 1300 550;" xml:space="preserve">


    <path class="st1" d="M 0 250 C 600 450 650 100 1300 250 L 1300 550 L 0 550 L 0 250">
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

	<path class="st1" d="M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250">
		<animate
                attributeName="d"
                dur="5s"
                values="M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250;
                M 0 250 C 600 450 650 100 1300 250 L 1300 550 L 0 550 L 0 250;
				M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250"
                repeatCount="indefinite"
        />
	</path>

	<path class="st1" d="M 0 250 C 950 350 950 150 1300 250 L 1300 550 L 0 550 L 0 250">
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

	<path class="st1" d="M 0 250 C 350 150 350 350 1300 250 L 1300 550 L 0 550 L 0 250">
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
.svg{
  color: green;
}
.map{
  margin-top: 50px;
}
.picture-map{
  height: 400px;
  width: 200px;
}
</style>