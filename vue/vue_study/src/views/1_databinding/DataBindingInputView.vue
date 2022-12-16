<template>
    <div>
        <input type="text" v-model="userId"/>
        <button @click="myFunction">클릭</button>
    </div>
</template>
<script>
export default {
    coponents: {},
    data() {
        return {
            userId: 'taeeun.kim'
        }
    },
    setup() {},
    created() {},
    mounted() {},
    unmounted() {},
    methods: {
        myFunction() {
            // this.userId
            console.log(this.userId)
        }
    }
}
</script>
