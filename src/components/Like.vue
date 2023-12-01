<script>
export default {
    name: 'Like',
    data() {
        return {
            counter: 0,
        }
    },
    methods: {
        increment: function() {
            this.counter++;
        }
    },
    computed: {

    }
}
</script>

<template>
    <button type="button" class="main__button-like" :class="{border: true}" @click="increment">&#10084; {{this.counter}}</button>
</template>