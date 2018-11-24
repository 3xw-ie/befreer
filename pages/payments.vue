<template>
  <section>
    <header class="relative overflow-hidden pt-12 md:pt-24 pb-24 md:pb-32">
      <div class="absolute pin h-full w-full skew bg-grey-light"/>
      <div class="relative container px-8 mx-auto lg:flex lg:justify-between">
        <section class="lg:max-w-sm mb-8">
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
          <h1 class="font-black text-2xl xs:text-3xl sm:text-4xl md:text-5xl text-grey-darkest leading-none mb-4">
            Get paid quicker and easier online.
          </h1>
          <h2 class="font-light text-base xs:text-xl sm:text-2xl text-black leading-tight mb-4">
            Increase sales and convert more customers with well-designed checkout flows. Accept one-off payments, invoiced payments, and recurring subscriptions. Automate everything that comes after payment with our automation platform.
          </h2>
          <div>
            <!-- <nuxt-link
              to=""
              class="inline-block rounded p-3 bg-indigo shadow-md font-bold text-white no-underline uppercase tracking-wide lift-on-hover mb-2 mr-2"
            >
              Get Started
            </nuxt-link> -->
            <a
              href="#learn-more"
              class="inline-block rounded p-3 bg-indigo shadow-md font-bold text-white no-underline uppercase tracking-wide lift-on-hover mb-2 mr-2"
            >
              Get Started
            </a>
            <!-- <nuxt-link
              to=""
              class="inline-block rounded p-3 bg-white shadow-md font-bold text-indigo no-underline uppercase tracking-wide lift-on-hover"
            >
              Contact us
            </nuxt-link> -->
            <a
              href="mailto:dave@befreer.ie"
              class="inline-block rounded p-3 bg-white shadow-md font-bold text-indigo no-underline uppercase tracking-wide lift-on-hover mb-2"
            >
              Contact us &rarr;
            </a>
          </div>
        </section>
        <section class="max-w-sm lg:flex lg:items-center lg:max-w-md">
          <img 
            src="/make-it-rain.svg"
            alt="An illustration of a man making it rain with green dollar notes onto a large credit card"
            class="w-full h-auto"
          >
        </section>
      </div>
    </header>
    <main>
      <section
        id="steps"
        ref="container"
        class="px-4 mx-auto flex flex-col items-center lg:items-start container pt-12 md:pt-24 pb-24 md:pb-48"
      >
        <h1 class="text-xl sm:text-2xl font-bold text-indigo uppercase tracking-wide mb-12">
          Incoming Payments
        </h1>
        <div
          id="step"
          class="w-full lg:w-auto lg:self-start"
        >
          <div class="flex items-center lg:justify-start">
            <figure class="flex-no-shrink h-24 sm:h-32 w-24 sm:w-32 rounded-full overflow-hidden z-10">
              <img
                src="/accept-payments.svg"
                alt="Accept payments"
                class="h-full w-full"
              >
            </figure>
            <figcaption class="max-w-xs ml-4 sm:ml-8 md:ml-24 lg:ml-8">
              <h1 class="font-black text-base xs:text-xl sm:text-2xl text-grey-darkest leading-none mb-1">
                1. Accept Payment
              </h1>
              <h2 class="font-light text-sm xs:text-base sm:text-xl text-black leading-tight">
                On your website, from a link in an invoice you send, direct debit, etc.
              </h2>
            </figcaption>
          </div>
          <div
            class="relative ml-12 sm:ml-16"
          >
            <AnimatedFlow/>
          </div>
        </div>
        <div
          id="step"
          class="w-full lg:w-auto lg:self-center"
        >
          <div class="flex flex-row-reverse justify-start lg:flex-row lg:justify-start items-center">
            <figure class="flex-no-shrink h-24 sm:h-32 w-24 sm:w-32 rounded-full overflow-hidden ml-4 sm:ml-8 md:ml-24 lg:ml-0 lg:mr-8 z-10">
              <img
                src="/fulfil-customer.svg"
                alt="Fulfill customer"
                class="h-full w-full"
              >
            </figure>
            <figcaption class="max-w-xs">
              <h1 class="font-black text-base xs:text-xl sm:text-2xl text-grey-darkest leading-none mb-1">
                2. Fulfill Customer
              </h1>
              <h2 class="font-light text-sm xs:text-base sm:text-xl text-black leading-tight">
                Send an e-ticket, confirm their appointment, ship a product, etc.
              </h2>
            </figcaption>
          </div>
          <div
            class="relative ml-12 sm:ml-16"
          >
            <AnimatedFlow
              :left-to-right="viewportWiderThan992"
              :delay="4000"
            />
          </div>
        </div>
        <div
          id="step"
          class="w-full lg:w-auto lg:self-end"
        >
          <div class="flex items-center">
            <figure class="flex-no-shrink h-24 sm:h-32 w-24 sm:w-32 rounded-full overflow-hidden z-10">
              <img
                src="/record-transaction.svg"
                alt="Record transaction"
                class="h-full w-full"
              >
            </figure>
            <figcaption class="max-w-xs ml-4 sm:ml-8 md:ml-24 lg:ml-8">
              <h1 class="font-black text-base xs:text-xl sm:text-2xl text-grey-darkest leading-none mb-1">
                3. Record Transaction
              </h1>
              <h2 class="font-light text-sm xs:text-base sm:text-xl text-black leading-tight">
                Create a sales invoice in your accounting software, keeping your accountant happy.
              </h2>
            </figcaption>
          </div>
        </div>
      </section>
      <section class="bg-grey-lightest relative pt-16 md:pt-8 pb-24 md:pb-40">
        <div class="absolute pin h-full w-full skew bg-indigo"/>
        <div class="relative mx-auto md:flex px-4 sm:px-8 sm:max-w-sm md:max-w-xl">
          <div class="mb-8 md:mr-8">
            <div class="flex items-end md:block">
              <img
                src="/lock.svg"
                alt=""
                class="h-12 w-12 mr-4 mb-4"
              >
              <h1 class="font-medium text-2xl text-white mb-4">
                Secure payments
              </h1>
            </div>
            <p class="text-indigo-lightest leading-loose">
              Don't break a sweat worrying about securely handling your customers' credit cards. We use
              <a
                href="https://stripe.com"
                class="text-indigo-lightest"
                target="_blank"
                rel="noopener"
              >
                Stripe
              </a>
              to ensure your customers' data is securely handled.
            </p>
          </div>
          <div class="mb-8 md:mr-8">
            <div class="flex items-end md:block">
              <img
                src="/time.svg"
                alt=""
                class="h-12 w-12 mr-4 mb-4"
              >
              <h1 class="font-medium text-2xl text-white mb-4">
                Faster fulfillment
              </h1>
            </div>
            <p class="text-indigo-lightest leading-loose">
              Delight your customers with quicker if not instant fulfillment of their order. Improve customer experience with faster response times.
            </p>
          </div>
          <div>
            <div class="flex items-end md:block">
              <img
                src="/timer.svg"
                alt=""
                class="h-12 w-12 mb-4 mr-4"
              >
              <h1 class="font-medium text-2xl text-white mb-4">
                Minimised admin
              </h1>
            </div>
            <p class="text-indigo-lightest leading-loose">
              Leave what can be done by computers to the computers. Automate the repetitive work so you can focus on more important tasks.
            </p>
            <!-- <nuxt-link
              to="/automation"
              class="text-white no-underline leading-loose"
            >
              Learn more about automation &rarr;
            </nuxt-link> -->
          </div>
        </div>
      </section>
      <section 
        id="learn-more"
        class="px-4 pt-16 pb-24 bg-grey-lightest"
      >
        <div class="mx-auto lg:max-w-lg">
          <h1 class="font-black text-3xl sm:text-4xl text-grey-darkest mb-2">
            Sound interesting?
          </h1>
          <h2 class="font-light text-xl sm:text-2xl leading-normal text-black mr-24 mb-6">
            Enter your email below and we'll be in touch.
          </h2>
          <form
            name="Email Interest"
            method="POST"
            netlify
            class="flex max-w-md w-full bg-white sm:shadow-lg rounded-lg"
          >
            <input
              type="hidden"
              name="page"
              value="/payments"
            >
            <!-- <label
              for="email"
              class="hidden"
            >
              Email
            </label> -->
            <input
              name="email"
              type="email"
              placeholder="sick-of-admin@youremail.com"
              class="flex-1 pt-4 pr-2 pl-4 pb-4 sm:pr-4 bg-transparent text-sm sm:text-base rounded-l-lg border sm:border-transparent focus:outline-none focus:shadow-outline focus:mr-3px"
              required
            >
            <button
              type="submit"
              class="rounded-r-lg p-4 bg-indigo uppercase tracking-wide font-bold text-sm sm:text-base text-white border border-indigo sm:border-transparent focus:outline-none focus:shadow-outline"
            >
              <!-- Submit -->
            </button>
          </form>
          <small class="block pt-2 px-4 text-grey-darkest">
            We promise we will send exactly one email, written by a human. <em>No spam, no obligation.</em>
          </small>
        </div>
      </section>
    </main>
  </section>
</template>

<script>
import AnimatedFlow from '~/components/AnimatedFlow'

export default {
  components: {
    AnimatedFlow
  },
  computed: {
    viewportWiderThan992() {
      if (typeof window !== 'undefined') {
        return window.innerWidth >= 992 ? true : false
      }
    }
  },
  mounted() {
    const container = document.querySelector('#steps')
    const steps = document.querySelectorAll('#step')
  }
}
</script>

<style scoped>
@media screen and (max-width: 375px) {
  #steps.container {
    @apply max-w-xs;
  }
}
</style>
