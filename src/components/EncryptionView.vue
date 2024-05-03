<template>
    <div class="settings">
        <p id="encrypt" class="name-enc">Шифрование</p>
            <div class="conteiner">
                <div class="block">
                    <textarea></textarea>
                    <div class="btn-cont">
                        <div 
                        class="btn"
                        v-on:click="start-crypto()"
                        >
                            <p class="text">Шифровать</p>
                        </div>
                    </div>
                </div>
                <div class="block">
                    <textarea></textarea>
                    <div class="btn-cont">
                        <div 
                        class="btn"
                        v-on:click="start-crypto()"
                        >
                            <p class="text">Очистить</p>
                        </div>
                    </div>
                </div>
            </div>
    </div>
</template>

<script>
export default {
  name: 'encryption'
}
</script>

<style scoped>
.settings {
    width: 100%;
    height: auto;
}

.name-enc {
    width: 100%;
    height: 100px;
    font-size: 26px;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #2e002e;
}

.conteiner {
    width: 100%;
    height: auto;
    text-align: center;
    align-items: center;
    display: flex;
    justify-content: center;
    text-align: center;

}

.block {
    width: 800px;
    margin: 10px;
    padding: 10px 30px 10px 10px;
    border: 3px gray dotted;
}

textarea {
    width: 100%;
    height: 400px;
    padding: 10px;
    font-size: 20px;
}

.btn-cont {
    width: 100%;
    text-align: center;
    align-items: center;
    display: flex;
    justify-content: center;
    text-align: center;
}

.btn {
    width: 150px;
    height: 40px;
    border: 2px red solid;
    align-items: center;
    display: flex;
    margin: 40px 10px 40px 40px;
    text-align: center;
    background: pink;
    border-radius: 4px;
}

.btn:hover {
    cursor: pointer;
    background: #ffe6e6;
}

.text {
    width: 100%;
    text-align: center;
    font-size: 20px;
}
</style>