<template>
    <footer>
        <section class="upper_footer">
            <div class="listes">
                <div class="list">
                    <h2>Dc comics</h2>
                    <ul>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                    </ul>
                </div>
                <div class="list">
                    <h2>Dc</h2>
                    <ul>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                    </ul>
                </div>
                <div class="list">
                    <h2>Sites</h2>
                    <ul>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                    </ul>
                </div>
                <div class="list">
                    <h2>Shop</h2>
                    <ul>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                        <li>contenuco</li>
                    </ul>
                </div>
              
            </div>
            <div>
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </section>
        <section class="lower_footer">
            <div class="button">
                <button>
                    Sign-up Now!
                </button>
            </div>
            <div class="social">
                <p>
                    FolloUs
                </p>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </section>
    </footer>
</template>

<script>
export default {
    name: 'FooterApp',
    data(){
        return{

        }
    }
}
</script>

<!-- lang="scss" -->
<style scoped>
section.upper_footer{
    display: flex;
    justify-content: space-between;
    width: 100%;
    background: url(../assets/img/footer-bg.jpg);
}
div.listes{
    display: flex;
}
h2{
    color: white;
}
ul{
    list-style-type: none;
    padding-left: 0;
}
ul li{
    color: white;
}
section.lower_footer{
    display: flex;
    justify-content: space-between;
    height: 30px;
}
div.social{
    display: flex;
}
</style>