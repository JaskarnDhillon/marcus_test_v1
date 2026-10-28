<script setup>
import { employees } from './data/employees';

// TODO: Add reactive search text and a computed property for filtered employees.
</script>

<template>
  <main>
    <h1>Staff Directory</h1>
    <p>{{ employees.length }} employees supplied. Complete the exercise in README.md.</p>

    <label for="search">Search by name</label>
    <!-- TODO: Bind this input using v-model. -->
    <input id="search" type="search" placeholder="Enter an employee name" />

    <table>
      <caption>Employees</caption>
      <thead>
        <tr>
          <th scope="col">Name</th>
          <th scope="col">Department</th>
        </tr>
      </thead>
      <tbody>
        <!-- TODO: Render the employee rows using v-for and a stable :key. -->
      </tbody>
    </table>

    <!-- TODO: Show an empty-state message when no employees match. -->
  </main>
</template>
