<script setup></script>

<template>
  <div class="min-h-screen bg-slate-100 text-slate-900">
    <!-- Header -->
    <header class="mx-auto max-w-6xl px-6 pt-10">
      <h1 class="text-4xl font-extrabold tracking-tight">Van Booking</h1>
      <p class="mt-2 text-slate-600">Gestion de réservations de vans</p>
    </header>

    <!-- Main -->
    <main class="mx-auto max-w-6xl px-6 pb-12 pt-8">
      <div class="grid gap-6 lg:grid-cols-12">
        <!-- Sidebar -->
        <aside class="lg:col-span-4">
          <div
            class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm"
          >
            <h2 class="text-lg font-semibold">Ressource</h2>

            <div class="mt-3">
              <label class="text-sm text-slate-600">Van</label>
              <select
                class="mt-2 w-full rounded-xl border border-slate-200 bg-white px-3 py-2 outline-none focus:ring-2 focus:ring-slate-300"
              >
                <option>Van A</option>
                <option>Van B</option>
              </select>
            </div>

            <button
              class="mt-5 inline-flex w-full items-center justify-center gap-2 rounded-xl bg-blue-600 px-4 py-3 font-semibold text-white shadow-sm hover:bg-blue-700 active:translate-y-px"
              type="button"
            >
              <span class="text-xl leading-none">+</span>
              Nouvelle réservation
            </button>

            <div class="mt-6 border-t border-slate-100 pt-5">
              <p class="text-sm font-semibold text-slate-700">Légende</p>

              <div class="mt-3 space-y-2 text-sm">
                <div class="flex items-center gap-2">
                  <span class="h-3 w-3 rounded bg-emerald-200"></span>
                  <span>Libre</span>
                </div>
                <div class="flex items-center gap-2">
                  <span class="h-3 w-3 rounded bg-rose-300"></span>
                  <span>Réservé</span>
                </div>
              </div>
            </div>
          </div>
        </aside>

        <!-- Right column -->
        <section class="lg:col-span-8 space-y-6">
          <!-- Timeline -->
          <div
            class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm"
          >
            <div class="flex items-center justify-between">
              <h2 class="text-lg font-semibold">Disponibilités</h2>

              <div class="flex items-center gap-2 text-sm">
                <button
                  class="rounded-lg border border-slate-200 px-3 py-1.5 hover:bg-slate-50"
                  type="button"
                >
                  ←
                </button>
                <span class="font-semibold">Janvier 2026</span>
                <button
                  class="rounded-lg border border-slate-200 px-3 py-1.5 hover:bg-slate-50"
                  type="button"
                >
                  →
                </button>
              </div>
            </div>

            <!-- Timeline grid (STATIC MOCKUP) -->
            <div
              class="mt-5 overflow-x-auto rounded-xl border border-slate-200"
            >
              <div class="min-w-[900px]">
                <!-- Header row -->
                <div
                  class="grid grid-cols-[160px_repeat(31,32px)] border-b border-slate-200 bg-slate-50"
                >
                  <div class="px-4 py-3 text-sm font-semibold">Dates</div>

                  <!-- 1..31 -->
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    1
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    2
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    3
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    4
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    5
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    6
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    7
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    8
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    9
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    10
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    11
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    12
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    13
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    14
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    15
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    16
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    17
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    18
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    19
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    20
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    21
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    22
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    23
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    24
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    25
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    26
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    27
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    28
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    29
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    30
                  </div>
                  <div
                    class="flex items-center justify-center text-xs font-semibold"
                  >
                    31
                  </div>
                </div>

                <!-- Van A row -->
                <div
                  class="grid grid-cols-[160px_repeat(31,32px)] border-b border-slate-100 bg-white"
                >
                  <div class="px-4 py-3 text-sm font-semibold">Van A</div>

                  <!-- Exemple: réservé jours 3-5 -->
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-rose-200"></div>
                  <div class="h-10 bg-rose-200"></div>
                  <div class="h-10 bg-rose-200"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                </div>

                <!-- Van B row -->
                <div class="grid grid-cols-[160px_repeat(31,32px)] bg-white">
                  <div class="px-4 py-3 text-sm font-semibold">Van B</div>

                  <!-- Exemple: réservé jours 11-13 -->
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-rose-200"></div>
                  <div class="h-10 bg-rose-200"></div>
                  <div class="h-10 bg-rose-200"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                  <div class="h-10 bg-emerald-50"></div>
                </div>
              </div>
            </div>
          </div>

          <!-- Reservations list (STATIC MOCKUP) -->
          <div
            class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm"
          >
            <div class="flex items-center justify-between">
              <h2 class="text-lg font-semibold">Réservations</h2>
              <span class="text-sm text-slate-500">2 résultats</span>
            </div>

            <div class="mt-4 overflow-x-auto">
              <table class="w-full border-collapse text-sm">
                <thead>
                  <tr
                    class="border-b border-slate-200 text-left text-slate-600"
                  >
                    <th class="py-2 pr-4 font-medium">Van</th>
                    <th class="py-2 pr-4 font-medium">Client</th>
                    <th class="py-2 pr-4 font-medium">Du</th>
                    <th class="py-2 pr-4 font-medium">Au</th>
                    <th class="py-2 text-right font-medium">Action</th>
                  </tr>
                </thead>

                <tbody>
                  <tr class="border-b border-slate-100">
                    <td class="py-3 pr-4 font-medium">Van A</td>
                    <td class="py-3 pr-4">Paul</td>
                    <td class="py-3 pr-4">03/01/2026</td>
                    <td class="py-3 pr-4">06/01/2026</td>
                    <td class="py-3 text-right">
                      <button
                        class="text-rose-600 hover:underline"
                        type="button"
                      >
                        Supprimer
                      </button>
                    </td>
                  </tr>

                  <tr>
                    <td class="py-3 pr-4 font-medium">Van B</td>
                    <td class="py-3 pr-4">Julie</td>
                    <td class="py-3 pr-4">11/01/2026</td>
                    <td class="py-3 pr-4">14/01/2026</td>
                    <td class="py-3 text-right">
                      <button
                        class="text-rose-600 hover:underline"
                        type="button"
                      >
                        Supprimer
                      </button>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </section>
      </div>
    </main>
  </div>
</template>

<style scoped></style>
