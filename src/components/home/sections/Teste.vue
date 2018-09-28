<template>
    <span>
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
    </span>
</template>
<script>
    export default {
      name: 'Teste'
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
