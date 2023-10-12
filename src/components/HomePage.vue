<template>
<h1>
My name is {{name}}<br>
I live on Planet {{getName().world}}<br>
{{getRank()}}
</h1>
</template>

<script>
export default {
    name: 'HomePage',
    data() {
        return {
            name: "Rahul",
            getRank: function() {
                return "our rank is 3rd"

            }

        }
    },
    methods: {
        getName() {
            return {
                world: "Earth"
            }
        }
    }
}
</script>

<style>
</style>