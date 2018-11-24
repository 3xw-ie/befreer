<template>
  <section class="bg-white">
    <main
      class="font-base text-grey-darkest text-base sm:text-lg leading-normal"
      style="background-image: linear-gradient(-180deg, #FFFFFF 0%, #F4F6F9 100%);"
    >
      <section class="max-w-lg mx-auto py-8 lg:py-24 px-4 md:py-8 pb-16 md:pb-32">
        <h1 class="font-black text-2xl xs:text-3xl sm:text-4xl md:text-5xl text-grey-darkest leading-none mb-6">
          People don’t start a business so they can deal with admin.
        </h1>
        <h2 class="font-light text-xl md:text-2xl text-black leading-tight mb-2">
          People start businesses to share a passion or skill with the world.<br>
        </h2>
        <h2 class="font-light text-xl md:text-2xl text-black leading-tight mb-6">
          We help people be less busy. We help people <strong class="font-bold">Be Freer.</strong>
        </h2>
        <p class="mb-4">
          Do you own a business? Can you remember a time when you've had an <em>empty to-do list</em>? Receipts need to be photographed and sent to your accountant. Customers need to be contacted. Invoice reminders need to be sent <em>again</em>.
        </p>
        <p class="mb-4">
          Things pile up. You find <em>more and more</em> of your time spent on tasks that have to be done, and <em>less</em> on what you want to be doing. Is this why you got started in the first place?
        </p>
        <p class="mb-4">
          How many hours a week do you think you spend on admin? How many a month? <em>A year?</em> Imagine you could stop doing most of that today. <em>What could you spend your time on instead?</em>
        </p>
        <p class="mb-4">
          We think people should be free to spend more of their time <em>doing what they do best</em>, rather than on automatable admin. We help make this a reality.
        </p>
        <p class="mb-2"> 
          All it takes is a few straightforward steps:
        </p>
        <ol class="mb-4">
          <li>Get in touch</li>
          <li>We go through your most time-consuming tasks</li>
          <li>We streamline what can be avoided</li>
          <li>We automate as much as possible</li>
          <li>You decide how to spend all your new time</li>
        </ol>
        <p class="mb-4">
          This all starts with you reaching out. If we've piqued your interest and you'd like to chat, <em>get in touch</em>. We'll talk, and we'll propose how we can get rid of tasks you hate doing. Then, if it sounds worth it to you &mdash; we're off to the races. If not, there's <em>no charge and no obligation</em> whatsoever.
        </p>
        <p class="mb-6 sm:mb-8 font-bold">
          If you’re tired of admin, and interested in learning how we can reduce your admin workload &mdash; enter your email below and we’ll start making that happen.
        </p>
        <form
          name="Email Interest (/)"
          method="POST"
          netlify
          class="flex max-w-md w-full bg-white sm:shadow-lg rounded-lg"
        >
          <input
            type="hidden"
            name="page"
            value="/payments"
          >
          <label
            for="email"
            class="hidden"
          >
            Email
          </label>
          <input
            name="email"
            type="email"
            placeholder="sick-of-admin@email.com"
            class="flex-1 pt-4 pr-2 pl-4 pb-4 sm:pr-4 bg-transparent text-sm sm:text-base rounded-l-lg border sm:border-transparent focus:outline-none focus:shadow-outline focus:mr-3px"
            required
          >
          <button
            type="submit"
            class="rounded-r-lg p-4 bg-indigo uppercase tracking-wide font-bold text-sm sm:text-base text-white border border-indigo sm:border-transparent focus:outline-none focus:shadow-outline"
          >
            <span class="hidden sm:inline">
              Hear from us
            </span>
            <span class="sm:hidden">
              Submit
            </span>
          </button>
        </form>
        <small class="block pt-2 px-4 text-grey-darkest">
          We promise we will send exactly one email, written by a human. <em>No spam, no obligation.</em>
        </small>
      </section>
      <section class="p-8 bg-indigo-lightest">
        <div class="mx-auto md:flex md:justify-between md:items-center max-w-xl">
          <section class="max-w-sm mb-2 md:mb-4">
            <div class="flex items-center -ml-4 mb-8">
              <img
                src="/payments-icon.svg"
                alt="Payments icon"
                class="h-12 w-12 mr-4"
              >
              <p class="text-2xl font-bold text-indigo uppercase tracking-wide">
                Payments
              </p>
            </div>
            <h1 class="font-black text-4xl sm:text-5xl text-grey-darkest leading-none mb-6">
              Get paid quicker and easier online.
            </h1>
            <nuxt-link
              to="/payments"
              class="inline-block rounded p-3 bg-white shadow-md font-bold text-indigo no-underline uppercase tracking-wide lift-on-hover mb-2 mr-2"
            >
              Learn more &rarr;
            </nuxt-link>
          </section>
          <section class="hidden md:block max-w-xs lg:flex lg:items-center">
            <img 
              src="/make-it-rain.svg"
              alt="An illustration of a man making it rain with green dollar notes onto a large credit card"
              class="w-full h-auto"
            >
          </section>
        </div>
      </section>
    </main>
  </section>
</template>

<script>
import Header from '~/components/Header'

export default {
  components: {
    Header
  }
}
</script>

<style scoped>
body {
  background-color: #f4f6f9;
}
</style>
