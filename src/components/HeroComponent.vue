<template>
  <section class="mt-5 hero">
            <div class="container">
                <div class="row">
                    <div class="col-6 d-flex flex-column justify-content-center align-items-center">
                        <div class="welcome-text w-75">
                            <h1 class="display-5 fw-bolder mb-3">
                                Anda bosen..? Chat dong aja
                            </h1>
                            <p>
                                anda merasa jomblo, kami menyediakan jasa untuk menemani malam anda yang sepi
                            </p>
                            <button
                                class="btn btn-success btn-lg px-4 rounded-pill mt-5"
                            >
                                Chat Dong
                            </button>
                        </div>
                    </div>
                    <div class="col-6">
                        <lottie-player src="https://assets3.lottiefiles.com/packages/lf20_sk5h1kfn.json" background="transparent" speed="1"
                        style="width: 100%; height: auto;" loop autoplay></lottie-player>
                    </div>
                </div>
            </div>
        </section>
</template>

<script>
export default {
  name: 'HeroComponent',
  props: {
    // msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
