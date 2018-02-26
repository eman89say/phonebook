<template>
	<nav class="navbar is-link" role="navigation" aria-label="main navigation">
	  <div class="navbar-brand">
	    <a class="navbar-item">
           <strong style="font-size:24px; width:150px;">Phonebook</strong>
        </a>


       <div class="navbar-menu is-active"
           <router-link to="/home" class="navbar-item">Home</router-link>
           <router-link to="/about" class="navbar-item">About</router-link>
       </div>



	    <div class="navbar-burger">
	      <span></span>
	      <span></span>
	      <span></span>
	    </div>
	  </div>
	</nav>
</template>