<template>
  <q-layout view="lHh Lpr lFf">
    <div class="row q-my-xl justify-center">
      <div class="col-7 bg-grey-1 q-py-xl" style="border-radius:7px;">
        <div class="row justify-around items-center">
          <div class="col-4">
            <p align="center" class="text-h5 q-py-xl">Sing up</p>
            <q-form
              @submit="onSubmit"
              @reset="onReset"
              class="q-gutter-md"
            >
              <q-input
                rounded standout
                label="Имя пользователя*"
              />

              <q-input
                rounded standout
                type="password"
                label="Пароль*"
              />

              <q-input
                rounded standout
                label="Ф.И.О."
              />

              <q-input
                rounded standout
                label="Почта*"
              />

              <q-file
                rounded standout
                label="Выбрать фото профиля"
              >
                <template v-slot:prepend>
                  <q-icon name="image" />
                </template>
              </q-file>

              <div>
                <q-btn unelevated rounded color="teal" class="full-width q-mt-lg" label="Войти"/>
              </div>
            </q-form>
          </div>
        </div>
      </div>
    </div>
  </q-layout>
</template>
