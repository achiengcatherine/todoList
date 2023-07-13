<script setup lang="ts"></script>

<template>
<div class="todo">
  <h2>TODO-LIST</h2>
  <div class="task">
  <input type="text"  placeholder="Enter New Task"/>
  <button class="btn">ADD</button>
  </div>
  <hr/>
 <div class="list">
    <table>
      <thead>
        <tr class="header">
          <th>Id</th>
          <th>Tasks</th>
          <th>Status</th>
          <th>Edit</th>
         <th>Delete</th>
        </tr>
        <tr>
          <td>01</td>
          <td>add new task</td>
          <td>to do</td>
          <td>
            <div><span class="fa fa-pen"></span></div>
          </td>
          <td>
               <div><span class="fa fa-trash"></span></div>
          </td>
        </tr>
      </thead>
    </table>
  </div>

</div>

</template>

<style scoped></style>
