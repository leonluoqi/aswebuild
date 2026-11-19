---
layout: single
title: "加拿大大温华人创业通关图文指南手册"
permalink: /guide/
author_profile: true
toc: false
---

<style>
  /* 隐藏默认重复标题，改用定制刊物风刊头 */
  #page-title,
  .page__title {
    display: none !important;
  }

  .guide-wrap {
    max-width: 100%;
    color: #141413;
    font-family: -apple-system, BlinkMacSystemFont, "PingFang SC", "Microsoft YaHei", sans-serif;
  }

  /* 刊头区域 */
  .guide-hero {
    padding: 0 0 22px 0;
    border-bottom: 1.5px solid #141413;
    margin-bottom: 24px;
  }

  .guide-kicker {
    font-family: "JetBrains Mono", ui-monospace, SFMono-Regular, Menlo, monospace;
    font-size: 11px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: #8A2520;
    font-weight: 600;
    margin-bottom: 8px;
  }

  .guide-hero h1 {
    font-family: "Songti SC", "STSong", "Source Han Serif SC", Georgia, serif;
    font-size: 28px;
    font-weight: 700;
    line-height: 1.3;
    color: #141413;
    margin: 0 0 12px 0 !important;
  }

  .guide-intro {
    font-size: 15px;
    line-height: 1.7;
    color: #555552;
    margin: 0 0 18px 0 !important;
  }

  /* 顶部模块快速跳转导航 */
  .guide-nav {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    align-items: center;
  }

  .guide-nav a {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    padding: 6px 14px;
    font-size: 13px;
    font-weight: 500;
    color: #141413 !important;
    background: #F6F4EF;
    border: 1px solid #141413;
    border-radius: 2px;
    text-decoration: none !important;
    transition: all 0.15s ease;
  }

  .guide-nav a:hover {
    background: #141413;
    color: #FFFFFF !important;
  }

  .guide-nav a.roadmap-btn {
    background: #8A2520;
    border-color: #8A2520;
    color: #FFFFFF !important;
  }

  .guide-nav a.roadmap-btn:hover {
    background: #6E1C18;
    border-color: #6E1C18;
  }

  /* 模块标题 */
  .module-section {
    margin: 34px 0 38px 0;
  }

  .module-header {
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 8px;
    padding-bottom: 10px;
    border-bottom: 1.5px solid #141413;
    margin-bottom: 4px;
  }

  .module-title {
    font-family: "Songti SC", "STSong", "Source Han Serif SC", Georgia, serif;
    font-size: 20px;
    font-weight: 700;
    color: #141413;
    margin: 0 !important;
  }

  .module-meta {
    font-family: "JetBrains Mono", ui-monospace, SFMono-Regular, Menlo, monospace;
    font-size: 11px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: #8A2520;
    font-weight: 600;
  }

  /* 文章目录行 */
  .guide-list {
    list-style: none !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  .guide-item {
    border-bottom: 1px solid #DCDCD6;
    margin: 0 !important;
    padding: 0 !important;
  }

  .guide-link {
    display: grid;
    grid-template-columns: 42px 1fr 20px;
    gap: 12px;
    align-items: baseline;
    padding: 13px 8px;
    text-decoration: none !important;
    color: #141413 !important;
    transition: background-color 0.15s ease;
  }

  .guide-link:hover {
    background-color: rgba(20, 20, 19, 0.03);
  }

  .guide-num {
    font-family: "JetBrains Mono", ui-monospace, SFMono-Regular, Menlo, monospace;
    font-size: 13px;
    font-weight: 700;
    color: #8A2520;
    letter-spacing: 0.06em;
  }

  .guide-text {
    font-family: "Songti SC", "STSong", "Source Han Serif SC", Georgia, serif;
    font-size: 16.5px;
    font-weight: 600;
    line-height: 1.48;
    color: #141413;
  }

  .guide-link:hover .guide-text {
    color: #8A2520;
  }

  .guide-arrow {
    font-family: "JetBrains Mono", monospace;
    font-size: 14px;
    color: #8E8D8A;
    text-align: right;
    transition: transform 0.15s ease, color 0.15s ease;
  }

  .guide-link:hover .guide-arrow {
    color: #8A2520;
    transform: translateX(3px);
  }

  /* 底部订阅盒 */
  .guide-subscribe {
    margin-top: 42px;
    padding: 20px 22px;
    background: #F6F4EF;
    border: 1px solid #141413;
    border-radius: 2px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 14px;
  }

  .guide-subscribe-copy strong {
    display: block;
    font-family: "Songti SC", "STSong", "Source Han Serif SC", Georgia, serif;
    font-size: 17px;
    color: #141413;
    margin-bottom: 4px;
  }

  .guide-subscribe-copy span {
    font-size: 13.5px;
    color: #555552;
  }

  .guide-subscribe form {
    display: flex;
    gap: 8px;
    margin: 0;
    flex-wrap: nowrap;
  }

  .guide-subscribe input[type="email"] {
    width: 210px;
    height: 36px;
    margin: 0;
    padding: 0 12px;
    background: #FFFFFF;
    border: 1px solid #BDBDB8;
    border-radius: 2px;
    font-size: 13.5px;
    color: #141413;
    outline: none;
    box-sizing: border-box;
  }

  .guide-subscribe button {
    height: 36px;
    margin: 0;
    padding: 0 18px;
    background: #141413;
    color: #FFFFFF;
    font-size: 13.5px;
    font-weight: 600;
    border: none;
    border-radius: 2px;
    cursor: pointer;
    white-space: nowrap;
  }

  .guide-subscribe button:hover {
    background: #8A2520;
  }

  @media (max-width: 600px) {
    .guide-hero h1 { font-size: 23px; }
    .guide-link { grid-template-columns: 34px 1fr 16px; gap: 8px; padding: 12px 4px; }
    .guide-text { font-size: 15.5px; }
    .guide-subscribe form { width: 100%; }
    .guide-subscribe input[type="email"] { flex: 1; width: auto; }
  }
</style>

<div class="guide-wrap">

  <!-- 顶部刊头与模块跳转 -->
  <div class="guide-hero">
    <div class="guide-kicker">ASWEBUILD SPECIAL EDITION · 28-PART PLAYBOOK</div>
    <h1>加拿大大温华人创业通关图文指南手册</h1>
    <p class="guide-intro">
      从 216 加元 DIY 公司注册、商业开户、商超进店、B2B 冷邮件获客，到 CRA 稽查自救与 $127.5 万免税退出——全套 28 篇按创业阶段系统拆解，附 2026 最新加拿大及 BC 省官方政策链接与实操。
    </p>
    <div class="guide-nav">
      <a href="#module-1">模块一：初创与架构筹备（01–08）</a>
      <a href="#module-2">模块二：日常运营与高效获客（09–20）</a>
      <a href="#module-3">模块三：突发危机与合规避坑（21–28）</a>
      <a href="/vancouver-roadmap/" class="roadmap-btn">查看大温创业互动路线图 →</a>
    </div>
  </div>

  <!-- 模块一：01 - 08 -->
  <section id="module-1" class="module-section">
    <div class="module-header">
      <h2 class="module-title">模块一｜企业初创与架构筹备篇</h2>
      <span class="module-meta">MODULE 01 · ISSUES 01–08</span>
    </div>
    <ul class="guide-list">
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/001-company-incorporation-diy/">
          <span class="guide-num">01</span>
          <span class="guide-text">公司注册选择：联邦 Incorporation vs BC省注册，216 加元 DIY 全流程</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/002-business-bank-account-cashflow/">
          <span class="guide-num">02</span>
          <span class="guide-text">商业账户与资金流：TD/RBC 商业开户、E-transfer 限制与 Stripe/Square 避坑</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/003-bn-gst-pst-carm-customs/">
          <span class="guide-num">03</span>
          <span class="guide-text">税务号与海关注册：BN 号、GST/PST 注册时机与 CARM 海关系统配置</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/004-chinese-food-repositioning-mainstream-shelf/">
          <span class="guide-num">04</span>
          <span class="guide-text">红海选品重塑：如何剔除“亚超低价内卷”，将传统食材推入主流高蛋白/健康货架</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/005-asset-light-mvp-nocode-pod/">
          <span class="guide-num">05</span>
          <span class="guide-text">轻资产需求验证：用 No-Code 与 POD（按需印刷）做零库存 MVP 需求测试</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/006-csbfp-bdc-grants-funding/">
          <span class="guide-num">06</span>
          <span class="guide-text">本地政策资金撬动：CSBFP 贷款、BDC 与非稀释性政府 Grant 申请全景图</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/007-bc-commercial-lease-traps/">
          <span class="guide-num">07</span>
          <span class="guide-text">商业租赁陷阱：选址评估与 Commercial Lease 商业租约必查的 5 个致命条款</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/008-cipo-trademark-brand-protection/">
          <span class="guide-num">08</span>
          <span class="guide-text">品牌与资产保护：CIPO 加拿大商标注册、域名选择与社交平台矩阵锁名</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
    </ul>
  </section>

  <!-- 模块二：09 - 20 -->
  <section id="module-2" class="module-section">
    <div class="module-header">
      <h2 class="module-title">模块二｜日常运营与高效获客篇</h2>
      <span class="module-meta">MODULE 02 · ISSUES 09–20</span>
    </div>
    <ul class="guide-list">
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/009-mainstream-retail-grocery-sell-sheet/">
          <span class="guide-num">09</span>
          <span class="guide-text">主流商超进店 SOP：制作专业 Sell Sheet、打动买手与进驻连锁超市指南</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/010-b2b-cold-email-linkedin-growth/">
          <span class="guide-num">10</span>
          <span class="guide-text">B2B 高客单获客：冷邮件（Cold Email）三段论与 LinkedIn 主页高转化改造</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/011-brand-private-traffic-substack/">
          <span class="guide-num">11</span>
          <span class="guide-text">品牌私域与内容沉淀：告别微信群促销轰炸，用 Substack 与 Build in Public 建构私域护城河</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/012-ai-automation-solopreneur-sop/">
          <span class="guide-num">12</span>
          <span class="guide-text">AI 自动化极简人效：用 Durable、Make 与 n8n 打造 1 人抵 5 人的无人值守接单系统</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/013-english-copywriting-visual-localization/">
          <span class="guide-num">13</span>
          <span class="guide-text">本地化文案与视觉避坑：北美英文营销 6 大语法雷区与字体/配色本地化 SOP</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/014-shopify-klaviyo-abandoned-cart-sop/">
          <span class="guide-num">14</span>
          <span class="guide-text">独立站与复购引擎：Shopify 结账转化优化与 Klaviyo 弃单挽回 3 步自动化邮件流</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/015-small-business-bookkeeping-tax-deductions/">
          <span class="guide-num">15</span>
          <span class="guide-text">财税与记账实操：QuickBooks/Wave 记账流与小企业 20 个年度抵税分类清单</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/016-bc-hiring-worksafebc-employment-contract/">
          <span class="guide-num">16</span>
          <span class="guide-text">合规雇佣与风控：BC 省 WorkSafeBC 投保、雇佣合同防雷与员工福利筹划</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/017-cross-border-supply-chain-lead-time/">
          <span class="guide-num">17</span>
          <span class="guide-text">跨境供应链管控：中国代工+加拿大海运清关 60 天安全时间模型与 12 周滚动预测</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/018-price-anchoring-negotiation-sop/">
          <span class="guide-num">18</span>
          <span class="guide-text">高情商谈判与防砍价：用价格锚定与条件交换守住北美商业利润底线</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/019-local-home-service-productized-dispatch/">
          <span class="guide-num">19</span>
          <span class="guide-text">本地上门服务规模化：告别按小时卖体力，用服务产品化与自动派单系统赚取 50% 毛利</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/020-vancouver-farmers-market-popup-mvp/">
          <span class="guide-num">20</span>
          <span class="guide-text">农夫市集与快闪店：租店面之前先花 $100 摆摊，完成低成本测款与私域沉淀</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
    </ul>
  </section>

  <!-- 模块三：21 - 28 -->
  <section id="module-3" class="module-section">
    <div class="module-header">
      <h2 class="module-title">模块三｜突发危机与合规避坑篇</h2>
      <span class="module-meta">MODULE 03 · ISSUES 21–28</span>
    </div>
    <ul class="guide-list">
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/021-bc-food-safety-health-inspection-sop/">
          <span class="guide-num">21</span>
          <span class="guide-text">食品安全与监管危机：卫生局检查合规、餐盒存储风险与餐饮创业避雷</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/022-ecommerce-suspension-poa-data-decoupling/">
          <span class="guide-num">22</span>
          <span class="guide-text">电商平台封店自救：亚马逊/电商账号下架申诉与第一方数据备份解耦</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/023-supply-chain-delivery-crisis-sop/">
          <span class="guide-num">23</span>
          <span class="guide-text">供应链中断与交付危机：大订单交不出货时的产能调配与客户信任保护</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/024-canada-us-tariff-compliance-hedging/">
          <span class="guide-num">24</span>
          <span class="guide-text">加美关税避险与成本转移：Tariff Finder 工具、CUSMA 原产地穿透与 75 亿救济包</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/025-canada-shareholder-agreement-usa/">
          <span class="guide-num">25</span>
          <span class="guide-text">合伙人纠纷防线：股东协议（USA）必含的 13 个股权退场、防僵局与竞业条款</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/026-cra-tax-audit-etransfer-vdp-sop/">
          <span class="guide-num">26</span>
          <span class="guide-text">CRA 税务稽查自救：E-transfer 收款查税逻辑、净资产审计与 VDP 自愿披露救命新政</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/027-brick-and-mortar-pivot-b2b-asset-light/">
          <span class="guide-num">27</span>
          <span class="guide-text">实体店转轻资产 B2B：租约转让换现金、爆款预制标准化与退守共享厨房 4 步 SOP</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
      <li class="guide-item">
        <a class="guide-link" href="/business/guide/028-business-exit-valuation-lcge-tax-free/">
          <span class="guide-num">28</span>
          <span class="guide-text">商业估值与合规退出：SDE/EBITDA 估值模型、尽调清理与 $127.5 万 LCGE 免税套现</span>
          <span class="guide-arrow">→</span>
        </a>
      </li>
    </ul>
  </section>

  <!-- 底部邮箱订阅 -->
  <div class="guide-subscribe">
    <div class="guide-subscribe-copy">
      <strong>订阅 As We Build 北美商业笔记</strong>
      <span>获取最新加拿大创业实盘拆解、政策变动与合规清单更新</span>
    </div>
    <form action="https://submit-form.com/kxienKoQo" method="POST">
      <input type="checkbox" name="_honey" style="display:none" tabindex="-1" autocomplete="off" />
      <input type="email" name="email" placeholder="输入常用邮箱..." required />
      <button type="submit">免费订阅</button>
    </form>
  </div>

</div>