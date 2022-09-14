<script setup>

</script>

<template>
    <main class="main">
        <div class="qr"></div>
        <div class="content">
            <h1>Improve your front-end skills building projects</h1>
            <p>Scan the QR code to visit Fronted Mentor and take your coding skills to the next level</p>
        </div>
    </main>
</template>

<style lang="scss" scoped>
    .main {
        background-color: var(--bg-main);
        padding: 16px;
        margin: 16px;
        border-radius: 8px;
        max-width: 318px;
        .qr {
            width: 100%;
            height: 288px;
            border-radius: 8px;
            background-color: var(--bg-qr);
            background-image: url("../assets/qr-code.png");
            background-repeat: no-repeat;
            background-position: center;
            background-size: 160px;
        }
        .content {
            h1 {
                font-family: 'Outfit';
                font-style: normal;
                font-weight: 700;
                font-size: 22px;
                line-height: 28px;
                text-align: center;
            }
            p {
                color: var(--text-gray);
                font-family: 'Outfit';
                font-style: normal;
                font-weight: 400;
                font-size: 15px;
                line-height: 19px;
                text-align: center;
                letter-spacing: 0.1875px;
            }
        }
    }
</style>