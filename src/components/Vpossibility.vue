<script setup>
import { Swiper, SwiperSlide } from "swiper/vue";
import { Pagination, Navigation } from "swiper/modules";
import "swiper/css";
import "swiper/css/pagination";

</script>

<template>
<section class="possibility">
            <div class="container">
                <div class="possibilities">
                    <h2>Возможности</h2>
                    <div class="row">
                        <div class="col-xs-12 col-md-3">
                            <div class="possibilities__card1">
                                <div class="possibilities__card1-img-wrap">
                                    <img src="/Group 116.png" alt="">
                                </div>
                                <div class="possibilities__card1-name"><strong>Общение с классом</strong></div>
                                <div class="possibilities__card1-description">
                                    Видеосвязь<br>Чат с классом
                                </div>
                            </div>
                        </div>
                        <div class="col-xs-12 col-md-3">
                            <div class="possibilities__card2">
                                <div class="possibilities__card2-img-wrap">
                                    <img src="/Group 174.png" alt="">
                                </div>
                                <div class="possibilities__card2-name"><strong>Проведение занятий</strong></div>
                                <div class="possibilities__card2-description">
                                    Презентация файлов Демонстрация экрана
                                </div>
                            </div>
                        </div>
                        <div class="col-xs-12 col-md-3">
                            <div class="possibilities__card1">
                                <div class="possibilities__card1-img-wrap">
                                    <img src="/Group 218.png" alt="">
                                </div>
                                <div class="possibilities__card1-name"><strong>Посещаемость</strong></div>
                                <div class="possibilities__card1-description">
                                    Автоматическое отслеживание присутсвующих
                                </div>
                            </div>
                        </div>
                        <div class="col-xs-12 col-md-3">
                            <div class="possibilities__card2">
                                <div class="possibilities__card2-img-wrap">
                                    <img src="/Group.png" alt="">
                                </div>
                                <div class="possibilities__card2-name"><strong>История занятий</strong></div>
                                <div class="possibilities__card2-description">
                                    Материалы урока
                                </div>
                            </div>
                        </div>
                    </div>
                    <Swiper :loop="true" :modules="[Pagination]" :pagination="true" class="swiper" space-between="30">
                        <SwiperSlide class="swiper-slide">
                            <div class="possibilities__card1">
                                    <div class="possibilities__card1-img-wrap">
                                        <img src="/Group 116.png" alt="">
                                    </div>
                                    <div class="possibilities__card1-name"><strong>Общение с классом</strong></div>
                                    <div class="possibilities__card1-description">
                                        Видеосвязь Чат с классом
                                    </div>
                                </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div class="possibilities__card2">
                                    <div class="possibilities__card2-img-wrap">
                                        <img src="/Group 174.png" alt="">
                                    </div>
                                    <div class="possibilities__card2-name"><strong>Проведение занятий</strong></div>
                                    <div class="possibilities__card2-description">
                                        Презентация файлов Демонстрация экрана
                                    </div>
                                </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div class="possibilities__card1">
                                    <div class="possibilities__card1-img-wrap">
                                        <img src="/Group 218.png" alt="">
                                    </div>
                                    <div class="possibilities__card1-name"><strong>Посещаемость</strong></div>
                                    <div class="possibilities__card1-description">
                                        Автоматическое отслеживание присутсвующих
                                    </div>
                                </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div class="possibilities__card2">
                                    <div class="possibilities__card2-img-wrap">
                                        <img src="/Group.png" alt="">
                                    </div>
                                    <div class="possibilities__card2-name"><strong>История занятий</strong></div>
                                    <div class="possibilities__card2-description">
                                        Материалы урока
                                    </div>
                                </div>
                        </SwiperSlide>
                        <br>
                        <br>
                    </Swiper>
                </div>
            </div>
        </section>
</template>

<style scoped>

</style>