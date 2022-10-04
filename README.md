# Nuxt Docs

- [Nuxt Docs](#nuxt-docs)
  - [State Management](#state-management)
    - [Pinia vs Nuxt 3's `useState`](#pinia-vs-nuxt-3s-usestate)
    - [Pinia](#pinia)
      - [Getters](#getters)

## State Management

### Pinia vs Nuxt 3's `useState`

- Link: [Vue Mastery article](https://www.vuemastery.com/blog/nuxt-3-state-mangement-pinia-vs-usestate/)

> 💡 Conclusion: Use **Pinia**

### Pinia

#### Getters

> Usage: We want to save the smallest amount possible and then calculate everything else we need from that tiny piece.

- If we stored fullName, we’d always have to update it whenever firstName or lastName are updated, which is no small task.
