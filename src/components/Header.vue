<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>

            <nav>
               <ul class="menu-list">
                   <li>characters</li>
                   <li>comics</li>
                   <li>movies</li>
                   <li>tv</li>
                   <li>games</li>
                   <li>collectibles</li>
                   <li>videos</li>
                   <li>fans</li>
                   <li>news</li>
                   <li>shop</li>
               </ul>
            </nav>

        </div>
        
    </header>
</template>


<script>
export default {
    name: "Header"
}
</script>

<style scoped lang="scss">

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
            list-style-type: none;
            flex-direction: column;
            margin: 10px;
            font-size: 14px;
            font-weight: bold;
            color: rgb(75, 75, 75); 
            cursor: pointer;
        }
    }
}



</style>