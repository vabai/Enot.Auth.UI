<template>
  <q-page class="row justify-center items-center">

      <div class="col-12 col-md-8 col-lg-6">
        <q-card class="q-pa-lg " style="height: 608px">
          <div class="row full-height items-center q-gutter-sm">
            <div class="col-5"></div>
            <div class="col-6">
              <div class="row q-gutter-sm justify-center">

                <div class="col-12 text-center q-mb-md">
                  <span class="text-h3">Авторизация</span>
                </div>

                <div class="col-5">
                  <q-btn
                    padding="sm"
                    no-caps
                    unelevated
                    rounded
                    icon=""
                    color="grey-10">
                      <q-avatar class="q-mr-sm" size="15px">
                        <q-img src="~assets/yandex_logo.png"/>
                      </q-avatar>
                    Войти с Яндекс ID
                  </q-btn>
                </div>
                <div class="col-5">
                  <q-btn
                    padding="sm"
                    no-caps
                    unelevated
                    rounded
                    icon="ion-logo-vk"
                    style="background: #5C82A7"
                    class="text-white"
                    label="Войти с Вконтакте"
                    href="https://oauth.vk.com/authorize?client_id=8108646&display=page&redirect_uri=http://localhost:3000/user/oauth/verify&scope=offline,profile,email&response_type=code&v=5.131" />
                </div>
                <div class="col-12 q-mt-xl">
                  <q-input rounded outlined label="Логин">
                    <template v-slot:prepend>
                      <q-icon name="mdi-pencil" />
                    </template>
                  </q-input>
                </div>
                <div class="col-12 q-my-sm">
                  <q-input rounded outlined type="password" label="Пароль">
                    <template v-slot:prepend>
                      <q-icon name="mdi-lock" />
                    </template>
                    <template v-slot:append>
                      <q-icon name="mdi-eye-outline" />
                    </template>
                  </q-input>
                </div>
                <div class="col-12 q-mt-xl">
                  <q-btn class="full-width" unelevated rounded color="grey-10" label="Войти" />
                </div>
                <q-item to="/registration">
                  Не зарегистрированы?&nbsp;<span style="text-decoration:underline;">Регистрация</span>
                </q-item>
              </div>
            </div>
          </div>
        </q-card>
      </div>

      <q-img class="absolute-bottom-right" style="opacity:.7" width="213px" height="225px" src="~assets/ddos-guard_logo.jpg" />

  </q-page>
</template>

<script>
export default ({
  name: 'PageIndex'
})
</script>
