<template>
  <q-layout view="lHh Lpr lFf">
    <div class="row q-my-xl justify-center">
      <div class="col-7 bg-grey-1 q-py-xl" style="border-radius:7px;">
        <div class="row justify-around items-center">
          <div class="col-4 bg-grey-11" style="width:150px;height:150px;border-radius:50%"></div>
          <div class="col-4">
            <p align="center" class="text-h5 q-py-xl">Member Login</p>
            <q-form
              @submit="onSubmit"
              @reset="onReset"
              class="q-gutter-md"
            >
              <q-input
                rounded standout
                label="Email"
              >
                <template v-slot:prepend>
                  <q-icon name="email" />
                </template>
              </q-input>

              <q-input
                rounded standout
                type="password"
                label="Password"
              >
                <template v-slot:prepend>
                  <q-icon name="lock" />
                </template>
              </q-input>
              <div>
                <q-btn unelevated rounded color="teal" class="full-width q-mt-lg" label="Войти"/>
              </div>
              <div>
                <q-btn unelevated rounded outline class="full-width">
                  <q-avatar size="20px" class="q-mx-xs">
                    <img src="../assets/yandex_logo.png">
                  </q-avatar>
                  Войти с Яндекс ID
                </q-btn>
              </div>
              <div>
                <q-btn unelevated rounded outline class="full-width">
                  <q-avatar size="20px" class="q-mx-xs">
                    <img src="../assets/vk_logo.png">
                  </q-avatar>
                  Войти с Вконтакте
                </q-btn>
              </div>
              <p align="center"><a href="" style="text-decoration:none;color:white;">Forgot Username/Password?</a></p>
            </q-form>
            <q-item to="/registration" clickable v-ripple>
              Create your Account
            </q-item>
          </div>
        </div>
      </div>
    </div>
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
