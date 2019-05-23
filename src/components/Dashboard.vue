<template>
  <el-row class="warp">
    <el-col :span="24" class="warp-breadcrum">
      <el-breadcrumb separator="/">
        <el-breadcrumb-item :to="{ path: '/' }"><b>个人网页</b></el-breadcrumb-item>
      </el-breadcrumb>
    </el-col>
    <el-col>
      <template>
        <el-carousel indicator-position="outside">
          <el-carousel-item>
            <img src="../assets/images/1.jpg" class="image">
          </el-carousel-item>
          <el-carousel-item>
            <img src="../assets/images/2.jpg" class="image">
          </el-carousel-item>
          <el-carousel-item>
            <img src="../assets/images/3.jpg" class="image">
          </el-carousel-item>
          <el-carousel-item>
            <img src="../assets/images/4.jpg" class="image">
          </el-carousel-item>
        </el-carousel>
      </template>
    </el-col>
    <el-col :span="24" class="warp-main">
      <section class="chart-container">
        <el-row>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/forest.png" class="image">
              <div style="padding: 14px;text-align: center">
                  <div>作品：深林</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/sunrise.png" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：大海</div>
              </div>
            </el-card>
          </el-col>

          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/sunshine.png" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：天空</div>
              </div>
            </el-card>
          </el-col>

          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/1.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：瀑布</div>
              </div>
            </el-card>
          </el-col>

          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/2.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：动物园</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/3.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：小湖</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/4.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：秋天</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/5.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：瀑布</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/6.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：小湖</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/10.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：大湖</div>
              </div>
            </el-card>
          </el-col>

          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/8.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：黄山</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/9.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：动物园</div>
              </div>
            </el-card>
          </el-col>




          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/14.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：划船</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/15.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：花</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/11.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：夜路</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/7.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：星空</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/12.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：喷泉</div>
              </div>
            </el-card>
          </el-col>
          <el-col :span="8">
            <el-card :body-style="{ padding: '0px' }">
              <img src="../assets/images/13.jpg" class="image">
              <div style="padding: 14px;text-align: center">
                <div>作品：草原</div>
              </div>
            </el-card>
          </el-col>
        </el-row>
      </section>

    </el-col>
  </el-row>
</template>
<style>

  .image {
    width: 100%;
    display: block;
  }
  .chart-container {
    width: 100%;
  }
  .chart-container .el-col {
    padding: 30px 20px;
  }
</style>

<script>
  export default {
  }
</script>
<style>
  el-card{
    float: right;
  }
  .el-carousel__item h3 {
    color: #475669;
    font-size: 18px;
    opacity: 0.75;
    line-height: 300px;
    margin: 0;
  }
</style>
