<template>
  <div>
    <h4>{{ reseau }}</h4>

    <div class="slogan">
      <h1>#La Livraison de maintenant</h1>
      <h2>Venez nous rejoindre sur nos réseau sociaux</h2>
      <div class="reseaux-sociaux">
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-brands fa-twitter"></i>
        <i class="fa-brands fa-facebook"></i>
      </div>
    </div>

    <svg
      class="svg"
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
      version="1.1"
      id="Calque_1"
      x="0px"
      y="0px"
      viewBox="0 0 1300 550"
      style="enable-background: new 0 0 1300 550"
      xml:space="preserve"
    >
      <path
        class="st1"
        fill="#00cba9"
        fill-opacity="1"
        d="M 0 250 C 600 450 650 100 1300 250 L 1300 550 L 0 550 L 0 250"
      >
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

      <path
        class="st1"
        fill="#00cba9"
        fill-opacity="1"
        d="M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250"
      >
        <animate
          attributeName="d"
          dur="5s"
          values="M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250;
                M 0 250 C 600 450 650 100 1300 250 L 1300 550 L 0 550 L 0 250;
				M 0 250 C 600 100 650 450 1300 250 L 1300 550 L 0 550 L 0 250"
          repeatCount="indefinite"
        />
      </path>

      <path
        class="st1"
        fill="#00cba9"
        fill-opacity="1"
        d="M 0 250 C 950 350 950 150 1300 250 L 1300 550 L 0 550 L 0 250"
      >
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

      <path
        class="st1"
        fill="#00cba9"
        fill-opacity="1"
        d="M 0 250 C 350 150 350 350 1300 250 L 1300 550 L 0 550 L 0 250"
      >
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
  name: "Maps",
};
</script>

<style scoped>
.slogan {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.fa-instagram {
  color: #8a3ab9;
}
.fa-twitter {
  color: #00e3ff;
}
.fa-facebook {
  color: #2f55a4;
}
.reseaux-sociaux {
  display: flex;
  justify-content: center;
  font-size: 30px;
}
</style>