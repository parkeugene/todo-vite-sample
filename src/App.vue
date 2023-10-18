<template>
  <div>
    <h1 class="text-5xl text-amber-900">Todo List</h1>

    <form>
      <input class="bg-gray-50 border"/>
      <button>Add Todo</button>
      <button>Remove All Todos</button>
    </form>
  </div>

  <div>
    <h1>Done Homework</h1>
    <h1 class="completed">Riding a Bicycle</h1>
  </div>
</template>
<script setup></script>
<style>
.completed
{
  text-decoration: line-through;
}
</style>