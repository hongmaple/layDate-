# layDate-
layDate 是 layui 独立维护的三大组件之一 、用于对日期的操作
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>使用 layDate 独立版</title>
</head>
<body>
<input type="text" id="test1">
<script src="/laydate/laydate.js"></script> <!-- 改成你的路径 -->
<script>
//执行一个laydate实例
laydate.render({
  elem: '#test1' //指定元素
});
</script>
</body>
</html>
