<script setup>
// example component
import HorizontalTeamCard from "@/examples/cards/teamCards/HorizontalTeamCard.vue";

// images
import jose from "@/assets/img/team/jose.jpeg";
import louis from "@/assets/img/team/louis.jpeg";
</script>

<template>
  <section class="pb-5 position-relative bg-gradient-dark mx-n3">
    <div class="container">
      <div class="row">
        <div class="col-md-8 text-start mb-5 mt-5">
          <h3 class="text-white z-index-1 position-relative">
            The Team
          </h3>
          <!-- <p class="text-white opacity-8 mb-0">
            There’s nothing I really wanted to do in life that I wasn’t able to
            get good at. That’s my skill.
          </p> -->
        </div>
      </div>
      <div class="row">
        <div class="col-lg-6 col-12">
          <HorizontalTeamCard
            class="mt-4"
            :image="jose"
            :profile="{ name: 'Jose Christian Abraham', link: 'https://www.linkedin.com/in/jose-christian-abraham-80a83421a/' }"
            :position="{ label: 'CEO', color: 'success' }"
            description="Artist is a term applied to a person who engages in an activity deemed to be an art."
          />
        </div>
        <div class="col-lg-6 col-12">
          <HorizontalTeamCard
            class="mt-lg-4 mt-5"
            :image="louis"
            :profile="{ name: 'Louis Caesa Kesuma', link: 'https://www.linkedin.com/in/louiscaesakesuma/' }"
            :position="{ label: 'Developer', color: 'success' }"
            description="Artist is a term applied to a person who engages in an activity deemed to be an art."
          />
        </div>
      </div>
    </div>
  </section>
</template>
