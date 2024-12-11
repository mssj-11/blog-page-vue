<template>
  <div class="px-4 xl:px-12 py-12 min-h-screen">
    <div>
      <h4 class="text-4xl xl:text-7xl mb-1">Latest Articles</h4>
      <p class="text-base xl:text-xl">
        Explore practical tips and strategies to build better habits and boost productivity.
      </p>
    </div>

    <div class="grid grid-cols-1 xl:grid-cols-2 gap-6 mt-6">
      <!-- Latest Article -->
      <div>
        <img
          src="https://images.unsplash.com/photo-1496180727794-817822f65950?q=80&w=1740"
          class="object-cover rounded-xl w-full h-81"
        />
        <div class="mt-2">
          <h5 class="text-2xl xl:text-4xl">
            Morning Routines to Maximize Productivity
          </h5>
          <p class="mt-2 mb-4">
            Discover how creating a structured morning routine can set the tone for a successful day.
          </p>
          <div class="flex items-center justify-between">
            <p class="italic">Published on 25 Jul, 2024</p>
            <p class="border rounded-full px-2">Daily Habits</p>
          </div>
        </div>
      </div>

      <!-- Older Articles -->
      <div class="flex flex-col gap-6">
        <div class="flex flex-col xl:flex-row gap-4">
          <img
            src="https://images.unsplash.com/photo-1593642532973-d31b6557fa68?q=80&w=1738"
            class="object-cover rounded-xl w-full xl:w-36 xl:h-36"
          />
          <div class="mt-2">
            <h5 class="text-2xl">The Power of Habit Stacking</h5>
            <p class="mt-2 mb-4">
              Learn how to build powerful routines by linking small habits together for greater impact.
            </p>
            <div class="flex items-center justify-between">
              <p class="italic">Published on 20 Jul, 2024</p>
              <p class="border rounded-full px-2">Habit Formation</p>
            </div>
          </div>
        </div>
        <div class="flex flex-col xl:flex-row gap-4">
          <img
            src="https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?q=80&w=1782"
            class="object-cover rounded-xl w-full xl:w-36 xl:h-36"
          />
          <div class="mt-2">
            <h5 class="text-2xl">Time Blocking: A Simple Productivity Hack</h5>
            <p class="mt-2 mb-4">
              Enhance focus and reduce stress by scheduling your day in blocks of time for specific tasks.
            </p>
            <div class="flex items-center justify-between">
              <p class="italic">Published on 18 Jul, 2024</p>
              <p class="border rounded-full px-2">Time Management</p>
            </div>
          </div>
        </div>
        <div class="flex flex-col xl:flex-row gap-4">
          <img
            src="https://images.unsplash.com/photo-1519337265831-281ec6cc8514?q=80&w=1738"
            class="object-cover rounded-xl w-full xl:w-36 xl:h-36"
          />
          <div class="mt-2">
            <h5 class="text-2xl">The Science of Focus: Avoiding Distractions</h5>
            <p class="mt-2 mb-4">
              Explore research-backed strategies to minimize distractions and improve your concentration.
            </p>
            <div class="flex items-center justify-between">
              <p class="italic">Published on 10 Jul, 2024</p>
              <p class="border rounded-full px-2">Focus Techniques</p>
            </div>
          </div>
        </div>
        <!-- New Article -->
        <div class="flex flex-col xl:flex-row gap-4">
          <img
            src="https://images.unsplash.com/photo-1598257006626-48b0c252070d?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            class="object-cover rounded-xl w-full xl:w-36 xl:h-36"
          />
          <div class="mt-2">
            <h5 class="text-2xl">Overcoming Procrastination</h5>
            <p class="mt-2 mb-4">
              Practical steps to beat procrastination and achieve your goals effectively.
            </p>
            <div class="flex items-center justify-between">
              <p class="italic">Published on 15 Dec, 2024</p>
              <p class="border rounded-full px-2">Self-Improvement</p>
            </div>
          </div>
        </div>
        <button class="rounded-full border font-semibold py-2 px-6 self-center">
          View All Articles
        </button>
      </div>
    </div>
  </div>
</template>