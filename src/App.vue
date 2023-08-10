<script setup>
import {ref} from 'vue'
import ApplicantDetails from './components/ApplicantDetails.vue';
const activeIndex = ref(0)
const people = [
  {
    name:'Margot Foster',
    position:'Backend Developer',
    email:'margotfoster@example.com',
    salary:'$120,000',
    about:'Fugiat ipsum ipsum deserunt culpa aute sint do nostrud anim incididunt cillum culpa consequat. Excepteur qui ipsum aliquip consequat sint. Sit id mollit nulla mollit nostrud in ea officia proident. Irure nostrud pariatur mollit ad adipisicing reprehenderit deserunt qui eu.',
    attachments:[
      {
        name:'resume_back_end_developer.pdf',
        size:'256kb',
        type:'PDF',
        url:'#'
      },
      {
        name:'coverletter_back_end_developer.pdf',
        size:'128kb',
        type:'PDF',
        url:'#'
      }
    ]
  },
  {
    name:'John Doe',
    position:'Frontend Developer',
    email:'john@doe.com',
    salary:'$100,000',
    about:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.',
    attachments:[
      {
        name:'resume_front_end_developer.pdf',
        size:'1MB',
        type:'PDF',
        url:'#'
      },
      {
        name:'coverletter_front_end_developer.pdf',
        size:'512kb',
        type:'PDF',
        url:'#'
      }
    ]
  },
  {
    name:'Jane Doe',
    position:'Designer',
    email:'jane@doe.com',
    salary:'$110,000',
    about:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum. Here is some more text.',
    attachments:[
      {
        name:'resume_designer.pdf',
        size:'5MB',
        type:'PDF',
        url:'#'
      },
      {
        name:'coverletter_designer.pdf',
        size:'2MB',
        type:'PDF',
        url:'#'
      }
    ]
  }
]
</script>

<template>
  <section class="mx-auto ">
    <h1 class="my-10 text-center">Components</h1>
    <div class="flex justify-between space-x-5">
      <div class="w-1/3">
        <div @click="activeIndex=index" class="my-2 p-5 hover:bg-gray-200 cursor-pointer" v-for="(person, index) in people" :key="index">
          {{person.name}}
        </div>

      </div>
      <div class="w-2/3">
        <ApplicantDetails :person="people[activeIndex]" />
      </div>
    </div>
  </section>
</template>

<style scoped>
input[type=checkbox]:checked+label span:first-of-type {
  background-color: #10B981;
  border-color: #10B981;
  color: #fff;
}

input[type=checkbox]:checked+label span:nth-of-type(2) {
  text-decoration: line-through;
  color: #9CA3AF;
}
</style>
