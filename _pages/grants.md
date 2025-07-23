---
layout: page
permalink: /grants/
title: Grants
description: List of research grants involving PI and team participation in national-level scientific projects.
nav: true
nav_order: 7
---

---

<button onclick="toggleLang()" style="
  background-color: var(--global-theme-color);
  color: white;
  font-weight: bold;
  border: 2px solid var(--global-theme-color);
  border-radius: 6px;
  padding: 6px 12px;
  cursor: pointer;
  margin-top: -40px;
  float: right;
">
  🌐 Switch Language
</button>

<div id="en-grants" markdown="block">

## 🎯 Principal Investigator

| **Duration**       | **Details** |
|--------------------|-------------|
| Jan 2025 – Present | **Fundamental Research Funds for the Central Universities**  
Grant No.: 12625611  
Funding: ¥100,000  
Role: Principal Investigator |

---

## 🤝 Research Team Member

| Duration       | Details |
|----------------|---------|
| Jan 2022 – Present | **NSFC General Program**  
*Research on Identification and Intervention Methods of Disordered Network Information Dissemination in Crisis Situations*  
Grant No.: 72174153 |
| Dec 2023 – Present | **Major Project of National Social Science Fund of China**  
*Resilient Social Intelligence Support and Decision-making under Uncertain Environments*  
Grant No.: 23&ZD230 |
| Sep 2019 – Present | **NSFC Innovation Research Group Project**  
*Information Resource Management*  
Grant No.: 71921002 |
| Sep 2019 – Present | **NSFC Major Project**  
*National Security Big Data Comprehensive Information Integration and Analysis Methods*  
Grant No.: 71790612 |
| Sep 2019 – Dec 2020 | **Ministry of Education Philosophy and Social Sciences Major Project**  
*Improving Capabilities of Counter-terrorism Intelligence Work*  
Grant No.: 17JZD034 |
</div>

<div id="zh-grants" style="display: none;" markdown="block">

  ## 🎯 主持项目

| **时间**           | **项目内容** |
|--------------------|--------------|
| 2025年 – 至今       | **中央高校基本科研业务费专项资金资助**  
项目编号：12625611  
经费：10万元  
负责人：陈苗苗 |

---

## 🤝 参与项目

| **时间**           | **项目内容** |
|--------------------|--------------|
| 2022年1月 – 至今    | **国家自然科学基金面上项目**  
危机情境下网络信息传播失序识别与干预方法研究  
项目编号：72174153 |
| 2023年12月 – 至今   | **国家社会科学基金重大项目**  
不确定环境下韧性社会智能情报支持与决策研究  
项目编号：23&ZD230 |
| 2019年9月 – 至今    | **国家自然科学基金创新研究群体项目**  
信息资源管理  
项目编号：71921002 |
| 2019年9月 – 至今    | **国家自然科学基金重大项目**  
国家安全大数据综合信息集成与分析方法  
项目编号：71790612 |
| 2019年9月 – 2020年12月 | **教育部哲学社会科学研究重大课题攻关项目**  
提高反恐怖主义情报信息工作能力对策研究  
项目编号：17JZD034 |
</div>

<script>
  function toggleLang() {
    const en = document.getElementById('en-grants');
    const zh = document.getElementById('zh-grants');
    if (en.style.display === 'none') {
      en.style.display = 'block';
      zh.style.display = 'none';
    } else {
      en.style.display = 'none';
      zh.style.display = 'block';
    }
  }
</script>
