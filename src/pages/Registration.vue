<template>
  <q-layout view="lHh Lpr lFf">
    <div class="row q-my-xl justify-center">
      <div class="col-3"></div>
      <div class="col-6 bg-grey-11 q-pa-sm">
        <div class="row">
          <div class="col-6 q-my-xl"></div>
          <div class="col-6 q-my-xl">
            <div class="row justify-center">
              <span class="text-h5">Регистрация</span>
            </div>
            <div class="row q-pa-lg">
              <div class="col-6">
                <q-btn unelevated rounded class="full-width" icon="" color="black" label="Войти с Яндекс ID"/>
              </div>
              <div class="col-6">
                <q-btn unelevated rounded class="full-width" icon="ion-logo-vk" color="primary" label="Войти с Вконтакте"/>
              </div>
            </div>
            <div class="row q-mt-sm">
              <div class="col-12">
                <q-input rounded standout label="Email*">
                  <template v-slot:prepend>
                    <q-icon name="mdi-email" />
                  </template>
                </q-input>
              </div>
              <div class="col-12 q-mt-sm">
                <q-input rounded standout label="Имя пользователя">
                  <template v-slot:prepend>
                    <q-img src="../assets/name.svg"/>
                  </template>
                </q-input>
              </div>
              <div class="col-12 q-mt-sm">
                <q-input rounded standout label="Логин">
                  <template v-slot:prepend>
                    <q-icon name="mdi-pencil" />
                  </template>
                </q-input>
              </div>
              <div class="col-12 q-mt-sm">
                <q-input rounded standout type="password" label="Пароль">
                  <template v-slot:prepend>
                    <q-icon name="mdi-lock" />
                  </template>
                  <template v-slot:append>
                    <q-icon name="mdi-eye-outline" />
                  </template>
                </q-input>
              </div>
              <div class="col-12 q-mt-sm">
                <q-btn unelevated rounded class="full-width" color="grey-7" label="Регистрация"/>
              </div>
              <div class="col-12 q-my-sm">
                <q-item clickable v-ripple to="/registration">
                  <q-item-section>Не зарегистрированы?<span>Регистрация</span></q-item-section>
                </q-item>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-3"></div>
      <!--
      <div class="col-7" id="rect1">
        <q-file class="file rect15" v-model="file" borderless><p></p></q-file>
        <div>
          <p id="reg">Регистрация</p>
          <q-btn id="rect11">
            <q-avatar size="16px" class="q-mx-xs">
              <img src="../assets/yandex_logo.png">
            </q-avatar>
            Войти с Яндекс ID
          </q-btn>
          <q-btn id="rect10">
            <q-avatar size="16px" class="q-mx-xs">
              <img src="../assets/vk_logo.png">
            </q-avatar>
            Войти с Вконтакте
          </q-btn>
          <q-input borderless class="rect8" label="Email*">
            <template v-slot:before>
              <q-avatar class="q-ma-sm" size="20px">
                <img src="../assets/login.svg">
              </q-avatar>
            </template>
          </q-input>
          <q-input borderless class="rect9" label="Имя пользователя*">
            <template v-slot:before>
              <q-avatar class="q-ma-sm" size="20px">
                <img src="../assets/login.svg">
              </q-avatar>
            </template>
          </q-input>
          <q-input borderless class="rect01" label="Логин*">
            <template v-slot:before>
              <q-avatar class="q-ma-sm" size="20px">
                <img src="../assets/login.svg">
              </q-avatar>
            </template>
          </q-input>
          <q-input borderless class="rect02" label="Пароль*">
            <template v-slot:before>
              <q-avatar class="q-ma-sm" size="20px">
                <img src="../assets/login.svg">
              </q-avatar>
            </template>
          </q-input>
          <q-input borderless class="rect03" label="ФИО">
            <template v-slot:before>
              <q-avatar class="q-ma-sm" size="20px">
                <img src="../assets/login.svg">
              </q-avatar>
            </template>
          </q-input>
          <q-btn id="rect09" label="Регистрация" />
        </div>
      </div>
      -->
    </div>
  </q-layout>
</template>

<style>

body{
  background: linear-gradient(249.89deg, #48D5DB -0.91%, #72BDF2 48.1%, #404FD7 101.38%);
}

</style>
