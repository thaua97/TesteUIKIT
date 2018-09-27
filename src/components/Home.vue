<template>
    <div>
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
        <div class="uk-section uk-section-muted">
            <div class="uk-container">
                <h2> Teste Section</h2>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim, ea adipisci. Perferendis beatae, ipsam labore aspernatur repellendus laboriosam reiciendis facilis aut amet quis magnam voluptas enim quos? Cum, sunt eligendi?
                </p>
                <div class="uk-container">
                    <div class="uk-grid-collapse uk-child-width-expand@s uk-text-center" uk-grid>
                        <div>
                            <div class="uk-padding">Teste</div>
                        </div>
                        <div>
                            <div class="uk-padding bg1 white-text">Teste</div>
                        </div>
                        <div>
                            <div class="uk-padding bg2 white-text">Teste</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="uk-height-large uk-background-cover uk-light uk-flex" 
              uk-parallax="bgy: -700" 
              style="background-image: url(https://getuikit.com/docs/images/dark.jpg);"
        ></div>
        <div class="uk-section uk-section-muted white-text">
            <div class="uk-container uk-container-small">
                <h2>teste</h2>
                <p class="uk-text-lead">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora quo dicta culpa maxime quae beatae eaque nesciunt ipsum veniam, tempore autem, nam alias iste saepe quod voluptatum praesentium exercitationem voluptatem!
                </p>
                <div class="uk-text-center" uk-grid>
                    <div class="uk-width-1-3">
                        <div class="uk-card uk-card-default">
                            <div class="uk-card-media-top">
                                <img 
                                    src="https://images.pexels.com/photos/1438275/pexels-photo-1438275.jpeg?dl&fit=crop&crop=entropy&w=600&h=400" 
                                    alt=""
                                >
                            </div>
                            <div class="uk-card-body">
                                <h3 class="uk-card-title">Titulo</h3>
                                <p>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis, nihil consequatur! Provident nihil hic pariatur.
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="uk-width-1-3">
                        <div class="uk-card uk-card-default">
                            <div class="uk-card-body">
                                <h3 class="uk-card-title">Titulo</h3>
                                <p>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis, nihil consequatur! Provident nihil hic pariatur.
                                </p>
                            </div>
                            <div class="uk-card-media-bottom">
                                <img 
                                    src="https://images.pexels.com/photos/1112796/pexels-photo-1112796.jpeg?dl&fit=crop&crop=entropy&w=600&h=400" 
                                    alt=""
                                >
                            </div>
                        </div>
                    </div>
                    <div class="uk-width-1-3">
                        <div class="uk-card uk-card-default uk-card-body">
                            <h3 class="uk-card-title">Teste</h3>
                            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perferendis eum reiciendis quod accusantium consectetur ea ut qui corrupti.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="uk-section-large uk-light uk-background-cover" style="background-image: url('https://images.pexels.com/photos/1037992/pexels-photo-1037992.jpeg?cs=srgb&dl=abstract-art-background-1037992.jpg&fm=jpg')">
            <div class="uk-container">
                <h3>Section with Images</h3>
                <div class="uk-grid-match uk-child-width-1-3@m" uk-grid>
                    <div>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis tenetur adipisci vitae aliquid repellat. Culpa laborum blanditiis molestiae quod aliquid eligendi adipisci nulla quam maiores laboriosam eos, ipsa necessitatibus iste![]
                    </div>
                </div>
            </div>
        </div>
        <div class="uk-section-large">
            <div class="uk-container">
                <div class="uk-column-1-2 uk-column-divider">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui maxime dolores minima, tempore labore non est quae rem cumque nesciunt incidunt fugit velit error dolorem quia reprehenderit tempora! Iure, atque?</p>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui maxime dolores minima, tempore labore non est quae rem cumque nesciunt incidunt fugit velit error dolorem quia reprehenderit tempora! Iure, atque?</p>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui maxime dolores minima, tempore labore non est quae rem cumque nesciunt incidunt fugit velit error dolorem quia reprehenderit tempora! Iure, atque?</p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
  export default {
    name: 'home'
  }
</script>
<style scoped>
    .bg1 {
        background: -webkit-linear-gradient(45deg, #1e87f0 0%, #4450ff 100%);
        background-color: aqua;
    }
    .bg2 {
        background: -webkit-linear-gradient(45deg, #f88383 0%, #fa3f3f 100%);
        background-color: red;
    }
    .white-text {
        color: azure;
    }
</style>