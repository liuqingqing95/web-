# npm安装插件包后导入插件js及css

> package.json

```json
    "dependencies": {
      "jointjs": "^2.0.1",
      "vue": "^2.5.2",
      "vue-router": "^3.0.1"
    }
```

> index.vue

```vue
<script>
import joint from 'jointjs'
</script>
<style>
	@import 'jointjs/dist/joint.css'; 
</style>
```