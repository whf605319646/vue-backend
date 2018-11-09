<template>
    <div class="sys-page">
        <div id="container">
            <e-map></e-map>
        </div>
    </div>
</template>

<script>
import EMap from './EMap'
export default {
    name: 'exampleMap',
    components: {EMap}
}
</script>

<style lang="scss" scoped>
#container{
    width: 100%;
    height: 100%;
}
.note{
    position: absolute;
    top: 0px;
    left: 0;
    width: 100%;
    z-index: 1000;
}
</style>