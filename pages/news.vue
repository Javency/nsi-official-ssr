<template>
    <div class="news-com">
        <h4>this is news page</h4>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque laudantium laborum doloribus quam! Aperiam odio ipsam ratione et facilis ut rerum fuga iusto, voluptate provident incidunt reiciendis dolorum minus totam!</p>
        <nuxt-link class="button--grey" to="/" tag="a">返回</nuxt-link>
    </div>
</template>

<script>
export default {
    head () {
    return {
        title: '新学说新闻',
        meta: [
            { hid: 'description', name: 'description', content: '新闻新闻新闻新闻新闻新闻新闻新闻新闻新闻新闻新闻新学说国际学校，国际学校，国际学校新闻' },
            { hid: 'keywords', name: 'keywords ', content: '新学说,新学说传媒,国际学校,国际学校数据库,国际学校大全,国际学校四库全书,学校数据库,国际教育，教育公司，教育活动，教育资讯，国际教育资讯，国际教育研究，国际学校内参，新荷学校，国际教育研究院，国际教育咨询，国际学校发展大会，国际学校指南' }
        ]
    }
  }
}
</script>

<style lang="scss">
    .news-com{
        padding: 30px;
        text-align: center;
        a{
            display: inline-block;
            margin-top: 30px;
        }
    }
</style>
