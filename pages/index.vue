<template>
  <section>
    <header class="flex h-16 w-full p-4 bg-indigo">
      <div>
        <img
          src="/logo-white.svg"
          alt="Be Freer logo"
          class="h-full w-auto"
        >
      </div>
    </header>
    <main
      class=" py-8 lg:py-24 px-4 md:py-8 font-base text-grey-darkest text-base sm:text-lg leading-normal"
      style="background-image: linear-gradient(-180deg, #FFFFFF 0%, #F4F6F9 100%);"
    >
      <section class="lg:max-w-lg mx-auto">
        <h1 class="font-black text-2xl xs:text-3xl sm:text-4xl md:text-5xl text-grey-darkest leading-none mb-6">
          People don’t start a business so they can deal with admin.
        </h1>
        <h2 class="font-light text-xl md:text-2xl text-black leading-tight mb-2">
          People start businesses to share their passion or skill with the world.<br>
        </h2>
        <h2 class="font-light text-xl md:text-2xl text-black leading-tight mb-6">
          We’ll help you to be less busy. <strong class="font-bold">Be Freer.</strong>
        </h2>
        <p class="mb-4">
          Do you own a business? Can you remember a time where you haven’t had a stack of to-dos? Receipts that need to be photographed and sent to your accountant? Invoice reminders that need to be resent? Customers that need to be contacted? Appointments that need to be confirmed?
        </p>
        <p class="mb-4">
          Things pile up. You find more and more of your time spent on tasks that have to be done and less on what you want to be doing. Is this why you started in the first place?
        </p>
        <p class="mb-4">
          What if you could get rid of most of that work? What if you could spend more of your time doing what you’re good at? We can help.
        </p>
        <p class="mb-4">
          We work with each client, go through your processes from buying stock or planning an event all the way to filing your tax returns and putting your feet up.
        </p>
        <p class="mb-4">
          We remove unnecessary steps, automate what can be automated and leave you with more time to do what you do best.
        </p>
        <p class="mb-4">
          It starts with an email. All of our initial consultations are free and are followed up with a proposal of how we can get rid of tasks you hate.
        </p>
        <p class="mb-6 sm:mb-8 font-bold">
          If you’re sick of admin, and want to find out how much you can stop doing yourself enter your email below and we’ll start making that happen.
        </p>
        <form
          name="Email Interest"
          method="POST"
          netlify
          class="flex max-w-md w-full bg-white sm:shadow-lg rounded-lg"
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
      </section>
    </main>
  </section>
</template>

<script>
export default {
  //
}
</script>

<style>
html {
  @apply font-sans;
}
</style>
