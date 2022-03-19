<template>
  <header>
    <q-toolbar class="bg-grey-10 text-white">
      <q-toolbar-title>
        powered by Enot.Auth
      </q-toolbar-title>
      Выход
      <q-btn flat round dense color="primary" icon="mdi-exit-to-app" class="q-mr-xs" />
    </q-toolbar>
  </header>
  <q-page class="row justify-center items-center">
      <div class="col-12 col-md-6 col-lg-4">
        <q-card class="q-pa-lg" style="height: 620px">
          <div class="row full-height q-gutter-sm">
            <div class="col-5 q-mr-lg">
            </div>
            <div class="col-6">
              <div class="row q-gutter-md justify-center">
                <div class="col-12 q-mt-md">
                  <span class="text-h5">Личный кабинет</span>
                </div>
                <div class="col-12">
                  <q-card class="bg-grey-4 q-gutter-sm q-pb-md">
                    <div class="row">
                      <div class="col-5 q-mt-sm">
                        <q-icon class="q-mx-xs" color="primary" name="mdi-email"/>Email
                      </div>
                      <div class="col-7 q-mt-sm">
                        <p align="right">lazydumplings@mail.ru
                        <q-btn flat round dense color="primary" icon="mdi-pencil-box-multiple-outline" size="10px"/></p>
                      </div>
                    </div>
                    <div class="row">
                      <div class="col-6">
                        <q-icon class="q-mx-xs" color="primary" name="mdi-format-letter-case"/>Имя пользователя
                      </div>
                      <div class="col-6">
                        <p align="right">Енот
                        <q-btn flat round dense color="primary" icon="mdi-pencil-box-multiple-outline" size="10px"/></p>
                      </div>
                    </div>
                    <div class="row">
                      <div class="col-5">
                        <q-icon class="q-mx-xs" color="primary" name="mdi-pencil"/>Логин
                      </div>
                      <div class="col-7">
                        <p align="right">Енотик
                        <q-btn flat round dense color="primary" icon="mdi-pencil-box-multiple-outline" size="10px"/></p>
                      </div>
                    </div>
                    <div class="row">
                      <div class="col-5">
                        <q-icon class="q-mx-xs" color="primary" name="mdi-lock"/>Пароль
                      </div>
                      <div class="col-7">
                        <p align="right">Обновлен 2 дня назад
                        <q-btn flat round dense color="primary" icon="mdi-pencil-box-multiple-outline" size="10px"/></p>
                      </div>
                    </div>
                    <div class="row">
                      <div class="col-4">
                        <q-icon class="q-mx-xs" color="primary" name="mdi-account"/>ФИО
                      </div>
                      <div class="col-8">
                        <p align="right">Альберт Енотович Енотов
                        <q-btn flat round dense color="primary" icon="mdi-pencil-box-multiple-outline" size="10px"/></p>
                      </div>
                    </div>
                    <div class="col-5">
                      <q-btn
                        padding="sm"
                        no-caps
                        unelevated
                        rounded
                        color="grey-10"
                        >
                          <q-avatar class="q-mr-sm" size="15px">
                            <q-img src="~assets/yandex_logo.png"/>
                          </q-avatar>
                          Войти с Яндекс ID
                        </q-btn>
                        <q-icon class="q-mx-xs" color="primary" name="mdi-tooltip-check"/>
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
                        label="Войти с Вконтакте" />
                      <q-icon class="q-mx-xs" color="primary" name="mdi-tooltip-check"/>
                    </div>
                  </q-card>
                  <q-card class="bg-grey-4 q-gutter-sm q-my-md">
                    <div class="row justify-between items-center">
                      <div class="col-5">Темная тема</div>
                      <div class="col-2">
                        <q-toggle/>
                      </div>
                    </div>
                  </q-card>
                </div>
              </div>
            </div>
          </div>
        </q-card>
      </div>

      <q-img class="absolute-bottom-right" style="opacity:.7" width="213px" height="225px" src="~assets/ddos-guard_logo.jpg" />

  </q-page>
</template>
