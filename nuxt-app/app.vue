<template>
  <div>
    <!-- Ello -->
    <div class="p-4">
      <FormKit
        type="text"
        label="Email address"
        help="Enter a full email address"
        validation="required|email"
        validation-visibility="live"
      />
      <FormKit type="text" />
      <FormKit type="select" />
      <FormKit type="textarea" />
      <button class="btn">Hello daisyUI</button>
    </div>
    <NuxtWelcome />
  </div>
</template>
