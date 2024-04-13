<template>
    <div class="my-component">
        <hr />
        <h1>Este es mi componente</h1>
        <h2>{{ subtitle }}</h2>
        <hr />
    </div>
</template>

<script>

export default {

    name: 'MyComponent',
    data() {
        return {
            subtitle: "Soy el subtitulo de MyComponent"
        }
    }

}
</script>
