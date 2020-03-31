<template>
  <div class="Project">
    <h1>{{ msg }}</h1>
    <p>
      제품/장치 관리 시스템 프론트엔드 화면<br>

    </p>
    <h3>1.SK브로드밴드 부품관리 시스템</h3>
    <ul>
      <li><a href="http://www.uxmatrix.org/project/sk_dims_mobile/home.html" target="_blank" rel="noopener">로그인</a></li>      
      <li><a href="http://uxmatrix.org/project/sk_dims/regist_accessories.php" target="_blank" rel="noopener">데이터 리스트</a></li>
      <li><a href="http://uxmatrix.org/project/sk_dims/status_bad.php" target="_blank" rel="noopener">검색조건 설정</a></li>
    </ul>
    <h3>2.세아제강 출고관리 시스템</h3>
    <ul>
      <li><a href="http://www.uxmatrix.org/project/seah/main.html" target="_blank" rel="noopener">로그인</a></li>
      <li><a href="http://www.uxmatrix.org/project/seah/sub.html" target="_blank" rel="noopener">데이터 리스트</a></li>
    </ul>

    <h3>3.파밍온 IoT장치관리 시스템</h3>
    <ul>
      <li><a href="http://www.uxmatrix.org/project/farmingon/admin/login.html" target="_blank" rel="noopener">로그인</a></li>
      <li><a href="http://www.uxmatrix.org/project/farmingon/admin/sub_08.php" target="_blank" rel="noopener">장치 리스트</a></li>
    </ul>

    <h3>4.나솔시스템 스마트필터/스캐너 서비스</h3>
    <ul>
      <li><a href="http://uxmatrix.org/project/nasol_filter_201704/login.html" target="_blank" rel="noopener">로그인</a></li>
      <li><a href="http://uxmatrix.org/project/nasol_filter_201704/main.html" target="_blank" rel="noopener">데시보드_필터</a></li>
      <li><a href="http://www.uxmatrix.org/project/nasol_scanner/main_01_03.html" target="_blank" rel="noopener">데시보드_스캐너</a></li>      
      <li><a href="http://uxmatrix.org/project/nasol_filter_201704/sub2_2.html" target="_blank" rel="noopener">필터링 정보</a></li>
      <li><a href="http://uxmatrix.org/project/nasol_filter_201704/sub3_1.html" target="_blank" rel="noopener">데이터 통계</a></li>      

    </ul>
  </div>
</template>

<script>
export default {
  name: 'ProjectList',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
  color:dodgerblue;
}
</style>
