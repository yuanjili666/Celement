<template>
  <div style="margin: 20px;">
    <el-input v-model="input" placeholder="请输入内容"></el-input>

    <div class="block">
      <span class="demonstration">折叠展示Tag</span>
      <el-cascader
        :options="options"
        ref="elCascaderRef"
        v-model="state"
        :props="props"
        collapse-tags
        clearable
        filterable
      ></el-cascader>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      input: "Hello Element UI!",
      state:[[1,2]],
      props: { 
        multiple: true,
        // checkStrictly: true 
       },
      options: [
        {
          value: 1,
          label: "东南",
          children: [
            {
              value: 2,
              label: "上海",
              children: [
                { value: 3, label: "普陀" },
                { value: 4, label: "黄埔" },
                { value: 5, label: "徐汇" },
              ],
            },
            {
              value: 7,
              label: "江苏",
              children: [
                { value: 8, label: "南京" },
                { value: 9, label: "苏州" },
                { value: 10, label: "无锡" },
              ],
            },
            {
              value: 12,
              label: "浙江",
              children: [
                { value: 13, label: "杭州" },
                { value: 14, label: "宁波" },
                { value: 15, label: "嘉兴" },
              ],
            },
          ],
        },
        {
          value: 17,
          label: "西北",
          children: [
            {
              value: 18,
              label: "陕西",
              children: [
                { value: 19, label: "西安" },
                { value: 20, label: "延安" },
              ],
            },
            {
              value: 21,
              label: "新疆维吾尔族自治区",
              children: [
                { value: 22, label: "乌鲁木齐" },
                { value: 23, label: "克拉玛依" },
              ],
            },
          ],
        },
      ],
    };
  },
  watch: {
    state: {
      handler(newVal, oldVal) {
        console.log("oldVal:", oldVal);
        console.log("newVal:", newVal);
      },
      // 立即处理 进入页面就触发
      immediate: true,
      // 深度监听 属性的变化
      deep: true,
    },
  },
  mounted() {
    // handleMultiCheckChange
    console.log(this.$refs.elCascaderRef,'elCascaderRef')
    console.log(this.$refs.elCascaderRef.handleMultiCheckChange,'handleMultiCheckChange')
  }
};
</script>
