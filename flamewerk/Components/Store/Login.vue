<template>
          <div class="mx-auto w-full max-w-md dark:text-white ">
        <div>
          <h2 class="mt-6 text-3xl font-bold tracking-tight text-gray-900 dark:text-white">Sign in to your account</h2>

        </div>

        <div class="mt-8">

          <div class="mt-6">
            <form action="#" method="POST" class="space-y-6">
              <div>
                <label for="email" class="block text-sm font-medium text-gray-700">Publickey:</label>
                <div class="mt-1">
                  <input id="email" name="email" type="email" autocomplete="email" required="" class="block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 placeholder-gray-400 shadow-sm focus:border-HighlightPrimary focus:outline-none focus:ring-HighlightPrimary sm:text-sm" />
                </div>
              </div>

              <div class="space-y-1">
                <label for="password" class="block text-sm font-medium text-gray-700">Privatekey</label>
                <div class="mt-1">
                  <input id="password" name="password" type="password" autocomplete="current-password" required="" class="block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 placeholder-gray-400 shadow-sm focus:border-HighlightPrimary focus:outline-none focus:ring-HighlightPrimary sm:text-sm" />
                </div>
              </div>



              <div>
                <NuxtLink :to="localePath('/inventory')" class="text-black flex w-full justify-center rounded-md border border-transparent bg-indigo-600 py-2 px-4 text-sm font-medium shadow-sm hover:bg-HighlightSecondary focus:outline-none focus:ring-2 focus:ring-HighlightPrimary focus:ring-offset-2">Sign in</NuxtLink>
              </div>
            </form>
          </div>
        </div>
      </div>
</template>