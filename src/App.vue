<template>
  <div id="app">
    <b-container>
      <b-nav tabs>
        <b-nav-item to='/todos' exact-active-class="active">Listado de todos</b-nav-item>
        <b-nav-item to='/todos/create' exact-active-class="active">Formulario de alta de todos</b-nav-item>
      </b-nav>
      <router-view/>
    </b-container>
  </div>
</template>