<template>
    <div class="about">
        <h1>Vue Todos About</h1>
        <p>
            Vue Todos is a CRUD Todo tracking application created for a Vue 3
            Crash Course.
        </p>
        <p>
            Track your daily task's using this todo tracker with abilities to
            save, complete, edit & delete todos.
        </p>
        <p>
            Feel free to add on to this application with functionalities such as
            the ability to drag and reorder todos, animate creation/deletion of
            todos or even create this into a full stack application with the
            ability to have different lists for different days of tracking
            todos!
        </p>
    </div>
</template>

<style scoped>
@media (min-width: 1024px) {
    .about {
        min-height: 100vh;
        /* display: flex; */
        align-items: center;
    }
}
p {
    margin: 1em;
}
h1 {
    margin: 0.5em;
}
</style>
