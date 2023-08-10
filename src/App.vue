<script setup>
import TeamMember from "./components/TeamMember.vue";

const fullName = "Jane Doe"
const person1 = {
  name:"Jane Doe X",
  designation:"CEO & Web Developer",
  avatar:"//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/bonnie-green.png",
  about:"Some inetersting information about Jane Doe",
  age:23
}
</script>

<template>
  <section class="mx-auto container">
    <section class="bg-white dark:bg-gray-900">
      <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 lg:px-6 ">
        <div class="mx-auto max-w-screen-sm text-center mb-8 lg:mb-16">
          <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Our Team</h2>
          <p class="font-light text-gray-500 lg:mb-16 sm:text-xl dark:text-gray-400">Explore the whole collection of open-source web components and elements built with the utility classes from Tailwind</p>
        </div>
        <div class="grid gap-8 mb-6 lg:mb-16 md:grid-cols-2">

          
          <!-- <TeamMember :name="person1.name" :designation="person1.designation" :avatar="person1.avatar" :about="person1.about" /> -->
          <TeamMember v-bind="person1" />
          <TeamMember name="John Doe" designation="Backend Developer" avatar="//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/joseph-mcfall.png" about="Some inetersting information about John Doe" />
          <TeamMember name="Jimmy Doe" designation="Devops Engineed" avatar="//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/michael-gouch.png" about="Some inetersting information about Jimmy Doe" />
          <TeamMember name="jana Byrd" designation="CMO" avatar="//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/sofia-mcguire.png" about="Some inetersting information about Lana Byrd" />
          
        </div>
      </div>
    </section>
  </section>
</template>

<style scoped></style>
