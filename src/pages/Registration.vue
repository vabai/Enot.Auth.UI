<template>
  <q-page class="row justify-center items-center">

      <div class="col-12 col-md-8 col-lg-6">
        <q-card class="q-pa-lg " style="height: 620px">
          <div class="row full-height items-center q-gutter-sm">
            <div class="col-5"></div>
            <div class="col-6">
              <div class="row q-gutter-sm justify-center">

                <div class="col-12 text-center q-mb-md">
                  <span class="text-h3">Регистрация</span>
                </div>
                <div class="col-12 q-mt-xl">
                  <q-input rounded outlined label="Email*">
                    <template v-slot:prepend>
                      <q-icon name="mdi-email" />
                    </template>
                  </q-input>
                </div>
                <div class="col-12 q-my-sm">
                  <q-input rounded outlined type="password" label="Имя пользователя*">
                    <template v-slot:prepend>
                      <q-avatar>
                        <img src="~assets/name.svg">
                      </q-avatar>
                    </template>
                  </q-input>
                </div>
                <div class="col-12 q-my-sm">
                  <q-input rounded outlined label="Логин*">
                    <template v-slot:prepend>
                      <q-icon name="mdi-pencil" />
                    </template>
                  </q-input>
                </div>
                <div class="col-12 q-my-sm">
                  <q-input rounded outlined type="password" label="Пароль*">
                    <template v-slot:prepend>
                      <q-icon name="mdi-lock" />
                    </template>
                  </q-input>
                </div>
                <div class="col-12 q-my-sm">
                  <q-input rounded outlined label="ФИО">
                    <template v-slot:prepend>
                      <q-icon name="mdi-account" />
                    </template>
                  </q-input>
                </div>
                <div class="col-12 q-mt-lg">
                  <q-btn class="full-width" unelevated rounded color="grey-10" label="Регистрация" />
                </div>
              </div>

            </div>
          </div>
        </q-card>
      </div>

      <q-img class="absolute-bottom-right" style="opacity:.7" width="213px" height="225px" src="~assets/ddos-guard_logo.jpg" />

  </q-page>
</template>

<style>

body{
  background: linear-gradient(249.89deg, #48D5DB -0.91%, #72BDF2 48.1%, #404FD7 101.38%);
}

</style>
