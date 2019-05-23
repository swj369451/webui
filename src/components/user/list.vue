<template>
  <div>
    <el-row>
      <el-col :span="24">
        <div class="grid-content bg-purple-dark">
          <div id="back"></div>
        </div>
      </el-col>
    </el-row>
    <el-row>
      <el-col :span="4"><div class="grid-content bg-purple"><h3>姓名</h3></div></el-col>
      <el-col :span="8"><div class="grid-content bg-purple-light"><h3>苏敏</h3></div></el-col>
      <el-col :span="4"><div class="grid-content bg-purple"><h3>性别</h3></div></el-col>
      <el-col :span="8"><div class="grid-content bg-purple-light"><h3>男</h3></div></el-col>
    </el-row>
    <el-row>
      <el-col :span="4"><div class="grid-content bg-purple"><h3>学历</h3></div></el-col>
      <el-col :span="8"><div class="grid-content bg-purple-light"><h3>本科</h3></div></el-col>
      <el-col :span="4"><div class="grid-content bg-purple"><h3>学历</h3></div></el-col>
      <el-col :span="8"><div class="grid-content bg-purple-light"><h3>本科</h3></div></el-col>
    </el-row>

    <el-row>
      <el-col :span="4"><div class="grid-content bg-purple"><h3>技能与特长</h3></div></el-col><br/>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple"><h3>技能与特长XXXX'xX</h3></div></el-col>
    </el-row>

    <el-row>
      <el-col :span="4"><div class="grid-content bg-purple"><h3>工作经验</h3></div></el-col><br/>
    </el-row>
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple"><h3>技能与特长XXXX'xX</h3></div></el-col>
    </el-row>
  </div>
</template>

<script>
  import API from '../../api/api_user';

  export default {
    data() {
      return {
        filters: {
          name: ''
        },
        users: [
          {
            name: '张三',
            nickname: '小张',
            sex: '男',
            email: '1111@qq.com',
            addr: '厦门'
          }
        ],
        total: 0,
        page: 1,
        limit: 10,

      }
    }
  }
</script>

<style scoped>
  #back{
    width: 200px;
    height: 200px;
    background-color: #00C1DE;
    border-radius: 100px;
    margin: 0 auto;
  }
  .bg-purple-dark {
    background: #fff;
    height: 200px;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 36px;
    text-align: center;
  }
</style>
