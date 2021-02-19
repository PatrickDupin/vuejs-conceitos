<template>
    <div>
        <h1 v-bind:style="{ textDecoration: decoration }">Hello {{ name }}!</h1>
        <input type="text" v-model="name" />
        <br>
        <a v-bind:href="link">Link para o curso!</a>
    </div>
</template>

<script>
export default {
    data: () => ({
        name: 'Igor',
        link: 'https://treinamento.vuejsbrasil.org',
        decoration: 'underline'
    })
}
</script>

<style>
</style>