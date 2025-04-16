<script>
import '~/components/HeaderComponent.scss'

</script>
<template>
    <div class="row">
        <div class="col-12 header-container">
            <div class="header-logo">
                <img src="./../assets/img/logo.png">
            </div>
            <div class="header-find">
                <div class="group-find">
                    <input placeholder="Key search" type="text" class="header-find-input" />
                    <img class="icon" src="./../assets/img/icon-find.svg" />
                </div>
            </div>
            <div class="header-common-infor hide-element">
                <img class="icon" src="./../assets/img/icon-hotline.svg" />
                <div class="infor">
                    <div>Hotline</div>
                    <div>1900 066 890</div>
                </div>
            </div>
            <div class="header-common-infor  hide-element">
                <img class="icon" src="./../assets/img/icon-user.svg" />
                <div class="infor">
                    <div>Hi,</div>
                    <div>Login</div>
                </div>
            </div>
            <div class="header-common-infor hide-element">
                <span class="icon-cart">
                    <img  src="./../assets/img/icon-cart.svg" />
                </span>
            </div>
            <div class="header-common-infor language-transfer">
                <span>
                    <img class="flag" src="./../assets/img/flag-vi.svg" />
                </span>
                <span>
                    <img class="flag" src="./../assets/img/flag-en.svg" />

                </span>
            </div>
        </div>
    </div>
</template>
