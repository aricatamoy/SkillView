# SkillView

<!-- 圆形遮罩容器，超出圆形的部分会被隐藏 -->
<div style="
  width: 200px;  /* 图标宽度 */
  height: 200px; /* 图标高度 */
  border-radius: 50%; /* 关键：将方形容器变成圆形 */
  overflow: hidden; /* 隐藏圆形外的内容 */
  margin: 0 auto; /* 居中显示（可选） */
">
  <!-- 放入需要被遮罩的图片 -->
  <img src="images/skill4.png" alt="技能图标" style="
    width: 100%;
    height: 100%;
    object-fit: cover; /* 保持图片比例，填满圆形 */
  ">
</div>