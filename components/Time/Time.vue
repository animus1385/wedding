<template>
    <section class="time">
        <div class="time__container container">
            <h2 class="time__title title-level-2">
                <span data-aos="fade-right" data-aos-delay="500" data-aos-once="true">Ждём вас</span
                ><span data-aos="fade-left" data-aos-delay="700" data-aos-once="true">с нетерпением </span>
            </h2>
            <div class="time__content">
                <span class="time__text text-1" data-aos="fade-down" data-aos-delay="900" data-aos-once="true">через...</span>
                <div class="time__block">
                    <div class="time__days" data-aos="fade-up" data-aos-delay="1100" data-aos-once="true">
                        <span class="text-4">{{ timer.days }}</span
                        ><span class="text-1">Дней</span>
                    </div>
                    <div class="time__hours" data-aos="fade-up" data-aos-delay="1300" data-aos-once="true">
                        <span class="text-4">{{ timer.hours }}</span> <span class="text-1">Часов</span>
                    </div>
                    <div class="time__minutes" data-aos="fade-up" data-aos-delay="1500" data-aos-once="true">
                        <span class="text-4">{{ timer.minutes }}</span> <span class="text-1">Минут</span>
                    </div>
                    <div class="time__seconds" data-aos="fade-up" data-aos-delay="1700" data-aos-once="true">
                        <span class="text-4">{{ timer.seconds }}</span> <span class="text-1">Секунд</span>
                    </div>
                </div>
            </div>
            <p class="time__descr text-2" data-aos="fade-right" data-aos-delay="1900" data-aos-once="true">
                Очень ждем и будем рады видеть вас на нашей свадьбе
            </p>
            <span class="time__copy text-2" data-aos="fade-left" data-aos-delay="2100" data-aos-once="true">Ваши Бекзод и Сорахон!</span>

            <p class="time__check text-1" data-aos="fade" data-aos-delay="2300" data-aos-once="true">*Подтвердите, если сможете прийти.</p>
        </div>
    </section>
</template>

<script setup>
import { useTimer } from 'vue-timer-hook';
const endTime = new Date(2024, 8, 7, 18, 0, 0, 0);
const timer = useTimer(endTime);
</script>

<style lang="scss" scoped>
@import './Time.module.scss';
</style>
