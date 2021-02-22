<template>
    <footer id="footer">
        <div class="footer-wrap">
            <p class="copyRight">
                Copyright &copy; 2021 Seung-Mihn All Rights Reserved
            </p>
        </div>
    </footer>
</template>

<style lang="scss">
    #header{
        width: 100%;
        height:60px;
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