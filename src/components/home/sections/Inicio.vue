<template>
    <span>
        <div class="uk-position-relative">
            <img src="https://images.pexels.com/photos/1065084/pexels-photo-1065084.jpeg?dl&fit=crop&crop=entropy&w=1800&h=1024" alt="">
            <div class="uk-position-top">
                <nav class="uk-navbar-container uk-navbar-transparent" uk-navbar>
                    <div class="uk-navbar-center">
                        <ul class="uk-navbar-nav">
                            <li class="white-text"><a href="#">Active</a></li>
                            <li class="white-text"><a href="#">Item</a></li>
                            <li class="white-text">
                                <a href="#">Parent</a>
                                <div class="uk-navbar-dropdown">
                                    <ul class="uk-nav uk-navbar-dropdown-nav">
                                        <li class="uk-active"><a href="#">Active</a></li>
                                        <li><a href="#">Item</a></li>
                                        <li class="uk-nav-header">Header</li>
                                        <li><a href="#">Item</a></li>
                                        <li><a href="#">Item</a></li>
                                        <li class="uk-nav-divider"></li>
                                        <li><a href="#">Item</a></li>
                                    </ul>
                                </div>
                            </li>
                        </ul>
                    </div>
                </nav>
            </div>
        </div>
    </span>
</template>
<script>
    export default {
      name: 'Inicio'
    }
</script>