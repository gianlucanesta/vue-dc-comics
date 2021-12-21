<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>

            <nav>
               <ul class="menu-list">
                   <li><a href="#">characters</a></li>
                   <li><a class="current" href="#">comics</a></li>
                   <li><a href="#">movies</a></li>
                   <li><a href="#">tv</a></li>
                   <li><a href="#">games</a></li>
                   <li><a href="#">collectibles</a></li>
                   <li><a href="#">videos</a></li>
                   <li><a href="#">fans</a></li>
                   <li><a href="#">news</a></li>
                   <li><a href="#">shop</a></li>
                   
               </ul>
            </nav>

        </div>
        
    </header>
</template>


<script>
export default {
    name: "Header",
    data: function() {
        
        
    }
}
</script>

<style scoped lang="scss">
@import '../style/variables';


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
            margin: 10px;
            font-size: 16px;
            font-weight: bold;
        }
        
        a {
            display: inline-block;
            color: rgb(75, 75, 75);  
            line-height: 86px;

            &.current {
                color: $brand_primary_color;
                border-bottom: 4px solid $brand_primary_color;
            }
        }
    }
}



</style>