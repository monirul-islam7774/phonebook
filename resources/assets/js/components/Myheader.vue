<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
            <div class="navbar-item">
                <strong width="112" height="28"> iQuantile </strong>
            </div>

            <div class="navbar-menu is-active">

                <router-link to="/home" class="navbar-item">Home</router-link>
                <router-link to="/about" class="navbar-item">About</router-link>

            </div>

            <button class="button navbar-burger">
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
            </button>
        </div>
    </nav>
</template>