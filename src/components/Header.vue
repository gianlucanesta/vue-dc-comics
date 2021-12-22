<template>
    <header class="container">
        
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="Logo DC">
        </div>

        <nav>
            <ul class="menu-list">
                <li v-for="(link, index) in links" :key='index'>
                    <a :class="{current: link.current}" href="link.url">{{link.text}}</a>
                </li>                   
            </ul>
        </nav>
        
    </header>
</template>


<script>
export default {
    name: "Header",
    props: ['links']
}
</script>

<style scoped lang="scss">
@import '../style/variables';
@import '../style/common';

header {
    width: 100%;
    display: flex;   
}

.container {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    flex-direction: column;

    img {
        width: 75%;    
    }
}

nav {
    display: flex;
    justify-content: center;

    ul {
        display: flex;

        li {
            text-transform: uppercase;
            flex-direction: column;
            margin: 0 10px ;
            font-size: 16px;
            font-weight: bold;
        }
        
        a {
            display: inline-block;
            color: rgb(75, 75, 75);  
            line-height: 96px;

            &.current {
                color: #0282f9;
                border-bottom: 4px solid #0282f9;
            }
        }
    }
}

</style>