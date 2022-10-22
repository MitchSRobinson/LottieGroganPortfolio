<template>
  <svg
    v-bind="$attrs"
    id="sw-js-blob-svg"
    viewBox="0 0 100 100"
    xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="sw-gradient" x1="0" x2="1" y1="1" y2="0">
        <stop id="stop1" stop-color="rgba(110, 231, 183, 1)" offset="0%"></stop>
        <stop
          id="stop2"
          stop-color="rgba(167, 139, 250, 1)"
          offset="100%"></stop>
      </linearGradient>
    </defs>
    <path
      fill="url(#sw-gradient)"
      d="M17.5,-21.9C24.9,-18.6,34.8,-16.6,37.8,-11.3C40.8,-6.1,36.9,2.3,33.2,9.9C29.5,17.5,26.1,24.3,20.6,26C15.1,27.6,7.5,24.2,1.3,22.4C-4.8,20.5,-9.7,20.2,-17.3,19.2C-24.9,18.2,-35.2,16.5,-40.3,10.8C-45.5,5,-45.3,-4.8,-39.9,-10.3C-34.5,-15.8,-23.8,-17,-16.3,-20.2C-8.8,-23.4,-4.4,-28.6,0.3,-29.1C5,-29.5,10,-25.1,17.5,-21.9Z"
      width="100%"
      height="100%"
      transform="translate(50 50)"
      stroke-width="0"
      style="transition: all 0.3s ease 0s"
      stroke="url(#sw-gradient)"></path>
  </svg>
</template>
