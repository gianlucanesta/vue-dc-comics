<template>
    <footer>
         <div class="content">
        <div class="container">
            <div class="footer-menu">-- Content goes here -- </div> 
            <div class="footer-bg"><img src="../assets/img/dc-logo-bg.png" alt=""></div>
        </div> 
    </div>

    <div class="menu-bar"> 
        <div class="container">
            <div class="signup-btn">
                SIGN-UP NOW!               
            </div>

            <nav>
                
               <ul class="menu-list">
                   <li class="follow">FOLLOW UP</li>
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
@import '../style/variables';
@import '../style/common';

.content {
    display:flex;
    width: 100%;
    height: 80%;
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: cover;
    background-repeat: no-repeat;   
    overflow: hidden;
}

.menu-bar {
    display: flex;
    width: 100%;
    padding: 20px 0;
    background-color: #303030;
}


.container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    justify-items: center;
    font-size: 22px;
    position: relative;   
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

        .follow {
            color: #0282f9;
            font-size: 20px;  
            margin: auto;
            margin-right: 10px;
            cursor: default;
            
        }
        li {
            text-transform: uppercase;
            flex-direction: column;
            margin: 10px;
            font-size: 16px;
            font-weight: bold;
            
        }

    }
}

.footer-bg {
    position: absolute;
    right: 0;
}

</style>