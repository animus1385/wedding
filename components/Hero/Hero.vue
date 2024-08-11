<template>
    <section class="hero">
        <picture class="hero__picture" data-aos="zoom-in" data-aos-duration="1000" data-aos-once="true">
            <img class="hero__img" src="/img/hero.png" alt="hero" />
        </picture>
        <div
            class="hero__container container"
            data-aos="fade"
            data-aos-delay="50"
            data-aos-duration="1000"
            data-aos-easing="ease-in-out"
            data-aos-mirror="true"
            data-aos-once="true"
        >
            <div class="hero__content">
                <h1 class="hero__title title-level-1">Свадебное приглашение</h1>
                <div class="hero__names text-2">
                    <span class="hero__man">Бекзод</span>
                    <span class="hero__and-simbol">&</span>
                    <span class="hero__man">Сорахон</span>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup></script>

<style lang="scss" scoped>
@import './Hero.module.scss';
</style>
