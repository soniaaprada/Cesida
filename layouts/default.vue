<script setup></script>

<template>
    <aside>
        <h1>nav</h1>
        <ul>
            <li>
                <NuxtLink to="/">Home</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/nosotros">Nosotros</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/identificador">Identificador</NuxtLink>
            </li>
        </ul>
    </aside>
    <div>
        <slot />
    </div>
</template>

<style scoped lang="scss">
.router-link-active {
    background-color: blue;
    color: white;
}
</style>
