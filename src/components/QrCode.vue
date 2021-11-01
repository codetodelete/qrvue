<template>
  <div>
    <h1>Vue QrCode</h1>
    <qrcode-vue 
      :value="value" 
      :size="size" 
      level="H" 
    />
  </div>
</template>
<script>
  export default {
    data () {
      return {
        value: 'https://www.google.com',
        size: 150,
      }
    }
  }
</script>