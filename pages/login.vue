<template>
  <div>
    <section class="section">
      <div class="container">
        <div class="columns is-desktop is-justify-content-center">
          <div class="column is-4-desktop">
            <img src="imagens/frase-do-dia.png" />
          </div>
          <div class="column is-6-desktop">
            <div class="p-6 shadow rounded content">
              <h2 class="section-title">Seja bem-vindo de volta a bordo! ⚓</h2>
              <p>A FiliPay vai ajudá-lo a maximizar os seus lucros</p>
              <form method="POST" action="#" style="margin-top: 50px">
                <div class="columns is-multiline">
                  <div class="form-group column is-12">
                    <label for="email">Email</label>
                    <input
                      type="email"
                      class="input"
                      id="email"
                      name="email"
                      placeholder="Your Email Address"
                      required=""
                    />
                  </div>
                  <div class="form-group column is-12">
                    <label for="password">Senha</label>
                    <input
                      type="password"
                      class="input"
                      id="password"
                      name="password"
                      placeholder="*****"
                      required=""
                    />
                  </div>

                  <div class="column is-12">
                    <button type="submit" class="btn btn-primary">
                      Entrar
                    </button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>
