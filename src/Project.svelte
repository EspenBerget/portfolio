<script>
    export let href;
    export let src;
    export let alt;
    export let name;
    export let extref = null;

</script>

<div>
    <a {href} target="_blank">
       <img {src} {alt} />
       <span>{name}</span>
       {#if extref != null}
       <a href={extref} target="_blank"><i class="fab fa-github fa-2x"></i></a>
       {/if}
    </a>
</div>

<style>
    div {
        width: 300px;
        height: 300px;
        text-align: center;
        background-color: #424242;
        border-radius: 10px;
        overflow: hidden;

        box-shadow: 2px 2px 5px 1px black;
        transition: 0.5s transform;

        margin: 1rem;
    }

    div:hover {
        transform: scale(1.05);
    }

    div a {
        width: 100%;
        height: 100%;
        text-decoration: none;
        color: white;
    }

    div a img {
        width: 300px;
        height: 250px;
    }

    div span {
        font-size: 2rem;
    }

    div a a:hover {
        color: orange;
    }
</style>