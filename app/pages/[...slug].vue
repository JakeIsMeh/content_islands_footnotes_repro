<template>
    <ContentDoc>
        <template v-slot="{ doc }">
            <h1>Regular Rendering</h1>
            <NotIslandRenderer :value="doc" />
            <hr>
            <h1>Server Rendering</h1>
            <IslandRenderer :value="doc" />
        </template>
    </ContentDoc>
</template>