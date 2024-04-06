<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Education Background</template>

    I am currently carrying out my bachelor's degree at Riau Islamic University
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">(Universitas Islam Riau)</a>
    <br>
    And I also did a student exchange at Udayana University
    <a href="https://www.unud.ac.id/" target="_blank" rel="noopener">(Universitas Udayana)</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skill</template>

    I have quite a lot of skills,
    Master MS Office, Create web projects,
    and Skills in graphic design

    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    My study program is Informatics Engineering, 
    Here's my class Instagram. Hit me up at there!
    <a href="https://www.instagram.com/b1universe_?igsh=MTQ2ZmNscTI0ZmVsdA==" target="_blank" rel="noopener">@b1universe</a>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>

    So, here are the social media that I have, 
    if you have questions and want to visit my profile, you can check me out! xoxo <br />
    Instagram = @<a href="https://www.instagram.com/septiaheskaa?igsh=MTJzNGZhamQ5Zjh3OA%3D%3D&utm_source=qr" target="_blank" rel="noopener"
      >septiaheskaa</a
    > <br/>
    Tiktok = @<a href="https://www.tiktok.com/@heskuyy?_t=8lHHVzP0A6y&_r=1" target="_blank" rel="noopener"
      >Heskuyy</a
    >

  </WelcomeItem>
</template>







