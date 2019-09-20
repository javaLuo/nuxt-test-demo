# nuxt-test-demo
测试nuxt2.9.x,疑似有个小BUG

<hr/>

在`nuxt.config.js`中设置了allChunks后
```
  build:{
    extractCSS: {allChunks: true}
  }
```
每次`yarn build` 生成的文件hash都不一样