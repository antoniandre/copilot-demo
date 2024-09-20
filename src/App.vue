<script setup>
</script>

<template lang="pug">
.top-bar
  .logo
  nav
    ul
      li
        a Product
      li
        a Solutions
      li
        a Resources
      li
        a Open Source
      li
        a Enterprise
      li
        a Pricing

header
  section.section.section--hero
    .pill.pill--rainbow Copilot Enterprise now available
    h1 The world’s most widely adopted AI developer tool.
    video(
      autoplay=""
      playsinline=""
      muted=""
      width="1248"
      height="735"
      poster="https://github.githubassets.com/assets/hero-poster-18f705106687.webp")
      source(src="https://github.githubassets.com/assets/hero-lg-6a98e47708e8.mp4"
      type="video/mp4; codecs=avc1.4d002a")

main
  section.section.section--enterprise-ready
    .pill Enterprise Grade
    h2 The competitive advantage developers ask for by name.

  section.section.section--industry-standard
    h2 The Industry Standard.
    .head
    .boxes.flex
      .box
        .headline 77,000+
        .subheader Businesses have adopted GitHub Copilot
      .box
        .headline 1 in 3
        .subheader Fortune 500 companies use GitHub Copilot
        p.caption Available for business since Dec 2022
      .box
        .headline 55%
        .subheader Developer preference for GitHub Copilot
        p.caption Stack Overflow 2023 Survey

    .box.box--quote
      p.quote Personalized, natural language recommendations are now at the fingertips of all our developers at Figma. Our engineers are coding faster, collaborating more effectively, and building better outcomes.
      .author
        .author__name Tommy MacWilliam
        .author__position Engineering Manager for Infrastructure @ Figma

  section.section.section--features-focus
    .pill Features
    h2 The AI coding assistant elevating developer workflows.
    video(
      playsinline=""
      preload="none"
      poster="https://github.com/images/modules/site/copilot/features-breakout-poster.webp"
      width="1248"
      height="647")
      source(src="https://github.com/images/modules/site/copilot/features-breakout.mp4" type="video/mp4; codecs=avc1.4d002a")

  section.section.section--pricing
    .pill Pricing
    h2 Take flight with GitHub Copilot.

  section.section.section--features-table
    h2 Features Table

  section.section.section--help
    .box
      h2 Need human help?
      p.caption Let’s define how to propel your team into a new era.
      button.cta Contact Sales

  section.section.section--related
    h2 Get the most out of GitHub Copilot.

    .boxes.flex
      .box
        .subheader.white Hands-on consulting, guided workshops, and training.
        .caption Insights, best practices, and knowledge to help you adopt GitHub quickly and efficiently.
        button.cta.cta--link.mta Explore GitHub Expert Services

      .box
        .subheader.white Meet the companies who build with GitHub.
        .caption Leading organizations choose GitHub to plan, build, secure and ship software.
        button.cta.cta--link.mta Read customer stories

      .box
        .subheader.white Keep up with the latest on GitHub and trends in AI.
        .caption Check out the GitHub blog for tips, technical guides, best practices, and more.
        button.cta.cta--link.mta Read blog

  section.section.section--faq
    h2 FAQ

footer
  .logo Github
  nav.menu Menu

  p.white Subscribe to our developer newsletter
  .caption Get tips, technical guides, and best practices. Twice a month. Right in your inbox.
  button.cta Subscribe
</template>

<style scoped>

</style>
