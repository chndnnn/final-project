<template>
    <div class="q-pa-md row justify-center">
      <div style="width: 100%; max-width: 400px">
        <q-chat-message
          :text="['hey, how are you? Chandan this side']"
          sent
        />
        <q-chat-message
          :text="['doing fine, how r you?']"
        />
      </div>
    </div>
  </template>