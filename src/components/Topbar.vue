<template>
    <v-toolbar
        class="d-flex align-center justify-center bg-white"
        style="border-bottom: 1px solid gray; height: 100px"

    >
        <div 
            class=""
        >
            <v-btn
                @click="redirect('/')"
            >
                Home
            </v-btn>
            <v-btn
                @click="redirect('/produtos')"
            >
                Produtos
            </v-btn>
        </div>
    </v-toolbar>
</template>

<script setup lang="ts">
import router from '@/router';


const redirect = (route: string) => {
    router.push(route)
}

</script>

<style scoped lang="scss">

</style>