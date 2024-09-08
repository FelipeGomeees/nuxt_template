<template>
    <v-container 
    fluid 
    fill-height 
    class="container">
        <v-row class="main-row">
            <v-col 
            md="7"
            class="main-row__img-col">
                <div class="img-bg">
                </div>
            </v-col>
            <v-col 
            cols="12" 
            lg="5"
            justify="center"
            align="center"
            class="main-row__login-col"
            > 
                <v-card class="login-card">
                    <v-img class="login-img"></v-img>
                    <v-form class="login-form">
                        <CoreTextField label="Email"></CoreTextField>
                        <CoreTextField label="Password"></CoreTextField>
                        <CoreBtn size="large">Log In</CoreBtn>
                    </v-form>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>

<script setup>

definePageMeta({
  layout: 'base'
})

</script>

<style scoped>
    .container {
        height: 100%;
    }
    .main-row {
        height: 100%;
    }
    .main-row__img-col {
        flex-direction: column;
    }
    @media screen and (max-width: 960px) {
        .main-row__img-col {
            display: none;
        }
    }
    .main-row__login-col {
        align-items: center;
        justify-content: center;
    }
    .login-card {
        height: 100%;
    }
    .login-form {
        width: 80%;
    }
    .img-bg {
        background: rgb(0,199,86);
        background: linear-gradient(350deg, rgba(0,199,86,1) 0%, rgba(0,220,130,1) 100%);
        height: 100%;
    }
</style>
