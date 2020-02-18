<template>
  <div>
    <PageHeader title="Kahoot Bot" subtitle="Most functions working in 2020" />
    <LoginForm />
    <InfoBox class="infoBox" />
  </div>
</template>

<script>
//import PageHeader from "@/components/PageHeader";
import LoginForm from "@/components/LoginForm";
//import InfoBox from "@/components/InfoBox";

export default {
  components: {
    PageHeader,
    LoginForm,
    InfoBox
  }
};
</script>

<style scoped>
.infoBox {
  margin-top: 5vh;
}
</style>
