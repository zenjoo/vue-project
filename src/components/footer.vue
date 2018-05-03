<template>
  <div class="footer">
    <!--<div class="top-section">-->
      <!--<div>x</div>-->
      <!--<div>专业P2P测评，为您的网贷理财保驾护航</div>-->
      <!--<div>...</div>-->
    <!--</div>-->
        <div>
          首页
          <i class="el-icon-edit"></i>
        </div>
        <div>
          示范
          <i class="el-icon-news"></i>
        </div>
        <div>
          评级
          <i class="el-icon-success"></i>
        </div>
        <div>
          舆情
          <i class="el-icon-bell"></i>
        </div>
        <div>
          我的
          <i class="el-icon-service"></i>
        </div>
      </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.footer{
  font-size: 14px;
  width: 100%;
  height: .5rem;
  background: #ddd;
  display: flex;
  >div{
    display: flex;
    align-items: center;
  }
}

</style>
