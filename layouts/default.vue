<template>
    <div class="site-container">
        <Header/>
        <div class="slot-container">
            <slot/>
        </div>
        <Footer/>
    </div>
</template>

<style scoped lang="scss">
.site-container {
    display: flex;
    flex-direction: column;
    height: 100%; /* Убирает высоту контейнера, гарантируя, что футер будет внизу */
}

.slot-container {
    display: flex;
    flex: 1; /* Эта часть должна занимать все оставшееся пространство */
}
</style>