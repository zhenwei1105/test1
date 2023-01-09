## ref属性
1. 被用来给元素或子组件注册引用信息（id的替代者）
2. 应用在html标签上获取的是真实DOM元素，应用在组件标签上是组件实例对象（vc）
3. 使用方式：  
	打标识：`<h1 ref="xxx">....</h1>` 或 `<School ref="xxx"></School>`  
	获取：`this.$refs.xxx`