---
layout: home                 # 使用 Minimal Mistakes 的主页布局
author_profile: true         # 显示左侧菜单栏
pagination:
  enabled: true
paginate: 10                 # 每页显示10篇文章
paginate_path: "/page:num/"  # 分页路径
---

<style>
  /* 强制隐藏主题自动生成的“最新文章”一行，紧缩顶部间距 */
  .archive__subtitle { display: none !important; }
  .archive .list__item:first-of-type .archive__item { padding-top: 1.1rem !important; }
</style>

<!-- 首页单行刊头：左标题 + 右订阅框 同行并排 -->
<div style="margin: 0 0 0.2em 0; padding-bottom: 0.75em; border-bottom: 1.5px solid #141413; display: flex; align-items: center; justify-content: space-between; gap: 16px; flex-wrap: wrap;">
  
  <!-- 左侧：刊物主标题 -->
  <span style="font-family: 'Songti SC', 'STSong', 'Source Han Serif SC', Georgia, serif; font-size: 1.45em; font-weight: 600; color: #141413; letter-spacing: 0.03em; line-height: 1.2;">
    北美小生意经
  </span>

  <!-- 右侧：紧凑单行订阅框 -->
  <form action="https://submit-form.com/kxienKoQo" method="POST" style="display: flex; align-items: center; gap: 8px; margin: 0; padding: 0; background: transparent; border: none; box-shadow: none;">
    <span style="font-size: 0.9em; font-weight: 500; color: #222; white-space: nowrap;">
      欢迎阅读
    </span>

    <!-- Formspark 防垃圾蜜罐 -->
    <input type="checkbox" name="_honey" style="display:none" tabindex="-1" autocomplete="off" />
    
    <!-- 紧凑输入框 -->
    <input type="email" name="email" placeholder="输入常用邮箱..." required 
           style="width: 190px; height: 32px; margin: 0; padding: 0 10px; background: #ffffff; border: 1px solid #BDBDB8; border-radius: 2px; font-size: 13.5px; color: #111; outline: none; box-sizing: border-box;" />
    
    <!-- 订阅按钮（深墨黑刊物风；若想保留原来的橙色，把 #141413 改为 #ff6600 即可） -->
    <button type="submit" 
            style="height: 32px; margin: 0; padding: 0 14px; background-color: #141413; color: #ffffff; font-weight: 500; font-size: 13.5px; border: none; border-radius: 2px; cursor: pointer; white-space: nowrap; box-sizing: border-box;">
      订阅
    </button>
  </form>

</div>