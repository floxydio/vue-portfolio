<template>
    <b-navbar class="is-info" :fixed-top="true" :transparent="true"> 
        <template slot="end">
            <b-navbar-item tag="router-link" to="/">
               <i class="fas fa-home fa-lg mr-1"> </i> Back To Home
            </b-navbar-item>
        </template>
    </b-navbar>
</template>


<script>
export default {

}
</script>

<style>
.navbar-item {
    margin-right: 20px;
}


</style>