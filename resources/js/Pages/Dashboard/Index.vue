<template>

      <AppLayout>
            <template #content>
                <center>
                  <img class="homeimg" src="../../../../public/images/homeimage.png" alt="Home"/>
                </center>
            </template>
      </AppLayout>


</template>

<script>

import AppLayout from '@/Layouts/App.vue'

export default {

    components: {

        AppLayout

    }

}

</script>

<style lang="css" scoped>

        .homeimg{
                width: 560px;
                height: 499px;
        }

</style>
