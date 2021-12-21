<template>
    <footer>
         <div class="content">
        <div class="container">
            -- Content goes here -- 
        </div> 
    </div>

    <div class="menu-bar"> 
        <div class="container">
            <div class="signup-btn">
                SIGN-UP NOW!
            </div>

            <nav>
               <ul class="menu-list">
                   <li><img src="../assets/img/footer-facebook.png" alt="Logo DC"></li>
                   <li><img src="../assets/img/footer-twitter.png" alt="Logo DC"></li>
                   <li><img src="../assets/img/footer-youtube.png" alt="Logo DC"></li>
                   <li><img src="../assets/img/footer-pinterest.png" alt="Logo DC"></li>
                   <li><img src="../assets/img/footer-periscope.png" alt="Logo DC"></li>
               </ul>
            </nav>

        </div>
    </div>
    </footer>
</template>


<script>
export default {
    name: "Footer"
}
</script>

<style scoped lang="scss">

.content {
    display:flex;
    width: 100%;
    height: 80%;
    background-image: url("../assets/img/footer-bg.jpg");    
}

.menu-bar {
    display: flex;
    width: 100%;
    height: 20%;
    background-color: #303030;
}


.container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    justify-items: center;
    font-size: 22px;
}

.signup-btn {
    flex-direction: column;
    color: white;
    border: 2px solid #0282f9;
    padding: 10px 16px;
    cursor: pointer;

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