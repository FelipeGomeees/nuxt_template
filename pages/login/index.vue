<template>
    <div class="root d-flex">
        <div class="bg">
            <div class="bg__img-wrapper">
                <v-img 
                src="/public/nuxt.png"
                :width="200"
                class="bg__img">
                </v-img>
            </div>
        </div>
        <div
        class="info"
        elevation="7">
            <div class="info__img-wrapper">
                <v-img 
                src="/public/nuxt.png"
                :width="120"
                :height="120"
                >
                </v-img>      
            </div>
            <h1 class="info__header">
                Login Message
            </h1>
            <v-form class="form">
                <CoreTextField label="Email"/>
                <CoreTextField 
                label="Password"
                type="password"/>
                <CoreBtn
                class="form__btn"
                size="large">Log In</CoreBtn>
            </v-form>
        </div>
    </div>
</template>

<script setup>

definePageMeta({
  layout: 'base'
})

</script>

<style lang="scss" src="./style.scss" scoped/>