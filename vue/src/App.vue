<template>
  <div>
    <header>
      <h1>Cypress Code Smells</h1>
    </header>
    <nav>
      <ul>
        <li>
          Unprepared Element
          <ul>
            <li>
              <router-link to="/unprepared/example1">
                Example 1
              </router-link>
              - Trivial Failure
            </li>
            <li>
              <router-link to="/unprepared/example2">
                Example 2
              </router-link>
              - Trivial Solution
            </li>
            <li>
              <router-link to="/unprepared/example3">
                Example 3
              </router-link>
              - Vuex Failure
            </li>
            <li>
              <router-link to="/unprepared/example4">
                Example 4
              </router-link>
              - Vuex Solution
            </li>
          </ul>
        </li>
        <li>
          Flickering Element
          <ul>
            <li>
              <router-link to="/flickering/example5">
                Example 5
              </router-link>
              - Trivial Failure
            </li>
            <li>
              <router-link to="/flickering/example6">
                Example 6
              </router-link>
              - Trivial Solution
            </li>
            <li>
              <router-link to="/flickering/example7">
                Example 7
              </router-link>
              - Vuex Failure
            </li>
            <li>
              <router-link to="/flickering/example8">
                Example 8
              </router-link>
              - Vuex Solution
            </li>
          </ul>
        </li>
        <li>
          Impatient Test
          <ul>
            <li>
              <router-link to="/impatient/example9">
                Example 9
              </router-link>
              - Trivial Failure
            </li>
            <li>
              <router-link to="/impatient/example10">
                Example 10
              </router-link>
              - Trivial Solution
            </li>
            <li>
              <router-link to="/impatient/example11">
                Example 11
              </router-link>
              - Loading-State Solution
            </li>
            <li>
              <router-link to="/impatient/example12">
                Example 12
              </router-link>
              - Green-Light Solution
            </li>
            <li>
              <router-link to="/impatient/example13">
                Example 13
              </router-link>
              - Vuex Failure
            </li>
            <li>
              <router-link to="/impatient/example14">
                Example 14
              </router-link>
              - Loading-State Solution
            </li>
          </ul>
        </li>
      </ul>
    </nav>
    <main>
      <router-view />
    </main>
  </div>
</template>
