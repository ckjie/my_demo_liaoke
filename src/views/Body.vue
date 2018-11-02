<template>
    <div id='lk_body'>
        <Carousel/>
        <About/>
        <Product/>
        <Hot/>
        <Link/>
    </div>
</template>

<script>
    import Carousel from '../components/Carousel'
    import About from '../components/About'
    import Product from '../components/Product'
    import Hot from '../components/Hot'
    import Link from '../components/Link'
    export default {
        name: 'Body',
        components: {
            Carousel,
            About,
            Product,
            Hot,
            Link
        }
    }
</script>

<style>
    #lk_about, #lk_hot, #lk_link{
        padding: 20px 0;
    }

    #lk_about .title, #lk_hot .title, #lk_link .title{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding-bottom: 15px;
    }
</style>
