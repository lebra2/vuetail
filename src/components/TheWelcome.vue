<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <div class="flex flex-col h-screen justify-center text-xl bg-[#181818] text-white">

    <WelcomeItem class="w-2/3">
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>
      <p class="text-2xl font-bold">git init</p>
    </template>

    <p class=""><code class="text-pink-400">git init</code> is one way to start a new project with Git. To start a repository, use either <code class="text-pink-400">git init</code> or <code class="text-pink-400">git clone</code> - not both.</p>
  </WelcomeItem>

  <WelcomeItem class="w-2/3">
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>
      <p class="text-2xl font-bold">git add</p>
    </template>

    The git add command adds new or changed files in your working directory to the Git staging area.
  </WelcomeItem>

  <WelcomeItem class="w-2/3">
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>
      <p class="text-2xl font-bold">git status</p>
    </template>

    git status shows the current state of your Git working directory and staging area.
  </WelcomeItem>

  <WelcomeItem class="w-2/3">
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>
      <p class="text-2xl font-bold">git commit</p>
    </template>
    
    <code class="text-pink-400">git commit</code> creates a commit, which is like a snapshot of your repository. These commits are snapshots of your entire repository at specific times.
  </WelcomeItem>

  <WelcomeItem class="w-2/3">
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>
      <p class="text-2xl font-bold">git push</p>
    </template>
    <div class="">
      <code class="text-pink-400">git push</code> updates the remote branch with local commits. It is one of the four commands in Git that prompts interaction with the remote repository. You can also think of <code class="text-pink-400">git push</code> as update or publish.
    </div>

    
  </WelcomeItem>
  </div>

</template>
