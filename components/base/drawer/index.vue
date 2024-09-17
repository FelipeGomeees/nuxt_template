<template>
    <v-navigation-drawer>
        <v-list-item 
        prepend-icon="mdi-nuxt"
        title="My Application"
        height="64px"
        subtitle="Nuxt + Vuetify"
        class="list__header">
        </v-list-item>
        <v-divider>
        </v-divider>
        <v-list-item 
        link 
        prepend-icon="mdi-home"
        title="Home">
        </v-list-item>
        <v-list-item 
        link 
        prepend-icon="mdi-text-account"
        title="View 1">
        </v-list-item>
        <v-list-item 
        link 
        prepend-icon="mdi-chart-bar"
        title="View 2">
        </v-list-item>
        <v-divider class="list__footer-divider"></v-divider>
        <v-list-item 
        class="list__footer"
        link 
        prepend-icon="mdi-logout"
        title="Log Out">
        </v-list-item>
    </v-navigation-drawer>
</template>

<style lang="scss" src="./style.scss" scoped/>