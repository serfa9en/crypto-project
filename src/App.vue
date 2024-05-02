<template>
  <div>
    <p class="title">Криптоанализ Аффинного шифра</p>
    <div class="block-main">
      <EncryptionView/>
      <DecryptionView/>
      <CryptoanalysisView/>
    </div>
  </div>
</template>

<script>
import EncryptionView from './components/EncryptionView.vue'
import DecryptionView from './components/DecryptionView.vue'
import CryptoanalysisView from './components/CryptoanalysisView.vue'

export default {
  name: 'App',
  components: {
    EncryptionView,
    DecryptionView,
    CryptoanalysisView
  }
}
</script>

<style>
body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin:0;
}

.title {
    width: 100%;
    height: 100px;
    font-size: 36px;
    margin-block: -100px;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #500050;
    background: rgba(255, 188, 255, 0.3);
    position: fixed;
}

.block-main {
  width: 100%;
  height: auto;
  margin-top: 100px;
}
</style>
