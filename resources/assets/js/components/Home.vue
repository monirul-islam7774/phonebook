<template>
    <nav class="panel column is-offset-2 is-8">
        <p class="panel-heading">
            Vuejs Phonebook
            <button class="button is-link is-outlined">
                Add new
            </button>
        </p>
        <a class="panel-block">

            <span class="column is-9">
                marksheet
            </span>

            <span class="panel-icon column is-1">
                <i class="has-text-danger fa fa-trash"></i>
            </span>
            <span class="has-text-info panel-icon column is-1">
                <i class="fa fa-edit"></i>
            </span>
            <span class="has-text-primary panel-icon column is-1">
                <i class="fa fa-eye"></i>
            </span>
        </a>

        <div class="panel-block">
            <p class="control has-icons-left">
                <input class="input is-small" type="text" placeholder="search">
                <span class="icon is-small is-left">
        <i class="fas fa-search" aria-hidden="true"></i>
      </span>
            </p>
        </div>

        <div class="panel-block">

        </div>
    </nav>

</template>