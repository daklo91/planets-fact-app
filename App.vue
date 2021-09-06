<template>
  <view class="container">
    <HeaderComponent />
    <text class="text-color-primary">My Vue Native App</text>
  </view>
</template>

<script>
import HeaderComponent from './components/headerComponent.vue';
export default {
  components: {
    HeaderComponent,
  },
}
</script>

<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.text-color-primary {
  color: blue;
}
</style>
