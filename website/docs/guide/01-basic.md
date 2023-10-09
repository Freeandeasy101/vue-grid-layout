# 01 - Basic 
"In the source code, I have discovered a function called cloneLayoutItem. I noticed that this function is repeatedly called and uses JSON.parse(JSON.stringify()) when resizing. It doesn't have much impact on memory usage when dealing with small data, but when the data size becomes large, the memory usage becomes unpredictable. I kindly request the author to consider optimizing this aspect."
[View source](https://github.com/jbaysolutions/vue-grid-layout/blob/master/website/docs/.vuepress/components/Example01Basic.vue)

<ClientOnly>
<Example01Basic></Example01Basic>
</ClientOnly>

