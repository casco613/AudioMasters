<script>
    import { SiInstagram, SiFacebook, SiX, SiVisa, SiMastercard, SiPaypal } from '@icons-pack/svelte-simple-icons';
</script>

<footer>
    <div class="footer-colum">
        <div class="social-media">
            <h2>Redes Sociales</h2>
            <button><SiInstagram /></button>
            <button><SiFacebook /></button>
            <button><SiX /></button>
        </div>
        <div class="contact">
            <h2>Telefono: 5544935900</h2>
            <h2>Direccion: Blvd. Benito Juarez 3122, Del Costo CDMX México</h2>
        </div>
        <div class="Payment-metoths">
            <h2>Métodos de pago</h2>
            <button><SiVisa /></button>
            <button><SiMastercard /></button>
            <button><SiPaypal /></button>
        </div>
    </div>
</footer>

<style>
    footer {
        background-color: #f5c518;
        display: flex;
        align-items: center;
    }

    .social-media {
        align-items: start;
    }

    .contact {
        align-items: center;
    }
</style>