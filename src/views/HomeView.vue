<script setup>
    import HomeCard from '../components/HomeCard.vue';
</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Podcasts to make you smarter
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Recommended radio
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/120/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard image="https://picsum.photos/id/110/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/221/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/232/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/187/300/300" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Recommended songs
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/88/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard image="https://picsum.photos/id/243/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/123/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/121/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/99/300/300" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>
</template>
