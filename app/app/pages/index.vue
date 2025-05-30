<template>
  <div class="dark:bg-gray-900">
    <!-- Hero Section -->
    <section>
      <div class="container mx-auto px-4 py-8">
        <div class="max-w-3xl mx-auto text-center">
          <h1 class="text-4xl font-bold mb-6 text-black dark:text-white">
            Welcome to the Future of Corporate Organization
          </h1>
          <p class="text-xl text-black dark:text-white mb-8">
            CNC Portal enables the creation and management of Crypto Native
            Corporations - a revolutionary way to build and scale companies
            using blockchain technology.
          </p>
          <div class="flex justify-center gap-4">
            <UButton
              size="lg"
              to="https://app.cncportal.io"
              class="transition-transform duration-300 hover:scale-105"
            >
              Get Started
            </UButton>
            <UButton
              variant="ghost"
              size="lg"
              to="/how-it-works"
              class="transition-transform duration-300 hover:scale-105"
            >
              Learn More
            </UButton>
          </div>
        </div>
      </div>
    </section>

    <!-- What is CNC Section -->
    <section>
      <div class="container mx-auto px-4">
        <div class="max-w-3xl mx-auto">
          <h2
            class="text-3xl font-bold mb-8 text-center text-black dark:text-emerald-400"
          >
            What is a CNC?
          </h2>
          <UCard
            class="shadow-sm bg-white dark:bg-gray-800 transition-transform duration-300 hover:shadow-lg hover:scale-[1.02] mb-8"
          >
            <template #header>
              <h3
                class="text-xl font-semibold text-black dark:text-emerald-400"
              >
                Crypto Native Corporation
              </h3>
            </template>
            <p class="text-black dark:text-white">
              Crypto Native Corporations are a subtype of Decentralized
              Autonomous Organizations (DAOs). It is a digital first company
              organized like a classic corporation but with it's existence
              represented on a blockchain instead of in the corporate registry
              of any one national jurisdiction. From the very beginning, a CNC
              can have a globally distributed ownership and generalized
              membership.
            </p>
          </UCard>
        </div>
      </div>
    </section>
    <section class="py-16">
      <div class="container mx-auto px-4">
        <div class="max-w-3xl mx-auto">
          <UCard
            class="shadow-sm bg-white dark:bg-gray-800 transition-transform duration-300 hover:shadow-lg hover:scale-[1.02] mb-8"
          >
            <template #header>
              <h3
                class="text-xl font-semibold text-black dark:text-emerald-400"
              >
                Vision
              </h3>
            </template>
            <p class="text-black dark:text-white">
              Any knowledge worker, regardless of the local currency,
              participating in globally distributed, economically viable,
              digital first company that use blockchain technology as the
              primary mechanism of value exchange, wealth maintenance, and
              symbolic representation of corporate existence.
            </p></UCard
          >
        </div>
      </div>
    </section>

    <!-- Key Differences Section -->
    <section class="py-16">
      <div class="container mx-auto px-4">
        <h2
          class="text-3xl font-bold mb-12 text-center text-black dark:text-emerald-400"
        >
          CNC vs DAO: Key Differences
        </h2>
        <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
          <UCard
            class="shadow-sm bg-white dark:bg-gray-800 transition-transform duration-300 hover:shadow-lg hover:scale-[1.02] mb-8"
          >
            <template #header>
              <h3
                class="text-xl font-semibold text-black dark:text-emerald-400"
              >
                CNC
              </h3>
            </template>
            <ul class="space-y-4 text-black dark:text-white">
              <li>
                • Central authority controlled by an elected Board of Directors.
              </li>
              <li>
                • Managed through the CNC Portal with selective on-chain
                recording.
              </li>
              <li>
                • Permissioned: membership and control determined by company
                rules.
              </li>
              <li>
                • Equity created through voluntary participation and tokenized
                representation.
              </li>
            </ul>
          </UCard>
          <UCard
            class="shadow-sm bg-white dark:bg-gray-800 transition-transform duration-300 hover:shadow-lg hover:scale-[1.02] mb-8"
          >
            <template #header>
              <h3
                class="text-xl font-semibold text-black dark:text-emerald-400"
              >
                DAO
              </h3>
            </template>
            <ul class="space-y-4 text-black dark:text-white">
              <li>• No central authority. Run by smart contracts.</li>
              <li>
                • Managed in the open with all decisions recorded on chain.
              </li>
              <li>
                • Permissionless: anyone can purchase voting power through token
                ownership.
              </li>
              <li>• Funds raised through token sales and ICOs.</li>
            </ul>
          </UCard>
        </div>
      </div>
    </section>

    <!-- Benefits Section -->
    <section class="py-16">
      <div class="container mx-auto px-4">
        <h2
          class="text-3xl font-bold mb-12 text-center text-black dark:text-emerald-400"
        >
          Why Choose CNC?
        </h2>
        <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
          <UCard
            class="shadow-sm bg-white dark:bg-gray-800 transition-transform duration-300 hover:shadow-lg hover:scale-[1.02] mb-8"
          >
            <template #header>
              <div class="flex items-center gap-2">
                <UIcon
                  name="i-heroicons-scale"
                  class="text-emerald-600 dark:text-emerald-400 transition-transform duration-300 group-hover:scale-110"
                />
                <h3
                  class="text-lg font-semibold text-black dark:text-emerald-400"
                >
                  Scale Through Participation
                </h3>
              </div>
            </template>
            <p class="text-black dark:text-white">
              Scale through micro-investments of skilled labor instead of a few
              large cash infusions. Enjoy the efficient corporate structure
              controls and the antifragility of distributed ownership.
            </p>
          </UCard>
          <UCard
            class="shadow-sm bg-white dark:bg-gray-800 transition-transform duration-300 hover:shadow-lg hover:scale-[1.02] mb-8"
          >
            <template #header>
              <div class="flex items-center gap-2">
                <UIcon
                  name="i-heroicons-globe-alt"
                  class="text-emerald-600 dark:text-emerald-400 transition-transform duration-300 group-hover:scale-110"
                />
                <h3
                  class="text-lg font-semibold text-black dark:text-emerald-400"
                >
                  Global Access
                </h3>
              </div>
            </template>
            <p class="text-black dark:text-white">
              Enable talented knowledge workers worldwide to participate as
              equal investors, regardless of local currency.
            </p>
          </UCard>
          <UCard
            class="shadow-sm bg-white dark:bg-gray-800 transition-transform duration-300 hover:shadow-lg hover:scale-[1.02] mb-8"
          >
            <template #header>
              <div class="flex items-center gap-2">
                <UIcon
                  name="i-heroicons-shield-check"
                  class="text-emerald-600 dark:text-emerald-400 transition-transform duration-300 group-hover:scale-110"
                />
                <h3
                  class="text-lg font-semibold text-black dark:text-emerald-400"
                >
                  Efficient Structure
                </h3>
              </div>
            </template>
            <p class="text-black dark:text-white">
              Maintain traditional corporate structures while leveraging
              blockchain technology for transparency and efficiency.
            </p>
          </UCard>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16">
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-3xl font-bold mb-6 text-black dark:text-emerald-400">
          Ready to Build Your CNC?
        </h2>
        <p class="text-xl text-black dark:text-white mb-8 max-w-2xl mx-auto">
          Join the future of corporate organization and start building your
          distributed team today.
        </p>
        <UButton
          size="lg"
          to="https://app.cncportal.io"
          class="transition-transform duration-300 hover:scale-105"
        >
          Start Building
        </UButton>
      </div>
    </section>
  </div>
</template>
