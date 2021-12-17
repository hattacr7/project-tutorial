<template>
    <div class="container">
        <h4>
            {{ cardsSection.title }}
        </h4>
        <p>
            {{ cardsSection.snippet }}
        </p>
    </div>
</template>

<script>
    export default {
        props: ['cardsSection']
    }
</script>

<style lang="scss" scoped>
    
</style>