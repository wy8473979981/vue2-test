<template>
    <transition name="fade">
        <div>
            test2
        </div>
    </transition>
</template>

<script>
    export default {
        data() {
            return {
                storeId: this.$route.params.storeId
            }
        },
        mounted: function() {
            console.log(this.storeId)
        }
    }
</script>