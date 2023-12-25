<template scoped>
    <div class="container">
        <div class="left-side">
            <AppLogo></AppLogo>
            <SearchBar></SearchBar>
        </div>

        <div class="right-side">
            <LanguageButton></LanguageButton>
            <img :src="require('@/assets/settings.png')" alt="">
            <img :src="require('@/assets/megaphone.png')" alt="">
            <HeaderAccount></HeaderAccount>
        </div> 
    </div>
</template>

<script scoped>
    import AppLogo from './AppLogo.vue'
    import SearchBar from './SearchBar.vue';
    import LanguageButton from './LanguageButton.vue';
    import HeaderAccount from './HeaderAccount.vue';

    export default {
        name: 'App',
        components: {
        AppLogo,
        SearchBar,
        LanguageButton,
        HeaderAccount
        }
    }
</script>

<style scoped>
    .container{
        width: 100vw;
        height: 80px;
        display: flex;
        justify-content: space-between;
        margin: 1px 10px;
        align-items: center;
    }
    .left-side{
        display: flex;
        width: 600px;
        justify-content: space-between;

    }
    .right-side{
        display: flex;
        width: 520px;
        justify-content: space-between;
        align-items: center;
    }
    img{
        width: 20px;
        height: 20px;
    }
</style>

  
