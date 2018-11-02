<template>
    <div id="app">
        <Header/>
        <Body/>
        <Footer/>
    </div>
</template>

<script>
    import Header from './views/Header'
    import Body from './views/Body'
    import Footer from './views/Footer'
    import jquery from 'jquery'
    export default {
        name: 'App',
        components: {
            Header,
            Body,
            Footer
        },
        methods: {
            scrollhot(){
                let allLis = jquery("#lk_nav li");
                jquery(allLis[2]).on('click', function(){
                    jquery('html, body').animate({scrollTop: jquery('#lk_hot').offset().top}, 1000);
                });
            }
        },
        mounted(){
            this.scrollhot()
        }
    }
</script>

<style>
    body{
        margin: 0;
        padding: 0;
        color: #000;
    }
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
    }
</style>