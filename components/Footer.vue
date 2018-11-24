<template>
  <footer class="bg-indigo p-8 md:py-16">
    <section class="md:flex mx-auto w-full max-w-xl">
      <div class="md:w-1/2 md:flex flex-col items-center pb-8 md:pb-0">
        <div>
          <h1 class="text-white text-semibold font-serif">by 3xW</h1>
          <ul class="list-reset">
            <li class="my-4">
              <a
                href="https://3xw.ie"
                class="no-underline text-indigo-lightest"
              >
                About us
              </a>
            </li>
            <li class="my-4">
              <a
                href="https://3xw.ie"
                class="no-underline text-indigo-lightest"
              >
                Want a website like this?
              </a>
            </li>
            <!-- <li class="hidden md:block my-4">
              <a href="" class="invisible">Hi</a>
            </li> -->
            <li class="my-4">
              <p class="no-underline text-indigo-lightest">
                &copy; 3xW Digital Ltd, 2018
              </p>
            </li>
          </ul>
        </div>
      </div>
      <div class="md:w-1/2 md:flex flex-col items-center pb-8 md:pb-0">
        <div>
          <p class="text-white uppercase tracking-wide leading-looser mb-6">Navigation</p>
          <ul class="list-reset">
            <li class="my-4">
              <nuxt-link
                to="/"
                class="no-underline text-indigo-lightest"
              >
                Home
              </nuxt-link>
            </li>
            <li class="my-4">
              <nuxt-link
                to="/payments"
                class="no-underline text-indigo-lightest"
              >
                Payments
              </nuxt-link>
            </li>
            <!-- <li class="my-4">
              <a
                href="https://app.befreer.ie"
                class="no-underline text-indigo-lightest"
              >
                Dashboard &rarr;
              </a>
            </li> -->
          </ul>
        </div>
      </div>
    </section>
  </footer>
</template>
