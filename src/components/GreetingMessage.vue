<script>
export default {
    data(){
        return {
            message: 'Ciao'
        }
    }
}
</script>
<template>
    <h1>{{ message }}</h1>
    <p>Sono il testo del paragrafo</p>
</template>
<style scoped>
    p {
        font-size: 2rem;
        color: blue;
    }
</style>