<template>
  <div class="flex pb-6">
    <div class="flex items-center px-6">
      <slot class="" name="icon"></slot>
    </div>
    <div class="details">
      <h3 class="text-xl font-semibold">
        <slot name="heading"></slot>
      </h3>
      <slot></slot>
    </div>
  </div>
</template>

