---
layout: single
title: "北美创业资源：合规与实战导航"
permalink: /resources/
author_profile: true
---

<style>
  .awb-res-intro {
    margin: 0 0 20px 0;
    padding: 0 0 16px 0;
    border-bottom: 1.5px solid #141413;
    font-size: 15px;
    color: #2C2B29;
    line-height: 1.65;
  }
  .awb-res-badge {
    display: inline-block;
    background: #8A2520;
    color: #FFFFFF;
    font-size: 11.5px;
    font-weight: 700;
    padding: 3px 10px;
    border-radius: 999px;
    letter-spacing: 0.04em;
    margin-bottom: 8px;
  }
  /* 顶部快速锚点导航 */
  .awb-quick-nav {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    background: #F8F7F3;
    border: 1.5px solid #141413;
    border-radius: 8px;
    padding: 12px 14px;
    margin-bottom: 28px;
  }
  .awb-quick-nav a {
    font-size: 12.5px;
    font-weight: 600;
    color: #141413 !important;
    text-decoration: none !important;
    background: #FFFFFF;
    border: 1px solid #D8D4CC;
    padding: 5px 11px;
    border-radius: 4px;
    transition: all 0.15s ease;
  }
  .awb-quick-nav a:hover {
    background: #8A2520;
    color: #FFFFFF !important;
    border-color: #8A2520;
  }
  /* 章节标题 */
  .awb-sec-title {
    margin: 42px 0 16px 0;
    padding-bottom: 8px;
    border-bottom: 2px solid #8A2520;
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 8px;
  }
  .awb-sec-title h2 {
    font-size: 20px;
    font-weight: 800;
    color: #141413;
    margin: 0;
  }
  .awb-sec-title span {
    font-size: 12.5px;
    color: #6E6E6A;
  }
  /* 交互式计算器容器 */
  .awb-calc-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin-bottom: 32px;
  }
  .awb-calc-box {
    background: #F8F7F3;
    border: 2px solid #141413;
    border-radius: 8px;
    padding: 20px;
  }
  .awb-calc-box h3 {
    font-size: 16.5px;
    font-weight: 800;
    color: #141413;
    margin: 0 0 12px 0;
    padding-bottom: 8px;
    border-bottom: 1px solid #D8D4CC;
  }
  .awb-form-row {
    margin-bottom: 12px;
  }
  .awb-form-row label {
    display: block;
    font-size: 12.5px;
    font-weight: 700;
    color: #2C2B29;
    margin-bottom: 4px;
  }
  .awb-form-row select,
  .awb-form-row input {
    width: 100%;
    height: 36px;
    padding: 0 10px;
    background: #FFFFFF;
    border: 1px solid #141413;
    border-radius: 4px;
    font-size: 13.5px;
    color: #141413;
    box-sizing: border-box;
  }
  .awb-calc-result {
    background: #FFFFFF;
    border-left: 4px solid #8A2520;
    border-top: 1px solid #D8D4CC;
    border-right: 1px solid #D8D4CC;
    border-bottom: 1px solid #D8D4CC;
    padding: 12px 14px;
    border-radius: 0 4px 4px 0;
    margin-top: 14px;
    font-size: 13px;
    line-height: 1.6;
    color: #141413;
  }
  /* 知识卡片网格 */
  .awb-res-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(290px, 1fr));
    gap: 20px;
    margin-bottom: 16px;
  }
  .awb-res-card {
    background: #F8F7F3;
    border: 1.5px solid #141413;
    border-radius: 8px;
    padding: 20px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .awb-res-tag {
    display: inline-block;
    background: #8A2520;
    color: #FFFFFF;
    font-size: 11px;
    font-weight: 700;
    padding: 2px 9px;
    border-radius: 999px;
    margin-bottom: 10px;
  }
  .awb-res-card h3 {
    font-size: 17px;
    font-weight: 800;
    color: #141413;
    margin: 0 0 10px 0;
    line-height: 1.35;
  }
  .awb-res-list {
    margin: 0 0 16px 0;
    padding-left: 18px;
    font-size: 13.5px;
    color: #2B2B2B;
    line-height: 1.6;
  }
  .awb-res-list li {
    margin-bottom: 6px;
  }
  .awb-res-links {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: auto;
    padding-top: 12px;
    border-top: 1px dashed #D8D4CC;
  }
  .awb-link-btn {
    display: inline-block;
    background: #141413;
    color: #FFFFFF !important;
    text-decoration: none !important;
    font-size: 12px;
    font-weight: 600;
    padding: 6px 12px;
    border-radius: 4px;
    transition: background 0.15s ease;
  }
  .awb-link-btn:hover {
    background: #8A2520;
  }
  .awb-link-btn.secondary {
    background: #FFFFFF;
    color: #141413 !important;
    border: 1px solid #141413;
  }
  .awb-link-btn.secondary:hover {
    background: #141413;
    color: #FFFFFF !important;
  }
  /* 站内专栏文库归档盒 */
  .awb-archive-box {
    background: #FFFFFF;
    border: 1.5px solid #DCDCD6;
    border-left: 4px solid #141413;
    border-radius: 6px;
    padding: 18px 20px;
    margin: 14px 0 26px 0;
  }
  .awb-archive-box h4 {
    font-size: 15px;
    font-weight: 800;
    color: #141413;
    margin: 0 0 12px 0;
    padding-bottom: 6px;
    border-bottom: 1px solid #EAEAE4;
  }
  .awb-archive-sub {
    font-size: 13px;
    font-weight: 700;
    color: #8A2520;
    margin: 12px 0 8px 0;
  }
  .awb-article-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 8px 20px;
    list-style: none !important;
    padding-left: 0 !important;
    margin: 0 !important;
  }
  .awb-article-grid li {
    margin: 0 !important;
    padding: 3px 0 !important;
    font-size: 13.5px !important;
    line-height: 1.5 !important;
  }
  .awb-article-grid li a {
    color: #2C2B29 !important;
    text-decoration: none !important;
    border-bottom: 1px solid transparent;
    transition: all 0.15s ease;
  }
  .awb-article-grid li a:hover {
    color: #8A2520 !important;
    border-bottom-color: #8A2520;
  }
  .awb-res-footer {
    font-size: 12px;
    color: #6E6E6A;
    border-top: 1px solid #D8D4CC;
    padding-top: 16px;
    margin-top: 40px;
    line-height: 1.6;
  }
</style>

<div class="awb-res-intro">
  <span class="awb-res-badge">2026.11 最新政策更新 · 站内专栏与官方工具总索引</span><br>
  这里整合了 <strong>aswebuild（北美小生意经）</strong> 历年沉淀的 50+ 篇站内深度指南、加美官方税率与海关查询工具、CRA 报税抵扣清单、企业并购尽调系列及创业扶持机构。只推荐深入访谈与亲自实测过的机构与工具。
</div>

<!-- 顶部快速跳转锚点 -->
<div class="awb-quick-nav">
  <a href="#calc-section">🧮 交互式税率与关税速算器</a>
  <a href="#sec-ecom">01 · 北美电商指南 & 美国查税</a>
  <a href="#sec-customs">02 · 加拿大关税 & 中国进口手册</a>
  <a href="#sec-tax">03 · 加拿大报税需知 & 20大抵扣</a>
  <a href="#sec-buy">04 · 加拿大购买企业指南</a>
  <a href="#sec-grants">05 · 创业贷款、注册合规</a>
  <a href="/tools/">🧰 前往「17款创业软件工具箱」→</a>
</div>

<!-- ============================================== -->
<!-- 交互式工具区：两大实时自测计算器 -->
<!-- ============================================== -->
<div class="awb-sec-title" id="calc-section">
  <h2>🧮 在线交互式合规自测器</h2>
  <span>输入你的业务参数，即刻测算跨省代收税率、注册红线与跨境关税节省空间</span>
</div>

<div class="awb-calc-grid">

  <!-- 计算器 1：加拿大销售税与红线自测 -->
  <div class="awb-calc-box">
    <h3>🇨🇦 加拿大跨省销售税 & 注册红线自测</h3>
    <div class="awb-form-row">
      <label for="destProv">客户收货所在地（目的地原则）：</label>
      <select id="destProv" onchange="calcCanTax()">
        <option value="BC">BC 省（不列颠哥伦比亚）</option>
        <option value="ON">ON 安大略省</option>
        <option value="AB">AB 阿尔伯塔 / YT / NT / NU</option>
        <option value="ATL">NB / NL / NS / PE（大西洋四省）</option>
        <option value="QC">QC 魁北克省</option>
        <option value="SK">SK 萨斯喀彻温省</option>
        <option value="MB">MB 曼尼托巴省</option>
        <option value="US">美国或国际买家（跨境出口）</option>
      </select>
    </div>
    <div class="awb-form-row">
      <label for="revAmount">过去连续 4 个季度全球累计营业额（CAD $）：</label>
      <input type="number" id="revAmount" value="35000" min="0" step="1000" oninput="calcCanTax()" />
    </div>
    <div class="awb-form-row">
      <label for="hasStore">是否在 BC 省拥有实体门店或本地存货仓？</label>
      <select id="hasStore" onchange="calcCanTax()">
        <option value="yes">是（大温/BC 本地经营）</option>
        <option value="no">否（纯远程/外省发货）</option>
      </select>
    </div>
    <div class="awb-calc-result" id="canTaxResult"></div>
  </div>

  <!-- 计算器 2：2026 跨境直邮 vs 集货/3PL 成本速算 -->
  <div class="awb-calc-box">
    <h3>📦 2026 跨境发美：单件直邮 vs 集货/3PL 关税速算</h3>
    <div class="awb-form-row">
      <label for="retailPrice">商品零售客单价（USD $）：</label>
      <input type="number" id="retailPrice" value="100" min="1" oninput="calcDutySave()" />
    </div>
    <div class="awb-form-row">
      <label for="costPrice">工厂出厂/批发成本价（USD $）：</label>
      <input type="number" id="costPrice" value="22" min="1" oninput="calcDutySave()" />
    </div>
    <div class="awb-form-row">
      <label for="monthlyOrders">月均发往美国订单量（单）：</label>
      <input type="number" id="monthlyOrders" value="150" min="1" oninput="calcDutySave()" />
    </div>
    <div class="awb-form-row">
      <label for="tariffRate">适用综合关税税率（%）：</label>
      <input type="number" id="tariffRate" value="25" min="0" max="100" oninput="calcDutySave()" />
    </div>
    <div class="awb-calc-result" id="dutySaveResult"></div>
  </div>

</div>

<!-- ============================================== -->
<!-- 模块 01：北美电商指南 & 美国税率查询 -->
<!-- ============================================== -->
<div class="awb-sec-title" id="sec-ecom">
  <h2>01 · 北美电商指南 & 美国税率查询</h2>
  <span>零库存 Dropshipping / POD 测款、2026 跨境履约新政与美国各州消费税查询</span>
</div>

<div class="awb-res-grid">

  <!-- 北美电商指南 -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">北美电商指南</span>
      <h3>DTC 独立站冷启动与 2026 履约新政</h3>
      <ul class="awb-res-list">
        <li><strong>零库存 MVP 测款：</strong>使用 Shopify 开启单页结账与 Shop Pay，对接 Printify 美加本地路由（Local Routing）或 Dropshipping 供应链，零库存低成本验证爆款。</li>
        <li><strong>弃单挽回黄金序列：</strong>配置 Klaviyo / 邮件与推送工具，48 小时三阶触达自动挽回 10%–15% 流失订单。</li>
        <li><strong>脉冲式集货与边境 3PL：</strong>应对美国取消 $800 免税额，采用每月集中预售合并大货报关（Batch Shipping）或备货美加边境 3PL 按出厂成本价申报入境。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="https://shopify.pxf.io/c/5878481/3323859/13624" target="_blank" rel="sponsored noopener">开启 Shopify 专属试用 →</a>
      <a class="awb-link-btn secondary" href="/tools/">查看电商全套工具栈</a>
    </div>
  </div>

  <!-- 美国税率查询 -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">美国税率查询</span>
      <h3>美国海关 HTS 税率与各州销售税 Nexus</h3>
      <ul class="awb-res-list">
        <li><strong>美国海关 HTS 官方查询：</strong>发往美国的商品须通过美国国际贸易委员会（USITC）官方系统核查 10 位 HTS 编码与附加税率。</li>
        <li><strong>各州 Economic Nexus 红线：</strong>美国按“州税+地方税”复合征收，通常在某州年销达 <strong>$100,000 USD 或满 200 笔订单</strong>时触发代收代缴义务。</li>
        <li><strong>加拿大发美零税率：</strong>加拿大商家向美国买家发货属于零税率出口（Zero-rated），免收加拿大 GST/HST，但须留存跨境运单备查。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="https://hts.usitc.gov/" target="_blank" rel="noopener">USITC 美国 HTS 税率官查 →</a>
      <a class="awb-link-btn secondary" href="https://www.streamlinedsalestax.org/" target="_blank" rel="noopener">美国各州 Sales Tax 规则</a>
    </div>
  </div>

</div>

<!-- 站内文库：北美电商指南全集 -->
<div class="awb-archive-box">
  <h4>📚 站内《北美电商指南》深度专栏文库（Dropshipping · Shopify 工具 · 物流省钱）</h4>
  
  <div class="awb-archive-sub">▸ 北美开 Dropshipping 网店四部曲</div>
  <ul class="awb-article-grid">
    <li><a href="/business/2021/04/22/%e5%bc%80dropshipping%e7%bd%91%e5%ba%97%e7%b3%bb%e5%88%97%e4%b9%8b%e4%b8%80%ef%bc%9a%e8%bf%99%e4%b8%aa%e6%a8%a1%e5%bc%8f%e5%88%b0%e5%ba%95%e6%9c%89%e5%a4%9a%e7%81%ab/">1. 开Dropshipping网店之一：这个模式到底有多火</a></li>
    <li><a href="/business/2021/04/23/%e5%bc%80dropshipping%e7%bd%91%e5%ba%97%e7%b3%bb%e5%88%97%e4%b9%8b%e4%ba%8c%ef%bc%9a%e4%bc%98%e5%8a%a3%e6%9c%89%e5%93%aa%e4%ba%9b%ef%bc%9f/">2. 开Dropshipping网店之二：优劣有哪些？</a></li>
    <li><a href="/business/2021/04/26/%e5%bc%80dropshipping%e7%bd%91%e5%ba%97%e7%b3%bb%e5%88%97%e4%b9%8b%e4%b8%89%ef%bc%9a%e9%80%89%e5%93%aa%e5%bc%80%e5%ba%97%ef%bc%9f/">3. 开Dropshipping网店之三：选哪开店？</a></li>
    <li><a href="/business/2021/04/27/%e5%bc%80dropshipping%e7%bd%91%e5%ba%97%e7%b3%bb%e5%88%97%e4%b9%8b%e5%9b%9b%ef%bc%9a%e5%93%aa%e9%87%8c%e8%bf%9b%e8%b4%a7%e5%a5%bd%ef%bc%9f/">4. 开Dropshipping网店之四：哪里进货好？</a></li>
  </ul>

  <div class="awb-archive-sub">▸ Shopify 网店转化插件与海外营销工具</div>
  <ul class="awb-article-grid">
    <li><a href="/business/2022/10/11/如何选对电商平台/">• 如何选对电商平台？</a></li>
    <li><a href="/business/2022/01/13/%e5%bc%80%e7%bd%91%e5%ba%97%ef%bc%8csquarespace-%e5%92%8c-shopify-%e8%b0%81%e6%9b%b4%e5%a5%bd%ef%bc%9f/">• 开网店，Squarespace 和 Shopify 谁更好？</a></li>
    <li><a href="/business/2022/10/26/6%e4%b8%aa%e5%b7%a5%e5%85%b7%ef%bc%8c%e7%8e%a9%e8%bd%ac%e6%b5%b7%e5%a4%96%e7%94%b5%e5%95%86%e8%90%a5%e9%94%80/">• 6个工具，玩转海外电商营销</a></li>
    <li><a href="/business/2021/10/28/shopify%e5%8d%81%e4%b8%87%e7%94%b5%e5%95%86%e4%b9%8b%e9%80%89%ef%bc%9aloox-product-reviews-and-photos/">• 图文视频晒单有奖：Loox Product Reviews</a></li>
    <li><a href="/business/2021/11/01/%e7%94%b5%e5%95%86%e5%ae%a2%e6%9c%8d%e5%a5%bd%e5%b7%a5%e5%85%b7%ef%bc%9awhatsapp-chat-abandoned-cart/">• 电商客服与弃单挽回：Whatsapp Chat</a></li>
    <li><a href="/business/2021/11/03/%e8%b5%a2%e5%9b%9e%e5%8c%bf%e5%90%8d%e5%ae%a2%e6%88%b7%e7%9a%84%e7%94%b5%e5%95%86%e5%a5%bd%e5%b7%a5%e5%85%b7%ef%bc%9apushowl-web-push-notifications/">• 赢回匿名客户：PushOwl Web Push</a></li>
    <li><a href="/business/2021/11/02/shopify%e7%bd%91%e5%ba%97%e5%85%8d%e8%bf%90%e8%b4%b9%e5%a4%a7%e6%8b%9b%ef%bc%9afree-shipping-bar/">• 买够金额免运费：Free Shipping Bar</a></li>
    <li><a href="/business/2021/10/25/%e8%8a%82%e6%97%a5%e4%bf%83%e9%94%80%ef%bc%8c%e4%b8%83%e5%a4%a7%e5%bf%85%e4%b8%8d%e5%8f%af%e5%b0%91%e7%9a%84shopify-%e5%ba%94%e7%94%a8%e4%b9%8bdialogue-ai-personalization/">• AI 智能个性化卖货：Dialogue AI</a></li>
    <li><a href="/business/2021/10/26/%e8%8a%82%e6%97%a5%e4%bf%83%e9%94%80%ef%bc%8c%e4%b8%83%e5%a4%a7%e5%bf%85%e4%b8%8d%e5%8f%af%e5%b0%91%e7%9a%84shopify-%e5%ba%94%e7%94%a8%e4%b9%8bmailchimp-forms/">• 电邮营销表单：Mailchimp Forms</a></li>
    <li><a href="/business/2021/10/27/%e8%8a%82%e6%97%a5%e4%bf%83%e9%94%80%ef%bc%8c%e4%b8%83%e5%a4%a7%e5%bf%85%e4%b8%8d%e5%8f%af%e5%b0%91%e7%9a%84shopify%e5%ba%94%e7%94%a8%e4%b9%8b%ef%bc%9aautomizely-dropshipping/">• 采购发货工具：Automizely Dropshipping</a></li>
    <li><a href="/business/2021/11/15/vajro%ef%bc%9a60%e5%88%86%e9%92%9f%e7%bb%99shopify%e7%bd%91%e5%ba%97%e5%bb%ba%e4%b8%aa%e6%89%8b%e6%9c%ba%e5%ba%94%e7%94%a8app/">• 60分钟给Shopify网店建手机App：Vajro</a></li>
  </ul>

  <div class="awb-archive-sub">▸ 北美跨境物流省钱、独立站避坑与案例拆解</div>
  <ul class="awb-article-grid">
    <li><a href="/business/2021/05/11/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%8f%91%e8%b4%a7%e5%88%b0%e7%be%8e%e5%9b%bd%ef%bc%8c%e8%bf%99%e6%a0%b7%e5%81%9a%e8%bf%90%e8%b4%b9%e8%83%bd%e7%9c%81%e5%9b%9b%e5%88%86%e4%b9%8b%e4%b8%89%ef%bc%81/">• 加拿大发货到美国，这样做运费能省四分之三！</a></li>
    <li><a href="/business/2021/05/13/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%a2%83%e5%86%85%e9%82%ae%e5%af%84%ef%bc%8c%e6%80%8e%e4%b9%88%e6%89%8d%e8%83%bd%e7%9c%81%e8%bf%90%e8%b4%b9%ef%bc%9f/">• 加拿大境内邮寄，怎么才能省运费？</a></li>
    <li><a href="/business/2021/10/19/%e7%94%b5%e5%95%86%e7%94%9f%e6%84%8f%e7%ac%ac%e4%b8%80%e5%b9%b4%e5%b8%b8%e7%8a%af%e7%9a%844%e4%b8%aa%e9%94%99%e8%af%af/">• 电商生意第一年常犯的4个错误</a></li>
    <li><a href="/business/2021/06/03/%e4%b8%ba%e5%95%a5%e5%8a%a0%e6%8b%bf%e5%a4%a7%e8%bf%99%e4%b9%88%e9%80%82%e5%90%88%e5%bc%80%e7%bd%91%e5%ba%97/">• 为啥加拿大这么适合开网店？</a></li>
    <li><a href="/business/2021/08/17/%e7%94%b5%e5%95%86%e7%94%9f%e6%84%8f%ef%bc%9a%e4%b8%ba%e4%bb%80%e4%b9%88%e8%a6%81%e9%81%bf%e5%bc%80%e4%ba%9a%e9%a9%ac%e9%80%8a%e7%ad%89%e5%a4%a7%e5%b9%b3%e5%8f%b0%e8%bf%9b%e8%a1%8c%e9%94%80%e5%94%ae/">• 为什么要避开亚马逊等大平台进行销售？</a></li>
    <li><a href="/business/2021/02/02/not-amazon-%e5%b0%8f%e7%94%9f%e6%84%8f%e4%b8%bb%e5%af%b9%e5%a4%a7%e7%94%b5%e5%95%86%e7%9a%84%e5%8f%8d%e5%87%bb/">• Not Amazon：小生意主对大电商的反击</a></li>
    <li><a href="/business/2021/04/28/%e7%94%a8pietra%ef%bc%8c%e4%bd%a0%e4%b9%9f%e8%83%bd%e5%81%9a%e4%b8%aa%e7%8b%ac%e7%ab%8b%e5%93%81%e7%89%8c/">• 用Pietra，你也能做个独立品牌</a></li>
    <li><a href="/business/2021/05/26/%e5%a6%82%e6%9e%9c%e4%bd%a0%e5%9c%a8etsy%e7%9a%84%e5%90%88%e6%b3%95%e5%ba%97%e9%93%ba%e8%a2%ab%e5%b0%81%ef%bc%8c%e4%b8%8d%e8%a6%81%e6%80%a5/">• 如果你在Etsy的合法店铺被封，不要急</a></li>
    <li><a href="/business/2021/05/18/mailchimp-%e5%b8%ae%e4%bd%a0%e5%85%8d%e8%b4%b9%e5%bc%80%e7%bd%91%e5%ba%97/">• Mailchimp 帮你免费开网店</a></li>
    <li><a href="/business/2021/06/01/%e5%9c%a8%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%ae%89%e5%a4%a7%e7%95%a5%e7%9c%81%e5%a6%82%e4%bd%95%e5%85%8d%e8%b4%b9%e5%bb%ba%e7%bd%91%e5%ba%97/">• 在加拿大安大略省如何免费建网店</a></li>
    <li><a href="/business/2021/09/07/%e7%94%b5%e5%95%86%e3%80%81%e9%a4%90%e9%a5%ae%e5%b0%8f%e4%bc%81%e4%b8%9a%ef%bc%8c%e5%ae%9a%e5%88%b6%e6%89%8b%e6%9c%ba%e5%ba%94%e7%94%a8app%e6%80%8e%e4%b9%88%e7%9c%81%e9%92%b1%ef%bc%9f/">• 电商、餐饮小企业定制手机APP怎么省钱？</a></li>
    <li><a href="/business/2022/09/23/%e8%bf%99%e7%ac%94%e7%94%b5%e5%95%86%e8%a1%a5%e5%8a%a9%e9%87%91%ef%bc%8c%e5%8a%a0%e6%8b%bf%e5%a4%a7%e6%94%bf%e5%ba%9c%e5%96%8a%e4%bd%a0%e8%b5%b6%e7%b4%a7%e7%94%b3%e8%af%b7%ef%bc%81/">• 加拿大政府电商补助金申请指南</a></li>
    <li><a href="/business/2021/07/12/%e5%8a%a0%e6%8b%bf%e5%a4%a7cdap%e8%ae%a1%e5%88%92%e6%8b%a8%e6%ac%be40%e4%ba%bf%ef%bc%8c%e5%b8%ae%e5%b0%8f%e4%bc%81%e4%b8%9a%e6%95%b0%e5%ad%97%e5%8c%96/">• 加拿大CDAP数字化计划解析</a></li>
    <li><a href="/business/2022/06/22/1902/">• 案例：Scott从电商开始的连续创业转型</a></li>
    <li><a href="/business/2022/06/06/%e4%b9%b0%e6%9d%af%e5%ad%90%e8%b5%b7%e5%ae%b6%e7%9a%8425%e5%b2%81%e7%94%b5%e5%95%86%e5%a5%87%e6%89%8ddylan/">• 案例：卖杯子起家的25岁电商奇才Dylan</a></li>
  </ul>
</div>

<!-- ============================================== -->
<!-- 模块 02：加拿大关税工具 & 加拿大进口指南 -->
<!-- ============================================== -->
<div class="awb-sec-title" id="sec-customs">
  <h2>02 · 加拿大关税工具 & 从中国进口到加拿大指南</h2>
  <span>Canada Tariff Finder 查税、CUSMA 原产地穿透、K32 退税与进口清关 6 步实操</span>
</div>

<div class="awb-res-grid">

  <!-- 加拿大关税工具 -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">加拿大关税工具</span>
      <h3>HS 编码查税、原产地穿透与 100% 退税</h3>
      <ul class="awb-res-list">
        <li><strong>Canada Tariff Finder：</strong>输入 6–10 位 HS 编码，横向比对最惠国（MFN）、CUSMA 协定税率及 2026 对美反制关税（家具/服装 50%、家电/海鲜乳品 25%、大型空调 15%）。</li>
        <li><strong>CUSMA 原产地铁律：</strong>“从美国海外仓发货 ≠ 美国原产免税”，须满足税则改变与区域价值成分（RVC），原产地证明须留存满 6 年。</li>
        <li><strong>Duty Drawback 再出口退税：</strong>进口原料或商品加工后再出口（或退运），4 年内通过 K32 申请可退回 <strong>99%–100% 已缴关税</strong>。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="https://www.tariffinder.ca/" target="_blank" rel="noopener">Canada Tariff Finder 官网 →</a>
      <a class="awb-link-btn secondary" href="https://www.cbsa-asfc.gc.ca/import/ddr-red/menu-eng.html" target="_blank" rel="noopener">CBSA 关税退税与减免指南</a>
    </div>
  </div>

  <!-- 加拿大进口指南 -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">加拿大进口指南</span>
      <h3>CBSA CARM 强制清关 4 步法与合同防雷</h3>
      <ul class="awb-res-list">
        <li><strong>CARM 海关门户必配：</strong>① 申请 9 位 BN 号 → ② 激活 RM0001 进口账户 → ③ 登录 CARM Client Portal 授权报关行 → ④ 绑定 RPP 财务担保享“先放行后付款”，免遭温哥华港滞港费。</li>
        <li><strong>贸易合同重构（弃用 DDP）：</strong>将供货合同从卖方包税的 DDP 改为 <strong>FOB / FCA</strong>，并写入关税波动分摊条款。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="https://ccp-pcc.cbsa-asfc.cloud-nuage.canada.ca/" target="_blank" rel="noopener">登录 CBSA CARM 门户 →</a>
      <a class="awb-link-btn secondary" href="https://investsurrey.ca/tariff-resources" target="_blank" rel="noopener">Invest Surrey 本地替代供应链</a>
    </div>
  </div>

</div>

<!-- 站内文库：从中国进口到加拿大指南手册 -->
<div class="awb-archive-box">
  <h4>📚 站内《从中国进口到加拿大指南手册》全套教程</h4>
  <ul class="awb-article-grid">
    <li><a href="/business/2021/07/26/%e6%80%8e%e4%b9%88%e6%8a%8a%e8%b4%a7%e7%89%a9%e8%bf%9b%e5%8f%a3%e5%88%b0%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%9a%e5%89%8d%e6%9c%9f%e5%87%86%e5%a4%87%e7%af%87/">第一步：把货物进口到加拿大 · 前期准备篇</a></li>
    <li><a href="/business/2021/07/27/%e6%80%8e%e4%b9%88%e6%8a%8a%e8%b4%a7%e7%89%a9%e8%bf%9b%e5%8f%a3%e5%88%b0%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%9a%e5%85%b3%e7%a8%8e%e5%88%86%e7%b1%bb%e7%af%87/">第二步：如何读懂加拿大关税分类和 HS 编码</a></li>
    <li><a href="/business/2021/08/09/%e6%80%8e%e4%b9%88%e6%8a%8a%e8%b4%a7%e7%89%a9%e8%bf%9b%e5%8f%a3%e5%88%b0%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%9a%e7%a1%ae%e5%ae%9a%e5%85%b3%e7%a8%8e%e5%92%8c%e5%90%84%e7%a7%8d%e5%85%b6%e4%bb%96%e7%a8%8e/">第三步：确定加拿大关税、GST 以及其他税率</a></li>
    <li><a href="/business/2021/08/10/%e6%80%8e%e4%b9%88%e6%8a%8a%e8%b4%a7%e7%89%a9%e8%bf%9b%e5%8f%a3%e5%88%b0%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%9a%e7%a1%ae%e5%ae%9a%e8%bf%9b%e5%8f%a3%e8%b4%a7%e7%89%a9%e4%bb%b7%e5%80%bc/">第四步：确定加拿大进口货物申报价值</a></li>
    <li><a href="/business/2021/08/11/%e6%80%8e%e4%b9%88%e6%8a%8a%e8%b4%a7%e7%89%a9%e8%bf%9b%e5%8f%a3%e5%88%b0%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%9a%e5%90%91%e8%bf%9b%e5%8f%a3%e5%95%86%e4%b8%8b%e8%ae%a2%e5%8d%95/">第五步：向中国供应商下订单与贸易条款注意项</a></li>
    <li><a href="/business/2021/08/12/%e6%80%8e%e4%b9%88%e6%8a%8a%e8%b4%a7%e7%89%a9%e8%bf%9b%e5%8f%a3%e5%88%b0%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%9a%e6%b5%b7%e5%85%b3%e6%94%be%e8%a1%8c%e8%bf%9b%e5%8f%a3/">第六步：加拿大海关放行与清关步骤</a></li>
    <li><a href="/business/2021/08/19/%e8%bf%9b%e5%8f%a3%e5%bf%85%e5%a4%87%e7%9a%84%e5%a5%bd%e5%b7%a5%e5%85%b7%ef%bc%9a%e5%8a%a0%e6%8b%bf%e5%a4%a7%e6%b5%b7%e5%85%b3%e8%87%aa%e5%8a%a9%e7%ae%a1%e7%90%86%e5%b7%a5%e5%85%b7carm/">• 进口必备工具：加拿大海关自助管理工具 CARM 详解</a></li>
    <li><a href="/business/2021/07/05/%e4%bb%8e%e4%b8%ad%e5%9b%bd%e8%bf%9b%e5%8f%a3%e8%b4%a7%e7%89%a9%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%8c%e4%bb%80%e4%b9%88%e6%9c%80%e7%83%ad%e9%97%a8%ef%bc%9f/">• 从中国进口货物到加拿大，什么品类最热门？</a></li>
  </ul>
</div>

<!-- ============================================== -->
<!-- 模块 03：加拿大报税指南（双税红线与20大抵税） -->
<!-- ============================================== -->
<div class="awb-sec-title" id="sec-tax">
  <h2>03 · 加拿大小企业报税指南 & 20 大合法抵税清单</h2>
  <span>11% 小企业综合低税率、100% ITC 进项退税、2026 设备全额抵扣新政与站内节税文库</span>
</div>

<div class="awb-res-grid">

  <!-- 税率、红线与 ITC -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">税率与申报红线</span>
      <h3>11% 小企业税率、GST/PST 红线与 ITC</h3>
      <ul class="awb-res-list">
        <li><strong>BC 有限公司低税率：</strong>前 50 万加元主动营业利润享 <strong>11% 综合低税率</strong>（联邦 9% + BC 省 2%）。</li>
        <li><strong>双税强制注册红线：</strong>联邦 GST 为连续 4 季度满 <strong>$30,000 CAD</strong>（超额 29 天内须开通 RT0001）；BC 省 PST 小卖家红线为 <strong>$10,000 CAD</strong>（有实体门市无豁免，须注册 eTaxBC 代收 7%）。</li>
        <li><strong>100% ITC 进项税退还：</strong>开通 GST 后，房租、进货、软件等商业开支所付 5% GST 可 100% 向 CRA 申领退回现金（商务餐饮按 50% 抵扣）。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-businesses/business-account.html" target="_blank" rel="noopener">CRA 商业税号门户 →</a>
      <a class="awb-link-btn secondary" href="https://www.etax.gov.bc.ca/" target="_blank" rel="noopener">BC eTaxBC 省税门户</a>
    </div>
  </div>

  <!-- 20大抵税与防稽查 -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">20 大抵税与防稽查</span>
      <h3>年度 20 项抵税科目与 CRA 凭证铁律</h3>
      <ul class="awb-res-list">
        <li><strong>核心抵扣清单：</strong>① 居家办公 ② 商业租金 ③ 车辆开支（须配 Mileage Logbook）④ 差旅机酒 ⑤ 手机网络 ⑥ SaaS 软件 ⑦ 办公耗材 ⑧ 广告投流 ⑨ 商业保险 ⑩ 物流清关 ⑪ 商务餐饮（50% 抵扣，背面须写客户名与事由）⑫ 会计律师费 ⑬ 行业年费 ⑭ 培训 ⑮ 银行与 Stripe 手续费/商业贷款利息 ⑯ 员工薪资 ⑰ CPP/EI 配缴 ⑱ 外包 T4A ⑲ PHSP 私人医疗计划。</li>
        <li><strong>2026.09 折旧新政（第 20 项）：</strong>新购商业电脑与特定设备享当年 <strong>100% 一次性全额抵扣</strong>！所有电子扫描凭证须依 CRA IC05-1R1 规范留存满 <strong>6 年</strong>。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="/tools/">配置 Synder 财税自动化对账 →</a>
    </div>
  </div>

</div>

<!-- 站内文库：加拿大小企业报税需知 -->
<div class="awb-archive-box">
  <h4>📚 站内《加拿大小企业报税手册》深度专栏文库</h4>

  <div class="awb-archive-sub">▸ 小生意报税与减税策略五部曲</div>
  <ul class="awb-article-grid">
    <li><a href="/business/2021/04/12/2020%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%b0%8f%e7%94%9f%e6%84%8f%e6%8a%a5%e7%a8%8e%e7%b3%bb%e5%88%97%e4%b9%8b%ef%bc%9a%e5%9f%ba%e6%9c%ac%e9%a1%bb%e7%9f%a5/">1. 加拿大小生意报税系列之一：基本须知</a></li>
    <li><a href="/business/2021/04/13/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%b0%8f%e7%94%9f%e6%84%8f%e6%8a%a5%e7%a8%8e%e7%b3%bb%e5%88%97%e4%b9%8b%e4%ba%8c%ef%bc%9a8%e4%b8%aa%e6%9c%80%e5%ae%9e%e7%94%a8%e7%9a%84%e5%87%8f%e7%a8%8e%e7%ad%96%e7%95%a5/">2. 加拿大小生意报税系列之二：8个最实用的减税策略</a></li>
    <li><a href="/business/2021/04/14/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%b0%8f%e7%94%9f%e6%84%8f%e6%8a%a5%e7%a8%8e%e7%b3%bb%e5%88%97%e4%b9%8b%e4%b8%89%ef%bc%9a%e5%b1%85%e5%ae%b6%e5%88%9b%e4%b8%9a%e7%9a%84%e5%87%8f%e7%a8%8e%e6%b8%85%e5%8d%95/">3. 加拿大小生意报税系列之三：居家创业的减税清单</a></li>
    <li><a href="/business/2021/04/15/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%b0%8f%e7%94%9f%e6%84%8f%e6%8a%a5%e7%a8%8e%e7%b3%bb%e5%88%97%e4%b9%8b%e5%9b%9b%ef%bc%9a%e7%94%a8%e8%bd%a6%e6%9c%80%e5%a4%a7%e5%8c%96%e5%87%8f%e7%a8%8e/">4. 加拿大小生意报税系列之四：用车最大化减税</a></li>
    <li><a href="/business/2021/04/19/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%b0%8f%e7%94%9f%e6%84%8f%e6%8a%a5%e7%a8%8e%e7%b3%bb%e5%88%97%e4%b9%8b%e4%ba%94%ef%bc%9a%e6%9c%80%e5%90%8e%e9%9c%80%e8%a6%81%e6%a0%b8%e6%9f%a5%e7%9a%84%e5%87%8f%e7%a8%8e/">5. 加拿大小生意报税系列之五：最后需要核查的减税清单</a></li>
  </ul>

  <div class="awb-archive-sub">▸ 有限公司税务筹划、GST 申请与免费记账工具评测</div>
  <ul class="awb-article-grid">
    <li><a href="/business/2021/06/08/%e5%9c%a8%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%8c%e6%b3%a8%e5%86%8c%e6%9c%89%e9%99%90%e5%85%ac%e5%8f%b8%e6%9c%89%e5%93%aa%e4%ba%9b%e5%a5%bd%e5%a4%84%ef%bc%9f/">• 在加拿大，注册有限公司有哪些好处？</a></li>
    <li><a href="/business/2021/01/07/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%a6%82%e4%bd%95%e7%94%b3%e8%af%b7gst%e5%8f%b7%e7%a0%81/">• 加拿大创业：如何申请 GST Number</a></li>
    <li><a href="/business/2021/07/21/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e6%9c%89%e9%99%90%e5%85%ac%e5%8f%b8%e7%a6%8f%e5%88%a9%e4%b9%8b%e5%8c%bb%e7%96%97%e8%b4%b9%e7%94%a8/">• 加拿大有限公司福利：医疗费用抵税（PHSP）</a></li>
    <li><a href="/business/2021/07/13/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e6%9c%89%e9%99%90%e5%85%ac%e5%8f%b8%e7%a6%8f%e5%88%a9%e4%b9%8b%e5%91%98%e5%b7%a5%e8%b4%b7%e6%ac%be/">• 加拿大有限公司福利：员工贷款合规规则</a></li>
    <li><a href="/business/2021/06/28/%e5%9c%a8%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%8c%e5%85%ac%e5%8f%b8%e4%b8%8d%e8%a6%81%e9%9a%8f%e4%be%bf%e7%bb%99%e5%ae%b6%e4%ba%ba%e5%88%86%e7%ba%a2/">• 避坑：在加拿大，公司不要随便给家人分红（TOSI）</a></li>
    <li><a href="/business/2021/07/20/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%b0%8f%e4%bc%81%e4%b8%9a%e7%a8%8e%e6%94%b6%e5%87%8f%e5%85%8dc-208-%e6%b3%95%e6%a1%88%e6%ad%a3%e5%bc%8f%e7%94%9f%e6%95%88%ef%bc%81/">• 小企业代际传承税收减免 C-208 法案解析</a></li>
    <li><a href="/business/2021/07/06/%e5%b0%8f%e7%94%9f%e6%84%8f%e4%b8%bb%ef%bc%8c%e4%b9%b0rrsp%e5%88%b0%e5%ba%95%e6%98%af%e8%b5%9a%e8%bf%98%e6%98%af%e4%ba%8f%ef%bc%9f/">• 小生意主，买 RRSP 到底是赚还是亏？</a></li>
    <li><a href="/business/2021/06/23/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%b0%8f%e4%bc%81%e4%b8%9a%e4%b8%bb%e4%b8%ba%e9%80%80%e4%bc%91%e5%ad%98%e9%92%b1%e7%9a%846%e4%b8%aa%e8%af%80%e7%aa%8d/">• 加拿大小企业主为退休存钱的 6 个诀窍</a></li>
    <li><a href="/business/2021/01/08/%e5%85%8d%e8%b4%b9%e5%a5%bd%e7%94%a8%e8%ae%b0%e8%b4%a6%e4%ba%91%e8%bd%af%e4%bb%b6wave-accounting/">• 免费好用的记账云软件：Wave Accounting 评测</a></li>
    <li><a href="/business/2021/07/19/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%b0%8f%e4%bc%81%e4%b8%9a%e4%b8%93%e7%94%a8appcanada-business/">• 加拿大小企业专用官方 App：Canada Business</a></li>
    <li><a href="/business/2022/01/06/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e7%94%b5%e5%ad%90%e6%8a%a5%e7%a8%8e%e4%bb%98%e8%b4%b9%e5%b7%a5%e5%85%b7turbotax-%e5%92%8c-hr-block-%ef%bc%8c%e8%af%a5%e9%80%89%e8%b0%81%ef%bc%9f/">• 电子报税工具 TurboTax 和 H&R Block 该选谁？</a></li>
    <li><a href="/business/2022/01/04/2022%e5%8a%a0%e6%8b%bf%e5%a4%a7%e5%85%8d%e8%b4%b9%e6%8a%a5%e7%a8%8e%e5%b7%a5%e5%85%b7%e5%ae%8c%e6%95%b4%e4%bc%98%e7%bc%ba%e7%82%b9%e5%af%b9%e7%85%a7/">• 加拿大免费报税工具完整优缺点对照</a></li>
    <li><a href="/business/2022/02/01/2022%e5%8a%a0%e6%8b%bf%e5%a4%a7%e6%8a%a5%e7%a8%8e%e6%97%b6%e9%97%b4%e8%a1%a8%ef%bc%8c%e4%bb%a5%e5%8f%8a%e9%87%8d%e8%a6%81%e6%8f%90%e9%86%92%e3%80%82/">• 加拿大报税关键时间节点与重要提醒</a></li>
    <li><a href="/business/2022/02/10/2022%e5%8a%a0%e6%8b%bf%e5%a4%a7%e6%8a%a5%e7%a8%8e%e9%a2%9d%e5%ba%a6%e5%8f%98%e5%8c%96%e6%9c%80%e5%a4%a7%e7%9a%849%e4%b8%aa%e6%96%b9%e9%9d%a2/">• 加拿大报税额度核心变化盘点</a></li>
  </ul>
</div>

<!-- ============================================== -->
<!-- 模块 04：购买与出售加拿大企业 -->
<!-- ============================================== -->
<div class="awb-sec-title" id="sec-buy">
  <h2>04 · 加拿大购买企业指南（线上并购 & 线下尽调）</h2>
  <span>北美购买小企业 6 大标准步骤、商业租约与 PPR 质押查册、Flippa 数字资产交易</span>
</div>

<div class="awb-res-grid">

  <!-- 线上数字资产并购 -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">线上商业资产买卖</span>
      <h3>收购或出售独立站、内容站与 Micro-SaaS</h3>
      <ul class="awb-res-list">
        <li><strong>按“可出售资产”标准建账：</strong>公私账户彻底隔离、日常运营沉淀为 ClickUp 标准 SOP，使生意脱离创始人肉身绑定，享受 3–5 倍年净利润估值溢价。</li>
        <li><strong>线上资产尽调核心：</strong>通过 Flippa.com 交易时，重点核验后台原生 Stripe / Shopify 真实流水、Google Analytics 自然搜索流量占比及域名历史健康度。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="https://flippa.com/" target="_blank" rel="sponsored noopener">前往 Flippa 交易数字资产 →</a>
    </div>
  </div>

  <!-- 线下实体企业并购 -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">线下实体生意尽调</span>
      <h3>买加拿大实体店的 3 条铁律（租约/债务/架构）</h3>
      <ul class="awb-res-list">
        <li><strong>商业租约（Lease）5 必查：</strong>严查有无 Demolition Clause（拆迁无偿赶人条款）、转租权、个人无限连带担保及 CAM 物业管理费涨幅上限。</li>
        <li><strong>PPR 质押与清税证明：</strong>交割前必须检索 BC PPR（动产质押登记库）确认设备无隐形贷款抵押，并索取 CRA Clearance Certificate 与 WorkSafeBC 结清证明。</li>
        <li><strong>买资产（Asset Sale）优先：</strong>买方优先买资产以剥离历史或有负债；卖方出售合格小企业股权可规划使用 LCGE 终生资本增值免税额。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="https://www2.gov.bc.ca/gov/content/employment-business/business/managing-a-business/bc-registry-services/personal-property-registry" target="_blank" rel="noopener">BC PPR 动产抵押官方查册 →</a>
    </div>
  </div>

</div>

<!-- 站内文库：加拿大购买生意指南 -->
<div class="awb-archive-box">
  <h4>📚 站内《加拿大购买企业指南手册》六步通关教程</h4>
  <ul class="awb-article-grid">
    <li><a href="/business/2021/08/25/%e5%8c%97%e7%be%8e%e8%b4%ad%e4%b9%b0%e5%b0%8f%e4%bc%81%e4%b8%9a%e7%b3%bb%e5%88%97%e5%bc%80%e7%af%87%ef%bc%9a%e4%bc%98%e7%bc%ba%e7%82%b9/">1. 加拿大购买小企业系列开篇：买现成生意的优缺点</a></li>
    <li><a href="/business/2021/08/31/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e8%b4%ad%e4%b9%b0%e5%b0%8f%e4%bc%81%e4%b8%9a%e7%b3%bb%e5%88%97%e4%b9%8b%e4%ba%8c%ef%bc%9a%e5%85%85%e5%ae%9e%e5%9f%ba%e6%9c%ac%e7%9f%a5%e8%af%86%e3%80%81%e7%bb%84%e5%bb%ba/">2. 加拿大购买小企业系列之二：充实基本知识、组建专业团队</a></li>
    <li><a href="/business/2021/09/08/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e8%b4%ad%e4%b9%b0%e5%b0%8f%e4%bc%81%e4%b8%9a%e7%b3%bb%e5%88%97%e4%b9%8b%e4%b8%89%ef%bc%9a%e5%9c%a8%e5%8a%a0%e6%8b%bf%e5%a4%a7%ef%bc%8c%e5%93%aa%e4%ba%9b%e6%b8%a0%e9%81%93/">3. 加拿大购买小企业系列之三：在加拿大，哪些渠道能买到好生意？</a></li>
    <li><a href="/business/2021/09/16/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e8%b4%ad%e4%b9%b0%e5%b0%8f%e4%bc%81%e4%b8%9a%e7%b3%bb%e5%88%97%e4%b9%8b%e5%9b%9b%ef%bc%9a%e6%80%8e%e6%a0%b7%e8%b0%83%e6%9f%a5%e4%b8%80%e5%ae%b6%e4%bc%81%e4%b8%9a%ef%bc%88/">4. 加拿大购买小企业系列之四：怎样调查一家企业（附尽调清单）</a></li>
    <li><a href="/business/2021/09/20/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e8%b4%ad%e4%b9%b0%e5%b0%8f%e4%bc%81%e4%b8%9a%e7%b3%bb%e5%88%97%e4%b9%8b%e4%ba%94%ef%bc%9a%e6%80%8e%e6%a0%b7%e5%af%b9%e4%bc%81%e4%b8%9a%e4%bc%b0%e5%80%bc%e5%8f%8a%e5%87%ba/">5. 加拿大购买小企业系列之五：怎样对企业估值及出价</a></li>
    <li><a href="/business/2021/09/28/%e5%8a%a0%e6%8b%bf%e5%a4%a7%e8%b4%ad%e4%b9%b0%e5%b0%8f%e4%bc%81%e4%b8%9a%e7%b3%bb%e5%88%97%e4%b9%8b%e5%85%ad%ef%bc%9a%e9%a1%ba%e5%88%a9%e8%bf%87%e6%b8%a1%e5%85%ad%e5%a4%a7%e5%85%b3%e9%94%ae/">6. 加拿大购买小企业系列之六：交割后顺利过渡六大关键</a></li>
  </ul>
</div>

<!-- ============================================== -->
<!-- 模块 05：创业扶持机构、注册合规 -->
<!-- ============================================== -->
<div class="awb-sec-title" id="sec-grants">
  <h2>05 · 创业贷款机构、$216 DIY 注册</h2>
  <span>Futurpreneur 贷款+导师、2026 联邦关税救济包、极简注册牌照与团队亲测软件</span>
</div>

<div class="awb-res-grid">

  <!-- 1：Futurpreneur 与政府扶持资金 -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">创业贷款 + 导师扶持</span>
      <h3>Futurpreneur 青年创业基金 & 联邦救济池</h3>
      <ul class="awb-res-list">
        <li><strong>Futurpreneur（18–39岁首选）：</strong>加拿大唯一全国性助力青年创业的非营利机构，提供无抵押启动贷款并免费配备专属商业导师（无论发展副业、初创或扩规模）。</li>
        <li><strong>女性与商业信贷：</strong>女性创业可选 <strong>WeBC</strong>；设备与装修选 <strong>CSBFP</strong>（政府担保 85%，最高 115 万加元）。</li>
        <li><strong>2026 联邦关税救济：</strong>包含零门槛的 <strong>WRRP 员工保留与重训补贴（最高 $1,000/人）</strong>、<strong>BDC Pivot to Grow</strong> 与 <strong>PacifiCan RTRI</strong>。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="/futurpreneur/">阅读本站 Futurpreneur 深度专访 →</a>
      <a class="awb-link-btn secondary" href="https://www.futurpreneur.ca/en/" target="_blank" rel="noopener">Futurpreneur 官网</a>
      <a class="awb-link-btn secondary" href="https://www.bdc.ca/" target="_blank" rel="noopener">BDC 官网</a>
    </div>
  </div>

  <!-- 2：$216 DIY 注册公司与大温本地合规 -->
  <div class="awb-res-card">
    <div>
      <span class="awb-res-tag">注册牌照与卫生用工</span>
      <h3>$216 直申联邦公司、BizPaL 牌照与卫生红线</h3>
      <ul class="awb-res-list">
        <li><strong>拒绝高价注册中介：</strong>直接登录联邦官网 `ic.gc.ca`，在线注册费 $200 + NUANS 查名 $13.80 即可拿证，并完成 BC 省跨省登记。</li>
        <li><strong>BizPaL 牌照与 CIPO 商标：</strong>一键查询市/省/联邦三级必办执照，印包装前先查 CIPO 商标库防侵权。</li>
        <li><strong>大温餐饮与用工合规：</strong>租用合规共享厨房（Commissary Kitchen，$25–$45/h）办卫生证；雇人必开 WorkSafeBC 与 CRA Payroll 账户。</li>
      </ul>
    </div>
    <div class="awb-res-links">
      <a class="awb-link-btn" href="https://ised-isde.canada.ca/site/corporations-canada/en" target="_blank" rel="noopener">联邦公司官网直申 →</a>
      <a class="awb-link-btn secondary" href="https://bizpal.ca/" target="_blank" rel="noopener">BizPaL 牌照查询</a>
      <a class="awb-link-btn secondary" href="https://www.worksafebc.com/" target="_blank" rel="noopener">WorkSafeBC 官网</a>
    </div>
  </div>


</div>


<div class="awb-res-footer">
  <strong>合规关联与免责声明：</strong>本页面所汇总的加美政策数据、计算器测算结果与实操指南仅供商业经验交流与教育参考，不构成任何执业法律（Legal）、注册会计师（CPA）或报关行专业建议。详情请参阅本站 <a href="/terms/">服务条款与免责声明 (Terms of Service)</a>。
</div>

<script>
function calcCanTax() {
  var prov = document.getElementById('destProv').value;
  var rev = parseFloat(document.getElementById('revAmount').value) || 0;
  var hasStore = document.getElementById('hasStore').value;

  var taxRateText = '';
  if (prov === 'BC') {
    taxRateText = '<strong>12%</strong>（5% 联邦 GST + 7% BC 省 PST）';
  } else if (prov === 'ON') {
    taxRateText = '<strong>13% HST</strong>（安省合并销售税）';
  } else if (prov === 'AB') {
    taxRateText = '<strong>5% GST</strong>（无省级销售税 PST）';
  } else if (prov === 'ATL') {
    taxRateText = '<strong>15% HST</strong>（大西洋省份合并销售税）';
  } else if (prov === 'QC') {
    taxRateText = '<strong>14.975%</strong>（5% GST + 9.975% QST）';
  } else if (prov === 'SK') {
    taxRateText = '<strong>11%</strong>（5% GST + 6% SK PST）';
  } else if (prov === 'MB') {
    taxRateText = '<strong>12%</strong>（5% GST + 7% MB RST）';
  } else if (prov === 'US') {
    taxRateText = '<strong>0%（零税率跨境出口 Zero-rated）</strong>，免收加拿大 GST/HST，但须保留出境物流运单凭证';
  }

  var gstStatus = rev > 30000
    ? '<span style="color:#8A2520;font-weight:700;">⚠️ 已超 $30,000 红线：必须在 29 天内强制注册 CRA GST (RT0001) 账户！</span>'
    : '✅ 未超 $30,000 小规模供应商红线（可暂免注册，但主动注册可 100% 退回商业开支 ITC 进项税）。';

  var pstStatus = (rev > 10000 || hasStore === 'yes')
    ? '<span style="color:#8A2520;font-weight:700;">⚠️ 需注册 BC PST (eTaxBC)：营业额超 $10,000 或在 BC 有实体经营场地，发 BC 订单须代收 7% PST。</span>'
    : '✅ 暂未触发 BC 省 $10,000 小卖家 PST 红线。';

  document.getElementById('canTaxResult').innerHTML =
    '<div>• <strong>该订单应代收税率：</strong>' + taxRateText + '</div>' +
    '<div style="margin-top:6px;">• <strong>联邦 GST 状态：</strong>' + gstStatus + '</div>' +
    '<div style="margin-top:6px;">• <strong>BC 省 PST 状态：</strong>' + pstStatus + '</div>';
}

function calcDutySave() {
  var retail = parseFloat(document.getElementById('retailPrice').value) || 0;
  var cost = parseFloat(document.getElementById('costPrice').value) || 0;
  var orders = parseInt(document.getElementById('monthlyOrders').value) || 1;
  var rate = (parseFloat(document.getElementById('tariffRate').value) || 0) / 100;

  var directDutyPerOrder = retail * rate + 12;
  var directMonthlyTotal = directDutyPerOrder * orders;

  var bulkDutyTotal = (cost * rate * orders) + 120;
  var savedMonthly = Math.max(0, directMonthlyTotal - bulkDutyTotal);

  document.getElementById('dutySaveResult').innerHTML =
    '<div>• <strong>传统单件直邮月度税费：</strong>约 <strong>$' + directMonthlyTotal.toFixed(0) + ' USD/月</strong>（按零售价计税 + 单票报关费累加）</div>' +
    '<div style="margin-top:6px;">• <strong>集货拼单 / 3PL 成本价申报：</strong>约 <strong>$' + bulkDutyTotal.toFixed(0) + ' USD/月</strong>（按出厂成本价申报 + 整票平摊报关费）</div>' +
    '<div style="margin-top:6px;color:#8A2520;font-weight:800;">💰 每月合法节省关税与报关成本：约 $' + savedMonthly.toFixed(0) + ' USD（年省 $' + (savedMonthly * 12).toFixed(0) + ' USD）！</div>';
}

window.addEventListener('DOMContentLoaded', function() {
  calcCanTax();
  calcDutySave();
});
</script>