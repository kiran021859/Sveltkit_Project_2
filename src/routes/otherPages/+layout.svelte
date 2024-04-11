<script>
import Title from '$lib/title.svelte'
import '../../global css/style.css'
</script>

<header>
<Title title="this is the layout"/>
</header>

<main>
<slot></slot>
</main>

<footer>
    <p>Copyright 2024 Kiran Isaacs Svelt test web site</p>
</footer>

<style>
    header {
        display: flex;
        justify-content: center;
    }
    main {
        max-width: 960px;
        margin: 20px auto;
    }
    footer {
        text-align: center;
    }
</style>