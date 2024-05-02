<template>
    <div>
        <HeaderView/>
        <EncryptionView/>
        <DecryptionView/>
        <CryptoanalysisView/>
    </div>
</template>

<script>
import HeaderView from './Header.vue'
import EncryptionView from './EncryptionView.vue'
import DecryptionView from './DecryptionView.vue'
import CryptoanalysisView from './CryptoanalysisView.vue'

export default {
  name: 'MainView',
  components: {
    HeaderView,
    EncryptionView,
    DecryptionView,
    CryptoanalysisView
  }
}
</script>

<style>
div {
    margin:0;
}
</style>