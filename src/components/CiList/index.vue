<template>
  <div class="cinema_body">
    <ul>
      <li>
        <div>
          <span>万达影院（群星城店）</span>
          <span class="q"><span class="price"> 38.5</span> 元起</span>
        </div>
        <div class="address">
          <span>徐东大街群星城5楼</span>
          <span> 2.5km </span>
        </div>
        <div class="card">
          <div>优惠</div>
          <div>折扣卡</div>
        </div>
      </li>
      <li>
        <div>
          <span>金逸影城（销品茂店）</span>
          <span class="q"><span class="price"> 37.5</span> 元起</span>
        </div>
        <div class="address">
          <span>徐东大街小销品茂五楼</span>
          <span> 1.5km</span>
        </div>
        <div class="card">
          <div>优惠</div>
          <div>折扣卡</div>
        </div>
      </li>
      <li>
        <div>
          <span>巨幕影城（绿地中心店）</span>
          <span class="q"><span class="price"> 37.9</span> 元起</span>
        </div>
        <div class="address">
          <span>武昌区绿地缤纷城6楼</span>
          <span> 900m </span>
        </div>
        <div class="card">
          <div>优惠</div>
          <div>折扣卡</div>
        </div>
      </li>
      <li>
        <div>
          <span>C+影城（漫时区）</span>
          <span class="q"><span class="price"> 30.9</span> 元起</span>
        </div>
        <div class="address">
          <span>漫时区三号楼</span>
          <span> 900m </span>
        </div>
        <div class="card">
          <div>优惠</div>
          <div>折扣卡</div>
        </div>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: "CiList",
};
</script>
<style scoped>
#content .cinema_body {
  flex: 1;
  overflow: auto;
}
.cinema_body ul {
  padding: 20px;
}
.cinema_body li {
  border-bottom: 1px solid #e6e6e6;
  margin-bottom: 20px;
}
.cinema_body div {
  margin-bottom: 10px;
}
.cinema_body .q {
  font-size: 11px;
  color: #f03d37;
}
.cinema_body .price {
  font-size: 18px;
}
.cinema_body .address {
  font-size: 13px;
  color: #666;
}
.cinema_body .address span:nth-of-type(2) {
  float: right;
}
.cinema_body .card {
  display: flex;
}
.cinema_body .card div {
  padding: 0 3px;
  height: 15px;
  line-height: 15px;
  border-radius: 2px;
  color: #f90;
  border: 1px solid #f90;
}
.cinema_body .card div.or {
  color: #f90;
  border: 1px solid #f90;
}
.cinema_body .card div.bl {
  color: #589daf;
  border: 1px solid #589daf;
}
</style>
