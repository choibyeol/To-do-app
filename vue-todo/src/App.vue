<template>
  <div id="app">
    <TodoHeader></TodoHeader>
    <TodoFooter></TodoFooter>
    <TodoInput></TodoInput>
    <TodoList></TodoList>
  </div>
</template>

<script>
import TodoHeader from './components/TodoHeader.vue'
import TodoFooter from './components/TodoFooter.vue'
import TodoInput from './components/TodoInput.vue'
import TodoList from './components/TodoList.vue'

export default {
    components: {
      // '컴포넌트 이름': '컴포넌트 내용'
      'TodoHeader': TodoHeader,
      'TodoFooter': TodoFooter,
      'TodoInput': TodoInput,
      'TodoList': TodoFooter,
  }
}
</script>

<style>

</style>
