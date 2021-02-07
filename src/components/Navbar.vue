<template>
    <!-- NAV -->
    <nav class="navbar navbar-expand-md navbar-light pt-2 m-0">
        <!-- <a href="#" class="navbar-brand">Brand</a> -->
        <button type="button" class="navbar-toggler mr-auto" data-toggle="collapse" data-target="#navbarCollapse">
            <span class="navbar-toggler-icon"></span>
        </button>
    
        <div class="collapse navbar-collapse flex-row-reverse" id="navbarCollapse">
            <div class="navbar-nav">
                <ul class="navbar-nav nav-ul">
                    <li class="nav-item">
                        <a class="nav-link nav-link-plans" href="#"><router-link class="nav-link-plans" to="/">Plans</router-link></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link nav-link-events" href="#"><router-link class="nav-link-events" to="/eventspage">Events </router-link></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">EAP</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Wellbeing</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">benefits</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">My organisation</a>
                    </li>
                    <li class="nav-item last-nav-item last-nav-link">
                        <a class="nav-link" href="#">Virtual</a>
                    </li>
                    </ul>
            </div>
        </div>
    </nav>
    <router-view/>
</template>