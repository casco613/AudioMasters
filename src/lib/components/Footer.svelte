<script>
    import { SiInstagram, SiFacebook, SiX, SiVisa, SiMastercard, SiPaypal } from '@icons-pack/svelte-simple-icons';
</script>

<footer>
    <div class="footer-colum">
        <div class="social-media">
            <p>Redes Sociales:</p>
            <a class="icon" href="https://instagram.com"><SiInstagram /></a>
            <a class="icon" href="https://facebook.com"><SiFacebook /></a>
            <a class="icon" href="https://x.com"><SiX /></a>
        </div>
        <div class="contact">
            <p>Telefono: 5544913900</p>
            <p>Direccion: Blvd. Benito Juarez 3122, Del Costo CDMX México</p>
        </div>
        <div class="payment-metoths">
            <p>Métodos de pago:</p>
            <span class="icon"><SiVisa /></span>
            <span class="icon"><SiMastercard /></span>
            <span class="icon"><SiPaypal /></span>
        </div>
    </div>
</footer>

<style>
    footer {
        background-color: #f5c518dd;
        height: 5vw;
        width: 100%;
        display: flex;
        margin-top: auto;
    }

    .footer-colum {
        font-size: 1.3vw;
        display: flex;
        align-items: center;
        width: 100%;
        gap: 1.3vw;
    }

    .social-media {
        display: flex;
        gap: 1vw;
    }

    .contact {
        display: flex;
        gap: 1vw;
    }

    .payment-metoths {
        display: flex;
        gap: 1vw;
    }

    .icon :global(svg) {
        width: 1.3vw;
        height: 1.3vw;
    }
</style>