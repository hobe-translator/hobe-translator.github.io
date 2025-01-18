---
layout: page
title: About
permalink: /about/
---

<div class="about-content">
  <!-- 英文内容 -->
  <div class="lang-content" id="en-content">
    <h2>About Hobe Translator</h2>
    <p>Hobe Translator is a specialized translation tool focusing on Chinese-Arabic translation. Our mission is to break down language barriers and facilitate communication between Chinese and Arabic speakers.</p>
    
    <h3>Our Features</h3>
    <ul>
      <li>Specialized Chinese-Arabic translation</li>
      <li>Clean and intuitive interface</li>
      <li>Full RTL support</li>
      <li>Voice input and playback</li>
      <li>Smart translation optimization</li>
    </ul>
  </div>

  <!-- 阿拉伯语内容 -->
  <div class="lang-content" id="ar-content" dir="rtl">
    <h2>حول مترجم هوبي</h2>
    <p>مترجم هوبي هو أداة ترجمة متخصصة تركز على الترجمة بين اللغتين الصينية والعربية. مهمتنا هي كسر حواجز اللغة وتسهيل التواصل بين المتحدثين باللغتين الصينية والعربية.</p>
    
    <h3>مميزاتنا</h3>
    <ul>
      <li>ترجمة متخصصة بين الصينية والعربية</li>
      <li>واجهة نظيفة وبديهية</li>
      <li>دعم كامل للكتابة من اليمين إلى اليسار</li>
      <li>إدخال صوتي وتشغيل</li>
      <li>تحسين ذكي للترجمة</li>
    </ul>
  </div>

  <!-- 中文内容 -->
  <div class="lang-content" id="zh-content">
    <h2>关于 Hobe Translator</h2>
    <p>Hobe Translator 是一款专注于中阿互译的翻译工具。我们的使命是打破语言障碍，促进中文和阿拉伯语使用者之间的交流。</p>
    
    <h3>我们的特点</h3>
    <ul>
      <li>专注中阿互译</li>
      <li>简洁直观的界面</li>
      <li>完整的 RTL 支持</li>
      <li>语音输入和播放</li>
      <li>智能翻译优化</li>
    </ul>
  </div>
</div>

<style>
.about-content {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem 0;
}

.lang-content {
  display: none;
}

html[lang="en"] #en-content,
html[lang="ar"] #ar-content,
html[lang="zh"] #zh-content {
  display: block;
}

.lang-content h2 {
  color: var(--text-color);
  margin-bottom: 1.5rem;
}

.lang-content h3 {
  color: var(--text-color);
  margin: 2rem 0 1rem;
}

.lang-content ul {
  list-style-type: none;
  padding: 0;
}

.lang-content ul li {
  margin: 0.5rem 0;
  padding-left: 1.5rem;
  position: relative;
}

.lang-content ul li:before {
  content: "•";
  position: absolute;
  left: 0;
  color: var(--text-light);
}

[dir="rtl"] .lang-content ul li {
  padding-left: 0;
  padding-right: 1.5rem;
}

[dir="rtl"] .lang-content ul li:before {
  left: auto;
  right: 0;
}
</style>
