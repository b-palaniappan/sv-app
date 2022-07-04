<script>
  import logo from "./assets/svelte.png";
  import Counter from "./lib/Counter.svelte";
</script>

<main>
  <img src={logo} alt="Svelte Logo" width="150px" />
  <h1 class="font-snas text-slate-500">Hello world!</h1>
  <Counter />

  <div class="bg-white dark:bg-gray-900">
    <div class="flex justify-center h-screen">
      <div
        class="hidden bg-cover lg:block lg:w-2/3"
        style="background-image: url(https://images.unsplash.com/photo-1616763355603-9755a640a287?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80)"
      >
        <div class="flex items-center h-full px-20 bg-gray-900 bg-opacity-40">
          <div>
            <h2 class="text-4xl font-bold text-white">Brand</h2>

            <p class="max-w-xl mt-3 text-gray-300">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. In autem
              ipsa, nulla laboriosam dolores, repellendus perferendis libero
              suscipit nam temporibus molestiae
            </p>
          </div>
        </div>
      </div>

      <div class="flex items-center w-full max-w-md px-6 mx-auto lg:w-2/6">
        <div class="flex-1">
          <div class="text-center">
            <h2
              class="text-4xl font-bold text-center text-gray-700 dark:text-white"
            >
              Brand
            </h2>

            <p class="mt-3 text-gray-500 dark:text-gray-300">
              Sign in to access your account
            </p>
          </div>

          <div class="mt-8">
            <form>
              <div>
                <label
                  for="email"
                  class="block mb-2 text-sm text-gray-600 dark:text-gray-200"
                  >Email Address</label
                >
                <input
                  type="email"
                  name="email"
                  id="email"
                  placeholder="example@example.com"
                  class="block w-full px-4 py-2 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40"
                />
              </div>

              <div class="mt-6">
                <div class="flex justify-between mb-2">
                  <label
                    for="password"
                    class="text-sm text-gray-600 dark:text-gray-200"
                    >Password</label
                  >
                  <a
                    href="#"
                    class="text-sm text-gray-400 focus:text-blue-500 hover:text-blue-500 hover:underline"
                    >Forgot password?</a
                  >
                </div>

                <input
                  type="password"
                  name="password"
                  id="password"
                  placeholder="Your Password"
                  class="block w-full px-4 py-2 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40"
                />
              </div>

              <div class="mt-6">
                <button
                  class="w-full px-4 py-2 tracking-wide text-white transition-colors duration-200 transform bg-blue-500 rounded-md hover:bg-blue-400 focus:outline-none focus:bg-blue-400 focus:ring focus:ring-blue-300 focus:ring-opacity-50"
                >
                  Sign in
                </button>
              </div>
            </form>

            <p class="mt-6 text-sm text-center text-gray-400">
              Don&#x27;t have an account yet? <a
                href="#"
                class="text-blue-500 focus:outline-none focus:underline hover:underline"
                >Sign up</a
              >.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- ============================================================================================== -->
  <hr />
  <!-- ============================================================================================== -->

  <section class="py-20 bg-white">
    <div class="flex flex-col px-8 mx-auto space-y-12 max-w-7xl xl:px-12">
      <div class="relative">
        <h2 class="w-full text-3xl font-bold text-center sm:text-4xl md:text-5xl">
          Level Up Your Designs
        </h2>
        <p class="w-full py-8 mx-auto -mt-2 text-lg text-center text-gray-700 intro sm:max-w-3xl">
          Add some nice touches to your interface with our latest designs,
          components, and templates. We've crafted a beautiful user experience
          that your visitors will love.
        </p>
      </div>
      <div class="flex flex-col mb-8 animated fadeIn sm:flex-row">
        <div class="flex items-center mb-8 sm:w-1/2 md:w-5/12 sm:order-last">
          <img
            class="rounded-lg shadow-xl"
            src="https://cdn.devdojo.com/images/december2020/dashboard-011.png"
            alt=""
          />
        </div>
        <div class="flex flex-col justify-center mt-5 mb-8 md:mt-0 sm:w-1/2 md:w-7/12 sm:pr-16">
          <p
            class="mb-2 text-sm font-semibold leading-none text-left text-indigo-600 uppercase"
          >
            Drag-n-drop design
          </p>
          <h3 class="mt-2 text-2xl sm:text-left md:text-4xl">
            Design Made Easy
          </h3>
          <p class="mt-5 text-lg text-gray-700 text md:text-left">
            Crafting your user experience has never been easier, with our
            intuitive drag'n drop interface you will be creating beatiful
            designs in no time.
          </p>
        </div>
      </div>
      <div class="flex flex-col mb-8 animated fadeIn sm:flex-row">
        <div class="flex items-center mb-8 sm:w-1/2 md:w-5/12">
          <img
            class="rounded-lg shadow-xl"
            src="https://cdn.devdojo.com/images/december2020/dashboard-04.png"
            alt=""
          />
        </div>
        <div
          class="flex flex-col justify-center mt-5 mb-8 md:mt-0 sm:w-1/2 md:w-7/12 sm:pl-16"
        >
          <p
            class="mb-2 text-sm font-semibold leading-none text-left text-indigo-600 uppercase"
          >
            know your data
          </p>
          <h3 class="mt-2 text-2xl sm:text-left md:text-4xl">
            Optimized For Conversions
          </h3>
          <p class="mt-5 text-lg text-gray-700 text md:text-left">
            Backed by data, these templates have been crafted for ultimate
            optimization. Now, converting your visitors into customers is easier
            than ever before.
          </p>
        </div>
      </div>
      <div class="flex flex-col mb-8 animated fadeIn sm:flex-row">
        <div class="flex items-center mb-8 sm:w-1/2 md:w-5/12 sm:order-last">
          <img
            class="rounded-lg shadow-xl"
            src="https://cdn.devdojo.com/images/december2020/dashboard-03.png"
            alt=""
          />
        </div>
        <div
          class="flex flex-col justify-center mt-5 mb-8 md:mt-0 sm:w-1/2 md:w-7/12 sm:pr-16"
        >
          <p
            class="mb-2 text-sm font-semibold leading-none text-left text-indigo-600 uppercase"
          >
            Easy to customize
          </p>
          <h3 class="mt-2 text-2xl sm:text-left md:text-4xl">
            Make It Your Own
          </h3>
          <p class="mt-5 text-lg text-gray-700 text md:text-left">
            All templates and components are fully customizable. You can use
            these templates to tell your personal story and convey your message.
          </p>
        </div>
      </div>
    </div>
  </section>
</main>

<style>
</style>
