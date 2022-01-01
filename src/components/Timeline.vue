<script setup lang="ts">
</script>

  <template>
  <el-image
    style="border-radius: 50%; width: 100px; height: 100px"
    :src="srcOne"
  ></el-image>
  <el-timeline>
    <el-timeline-item timestamp="2018/4/12" placement="top" color="#ff715b">
      <el-card>
        <h4>Update Github template</h4>
        <p>Tom committed 2018/4/12 20:46</p>
      </el-card>
    </el-timeline-item>
    <el-timeline-item timestamp="2018/4/3" placement="top" color="#ff715b">
      <el-card>
        <h4>Update Github template</h4>
        <p>Tom committed 2018/4/3 20:46</p>
      </el-card>
    </el-timeline-item>
    <el-timeline-item timestamp="2018/4/2" placement="top" color="#ff715b">
      <el-card>
        <h4>Update Github template</h4>
        <p>Tom committed 2018/4/2 20:46</p>
      </el-card>
    </el-timeline-item>
  </el-timeline>
  <el-image
    style="border-radius: 50%; width: 100px; height: 100px"
    :src="srcTwo"
  ></el-image>
</template>
<script lang="ts" setup>
const srcOne = "../src/assets/image/chrPortrett2.jpg";
const srcTwo = "../src/assets/image/cecilieliten.jpg";
</script>
<style scoped>
.el-timeline {
  padding-left: 0;
  padding-top: 20px;
}
.el-image {
  border: 5px solid #ff715b;
}
.el-card {
  /*background-color: #462255;*/
  background-color: white;
}
.el-timeline-element {
  background-color: #ff715b;
}
</style>
