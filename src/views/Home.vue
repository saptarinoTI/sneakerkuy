<template>
  <div class="home">
    <HeaderSneakerKuy />
    <HeroSneakerKuy />
    <BannerSneakerKuy />
    <InstaSneakerKuy />
    <PartSneakerKuy />
    <FooterSneakerKuy />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSneakerKuy from "@/components/HeaderSneakerKuy.vue";
import HeroSneakerKuy from "@/components/HeroSneakerKuy.vue";
import BannerSneakerKuy from "@/components/BannerSneakerKuy.vue";
import InstaSneakerKuy from "@/components/InstaSneakerKuy.vue";
import PartSneakerKuy from "@/components/PartSneakerKuy.vue";
import FooterSneakerKuy from "@/components/FooterSneakerKuy.vue";

export default {
  name: "Home",
  components: {
    HeaderSneakerKuy,
    HeroSneakerKuy,
    BannerSneakerKuy,
    InstaSneakerKuy,
    PartSneakerKuy,
    FooterSneakerKuy
  }
};
</script>
