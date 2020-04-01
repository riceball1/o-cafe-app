<template>
    <h1>{{ coffeeType }} Menu</h1>
</template>

<script>
export default {
    props: {
        coffeeType: {
            type: String,
            required: true
        }
    }
}
</script>