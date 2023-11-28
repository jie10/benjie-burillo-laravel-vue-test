<script setup>

</script>

<template>
  <div class="flex min-h-full flex-1 flex-col justify-center py-12 sm:px-6 lg:px-8">
    <div class="sm:mx-auto sm:w-full sm:max-w-md">
      <img alt="Your Company" class="mx-auto h-10 w-auto"
           src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600"/>
      <h2 class="mt-6 text-center text-2xl font-bold leading-9 tracking-tight text-gray-900">Sign in to your
        account</h2>
    </div>

    <div class="mt-10 sm:mx-auto sm:w-full sm:max-w-[480px]">
      <div class="bg-white px-6 py-12 shadow sm:rounded-lg sm:px-12">
        <form action="#" class="space-y-6" method="POST">
          <!--          Username-->
          <div>
            <label class="block text-sm font-medium leading-6 text-gray-900" for="email">Username</label>
            <div class="mt-2">
              <input id="username" autocomplete="username"
                     class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                     name="username" required=""
                     type="text"/>
            </div>
          </div>

          <!--          Email-->
          <div>
            <label class="block text-sm font-medium leading-6 text-gray-900" for="email">Email Address</label>
            <div class="mt-2">
              <input id="email" autocomplete="email"
                     class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                     name="email" required=""
                     type="email"/>
            </div>
          </div>

          <!--          Phone Number-->
          <div>
            <label class="block text-sm font-medium leading-6 text-gray-900" for="email">Phone Number</label>
            <div class="mt-2">
              <input id="phoneNumber" autocomplete="phoneNumber"
                     class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                     name="phoneNumber" required=""
                     type="number"/>
            </div>
          </div>

          <!--          Password-->
          <div>
            <label class="block text-sm font-medium leading-6 text-gray-900" for="password">Password</label>
            <div class="mt-2">
              <input id="password" autocomplete="current-password"
                     class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                     name="password" required=""
                     type="password"/>
            </div>
          </div>

          <!--         Confirm Password-->
          <div>
            <label class="block text-sm font-medium leading-6 text-gray-900" for="password">Confirm Password</label>
            <div class="mt-2">
              <input id="password" autocomplete="current-password"
                     class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                     name="password" required=""
                     type="password"/>
            </div>
          </div>

          <div>
            <button
                class="flex w-full justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
                type="submit">
              Signup
            </button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>