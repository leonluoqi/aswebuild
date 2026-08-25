---
layout: home                 # 使用 Minimal Mistakes 的主页布局
title: "北美小生意经"
author_profile: true         # 显示作者简介（可选）
pagination:
  enabled: true
paginate: 10                 # 每页显示10篇文章
paginate_path: "/page:num/"  # 分页路径
---


<!-- 首页紧凑订阅栏（电脑端单行自适应，手机端自动折行） -->
<div style="margin: 0.5em 0 1.8em 0; padding: 0.8em 1.2em; background: #f8f9fa; border: 1px solid #e5e7eb; border-left: 4px solid #000000; border-radius: 6px; display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 12px;">
  <div style="font-size: 0.9em; font-weight: 600; color: #111827;">
    <span>订阅 As We Build 商业笔记</span>
    <span style="font-size: 0.85em; font-weight: 400; color: #6b7280; margin-left: 4px;">（最新北美案例推送）</span>
  </div>
  
  <form action="https://submit-form.com/kxienKoQo" method="POST" style="display: flex; gap: 8px; margin: 0; flex: 1; min-width: 240px; max-width: 380px;">
    <!-- Formspark 防垃圾蜜罐 -->
    <input type="checkbox" name="_honey" style="display:none" tabindex="-1" autocomplete="off" />
    
    <!-- 邮箱输入框 -->
    <input type="email" name="email" placeholder="输入常用邮箱..." required 
           style="flex: 1; padding: 6px 12px; background: #ffffff; border: 1px solid #d1d5db; border-radius: 4px; font-size: 0.88em; color: #111827; outline: none;" />
    
    <!-- #ff6600 橙色按钮 -->
    <button type="submit" 
            style="padding: 6px 16px; background-color: #ff6600; color: #ffffff; font-weight: 600; font-size: 0.88em; border: none; border-radius: 4px; cursor: pointer; white-space: nowrap; transition: opacity 0.2s;"
            onmouseover="this.style.opacity='0.85'" onmouseout="this.style.opacity='1'">
      订阅
    </button>
  </form>
</div>