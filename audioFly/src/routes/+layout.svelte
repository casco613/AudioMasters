<script>import "../app.css";
import logo from '$lib/assets/logo.png'
import { ShoppingCart } from 'lucide-svelte';
import { User } from 'lucide-svelte';
let { children } = $props()</script>

<nav>
    <a href="/">
        <img class="logo" src="{logo}" alt="AudioFly" />
    </a>
    <a href="/products">Products</a>
    <div class="nav-icons">
        <button><ShoppingCart /></button>
        <button><User /></button>
    </div>
</nav>

{@render children()}

<style>
    nav {
        display: flex;
        align-items: center;
        background-color: #0f0f0f;
        gap: 2%;
    }

    a {
        color: #f5c518;
        text-decoration: none;
        font-size: 200%;
    }

    .nav-icons {
        color: #f5c518;
    }

    .logo {
        width: 10%;
    }
</style>
