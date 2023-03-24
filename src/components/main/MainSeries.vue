<script>
import CardElement from '../common/CardElement.vue';

export default {
    name: 'MainSeries',
    components: {
        CardElement
    },
    data() {
        return {
            seriesData: [
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$19.99",
                    series: "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$3.99",
                    series: "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$16.99",
                    series: "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$2.99",
                    series: "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$3.99",
                    series: "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$2.99",
                    series: "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$3.99",
                    series: "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$4.99",
                    series: "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$5.99",
                    series: "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$6.99",
                    series: "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$4.99",
                    series: "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/180/180",
                    "price": "$16.99",
                    series: "Catwoman",
                    "type": "graphic novel"
                }
            ]
        }
    }
}
</script>

<template>
    <div class="container">
        <h2>CURRENT SERIES</h2>
        <section>
            <CardElement 
                class="serie" 
                v-for="serie in seriesData"
                :img="serie.thumb"
                :title="serie.series.toUpperCase()" 
            />
        </section>
        <button>LOAD MORE</button>
    </div>
</template>

<style scoped lang="scss">

.container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
section {
    display: flex;
    flex-wrap: wrap;
    width: 75rem;

    :deep(.card) {
        width: calc(100% / 6);
        padding: 25px;
        display: flex;
        flex-direction: column;
        gap: .625rem;

        :deep(.image) {
            max-width: 100%;
        }
    }
}
</style>