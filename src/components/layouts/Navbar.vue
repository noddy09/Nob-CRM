<template>
    <nav class="navbar has-background-white-ter">
        <div class="navbar-brand">
            <router-link to="/" class="navbar-items">
                <img class="imgLogo" src="../../assets/logo.png"/>
            </router-link>
        </div>

        <div class="navbar-menu">
            <div class="navbar-end">
                <div class="navbar-item">
                    <div class="buttons">
                        <router-link to="/sign-up" class="button is-orange"><strong>Sign Up</strong></router-link>
                        <router-link to="/login" class="button is-dark"><strong>Login</strong></router-link>
                    </div>
                </div>
            </div>
        </div>
    </nav>
</template>

<script>
    export default {
        name: 'Navbar'
    }
</script>

<style lang="css">
.imgLogo{
    margin-left: 30px;
    height: 80px;
    width: 100px;
}
</style>
