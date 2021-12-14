<template>
    <div>
        <Top/>
        <Middle/>
        <Bottom/>
    </div>
</template>

<script>

import Top from '../components/Footer/Top.vue'
import Middle from '../components/Footer/Middle.vue'
import Bottom from '../components/Footer/Bottom.vue'

export default {
    name: 'App',
    components: {
        Top,
        Middle,
        Bottom
    }
}
</script>

<style>

</style>