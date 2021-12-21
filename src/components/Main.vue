<template>
    <main>
        
    <div class="content">
        <div class="container">
            -- Content goes here -- 
        </div> 
    </div>

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


        
    </main>
</template>


<script>
export default {
    name: "Main"
}
</script>



<style scoped lang="scss">

.content {
    display:flex;
    width: 100%;
    height: 125px;
    background-color: #1c1c1c;    
}

.menu-bar {
    display: flex;
    width: 100%;
    height: 175px;
    background-color: #0282f9;
}

.container {  
    justify-items: center;
    font-size: 22px;
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
            list-style-type: none;
            flex-direction: column;
            // margin: 30px;
            font-size: 15px;
            color: white; 
            cursor: pointer;
        }
    }
}




</style>