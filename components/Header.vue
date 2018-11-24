<template>
  <header class="flex w-full p-4 bg-indigo flex">
    <div class="container mx-auto flex justify-between items-center">
      <nuxt-link
        to="/"
        class="inline-flex"
      >
        <img
          src="/befreer-logo-light.svg"
          alt="Be Freer logo"
          class="h-8 w-auto"
        >
      </nuxt-link>
      <section>
        <!-- <nuxt-link
          to="/platform"
          class="no-underline text-white font-medium tracking-wide mr-8"
        >
          Automation
        </nuxt-link> -->
        <nuxt-link
          to="/payments"
          class="no-underline text-white font-medium tracking-wide mr-4"
        >
          Payments
        </nuxt-link>
        <!-- <nuxt-link
          to="/events"
          class="no-underline text-white font-medium tracking-wide mr-8"
        >
          Events
        </nuxt-link>
        <nuxt-link
          to="/contacts"
          class="no-underline text-white font-medium tracking-wide mr-8"
        >
          Contacts
        </nuxt-link>
        <a
          href=""
          class="no-underline text-white font-medium tracking-wide"
        >
          Dashboard &rarr;
        </a> -->
      </section>
    </div>
  </header>
</template>
