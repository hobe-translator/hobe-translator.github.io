---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div class="language-switcher">
  <button onclick="switchLanguage('en')" class="lang-btn">English</button>
  <button onclick="switchLanguage('ar')" class="lang-btn">العربية</button>
  <button onclick="switchLanguage('zh')" class="lang-btn">中文</button>
</div>

<div class="content-wrapper">
  <!-- 英文内容 -->
  <div class="lang-content" id="en-content">
    <div class="hero">
      <div class="hero-content">
        <img src="/assets/images/Hobe.png" alt="Hobe Logo" class="hero-logo">
        <h1>Hobe Translator</h1>
        <p class="hero-description">Professional Chinese-Arabic Translation Tool</p>
      </div>
    </div>

    <div class="features">
      <div class="feature-section">
        <h2>Elegant Translation Experience</h2>
        <p>Clean interface design with fast translation response makes your translation work easier.</p>
        <div class="screenshots">
          <img src="/assets/images/screen-shot-ar.jpg" alt="Arabic Interface" class="screenshot">
          <img src="/assets/images/screen-shot-en.jpg" alt="English Interface" class="screenshot">
        </div>
      </div>

      <div class="feature-section">
        <h2>Key Features</h2>
        <ul>
          <li>🌐 Bidirectional translation between Chinese and Arabic</li>
          <li>🎯 Translation engine optimized for Arabic</li>
          <li>🎨 Full RTL (Right-to-Left) interface support</li>
          <li>🎤 Voice input and playback support</li>
          <li>✨ Smart translation optimization</li>
        </ul>
      </div>

      <div class="try-section">
        <h2>Try Now</h2>
        <p>Scan QR code to get test Token</p>
        <img src="/assets/images/qrcode.png" alt="Test Token QR Code" class="qr-code">
      </div>
    </div>
  </div>

  <!-- 阿拉伯语内容 -->
  <div class="lang-content" id="ar-content" dir="rtl">
    <div class="hero">
      <div class="hero-content">
        <img src="/assets/images/Hobe.png" alt="Hobe Logo" class="hero-logo">
        <h1>مترجم هوبي</h1>
        <p class="hero-description">أداة احترافية للترجمة بين الصينية والعربية</p>
      </div>
    </div>

    <div class="features">
      <div class="feature-section">
        <h2>تجربة ترجمة أنيقة</h2>
        <p>تصميم واجهة نظيف مع استجابة ترجمة سريعة يجعل عملك في الترجمة أسهل.</p>
        <div class="screenshots">
          <img src="/assets/images/screen-shot-ar.jpg" alt="واجهة عربية" class="screenshot">
          <img src="/assets/images/screen-shot-en.jpg" alt="واجهة إنجليزية" class="screenshot">
        </div>
      </div>

      <div class="feature-section">
        <h2>الميزات الرئيسية</h2>
        <ul>
          <li>🌐 ترجمة ثنائية الاتجاه بين الصينية والعربية</li>
          <li>🎯 محرك ترجمة مُحسّن للغة العربية</li>
          <li>🎨 دعم كامل لواجهة RTL</li>
          <li>🎤 دعم الإدخال الصوتي والتشغيل</li>
          <li>✨ تحسين الترجمة الذكية</li>
        </ul>
      </div>

      <div class="try-section">
        <h2>جرب الآن</h2>
        <p>امسح رمز QR للحصول على رمز الاختبار</p>
        <img src="/assets/images/qrcode.png" alt="رمز QR للاختبار" class="qr-code">
      </div>
    </div>
  </div>

  <!-- 中文内容 -->
  <div class="lang-content" id="zh-content">
    <div class="hero">
      <div class="hero-content">
        <img src="/assets/images/Hobe.png" alt="Hobe Logo" class="hero-logo">
        <h1>Hobe Translator</h1>
        <p class="hero-description">专业的中阿互译工具</p>
      </div>
    </div>

    <div class="features">
      <div class="feature-section">
        <h2>优雅的翻译体验</h2>
        <p>简洁的界面设计，快速的翻译响应，让您的翻译工作更加轻松。</p>
        <div class="screenshots">
          <img src="/assets/images/screen-shot-ar.jpg" alt="阿拉伯语界面" class="screenshot">
          <img src="/assets/images/screen-shot-en.jpg" alt="英语界面" class="screenshot">
        </div>
      </div>

      <div class="feature-section">
        <h2>特色功能</h2>
        <ul>
          <li>🌐 支持中文与阿拉伯语的双向翻译</li>
          <li>🎯 针对阿拉伯语优化的翻译引擎</li>
          <li>🎨 完整支持阿拉伯语从右到左（RTL）的界面布局</li>
          <li>🎤 支持语音输入和语音播放</li>
          <li>✨ 智能优化翻译结果</li>
        </ul>
      </div>

      <div class="try-section">
        <h2>立即体验</h2>
        <p>扫描下方二维码获取测试 Token</p>
        <img src="/assets/images/qrcode.png" alt="测试 Token 二维码" class="qr-code">
      </div>
    </div>
  </div>
</div>

<style>
.language-switcher {
  text-align: center;
  margin: 1rem 0;
}

.lang-btn {
  padding: 0.5rem 1rem;
  margin: 0 0.5rem;
  border: 1px solid #ddd;
  border-radius: 20px;
  background: white;
  cursor: pointer;
  transition: all 0.3s ease;
}

.lang-btn:hover {
  background: #fff5f2;
}

.lang-btn.active {
  background: #ffe4dc;
  border-color: #ffcdb9;
}

.lang-content {
  display: none;
}

.lang-content.active {
  display: block;
}

.hero {
  text-align: center;
  padding: 4rem 0;
  background: linear-gradient(135deg, #fff5f2 0%, #ffe4dc 100%);
  border-radius: 20px;
  margin: 2rem 0;
}

.hero-logo {
  width: 120px;
  height: 120px;
  margin-bottom: 1rem;
}

.hero-description {
  font-size: 1.5rem;
  color: #666;
}

.features {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem 0;
}

.feature-section {
  margin: 4rem 0;
}

.screenshots {
  display: flex;
  gap: 2rem;
  justify-content: center;
  margin: 2rem 0;
  flex-wrap: wrap;
}

.screenshot {
  max-width: 300px;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.feature-section ul {
  list-style: none;
  padding: 0;
}

.feature-section li {
  margin: 1rem 0;
  font-size: 1.1rem;
}

.try-section {
  text-align: center;
  margin: 4rem 0;
}

.qr-code {
  width: 200px;
  margin: 2rem 0;
}

@media (max-width: 768px) {
  .screenshots {
    flex-direction: column;
    align-items: center;
  }
  
  .screenshot {
    max-width: 100%;
  }
}
</style>

<script>
function switchLanguage(lang) {
  // 隐藏所有语言内容
  document.querySelectorAll('.lang-content').forEach(el => {
    el.classList.remove('active');
  });
  
  // 显示选中的语言内容
  document.getElementById(lang + '-content').classList.add('active');
  
  // 更新按钮状态
  document.querySelectorAll('.lang-btn').forEach(btn => {
    btn.classList.remove('active');
  });
  const activeBtn = document.querySelector(`.lang-btn[onclick="switchLanguage('${lang}')"]`);
  if (activeBtn) {
    activeBtn.classList.add('active');
  }

  // 保存语言选择
  localStorage.setItem('preferred-language', lang);
}

// 页面加载时设置默认语言
document.addEventListener('DOMContentLoaded', function() {
  const savedLang = localStorage.getItem('preferred-language') || 'zh';
  switchLanguage(savedLang);
});
</script>
