<script setup>

</script>

<template>
  <div class="flex min-h-full flex-1">
    <div class="flex flex-1 flex-col justify-center px-4 py-12 sm:px-6 lg:flex-none lg:px-20 xl:px-24">
      <div class="mx-auto w-full max-w-sm lg:w-96">
        <div>
          <img alt="Your Company" class="h-10 w-auto"
               src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600"/>
          <h2 class="mt-8 text-2xl font-bold leading-9 tracking-tight text-gray-900">Sign in to your account</h2>
          <p class="mt-2 text-sm leading-6 text-gray-500">
            Not a member?
            {{ ' ' }}
            <RouterLink class="font-semibold text-indigo-600 hover:text-indigo-500" to="/register">Register here
            </RouterLink>
          </p>
        </div>

        <div class="mt-10">
          <div>
            <form action="#" class="space-y-6" method="POST">
              <div>
                <label class="block text-sm font-medium leading-6 text-gray-900" for="email">Username/Email</label>
                <div class="mt-2">
                  <input id="account" autocomplete="account"
                         class="block w-full rounded-md border-0 py-1.5 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                         name="account" required=""
                         type="text"/>
                </div>
              </div>

              <div>
                <label class="block text-sm font-medium leading-6 text-gray-900" for="password">Password</label>
                <div class="mt-2">
                  <input id="password" autocomplete="current-password"
                         class="block w-full rounded-md border-0 py-1.5 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                         name="password" required=""
                         type="password"/>
                </div>
              </div>

              <div>
                <button
                    class="flex w-full justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
                    type="submit">
                  Sign in
                </button>
              </div>
            </form>
          </div>

        </div>
      </div>
    </div>
    <div class="relative hidden w-0 flex-1 lg:block">
      <img alt="background"
           class="absolute inset-0 h-screen w-full object-cover"
           src="https://images.unsplash.com/photo-1496917756835-20cb06e75b4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1908&q=80"/>
    </div>
  </div>
</template>

<style scoped>

</style>