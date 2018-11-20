<template>
  <div>
    <Row>
      <Col>
        <img class="qq-group-img" :src="qqFans" alt="">
      </Col>
    </Row>
  </div>
</template>
<script>
import qqFans from '@/assets/images/qq-group1.jpg'
export default {
  name: 'hello',
  data () {
    return {
      msg: 'world'
    }
  }
}
</script>
