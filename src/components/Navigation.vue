<template>
        <v-toolbar flat color="transparent">
            <v-toolbar-title>{{appTitle}}</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn flat>Home</v-btn>
            <v-btn flat>Resources</v-btn>
        </v-toolbar>
</template>

<script>
export default {
    name: 'AppNavigation',
    data(){
        return{
            appTitle:"can|code"
        }
    }
};
</script>

<style scoped>

</style>