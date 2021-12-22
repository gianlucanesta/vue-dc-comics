<template>
    <section>
        <div class="single-serie">
            <img :src="serieObject.thumb" :alt="serieObject.type">
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
h4 {
    text-align: center;
}

</style>