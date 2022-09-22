<template>
    <div>
        <h1>La mia prima app con Vue CLI!</h1>
        <h2>Antonello, test di prova</h2>
    </div>
</template>

<script>
export default {
    name: 'firstComponent' // ESPORTA IL COMPONENTE
}
</script>

<style scoped> /* SE METTO SCOPED IL CSS E' RELATIVO A QUESTO COMPONENTE */
    * {
        text-align: center;
    }
    h1 {
        color: green;
        text-decoration: underline;
    }
    h2 {
        color: white;
    }
</style>