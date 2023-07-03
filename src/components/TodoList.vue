<script setup lang="ts"></script>

<template>
<div class="todo">
  <h2>TODO-LIST</h2>
  <div class="task">
  <input type="text" placeholder="Enter New Task"/>
  <button class="btn">ADD</button>
  </div>
  <hr/>
  <div class="content">
    <table>
      <thead>
        <tr>
          <th>Id</th>
          <th>Tasks</th>
          <th>Status</th>
        </tr>
      </thead>
    </table>
  </div>

</div>

</template>

<style scoped></style>
