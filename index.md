---
layout: home                 # 使用 Minimal Mistakes 的主页布局
title: "北美小生意经"
author_profile: true         # 显示作者简介（可选）
pagination:
  enabled: true
paginate: 10                 # 每页显示10篇文章
paginate_path: "/page:num/"  # 分页路径
---



<!-- 首页超窄单行极简订阅栏 -->
<div style="margin: 0.5em 0 1.6em 0; display: flex; align-items: center; gap: 12px; flex-wrap: wrap;">
  <span style="font-size: 0.9em; font-weight: 600; color: #222; white-space: nowrap; display: flex; align-items: center; gap: 4px;">
    📬 欢迎订阅
  </span>

  <form action="https://submit-form.com/kxienKoQo" method="POST" style="display: flex; align-items: center; gap: 6px; margin: 0; flex: 1; max-width: 360px;">
    <!-- Formspark 防垃圾蜜罐 -->
    <input type="checkbox" name="_honey" style="display:none" tabindex="-1" autocomplete="off" />
    
    <!-- 极窄输入框 -->
    <input type="email" name="email" placeholder="输入常用邮箱..." required 
           style="flex: 1; height: 32px; padding: 0 10px; background: #ffffff; border: 1px solid #d1d5db; border-radius: 4px; font-size: 0.85em; color: #111; outline: none; box-sizing: border-box;" />
    
    <!-- 紧凑橙色按钮 -->
    <button type="submit" 
            style="height: 32px; padding: 0 14px; background-color: #ff6600; color: #ffffff; font-weight: 600; font-size: 0.85em; border: none; border-radius: 4px; cursor: pointer; white-space: nowrap; box-sizing: border-box; transition: opacity 0.2s;"
            onmouseover="this.style.opacity='0.85'" onmouseout="this.style.opacity='1'">
      订阅
    </button>
  </form>
</div>