<script setup> 

</script>

<template>
  <div class="section header">
    <div class="message">
    <h1>个人简历</h1>
    <p>姓名：罗浩然</p>
    <p>意向岗位：前端开发工程师 | 武汉</p>
    <p>邮箱：xxx@qq.com | GitHub：<a href="https://github.com/xxx" target="_blank">github.com/xxx</a></p>
    <a href="/resume.pdf" class="btn" download>下载PDF简历</a>
    </div>
    <div class="photo">
    <img src="C:\Users\AA\Desktop\新建文件夹\personresume\public\avator\D0C8518356D5A8353F18395150FBE003.jpg" alt="头像" width="150" height="150">

</div>
</div>
  
    
</template>

<style scoped>
.header {
  text-align: center;
  display: flex;
  justify-content: space-between;
}
</style>


<style scoped> 

.base {
    display: flex;
    gap: 10px;
    margin-top: 10px;
    flex-wrap: wrap;
    align-items: center;
}
.base div {
  margin-top: 5px;
}
.base img {
    margin-left: 40px;
    border-radius: 5%;
}
.base{
    margin-left: 10%;
}
.header .message{
    flex:6;
}
</style>