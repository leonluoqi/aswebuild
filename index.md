---
layout: home                 # 使用 Minimal Mistakes 的主页布局
author_profile: true         # 显示左侧菜单栏
pagination:
  enabled: true
paginate: 10                 # 每页显示10篇文章
paginate_path: "/page:num/"  # 分页路径
---

<style>
  /* 1. 彻底去掉顶部的 AsWeBuild 默认大标题与“最新文章”副标题 */
  #page-title,
  .archive > .page__title,
  .archive__subtitle {
    display: none !important;
  }

  /* 2. 整体位置上提：消除主容器与顶部导航栏之间的多余空白 */
  #main {
    margin-top: 1rem !important;
    padding-top: 0 !important;
  }
  .archive {
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  /* 3. 桌面与平板端：收紧文章列表间距，消除分割线上下的大段空洞 */
  .entries-list,
  .list__item {
    margin: 0 !important;
    padding: 0 !important;
  }

  .list__item .archive__item {
    margin: 0 !important;
    padding: 15px 6px !important; /* 控制每篇文章上下紧凑间距 */
    border-bottom: 1px solid #DCDCD6 !important;
    transition: background-color 0.15s ease;
  }

  .list__item .archive__item:hover {
    background-color: rgba(20, 20, 19, 0.025) !important; /* 鼠标悬停微弱高亮，视线更清晰 */
  }

  /* 文章标题：去除默认顶部空白，字号适中、深墨色突出 */
  .list__item .archive__item-title {
    margin: 0 0 5px 0 !important;
    padding: 0 !important;
    font-family: "Songti SC", "STSong", "Source Han Serif SC", Georgia, serif !important;
    font-size: 19px !important;
    font-weight: 600 !important;
    line-height: 1.38 !important;
    color: #141413 !important;
  }

  .list__item .archive__item-title a {
    color: #141413 !important;
    text-decoration: none !important;
  }

  .list__item .archive__item-title a:hover {
    color: #555550 !important;
  }

  /* 文章摘要：彻底清除底部撑开间距的 margin，颜色设为中深灰与标题拉开层次 */
  .list__item .archive__item-excerpt,
  .list__item .archive__item-excerpt p {
    margin: 0 !important;
    padding: 0 !important;
    font-family: -apple-system, BlinkMacSystemFont, "PingFang SC", "Microsoft YaHei", sans-serif !important;
    font-size: 14.5px !important;
    font-weight: 400 !important;
    line-height: 1.55 !important;
    color: #555552 !important;
    display: -webkit-box;
    -webkit-line-clamp: 2; /* 最多显示2行，保持列表整齐划一 */
    -webkit-box-orient: vertical;
    overflow: hidden;
  }
</style>

<!-- 首页顶部单行刊头：整体上提，与左侧边栏顶部齐平 -->
<div style="margin: 0 0 4px 0; padding: 0 0 12px 0; border-bottom: 1.5px solid #141413; display: flex; align-items: center; justify-content: space-between; gap: 16px; flex-wrap: wrap;">
  
  <!-- 左侧：主标题 -->
  <span style="font-family: 'Songti SC', 'STSong', 'Source Han Serif SC', Georgia, serif; font-size: 23px; font-weight: 600; color: #141413; letter-spacing: 0.02em; line-height: 1.2;">
    北美小生意经
  </span>

  <!-- 右侧：紧凑单行订阅框 -->
  <form action="https://submit-form.com/kxienKoQo" method="POST" style="display: flex; align-items: center; gap: 8px; margin: 0; padding: 0; background: transparent; border: none; box-shadow: none;">
    <span style="font-size: 14px; font-weight: 500; color: #222; white-space: nowrap;">
      欢迎阅读
    </span>

    <input type="checkbox" name="_honey" style="display:none" tabindex="-1" autocomplete="off" />
    
    <input type="email" name="email" placeholder="输入常用邮箱..." required 
           style="width: 190px; height: 32px; margin: 0; padding: 0 10px; background: #ffffff; border: 1px solid #BDBDB8; border-radius: 2px; font-size: 13.5px; color: #111; outline: none; box-sizing: border-box;" />
    
    <button type="submit" 
            style="height: 32px; margin: 0; padding: 0 14px; background-color: #141413; color: #ffffff; font-weight: 500; font-size: 13.5px; border: none; border-radius: 2px; cursor: pointer; white-space: nowrap; box-sizing: border-box;">
      订阅
    </button>
  </form>

</div>