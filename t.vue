<template>
  <!-- ✓ GOOD -->
  <div>{{ text }}</div>
  <div>{{   text   }}</div><!-- Use vue/no-multi-spaces rule to disallow multiple spaces. -->

  <!-- ✗ BAD -->
  <div>{{text}}</div>
</template>
