<template>
    <div> 
        <Nav />
        <Nav2 />
        <Nav3 />
        <div class="container"> 
            <LargeCardDisplay 
                v-for="cardInfo in LargeCardInfo.slice(0,1)"
                :key="cardInfo.id"
                :cardsSection="cardInfo"
            />
            <SmallCardDisplay 
                v-for="cardInfo in SmallCardInfo"
                :key="cardInfo.id"
                :cardsSection="cardInfo"
            />
        </div>
    </div>
</template>

<script>
    import { largeCardSections, smallCardSections } from "@/assets/data.js"
    export default {
        data() {
            return {
                LargeCardInfo: largeCardSections,
                smallCardSections: smallCardSections
            }
        }
    }
</script>

<style scoped>

</style>