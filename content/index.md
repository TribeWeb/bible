---
seo:
  title: Nuxt Docs Template
  description: Create stunning, fast and SEO-optimized documentation sites with Nuxt UI.
---

::u-page-hero
---
class: dark:bg-gradient-to-b from-neutral-900 to-neutral-950
orientation: horizontal
---
  :::prose-pre
  ---
  code: |-
    export default defineNuxtConfig({
      modules: [
        '@nuxt/ui',
        '@nuxt/content',
        'nuxt-og-image',
        'nuxt-llms'
      ],

      css: ['~/assets/css/main.css']
    })
  filename: nuxt.config.ts
  ---
  ```ts [nuxt.config.ts]
  export default defineNuxtConfig({
    modules: [
      '@nuxt/ui',
      '@nuxt/content',
      'nuxt-og-image',
      'nuxt-llms'
    ],

    css: ['~/assets/css/main.css']
  })
  ```
  :::

#top
:hero-background

#title
Develop a [biblical paradigm]{.text-primary}.

#description
It is not enough to simply know the bible. We are those who desire to have the ***way*** we think about God and the world around us shaped by the bible.

#links
  :::u-button{size="xl" to="/paradigms" trailing-icon="i-lucide-arrow-right"}
  Get started
  :::
::

::u-page-section
---
class: dark:bg-neutral-950
---
#title
Approaches to the Bible patterned by the Apostles

#links
  :::u-button
  ---
  color: neutral
  size: lg
  target: _self
  to: /approaches
  trailingIcon: i-lucide-arrow-right
  variant: subtle
  ---
  Explore apostolic approaches
  :::

#features
  :::u-page-feature
  ---
  icon: i-lucide-palette
  ---
  #title
  Playful

  #description
  Access the complete Nuxt UI component library. From badges to modals, everything styled and accessible out of the box.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-type
  ---
  #title
  Curious

  #description
  Pre-styled prose components with perfect visual harmony. No need for @tailwindcss/typography - get precise control over every element.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-layers
  ---
  #title
  Navigation

  #description
  Accordions, cards, callouts, tabs, steps, code blocks, and more - all provided by Nuxt UI for interactive documentation.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-search
  ---
  #title
  History

  #description
  Full-text search with ContentSearch component. No need for Algolia - instant, relevant results with keyboard shortcuts (⌘K).
  :::

  :::u-page-feature
  ---
  icon: i-lucide-navigation
  ---
  #title
  Authors

  #description
  Auto-generated navigation with ContentNavigation and ContentToc components. Sticky table of contents and prev/next links.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-moon
  ---
  #title
  Thematic

  #description
  Automatic theme switching with smooth transitions. Respects system preferences and remembers user choice.
  :::
::

::u-page-section
---
class: dark:bg-neutral-950
---
#title
Discover together how to develop a biblical paradigm

#links
  :::u-button
  ---
  color: neutral
  size: lg
  target: _blank
  to: https://content.nuxt.com/docs/getting-started/installation
  trailingIcon: i-lucide-arrow-right
  variant: subtle
  ---
  Discover together
  :::

#features
  :::u-page-feature
  ---
  icon: i-simple-icons-markdown
  ---
  #title
  Workshops

  #description
  Write in Markdown while embedding Vue components. Seamlessly integrate interactive elements in your content.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-file-text
  ---
  #title
  Reading plans

  #description
  Organize content in folders and files. Your documentation structure automatically becomes your navigation.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-code
  ---
  #title
  Character studies

  #description
  Beautiful code blocks with language detection, line numbers, and copy buttons. Support for 100+ languages.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-database
  ---
  #title
  Dramatisation

  #description
  Query your content with a MongoDB-like API. Filter, sort, and search through your documentation programmatically.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-file-code
  ---
  #title
  Thematic patterns

  #description
  Add metadata to your content files. Define SEO tags, navigation properties, and custom fields.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-git-branch
  ---
  #title
  Radical application

  #description
  Content lives in your repository. Branch, review, and deploy documentation alongside your code.
  :::
::
