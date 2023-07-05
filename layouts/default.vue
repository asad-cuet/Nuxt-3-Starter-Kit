<template>
    <div>
        <Header/>
            <slot />
        <Footer/>
    </div>
</template>
<script setup>
  import Header from '@/layouts/header'
  import Footer from '@/layouts/footer'
</script>