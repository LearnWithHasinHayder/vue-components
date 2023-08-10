<script setup>
</script>

<template>
  <section class="mx-auto ">
    <h1 class="my-10 text-center">Components</h1>
    <div class="flex items-center justify-center h-[600px] font-medium">
      <div class="flex flex-grow items-center justify-center h-full text-gray-600 bg-gray-100">
        <!-- Component Start -->
        <div class="max-w-full p-8 bg-white rounded-lg shadow-lg w-96">
          <div class="flex items-center mb-6">
            <svg class="h-8 w-8 text-indigo-500 stroke-current" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 13V6a2 2 0 00-2-2H6a2 2 0 00-2 2v7m16 0v5a2 2 0 01-2 2H6a2 2 0 01-2-2v-5m16 0h-2.586a1 1 0 00-.707.293l-2.414 2.414a1 1 0 01-.707.293h-3.172a1 1 0 01-.707-.293l-2.414-2.414A1 1 0 006.586 13H4"></path>
            </svg>
            <h4 class="font-semibold ml-3 text-lg">Frodo's Jobs</h4>
          </div>
          <div>
            <input class="hidden" type="checkbox" id="task_1" checked="">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-100" for="task_1">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-300 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Weed front garden.</span>
            </label>
          </div>
          <div>
            <input disabled class="hidden" type="checkbox" id="task_2" checked="">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-100" for="task_2">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-300 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Chill and smoke some Old Toby.</span>
            </label>
          </div>
          <div>
            <input class="hidden" type="checkbox" id="task_3">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-100" for="task_3">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-300 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Keep ring secret and safe.</span>
            </label>
          </div>
          <div>
            <input class="hidden" type="checkbox" id="task_4">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-100" for="task_4">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-300 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Meet Gandalf at Bree.</span>
            </label>
          </div>
          <div>
            <input class="hidden" type="checkbox" id="task_5">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-100" for="task_5">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-300 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Destroy ring and defeat dark lord.</span>
            </label>
          </div>
          
        </div>
        <!-- Component End  -->
      </div>
      <div class="flex flex-grow items-center justify-center bg-gray-900 h-full">
        <!-- Component Start -->
        <div class="max-w-full p-8 bg-gray-800 rounded-lg shadow-lg w-96 text-gray-200">
          <div class="flex items-center mb-6">
            <svg class="h-8 w-8 text-indigo-500 stroke-current" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 13V6a2 2 0 00-2-2H6a2 2 0 00-2 2v7m16 0v5a2 2 0 01-2 2H6a2 2 0 01-2-2v-5m16 0h-2.586a1 1 0 00-.707.293l-2.414 2.414a1 1 0 01-.707.293h-3.172a1 1 0 01-.707-.293l-2.414-2.414A1 1 0 006.586 13H4"></path>
            </svg>
            <h4 class="font-semibold ml-3 text-lg">Sam's Jobs</h4>
          </div>
          <div>
            <input class="hidden" type="checkbox" id="task_6" checked="">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-900" for="task_6">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-500 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Trim the verge.</span>
            </label>
          </div>
          <div>
            <input class="hidden" type="checkbox" id="task_7" checked="">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-900" for="task_7">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-500 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Eavesdrop on Master Frodo &amp; Gandalf.</span>
            </label>
          </div>
          <div>
            <input class="hidden" type="checkbox" id="task_8">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-900" for="task_8">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-500 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Boil, mash, and stick potatoes in stew.</span>
            </label>
          </div>
          <div>
            <input class="hidden" type="checkbox" id="task_9">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-900" for="task_9">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-500 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Carry Frodo.</span>
            </label>
          </div>
          <div>
            <input class="hidden" type="checkbox" id="task_10">
            <label class="flex items-center h-10 px-2 rounded cursor-pointer hover:bg-gray-900" for="task_10">
              <span class="flex items-center justify-center w-5 h-5 text-transparent border-2 border-gray-500 rounded-full">
                <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                </svg>
              </span>
              <span class="ml-4 text-sm">Be all round legend.</span>
            </label>
          </div>
          
        </div>
        <!-- Component End  -->

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
