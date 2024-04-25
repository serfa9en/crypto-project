<template>
    <div class="conteiner">
        <textarea></textarea>
        <div class="">
            <div 
            class="btn"
            v-on:click="start-crypto()"
            >
                <p class="text">Шифровать</p>
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style scoped>
.conteiner {
    width: 100%;
    height: auto;
}

textarea {
    width: 800px;
    height: 400px;
    padding: 10px;
    font-size: 20px;
}

.btn {
    width: 150px;
    height: 40px;
    border: 2px red solid;
    align-items: center;
    display: flex;
    margin: 40px;
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