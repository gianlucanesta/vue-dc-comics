<template>
    <div class="menu-bar"> 
        <div class="container">
            <nav>
                <ul class="menu-list">
                    <li>digital comics</li>
                    <li>dc merchandise</li>
                    <li>subscription</li>
                    <li>comic shop locator</li>
                    <li>dc power visa</li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>
export default {
    name:'Icons'
}
</script>

<style scoped lang="scss">
@import '../style/variables';
@import '../style/common';

.menu-bar {
    display: flex;
    width: 100%;
    height: 150px;
    background-color: $brand_primary_color;
}

.container {
    display: flex;
}

nav {
    display: flex;
    justify-content: center;
    width: 100%;

    ul {
        display: flex;
        justify-content: center;
        justify-content: space-between;
        width: 100%;

        li {
            text-transform: uppercase;
            flex-direction: column; 
            font-size: 15px;
            color: white; 
        }
    }
}

</style>