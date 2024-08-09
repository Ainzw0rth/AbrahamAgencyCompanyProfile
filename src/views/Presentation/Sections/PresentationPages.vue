<script setup>
import ExampleCard from "../Components/ExampleCard.vue";
import MaterialBadge from "../../../components/MaterialBadge.vue";

// images
import imgSigninCover from "@/assets/img/signin-cover.png";
</script>
<template>
  <section class="py-5">
    <div class="container">
      <div class="row">
        <div class="row text-center my-sm-5 mt-5">
          <div class="col-lg-6 mx-auto">
            <!-- <MaterialBadge color="success" class="mb-3"
              >Boost creativity</MaterialBadge
            > -->
            <h2 class="">Our projects</h2>
            <!-- <p class="lead">
              The easiest way to get started is to use one of our <br />
              pre-built example pages.
            </p> -->
          </div>
        </div>
      </div>
    </div>
    <div class="container mt-5">
      <div class="row">
        <div class="col-md-8">
          <div class="row mt-4">
            <div class="col-md-6 mt-md-0 mt-5">
              <ExampleCard
                class="shadow-lg"
                title="AI chatbot for assessing managers"
                image="https://cdn.discordapp.com/attachments/813637236037910548/1270612625759273082/webbot.png?ex=66b455b8&is=66b30438&hm=c01673a9449278947f66be22a06e7f73f1691744ff269619808e69b4f5d60d05&"
              />
            </div>
            <div class="col-md-6 mt-md-0 mt-5">
              <ExampleCard
                class="shadow-lg"
                title="Whatsapp bot for customer service"
                image="https://cdn.discordapp.com/attachments/813637236037910548/1270612626002673787/whatsapp.png?ex=66b455b8&is=66b30438&hm=251c70eacbbc713b6769d39e13334f0c9c8c6bb32593efd0f6bbf936b20ff517&"
              />
            </div>
          </div>
        </div>
        <div class="col-md-3 mx-auto mt-md-0 mt-3">
          <div class="position-sticky" style="top: 100px !important">
            <h3>
              AI integration on websites and whatsapp chatbots
            </h3>
            <h6 class="text-secondary font-weight-normal">
              These are a few snippets of our projects.
            </h6>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
