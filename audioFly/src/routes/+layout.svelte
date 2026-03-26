<script>
    import "../app.css";
    import logo from '$lib/assets/logo.png';
    import { ShoppingCart } from 'lucide-svelte';
    import { User } from 'lucide-svelte';
    let { children } = $props();
</script>

<nav>
    <a href="/">
        <img class="logo" src="{logo}" alt="AudioFly" />
    </a>
    <a href="/products">Products</a>
    <a href="/stores">Stores</a>
    <div class="nav-icons">
        <button><ShoppingCart /></button>
        <button><User /></button>
    </div>
</nav>

{@render children()}

<style>

    .logo {
        width: 5vw;
        height: auto;
    }

    nav {
        display: flex;
        align-items: center;
        background-color: #0f0f0f;
        gap: 2vw;
    }


    a {
        color: #f5c518;
        text-decoration: none;
        font-size: 2vw;
    }

    a:hover {
        font-size: 2.5vw;
    }

    .nav-icons {
        color: #f5c518;
        margin-left: auto;
        margin-right: 2vw;
    }

    button:hover {
        transform: scale(1.2);
    }
</style>
