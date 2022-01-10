<template>
  <div>
    <h1>Github App</h1>
    <GitHubTokenForm />
    <UserInfo />
    <ReposInfo />
  </div>
</template>

<script>
import GitHubTokenForm from "./components/GitHubTokenForm.vue";
import UserInfo from "./components/UserInfo.vue";
import ReposInfo from "./components/ReposInfo.vue";

export default {
  name: 'App',
  components: { GitHubTokenForm, UserInfo, ReposInfo }
};
</script>
