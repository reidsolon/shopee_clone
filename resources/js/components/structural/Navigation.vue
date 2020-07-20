<template>
    <div class="p-1" id="navigation-wrapper">
        <div class="container text-white">
            <div class="row">
                <div class="col-md-6 col-12 text-left d-inline-flex">
                    <div class="nav-top-item-menu">
                        Seller Center
                    </div>
                    <div class="nav-top-item-menu">
                        Sell on Shopee
                    </div>
                </div>
                <div class="col-md-6 col-12 text-right">
                    <div class="nav-top-item-menu font-weight-bold">
                        <strong>Sign Up</strong>
                    </div>
                </div>
            </div>  
        </div>
        <nav class="navbar navbar-expand-lg navbar-light bg-light container text-white" id="navbar">
            <a class="navbar-brand" href="#">
                <!-- <img src="/docs/4.0/assets/brand/bootstrap-solid.svg" width="30" height="30" class="d-inline-block align-top" alt=""> -->
                Bootstrap
            </a>  
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="p-2">
                <div id="form-wrapper" class="p-1 row">
                    <form class="form-inline my-2 my-lg-0" id="navbar-search">
                        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                    </form>
                    <button class=" btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
                </div>
            </div>
            
        </nav>
    </div>
</template>

<script>
export default {

    
    
}
</script>
<style scoped>
input:focus, button:focus {
    outline: unset;
    box-shadow: unset;
}
#navigation-wrapper {
    background: rgb(245,62,45);
    background: linear-gradient(180deg, rgba(245,62,45,1) 35%, rgba(254,100,50,1) 100%);
}
#navbar {
    background-color: transparent !important; 
}
.nav-top-item-menu {
    border-right: 2px solid hsla(0,0%,100%,.22);
    padding: 0 .4375rem;
}
#navbar-search input {
    border: unset;
    background-color: transparent;
}
#form-wrapper button {
    color: #fff;
    background-color: #fe6432;
    border: unset;
}

#form-wrapper {
    background-color: #fff;
    border-radius: 2px;
}
</style>