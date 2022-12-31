<template>
  <div>
    <section class="section">
      <div class="container">
        <div class="columns is-desktop is-justify-content-center">
          <div class="column is-8-desktop">
            <div class="p-6 shadow rounded content">
              <h2 class="section-title">Seja bem-vindo à AfiliPay!</h2>
              <p>
                Estamos felizes por ter você aqui e estamos ansiosos para
                ajudá-lo a ter sucesso como afiliado.
              </p>
              <form method="POST" action="#" style="margin-top: 50px">
                <div class="columns is-multiline">
                  <div class="form-group column is-6-desktop">
                    <label for="fname">Nome</label>
                    <input
                      type="text"
                      class="input"
                      id="fname"
                      name="fname"
                      placeholder="Your First Name"
                      required=""
                    />
                  </div>
                  <div class="form-group column is-6-desktop">
                    <label for="lname">Sobrenome</label>
                    <input
                      type="text"
                      class="input"
                      id="lname"
                      name="lname"
                      placeholder="Your Last Name"
                    />
                  </div>
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
                  <div class="form-group column is-12">
                    <label for="password">Confirme a Senha</label>
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
                      Criar conta
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
