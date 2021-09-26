<script>
    import Header from "$lib/Header.svelte";
</script>

<Header />
<main><span>No Feed to Show</span></main>

<style lang="scss">
    main {
        display: flex;
        justify-content: center;
        align-items: center;
        height: calc(100vh - 3.5rem);

        span {
            // display: block;
            font-size: 4rem;
            font-weight: bold;
            color: rgb(150, 150, 150);
        }
    }
</style>
