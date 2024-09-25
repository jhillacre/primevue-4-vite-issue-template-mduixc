<template>
  <img src="./assets/primevue-logo.png" alt="PrimeVue Logo" />
  <h2 class="pt-4">PrimeVue Issue Template</h2>
  <p class="py-4">
    Please create a test case and attach the link of the codesandbox to your
    github issue report.
  </p>
  <Button label="default" v-tooltip="'default'" />
  <Button label="left" severity="danger" v-tooltip.left="'left'" />
  <Button label="right" severity="warning" v-tooltip.right="'right'" />
  <Button label="top" severity="info" v-tooltip.top="'top'" />
  <Button label="bottom" severity="success" v-tooltip.bottom="'bottom'" />
</template>
