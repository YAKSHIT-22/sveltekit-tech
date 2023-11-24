<script>
</script>

<section
  class="w-screen h-full min-h-screen flex items-center justify-center p-[1rem] py-16 bg-[#101010]"
>
  <div
    class="flex flex-col  gap-[4rem] lg:flex-row items-center justify-center w-full h-full max-w-screen-2xl mx-auto p-4 xs:p-8"
  >
    <div
      class="flex flex-col items-center justify-center gap-4"
    >
      <div class="flex-1 text-center">
        <h2 class="text-4xl font-extrabold mb-4">Get in Touch</h2>
        <p class="text-gray-400 leading-loose max-w-2xl">
          Have questions or want to collaborate? Reach out to us using the form
          below, and we'll get back to you as soon as possible.
        </p>
      </div>
      <div class="flex-1">
        <img
          class="w-64 h-64 object-cover rounded-full"
          src="https://images.unsplash.com/photo-1587560699334-bea93391dcef?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
          alt="Contact"
        />
      </div>
    </div>
    <div class="flex-1">
      <form class="grid grid-cols-2 md:grid-cols-2 gap-4">
        <div class="col-span-1">
          <label for="name" class="text-sm font-semibold text-gray-400"
            >Your Name</label
          >
          <input
            type="text"
            id="name"
            name="name"
            placeholder="John Doe"
            class="w-full bg-[#151515] mt-2 p-3 border border-gray-700 rounded-md focus:outline-none focus:border-indigo-500"
          />
        </div>
        <div class="col-span-1">
          <label for="email" class="text-sm font-semibold text-gray-400"
            >Your Email</label
          >
          <input
            type="email"
            id="email"
            name="email"
            placeholder="john@example.com"
            class="w-full bg-[#151515] mt-2 p-3 border border-gray-700 rounded-md focus:outline-none focus:border-indigo-500"
          />
        </div>
        <div class="col-span-2">
          <label for="message" class="text-sm font-semibold text-gray-400"
            >Your Message</label
          >
          <textarea
            id="message"
            name="message"
            rows="4"
            placeholder="How can we assist you?"
            class="w-full mt-2 p-3 bg-[#151515] border border-gray-700 rounded-md focus:outline-none focus:border-indigo-500"
          ></textarea>
        </div>
        <div class="col-span-2">
          <button
            type="submit"
            class="w-full bg-indigo-600 text-white py-3 rounded-md hover:bg-indigo-700 focus:outline-none focus:ring focus:border-indigo-200 transition duration-300"
            >Send Message</button
          >
        </div>
      </form>
    </div>
  </div>
</section>
