<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        nsi-official-ssr
      </h1>
      <h2 class="subtitle">
        Nuxt.js project
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
           <nuxt-link to="/news"  class="button--grey">新闻头条</nuxt-link>
      </div>
      <!-- <div class="one">
          <p class="two">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam nobis magnam eum dignissimos corrupti tempora labore accusantium odit reiciendis dolore. Aut a quas repellendus odio, rerum est quod repudiandae eius.</p>
      </div> -->
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  },
   head () {
    return {
      title: '新学说官网',
      meta: [
        { hid: 'keywords', name: 'keywords ', content: '新学说,新学说传媒,国际学校,国际学校数据库,国际学校大全,国际学校四库全书,学校数据库,国际教育，教育公司，教育活动，教育资讯，国际教育资讯，国际教育研究，国际学校内参，新荷学校，国际教育研究院，国际教育咨询，国际学校发展大会，国际学校指南' },
        { hid: 'description', name: 'description', content: '新学说,新学说传媒,国际学校,国际学校数据库,国际学校大全,国际学校四库全书,学校数据库,国际教育，教育公司，教育活动，教育资讯，国际教育资讯，国际教育研究，国际学校内参，新荷学校，国际教育研究院，国际教育咨询，国际学校发展大会，国际学校指南' }
      ]
    }
  }
}
</script>

<style lang="scss">
.one{
  .two{
    color: red;
  }
}
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

