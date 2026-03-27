<script lang="ts">
    import headphonesHome from '$lib/assets/headphones_home.jpg'
</script>

<section class="headphone">
    <div class="headphone-box-img">
        <div class="mask-transparent-horizontal"></div>
        <div class="mask-transparent-vertical"></div>
        <img class="headphone-img" src={headphonesHome} alt="headphonesHome">
    </div>
    <div class="headphone-text">
    <strong>El mundo del audio reunido en un solo lugar.</strong>
    </div>
</section>

<style>
    .headphone {
        display: flex;
        align-items: center;
    }

    .mask-transparent-horizontal {
        position: absolute;
        height: 100%;
        width: 100%;
        background: linear-gradient(to left, #0a0a0a 35%, transparent 100%);
    }

    .mask-transparent-vertical {
        position: absolute;
        height: 100%;
        width: 100%;
        background: linear-gradient(to top, #0a0a0a 5%, transparent 100%);
    }

    .headphone-text {
        font-size: 5vw;
        color: #f0f0f0;
    }

    .headphone-box-img {
        position: relative;
    }

    .headphone-img {
        width:70vw;
        height: 40vw;
    }
</style>