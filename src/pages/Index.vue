<template>
  <q-page>
    <q-parallax src="~assets/banner.jpg" :height="512">
      <h2 class="text-white shadow-text text-center">大安一中2018级1班</h2>
    </q-parallax>
    <div class="row justify-center">
      <div class="col-xs-10 col-md-8">
        <q-timeline color="secondary">
          <q-timeline-entry heading>
            大事记
          </q-timeline-entry>

          <q-timeline-entry title="参加高考" subtitle="2021年6月7日">
            <div>
              哦吼，奔赴战场，冲鸭!
            </div>
          </q-timeline-entry>

          <q-timeline-entry title="毕业典礼" subtitle="2021年6月4日">
          </q-timeline-entry>

          <q-timeline-entry title="举办了毕业班会" subtitle="2021年6月3日">
            <div>
              <q-img
                style="max-width: 300px"
                src="https://z3.ax1x.com/2021/06/03/28pw01.jpg"
              >
              </q-img>
            </div>
          </q-timeline-entry>

          <q-timeline-entry title="回学校了" subtitle="2021年2月">
            <div>好在疫情不太严重，网课并没有持续太久</div>
          </q-timeline-entry>

          <q-timeline-entry title="重回网课" subtitle="2021年1月">
            <div>没想到上网课的时光又回来了</div>
          </q-timeline-entry>

          <q-timeline-entry title="回学校了" subtitle="2020年6月">
            <div>
              在家里宅了快半年后，我们终于回到了学校。不过每个人都要带一个口罩。
            </div>
          </q-timeline-entry>

          <q-timeline-entry title="上网课" subtitle="2020年2月">
            <div>
              那场突如其来的疫情打破了往常的平静，为了疫情不扩散，所有人都待在家里上网课。
            </div>
          </q-timeline-entry>

          <q-timeline-entry title="研学旅行" subtitle="2019年8月">
            <div>
              这一次研学旅行，蛮新鲜的。难忘的时光又多了一段！
            </div>
            <q-img
              style="max-width: 300px"
              src="https://z3.ax1x.com/2021/06/03/28CjYV.jpg"
            >
            </q-img>
          </q-timeline-entry>

          <q-timeline-entry title="新班主任" subtitle="2019年8月">
            <div>
              张老师成为了我们的新班主任。
            </div>
          </q-timeline-entry>

          <q-timeline-entry title="初来一中" subtitle="2018年8月10日">
          </q-timeline-entry>
        </q-timeline>
      </div>
    </div>
    <div class="text-center text-h3">我们的老师</div>
    <div class="row justify-center" style="margin-top:32px">
      <div class="col-xs-8 col-sm-6 col-md-4 col-lg-3">
        <q-card class="my-card">
          <q-img height="300px" src="../assets/zhanghaijia.jpg" />
          <q-card-section>
            <div class="text-h4">
              张海佳老师 <q-badge align="top">班主任</q-badge>
            </div>
            <div class="text-subtitle2">化学</div>
          </q-card-section>
        </q-card>
      </div>
      <div class="col-xs-8 col-sm-6 col-md-4 col-lg-3">
        <q-card class="my-card">
          <q-img height="300px" src="../assets/chengyi.jpg" />
          <q-card-section>
            <div class="text-h4">
              程毅老师
            </div>
            <div class="text-subtitle2">物理</div>
          </q-card-section>
        </q-card>
      </div>
      <div class="col-xs-8 col-sm-6 col-md-4 col-lg-3">
        <q-card class="my-card">
          <q-img height="300px" src="../assets/dingyuefu.jpg" />
          <q-card-section>
            <div class="text-h4">
              丁跃富老师
            </div>
            <div class="text-subtitle2">生物</div>
          </q-card-section>
        </q-card>
      </div>
      <div class="col-xs-8 col-sm-6 col-md-4 col-lg-3">
        <q-card class="my-card">
          <q-img height="300px" src="../assets/yeshuhe.jpg" />
          <q-card-section>
            <div class="text-h4">
              叶树和老师
            </div>
            <div class="text-subtitle2">数学</div>
          </q-card-section>
        </q-card>
      </div>
      <div class="col-xs-8 col-sm-6 col-md-4 col-lg-3">
        <q-card class="my-card">
          <q-img height="300px" src="../assets/zhoucuifeng.jpg" />
          <q-card-section>
            <div class="text-h4">
              周翠峰老师
            </div>
            <div class="text-subtitle2">英语</div>
          </q-card-section>
        </q-card>
      </div>
      <div class="col-xs-8 col-sm-6 col-md-4 col-lg-3">
        <q-card class="my-card">
          <q-img height="300px" src="../assets/liuyanmei.jpg" />
          <q-card-section>
            <div class="text-h4">
              刘艳梅老师
            </div>
            <div class="text-subtitle2">语文</div>
          </q-card-section>
        </q-card>
      </div>
    </div>
  </q-page>
</template>

<script>
export default {
  name: "PageIndex"
};
</script>
<style scoped>
.shadow-text {
  text-shadow: 4px 4px black;
}
.my-card {
  margin: 8px;
}
</style>
