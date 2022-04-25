<template>
<!-- Main Wrapper -->
<div class="main-wrapper">

    <!-- Header -->
    <header class="header">
        <nav class="navbar navbar-expand-lg header-nav">
            <div class="navbar-header">
                <a id="mobile_btn" href="javascript:void(0);">
                    <span class="bar-icon">
                        <span></span>
                        <span></span>
                        <span></span>
                    </span>
                </a>
                <a href="index.html" class="navbar-brand logo">
                    <img src="assets/img/logo.png" class="img-fluid" alt="Logo">
                </a>
            </div>
            <div class="main-menu-wrapper">
                <div class="menu-header">
                    <a href="index.html" class="menu-logo">
                        <img src="assets/img/logo.png" class="img-fluid" alt="Logo">
                    </a>
                    <a id="menu_close" class="menu-close" href="javascript:void(0);">
                        <i class="fas fa-times"></i>
                    </a>
                </div>
                <ul class="main-nav">
                    <li>
                        <a href="index.html">Home</a>
                    </li>
                    <li class="has-submenu">
                        <a href="">Mentor <i class="fas fa-chevron-circle-down"></i></a>
                        <ul class="submenu">
                            <li><a href="dashboard.html">Mentor Dashboard</a></li>
                            <li class="active"><a href="bookings.html">Bookings</a></li>
                            <li><a href="schedule-timings.html">Schedule Timing</a></li>
                            <li><a href="mentee-list.html">Mentee List</a></li>
                            <li><a href="profile-mentee.html">Mentee Profile</a></li>
                            <li class="has-submenu">
                                <a href="blog.html">Blog</a>
                                <ul class="submenu">
                                    <li><a href="blog.html">Blog</a></li>
                                    <li><a href="blog-details.html">Blog View</a></li>
                                    <li><a href="add-blog.html">Add Blog</a></li>
                                    <li><a href="edit-blog.html">Edit Blog</a></li>
                                </ul>
                            </li>
                            <li><a href="chat.html">Chat</a></li>
                            <li><a href="invoices.html">Invoices</a></li>
                            <li><a href="profile-settings.html">Profile Settings</a></li>
                            <li><a href="reviews.html">Reviews</a></li>
                            <li><a href="mentor-register.html">Mentor Register</a></li>
                        </ul>
                    </li>
                    <li class="has-submenu active">
                        <a href="">Mentee <i class="fas fa-chevron-circle-down"></i></a>
                        <ul class="submenu">
                            <li class="has-submenu">
                                <a href="#">Mentors</a>
                                <ul class="submenu">
                                    <li><a href="map-grid.html">Map Grid</a></li>
                                    <li><a href="map-list.html">Map List</a></li>
                                </ul>
                            </li>
                            <li class="active"><a href="search.html">Search Mentor</a></li>
                            <li><a href="profile.html">Mentor Profile</a></li>
                            <li><a href="bookings-mentee.html">Bookings</a></li>
                            <li><a href="checkout.html">Checkout</a></li>
                            <li><a href="booking-success.html">Booking Success</a></li>
                            <li><a href="dashboard-mentee.html">Mentee Dashboard</a></li>
                            <li><a href="favourites.html">Favourites</a></li>
                            <li><a href="chat-mentee.html">Chat</a></li>
                            <li><a href="profile-settings-mentee.html">Profile Settings</a></li>
                            <li><a href="change-password.html">Change Password</a></li>
                        </ul>
                    </li>
                    <li class="has-submenu">
                        <a href="">Pages <i class="fas fa-chevron-circle-down"></i></a>
                        <ul class="submenu">
                            <li><a href="voice-call.html">Voice Call</a></li>
                            <li><a href="video-call.html">Video Call</a></li>
                            <li><a href="search.html">Search Mentors</a></li>
                            <li><a href="components.html">Components</a></li>
                            <li class="has-submenu">
                                <a href="invoices.html">Invoices</a>
                                <ul class="submenu">
                                    <li><a href="invoices.html">Invoices</a></li>
                                    <li><a href="invoice-view.html">Invoice View</a></li>
                                </ul>
                            </li>
                            <li><a href="blank-page.html">Starter Page</a></li>
                            <li><a href="login.html">Login</a></li>
                            <li><a href="register.html">Register</a></li>
                            <li><a href="forgot-password.html">Forgot Password</a></li>
                        </ul>
                    </li>
                    <li class="has-submenu">
                        <a href="">Blog <i class="fas fa-chevron-circle-down"></i></a>
                        <ul class="submenu">
                            <li><a href="blog-list.html">Blog List</a></li>
                            <li><a href="blog-grid.html">Blog Grid</a></li>
                            <li><a href="blog-details.html">Blog Details</a></li>
                        </ul>
                    </li>
                    <li>
                        <a href="admin/index.html" target="_blank">Admin</a>
                    </li>
                </ul>
            </div>
            <ul class="nav header-navbar-rht">

                <!-- User Menu -->
                <li class="nav-item dropdown has-arrow logged-item">
                    <a href="#" class="dropdown-toggle nav-link" data-toggle="dropdown">
                        <span class="user-img">
                            <img class="rounded-circle" src="assets/img/user/user.jpg" width="31" alt="Darren Elder">
                        </span>
                    </a>
                    <div class="dropdown-menu dropdown-menu-right">
                        <div class="user-header">
                            <div class="avatar avatar-sm">
                                <img src="assets/img/user/user.jpg" alt="User Image" class="avatar-img rounded-circle">
                            </div>
                            <div class="user-text">
                                <h6>Jonathan Doe</h6>
                                <p class="text-muted mb-0">Mentor</p>
                            </div>
                        </div>
                        <a class="dropdown-item" href="dashboard.html">Dashboard</a>
                        <a class="dropdown-item" href="profile-settings.html">Profile Settings</a>
                        <a class="dropdown-item" href="login.html">Logout</a>
                    </div>
                </li>
                <!-- /User Menu -->

            </ul>
        </nav>
    </header>
    <!-- /Header -->

    <!-- Breadcrumb -->
    <div class="breadcrumb-bar">
        <div class="container-fluid">
            <div class="row align-items-center">
                <div class="col-md-8 col-12">
                    <nav aria-label="breadcrumb" class="page-breadcrumb">
                        <ol class="breadcrumb">
                            <li class="breadcrumb-item"><a href="index.html">Home</a></li>
                            <li class="breadcrumb-item active" aria-current="page">Search</li>
                        </ol>
                    </nav>
                    <h2 class="breadcrumb-title">2245 matches found for : Mentors In Florida</h2>
                </div>
                <div class="col-md-4 col-12 d-md-block d-none">
                    <div class="sort-by">
                        <span class="sort-title">Sort by</span>
                        <span class="sortby-fliter">
                            <select class="select">
                                <option>Select</option>
                                <option class="sorting">Rating</option>
                                <option class="sorting">Popular</option>
                                <option class="sorting">Latest</option>
                                <option class="sorting">Free</option>
                            </select>
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- /Breadcrumb -->

    <!-- Page Content -->
    <div class="content">
        <div class="container-fluid">

            <div class="row">
                <div class="col-md-12 col-lg-4 col-xl-3 theiaStickySidebar">

                    <!-- Search Filter -->
                    <div class="card search-filter">
                        <div class="card-header">
                            <h4 class="card-title mb-0">Search Filter</h4>
                        </div>
                        <div class="card-body">
                            <div class="filter-widget">
                                <div class="cal-icon">
                                    <Datepicker v-model="date"></Datepicker>
                                </div>
                            </div>
                            <div class="filter-widget">
                                <h4>Grade</h4>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type">
                                        <span class="checkmark"></span> Grade 1-4
                                    </label>
                                </div>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type">
                                        <span class="checkmark"></span> Grade 5-9
                                    </label>
                                </div>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type">
                                        <span class="checkmark"></span> Grade 10
                                    </label>
                                </div>
                            </div>
                            <div class="filter-widget">
                                <h4>Subject</h4>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type">
                                        <span class="checkmark"></span> Mathematics
                                    </label>
                                </div>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type">
                                        <span class="checkmark"></span> English
                                    </label>
                                </div>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type">
                                        <span class="checkmark"></span> Physics
                                    </label>
                                </div>
                            </div>
                            <div class="filter-widget">
                                <h4>Type</h4>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type">
                                        <span class="checkmark"></span> Online
                                    </label>
                                </div>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type">
                                        <span class="checkmark"></span> Offline
                                    </label>
                                </div>

                            </div>
                            <div class="filter-widget">
                                <h4>Location</h4>
                                <div class="form-group">
                                    <select class="select form-control">
                                        <option>Select</option>
                                        <option>15 mins</option>
                                        <!-- <option selected="selected">30 mins</option> -->
                                        <option>45 mins</option>
                                        <option>1 Hour</option>
                                    </select>
                                </div>
                            </div>
                            <div class="filter-widget">
                                <h4>Language Spoken</h4>
                                <div class="form-group">
                                    <select class="select form-control">
                                        <option>Select</option>
                                        <option>15 mins</option>
                                        <!-- <option selected="selected">30 mins</option> -->
                                        <option>45 mins</option>
                                        <option>1 Hour</option>
                                    </select>
                                </div>
                            </div>
                            <div class="filter-widget">
                                <h4>Gender</h4>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type" checked>
                                        <span class="checkmark"></span> Male
                                    </label>
                                </div>
                                <div>
                                    <label class="custom_check">
                                        <input type="checkbox" name="gender_type">
                                        <span class="checkmark"></span> Female
                                    </label>
                                </div>
                            </div>
                            <div>
                                <div class="row row-sm">
                                    <div class="col-6 btn-search">
                                        <button type="button" class="btn btn-block">Search</button>
                                    </div>
                                    <div class="col-6 btn-reset">
                                        <button type="button" class="btn btn-block">Reset</button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- /Search Filter -->

                </div>

                <div class="col-md-12 col-lg-8 col-xl-9">

                    <!-- Mentor Widget -->
                    <div class="card" v-for="item in teacherslist" v-bind:key="item.id">
                        <div class="card-body">
                            <div class="mentor-widget">
                                <div class="user-info-left">
                                    <div class="mentor-img my-auto">
                                        <a href="profile.html">
                                            <img src="assets/img/user/user1.jpg" class="img-fluid" alt="User Image">
                                        </a>
                                    </div>
                                    <div class="user-info-cont">
                                        <h4 class="usr-name"><a href="profile.html">Donna Yancey {{item.user}}</a></h4>
                                        <span class="mentor-type">{{item.title}}</span><br>
                                        <span class="mentor-type">{{item.gender}}</span><br>
                                       
                                        <div class="rating">
                                            <i class="fas fa-star filled"></i>
                                            <i class="fas fa-star filled"></i>
                                            <i class="fas fa-star filled"></i>
                                            <i class="fas fa-star filled"></i>
                                            <i class="fas fa-star"></i>
                                            <span class="d-inline-block average-rating">(17)</span>
                                        </div>
                                        <div class="mentee-details">
                                            <template v-for="sub in item.subjects" v-bind:key="sub.id">
                                                <h5><i class="fa fa-graduation-cap"></i> {{sub.subject}} {{sub.subject_ar}}</h5>
                                            </template>
                                            <template v-for="grad in item.grades" v-bind:key="grad.id">
                                                <h5><i class="fa fa-server"></i> {{grad.grade}} {{grad.grade_ar}}</h5>
                                            </template>
                                            <template v-for="lang in item.languages" v-bind:key="lang.id">
                                                <h5><i class="fa fa-language"></i> {{lang.language}} {{lang.language_ar}}</h5>
                                            </template>
                                        </div>
                                    </div>
                                </div>
                                <div class="user-info-right">
                                    <div class="user-infos">
                                        <ul>
                                            <li>Available <span class="text-green"> Next Thursday</span></li>
                                             <span class="mentor-type">{{item.description}}</span>
                                            <li><i class="fas fa-map-marker-alt"></i> {{item.location.id}} {{item.location.location}} {{item.location.location_ar}}</li>

                                            <li><i class="far fa-money-bill-alt"></i> {{item.hourly_rate}} <i class="fas fa-info-circle" data-toggle="tooltip" title="Lorem Ipsum"></i> </li>
                                             <li> {{item.iban}} </li>
                                            
                                        </ul>
                                    </div>
                                    <div class="mentor-booking">
                                        <a class="apt-btn" href="booking.html">Book Appointment</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- /Mentor Widget -->

                    <div class="load-more text-center">
                        <a class="btn btn-primary btn-sm" href="javascript:void(0);">Load More</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- /Page Content -->

    <!-- Footer -->
    <footer class="footer">

        <!-- Footer Top -->
        <div class="footer-top">
            <div class="container-fluid">
                <div class="row">

                    <div class="col-lg-3 col-md-6">
                        <!-- Footer Widget -->
                        <div class="footer-widget footer-about">
                            <div class="footer-logo">
                                <img src="assets/img/logo-white.png" alt="logo">
                            </div>
                            <div class="footer-about-content">
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
                            </div>
                        </div>
                        <!-- /Footer Widget -->
                    </div>

                    <div class="col-lg-3 col-md-6">
                        <!-- Footer Widget -->
                        <div class="footer-widget footer-menu">
                            <h2 class="footer-title">For Mentee</h2>
                            <ul>
                                <li><a href="search.html">Search Mentors</a></li>
                                <li><a href="login.html">Login</a></li>
                                <li><a href="register.html">Register</a></li>
                                <li><a href="booking.html">Booking</a></li>
                                <li><a href="dashboard-mentee.html">Mentee Dashboard</a></li>
                            </ul>
                        </div>
                        <!-- /Footer Widget -->
                    </div>

                    <div class="col-lg-3 col-md-6">
                        <!-- Footer Widget -->
                        <div class="footer-widget footer-menu">
                            <h2 class="footer-title">For Mentors</h2>
                            <ul>
                                <li><a href="appointments.html">Appointments</a></li>
                                <li><a href="chat.html">Chat</a></li>
                                <li><a href="login.html">Login</a></li>
                                <li><a href="register.html">Register</a></li>
                                <li><a href="dashboard.html">Mentor Dashboard</a></li>
                            </ul>
                        </div>
                        <!-- /Footer Widget -->
                    </div>

                    <div class="col-lg-3 col-md-6">
                        <!-- Footer Widget -->
                        <div class="footer-widget footer-contact">
                            <h2 class="footer-title">Contact Us</h2>
                            <div class="footer-contact-info">
                                <div class="footer-address">
                                    <p> 3556 Beech Street, San Francisco,<br> California, CA 94108 </p>
                                </div>
                                <p>
                                    +1 315 369 5943
                                </p>
                                <p class="mb-0">
                                    mentoring@example.com
                                </p>
                            </div>
                        </div>
                        <!-- /Footer Widget -->
                    </div>

                </div>
            </div>
        </div>
        <!-- /Footer Top -->

        <!-- Footer Bottom -->
        <div class="footer-bottom">
            <div class="container-fluid">
                <!-- Copyright -->
                <div class="copyright">
                    <div class="row">
                        <div class="col-md-6">
                            <div class="copyright-text">
                                <p class="mb-0">&copy; 2020 Mentoring. All rights reserved.</p>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="social-icon text-md-right">
                                <ul>
                                    <li>
                                        <a href="#" target="_blank"><i class="fab fa-instagram"></i></a>
                                    </li>
                                    <li>
                                        <a href="#" target="_blank"><i class="fab fa-linkedin-in"></i></a>
                                    </li>
                                    <li>
                                        <a href="#" target="_blank"><i class="fab fa-twitter"></i> </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- /Copyright -->
            </div>
        </div>
        <!-- /Footer Bottom -->

    </footer>
    <!-- /Footer -->

</div>
<!-- /Main Wrapper -->
</template>

<script>
import * as Vue from 'vue'
import axios from 'axios'
import VueAxios from 'vue-axios'
import Datepicker from '@vuepic/vue-datepicker';
import '@vuepic/vue-datepicker/dist/main.css'
const app = Vue.createApp('#app')
app.use(VueAxios, axios)
export default {
    components: {
        Datepicker
    },
    name: 'TeachersListing',
    data() {
        return {
            teacherslist: undefined,
            date: null,
        }
    },
    //  computed: {
    //         filterteacherslist: function(){
    //             return this.filterteacherslistBygender(this.filterteacherslistBylocation(this.filterteacherslistBylanguage(this.filterteacherslist)))
    //         }
    //     },
    //  methods: {

    //         filterteacherslistBygender: function(teacherslist){
    //             return teacherslist.filter(teacherslist => !teacherslist.gender.indexOf(this.gender))
    //         },

    //         filterteacherslistBylocation: function(teacherslist) {
    //             return teacherslist.filter(teacherslist => !teacherslist.location.indexOf(this.location))
    //         },

    //          filterteacherslistBylanguage: function(teacherslist) {
    //             return teacherslist.filter(teacherslist => !teacherslist.language.indexOf(this.language))
    //         },
    //     },
    
    mounted() {
        axios.get('https://teacherapp-api.herokuapp.com/api/teacher-list/').then((response) => {
            this.teacherslist = response.data;
            console.log(response.data)
        })
        // or
        //   this.$http.get('https://teacherapp-api.herokuapp.com/api/teacher-list/').then((response) => {
        //     console.log(response.data)
        //   })
    }
}
</script>
