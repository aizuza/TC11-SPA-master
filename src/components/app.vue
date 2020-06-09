<template>
    <div>
        <p>Hello World</p>

        <!-- VueNavBar -->
        <!-- VueMenu -->

        <VueButton text="Hola"></VueButton>
        <VueButton text="Adios"></VueButton>
        <VueButton text="Bye"></VueButton>
        <VueButton></VueButton>
        <VueButton></VueButton>

        <!-- VueFooter -->
        <ul>
            <li>Elemento 1</li>
            <li>Elemento 2</li>
        </ul>
    </div>
</template>

<script>
import './../css/style.css';
import VueButton from './VueButton.vue';

export default {
    data: [],
    components: {
        VueButton
    }
}
</script>

<style>
    p {
        color: red;
    }
</style>