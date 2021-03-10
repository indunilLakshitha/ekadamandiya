<template>
  <!-- HEADER START -->
    <header class="ps-main-header2">
        <nav>
            <div class="navbar navbar-expand-lg navbar-light ps-navbar">
                <div class="ps-navbar__header">
                    <a href="index.html" class="navbar-brand">
                        <img src="images/logo.png" alt="Image Description">
                        <img src="images/homepage-2/logo.png" alt="Image Description">
                    </a>
                    <div id="ps-nav" class="ps-nav navbar-expand-lg">
                        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                            <i class="lnr lnr-menu"></i>
                        </button>
                        <div class="collapse navbar-collapse ps-navigation" id="navbarNav">
                            <ul class="navbar-nav nav-Js ml-auto ps-nav ps-nav__ul">
                                <li class="ps-menuhover menu-item-has-children page_item_has_children">
                                    <a href="javascript:void(0);" class="ps-header__line">Main <i class="fas fa-chevron-down"></i></a>
                                    <ul class="sub-menu ps-dropdown ps-first__dropdown">
                                        <li class="nav-item"><a href="index.html">Home 1</a></li>
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a href="index-v2.html">Home 2</a></li> 
                                    </ul>
                                </li>
                                <li class="nav-item"><a href="categories.html">Categories</a></li>
                                <li class="nav-item"><a href="contact.html">Contact</a></li>
                                <li class="ps-menuhover menu-item-has-children page_item_has_children">
                                    <a href="javascript:void(0);"><span class="lnr lnr-menu"></span></a>
                                    <ul class="ps-dropdown sub-menu">
                                        <li>
                                            <a href="about.html">About</a>
                                        </li>
                                        <li class="dropdown-divider"></li>
                                        <li class="current-menu-item">
                                            <a href="privacy-info.html">Privacy Info</a>
                                        </li>
                                        <li class="dropdown-divider"></li>
                                        <li class="ps-menuhover ps-submenuhover menu-item-has-children page_item_has_children">
                                            <a href="javascript:void(0);">Blog<i class="ti-angle-right"></i></a>
                                            <ul class="ps-dropdown ps-submenu sub-menu">
                                                <li class="nav-item"><a href="blog-grid.html">Blog Grid</a></li>                             
                                                <li class="dropdown-divider"></li>
                                                <li class="nav-item"><a href="blog-single.html">Blog Single</a></li>  
                                            </ul>
                                        </li>
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item ps-menuhover ps-submenuhover menu-item-has-children page_item_has_children">
                                            <a href="javascript:void(0);">Listing <i class="ti-angle-right"></i></a>
                                            <ul class="ps-dropdown ps-submenu sub-menu">
                                                <li class="nav-item"><a href="listing-grid.html">Listing Grid</a></li>                             
                                                <li class="dropdown-divider"></li>
                                                <li class="nav-item"><a href="listing-list.html">Listing List</a></li>  
                                                <li class="dropdown-divider"></li>
                                                <li class="nav-item"><a href="listing-single.html">Listing Single</a></li>  
                                            </ul>
                                        </li>
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a href="login.html">Login</a></li>
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a href="coming-soon.html">Coming Soon</a></li>
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a href="404-error.html">404 Error</a></li>
                                    </ul>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="ps-navbar__userbtn">
                        <div class="ps-headeruser">              
                            <ul class="navbar-nav ps-nav">
                                <li class="nav-item ps-login--btn"><a href="login.html" class="btn ps-btn">Login / Register</a></li>
                                <li class="nav-item dropdown ps-menuhover ps-userlogo">
                                    <a href="javascript:void(0);" id="navbarDropdown4" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                        <figure class="d-inline-block">
                                            <img src="images/user-logo.jpg" alt="Image Description">
                                        </figure>
                                    <span><i class="fas fa-chevron-down"></i></span>
                                    </a>
                                    <ul class="dropdown-menu ps-dropdown ps-user__dropdown position-absolute" aria-labelledby="navbarDropdown4">
                                        <li class="nav-item"><a class="dropdown-item" href="dashboard-insights.html"><i class="ti-dashboard"></i>Insights</a></li>                             
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a class="dropdown-item" href="dashboard-profile-setting.html"><i class="ti-user"></i>Profile Settings</a></li>
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a class="dropdown-item" href="dashboard-my-ads.html"><i class="ti-align-justify"></i>My Ads</a></li>  
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a class="dropdown-item" href="dashboard-post-ad.html"><i class="ti-settings"></i>Post Ads</a></li>  
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a class="dropdown-item" href="dashboard-offers-messages.html"><i class="ti-email"></i>Offers/Messages</a></li>  
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a class="dropdown-item" href="dashboard-buy-package.html"><i class="ti-shopping-cart"></i>Buy New Packages</a></li>  
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a class="dropdown-item" href="dashboard-payments.html"><i class="ti-user"></i>Payments</a></li>  
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item dropdown ps-menuhover ps-submenuhover">
                                            <a class="dropdown-item" href="javascript:void(0);" id="navbarDropdown5" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                                <i class="ti-heart"></i>My Favorite <i class="ti-angle-right ps-right"></i>
                                            </a>
                                            <ul class="dropdown-menu ps-dropdown ps-submenu navbar-nav" aria-labelledby="navbarDropdown5">
                                                <li class="nav-item"><a class="dropdown-item" href="dashboard-my-favorite.html">Favorite Listing</a></li>                             
                                                <li class="dropdown-divider"></li>
                                                <li class="nav-item"><a class="dropdown-item" href="javascript:void(0);">Sub Menu</a></li>
                                            </ul>
                                        </li> 
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a class="dropdown-item" href="dashboard-account-setting.html"><i class="ti-bookmark"></i>Account Setting</a></li>  
                                        <li class="dropdown-divider"></li>
                                        <li class="nav-item"><a class="dropdown-item" href="index.html"><i class="ti-shift-right"></i>Logout</a></li>  
                                    </ul>
                                </li>                            
                                <li class="nav-item ps-post--btn"><a href="dashboard-insights.html" class="btn ps-btn">Post Ad</a></li>
                            </ul>
                        </div>
                    </div>         
                </div>
            </div> 
        </nav>
    </header>
    <!-- HEADER END -->
</template>

<script>
export default {

}
</script>

<style>

</style>