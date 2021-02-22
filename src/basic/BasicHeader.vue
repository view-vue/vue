<template>
    <header id="header">
        <div class="header-wrap">
            <h1 class="logo">
                <!-- <a href="/"> -->
                <router-link to="/" class="Home">
                    <img src="../assets/logo.png" alt="">
                    <!-- <img src="../assets/logo.png" alt=""> -->
                    <span>뷰 로고</span>
                </router-link>
            </h1>
            <ul class="menu">
                <li class="menu-list item1"><router-link to="/about">About</router-link></li>
                <li class="menu-list item2"><router-link to="/conMenu3">conMenu3</router-link></li>
                <li class="menu-list item3"><router-link to="/conMenu4">conMenu4</router-link></li>
            </ul>
                
                
                
        </div>
    </header>
</template>

<style lang="scss">
    #header{
        position:absolute;
        width: 100%;
        height:60px;
        z-index: 10;
        .header-wrap{
            min-width: 980px;
            display:-webkit-box;
            display:-ms-flexbox;
            display:flex;
            -webkit-box-pack: justify;
                -ms-flex-pack: justify;
                    justify-content: space-between;
            .logo {
                display: inline-block;
                margin-left: 20px;
                a {
                    width: 100px;
                    height: 200px;
                    img{width: 50px; height: 50px;}
                    // background: url(../assets/logo.png) no-repeat;
                    span {
                        position:absolute;
                        width: 1px;
                        height: 1px;
                        overflow: hidden;
                        margin: 1px;
                    }
                }
            }
        }
    }
</style>