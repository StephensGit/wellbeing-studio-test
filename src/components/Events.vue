<template>
<!-- ROW 2 -->
    <div class="row row2">
        <!-- <h3 class="col-lg-6 col-md-9 col-sm-12 col-xl-5 row4-h3">Downloadable Guides</h3><span class="col-lg-6 col-md-3 col-sm-11 row4-hr hr-xs"></span> -->
        <h3 class="col-xl-4 col-lg-5 col-md-6 col-sm-12 col-12 row2-h3">Virtual Events</h3><span class="col-xl-8 col-lg-7 col-md-6 col-sm-11 col-11 row4-hr hr-sm hr-xs"></span>
        <p class="col-sm-12 row2-p mb-1 mt-1 media-small-p">Upcoming virtual events you can take part in:</p>
        
        <div class="col-xl-4 col-lg-6 col-md-6 col-sm-12 mt-4">
            <div class="card row2-cards">
                <div class="card-body row-2-card-body">
                    <h5>Virtual Yoga class with <br> Gemma Habington</h5>
                    <span class="row2-cards-date">20</span><span class="row2-cards-month">Nov</span>
                    <a class="row2-cards-more-info" href="#"><router-link class="nav-link-events" to="/eventspage">More information</router-link></a>
                </div>
            </div>
        </div>

        <div class="col-xl-4 col-lg-6 col-md-6 col-sm-12 mt-4">
            <div class="card row2-cards">
                <div class="card-body row-2-card-body">
                    <h5>Event Title to go here</h5>
                    <span class="row2-cards-date">21</span><span class="row2-cards-month">Nov</span>
                    <a class="row2-cards-more-info" href="#"><router-link class="nav-link-events" to="/eventspage">More information</router-link></a>
                </div>
            </div>
        </div>

        <div class="col-xl-4 col-lg-6 col-md-6 col-sm-12 mt-4">
            <div class="card row2-cards">
                <div class="card-body row-2-card-body">
                    <h5>Event Title to go here</h5>
                    <span class="row2-cards-date">22</span><span class="row2-cards-month">Nov</span>
                    <a class="row2-cards-more-info" href="#"><router-link class="nav-link-events" to="/eventspage">More information</router-link></a>
                </div>
            </div>
        </div>
    </div>
     <router-view/>
</template>