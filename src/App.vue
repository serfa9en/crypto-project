<template>
  <div>
    <div class="header-title">
      <p class="title">Криптоанализ Аффинного шифра</p>
      <div class="header-btn">
        <p class="btn-hh"><a href="#encrypt">Шифрование</a></p>
        <p class="btn-hh">Дешифровка</p>
        <p class="btn-hh">Криптоанализ</p>
      </div>
    </div>
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

.header-title {
    width: 100%;
    height: 230px;
    margin-block: -230px;
    text-align: center;
    justify-content: center;
    align-items: center;
    color: #500050;
    border: #500050 2px solid;
    background: #fff;
    position: fixed;
}

.title {
  width: 100%;
    font-size: 36px;
    text-align: center;
    justify-content: center;
    align-items: center;
    color: #500050;
}

.header-btn {
    width: 100%;
    height: 100px;
    display: flex;
    text-align: center;
    justify-content: center;
    align-items: center;
    font-size: 24px;
}

.btn-hh {
  border: 2px solid purple;
  margin: 20px;
  padding: 10px;
  border-radius: 4px;
}

.btn-hh:hover {
  background: #ebceeb;
  cursor: pointer;
}

.block-main {
  width: 100%;
  height: auto;
  margin-top: 230px;
}

a:link {
  color: #500050; 
  text-decoration: none;
}
a:visited {
  color: #500050;
  text-decoration: none;
}
a:hover {
  color: #500050; 
  text-decoration: none;
}
a:active {
  color: #500050; 
  text-decoration: none;
}
</style>
