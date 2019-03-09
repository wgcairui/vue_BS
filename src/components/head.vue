<template>
    <header class="container-fluid jumbotron headerimg" style="margin-bottom: 0">
        <div class="row header-ico">
            <a class="tip " :title="title" href="href">
                <img :src="src">
            </a>
        </div>
    </header>
</template>

<script>
export default {
    name:'app-header',
    props: {
        title:{
            type:String,
            default:''
        },
        href:{
            type:String,
            default:'#'
        },
        src:{
            type:String,
            default:''
        }
    }
}
</script>

<style>
    .headerimg{
	background-image: url(./../assets/logo.png);
	background-position: center;
    }
</style>
