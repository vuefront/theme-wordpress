<template>
  <section class="vf-o-header">
    <vf-m-container>
      <!-- <vf-m-row class="mb-3 py-2">
        <vf-m-col align-self="center" class="text-sm-left">
          <vf-o-currency />
          <vf-o-language />
        </vf-m-col>
        <vf-m-col align-self="center" class="text-sm-right">
          <vf-m-compare-link class="ml-auto" />
          <vf-m-wishlist-link />
          <vf-m-account-menu />
        </vf-m-col>
      </vf-m-row>-->
      <vf-m-row class="mb-3">
        <vf-m-col md class="text-md-left" align-self="center">
          <vf-m-logo />
        </vf-m-col>
        <vf-m-col md="auto" align-self="center">
          <vf-m-account-menu />
        </vf-m-col>
        <vf-m-col md="3" class="text-md-right" align-self="center">
          <vf-o-search-inline-form class="mx-auto" />
        </vf-m-col>
      </vf-m-row>
      <vf-m-row class="mb-3">
        <vf-m-col md="10">
          <vf-o-position name="headerMenu" />
        </vf-m-col>
        <vf-m-col class="text-md-right mt-2">
          <vf-m-cart-link />
        </vf-m-col>
      </vf-m-row>
    </vf-m-container>
  </section>
</template>
<script>
import { oHeader } from "vuefront/lib/components/organisms/header";
export default {
  mixins: [oHeader]
};
</script>
