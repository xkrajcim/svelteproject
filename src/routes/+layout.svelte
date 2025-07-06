<script>
    import "@fontsource/montserrat/200.css";
    import "@fontsource/montserrat/300.css";
    import "@fontsource/montserrat/400.css";
    import "@fontsource/montserrat/500.css";
    import "@fontsource/montserrat/600.css";
    import "@fontsource/montserrat/700.css";
    import "@fontsource/montserrat/800.css";
    import "@fontsource/montserrat/900.css";
</script>

<slot/>

<style>

    :global(body),:global(html),:global(*){
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        /*font-family: 'Monsterrat', sans-serif;*/
        font-family: 'Montserrat';
        margin-block-start: 0;
        margin-block-end: 0;
        margin-inline-start: 0;
        margin-inline-end: 0;
    }

</style>