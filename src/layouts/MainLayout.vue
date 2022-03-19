<template>
  <q-layout view="lHh Lpr lFf">
    <q-page class="justify-center items-center">
      <div class="row">
        <div class="col-6 bg-grey-11 q-pa-sm">
          <div class="row">
            <div class="col-6 q-my-xl"></div>
            <div class="col-6 q-my-xl">
              <div class="row justify-center">
                <span class="text-h5">Авторизация</span>
              </div>
              <div class="row q-pa-lg">
                <div class="col-6">
                  <q-btn unelevated rounded class="full-width" icon="" color="black" label="Войти с Яндекс ID"/>
                </div>
                <div class="col-6">
                  <q-btn unelevated rounded class="full-width" icon="ion-logo-vk" color="primary" label="Войти с Вконтакте"/>
                </div>
              </div>
              <div class="row q-my-xl">
                <div class="col-12">
                  <q-input rounded standout label="Логин">
                    <template v-slot:prepend>
                      <q-icon name="mdi-pencil" />
                    </template>
                  </q-input>
                </div>
                <div class="col-12 q-my-sm">
                  <q-input rounded standout type="password" label="Пароль">
                    <template v-slot:prepend>
                      <q-icon name="mdi-lock" />
                    </template>
                    <template v-slot:append>
                      <q-icon name="mdi-eye-outline" />
                    </template>
                  </q-input>
                </div>
                <div class="col-12">
                  <q-btn unelevated rounded class="full-width" color="grey-7" label="Войти"/>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row q-mt-xl justify-end">
        <q-img width="213px" height="225px" src="../assets/ddos-guard_logo.jpg"/>
      </div>
    </q-page>
  </q-layout>
</template>

<script>
/*import { useQuasar } from 'Quasar'
export default {
  setup() {
    const $q = useQuasar()
    $q.dark.set(true)
  }
}*/
</script>

<style>

body{
  background:linear-gradient(249.89deg, #48D5DB -0.91%, #72BDF2 48.1%, #404FD7 101.38%);
  font-family: 'Raleway';
}

</style>
