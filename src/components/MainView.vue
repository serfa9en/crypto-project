<template>
    <div>
        <div class="title">
            <h1>Криптоанализ Аффинного шифра</h1>
        </div>
        <div>
            <EncryptionView/>
            <DecryptionView/>
            <CryptoanalysisView/>
        </div>
    </div>
</template>

<script>
import EncryptionView from './EncryptionView.vue'
import DecryptionView from './DecryptionView.vue'
import CryptoanalysisView from './CryptoanalysisView.vue'

export default {
  name: 'MainView',
  components: {
    EncryptionView,
    DecryptionView,
    CryptoanalysisView
  }
}
</script>

<style scoped>
.title {
    width: 100%;
    height: 100px;
    background: paleturquoise;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
}
</style>