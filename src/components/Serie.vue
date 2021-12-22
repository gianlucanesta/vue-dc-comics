<template>
    <section>
        <div class="single-serie">
            <div class="square-img"><img :src="serieObject.thumb" :alt="serieObject.type"></div>
            <h4>{{ serieObject.series }}</h4>

            
        </div>
    </section>
</template>


<script>
export default {
    name:'Serie',
    props: ['serieObject']
}
</script>

<style scoped lang="scss">
@import '../style/variables';
@import '../style/common';

section {
    // display: inline-block;
    width: calc((100% / 6) - 6px);
}

.single-serie {
    margin: 20px 3px;
} 

.square-img {
    height: 200px;
    overflow: hidden;
}

h4 {
    margin-top: 7px;
    font-size: 16px;
    text-transform: uppercase;
    text-align: center;
}



</style>