<script>
    export let name;
    export let src;
    export let price;
</script>

<img {src} alt="" />
<h2>{name}</h2>
<p>{price}</p>

<style>
    img {
        height: 300px;
        width: 300px;
    }

    h2 {
        font-size: 1.75rem;
        color: #c4d2d8;
        font-family: "Russo One", sans-serif;
    }

    p {
        color: #89979c;
        font-size: 1rem;
        font-family: "Russo One", sans-serif;
    }
</style>
