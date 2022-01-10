<template>
  <div>
    <h1>Github App</h1>
    <GitHubTokenForm />
    <User />
    <Repos />
  </div>
</template>

<script>
import GitHubTokenForm from "./components/GitHubTokenForm.vue";
import User from "./components/User.vue";
import Repos from "./components/Repos.vue";

export default {
  name: 'App',
  components: { GitHubTokenForm, User, Repos }
};
</script>
