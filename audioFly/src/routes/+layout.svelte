<script lang="ts">
    import logo from '$lib/assets/logo.png'
    let { children } = $props()
</script>

<nav>
    <img class="logo" src={logo} alt="AudioFly">
    <a href="/">Home</a>
    <a href="/products">Products</a>
    <div class="nav-icons">
        <button>Carrito</button>
        <button>Login</button>
    </div>
</nav>

{@render children()}

<style>
    nav {
        display: flex;
        align-items: center;
        background-color: #0f0f0f;
        color: #0f0f0f;
        gap: 3%;
    }

    a {
        color: #f5c518;
        text-decoration: none;
        font-size: 200%;
    }

    .nav-icons {
        margin-left: auto;
        background-color: #f5c518;
        color: #0f0f0f;
    }

    .logo {
        width: 10%;
        height: auto;
    }
</style>