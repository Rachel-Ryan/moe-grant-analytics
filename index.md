<div class="page-content">

<div class="text-section">
<h1>2025年度教育部人文社科基金立项数据可视化</h1>
<p>本文集是微信公众号文章 <strong>《2025年度教育部人文社会科学项目立项结果可视化分析》</strong> 的配套高清可视化图表库。所有图表均可点击放大查看，交互式网络图可进入专属页面进行探索。</p>
</div>

<div class="text-section">
<h2>🔗 代码与数据下载 (Code & Data Download)</h2>
<p>为了方便同行对本研究进行复现或扩展，我们提供了完整的分析代码与所用数据。</p>
<div style="margin-top: 1.5rem; margin-bottom: 1.5rem;">
    <a href="./downloads/code.zip" class="interactive-link" style="background-color: #28a745; display: inline-block; margin-right: 1rem; margin-bottom: 0.5rem;">💾 下载分析代码 (code.zip)</a>
    <a href="./downloads/data.zip" class="interactive-link" style="display: inline-block; margin-bottom: 0.5rem;">📊 下载项目数据 (data.zip)</a>
</div>
<blockquote>
<strong>运行建议：</strong><br>
本项目代码与数据环境较为标准。建议直接将 <code>code.zip</code> 和 <code>data.zip</code> 上传并解压至 <strong>Kaggle</strong> 或 <strong>阿里云魔搭 (ModelScope)</strong> 的 Notebook 环境中，根据解压后的实际路径，修改代码文件开头部分的文件读取地址，即可直接运行，复现全部结果。
</blockquote>
</div>

## 一、宏观鸟瞰分析 (Macro Overview)

<div class="grid-container">

  <div class="grid-item">
    <img src="./assets/images/discipline_distribution_analysis.png" alt="各学科门类分布柱状图">
    <div class="item-content">
      <h3>1. 各学科门类分布</h3>
    </div>
  </div>

  <div class="grid-item">
    <img src="./assets/images/project_category_analysis_revised_smallpie.png" alt="项目类别分布饼图">
    <div class="item-content">
      <h3>2. 项目类别分布</h3>
    </div>
  </div>

  <div class="grid-item">
    <img src="./assets/images/top20_universities_analysis.png" alt="机构分布柱状图">
    <div class="item-content">
      <h3>3. 机构分布 (TOP 20)</h3>
    </div>
  </div>
  
  <div class="grid-item">
    <img src="./assets/images/province_distribution_analysis.png" alt="省份分布柱状图">
    <div class="item-content">
      <h3>4. 地域分布 (按省份)</h3>
    </div>
  </div>

  <div class="grid-item">
    <img src="./assets/images/region_distribution_analysis.png" alt="地区分布柱状图">
    <div class="item-content">
      <h3>5. 地域分布 (按地区)</h3>
    </div>
  </div>

</div>


## 二、项目名称高频词分析 (High-Frequency Word Analysis)

<div class="grid-container">

  <div class="grid-item">
    <img src="./assets/images/top_6_words_barchart_overall.png" alt="全部项目高频词柱状图">
    <div class="item-content">
      <h3>1. 全部项目高频词 (词频)</h3>
    </div>
  </div>
  
  <div class="grid-item">
    <img src="./assets/images/wordcloud_overall.png" alt="全部项目词云">
    <div class="item-content">
      <h3>2. 全部项目词云</h3>
    </div>
  </div>
  
  <div class="grid-item">
    <img src="./assets/images/top_13_words_barchart_management.png" alt="管理学项目高频词柱状图">
    <div class="item-content">
      <h3>3. 管理学项目高频词 (词频)</h3>
    </div>
  </div>

  <div class="grid-item">
    <img src="./assets/images/wordcloud_management.png" alt="管理学项目词云">
    <div class="item-content">
      <h3>4. 管理学项目词云</h3>
    </div>
  </div>

  <div class="grid-item">
    <img src="./assets/images/top_5_words_barchart_cross.png" alt="交叉学科项目高频词柱状图">
    <div class="item-content">
      <h3>5. 交叉学科项目高频词 (词频)</h3>
    </div>
  </div>

  <div class="grid-item">
    <img src="./assets/images/wordcloud_cross.png" alt="交叉学科项目词云">
    <div class="item-content">
      <h3>6. 交叉学科项目词云</h3>
    </div>
  </div>

</div>


## 三、关键词共现网络 (Keyword Co-occurrence Networks)
<p>为了获得最佳体验，请点击下方链接在新窗口中打开动态交互式网络图。</p>

<div class="grid-container">

  <div class="grid-item">
    <img src="./assets/images/keyword_co-occurrence_network_overall.png" alt="全部项目关键词共现网络静态图预览" style="background-color: #eee;">
    <div class="item-content">
      <h3>1. 全部项目关键词共现网络</h3>
      <a href="./interactive/interactive_keyword_network_overall.html" target="_blank" class="interactive-link">🔗 打开动态交互网络图</a>
    </div>
  </div>

  <div class="grid-item">
    <img src="./assets/images/keyword_co-occurrence_network_management.png" alt="管理学项目关键词共现网络静态图预览" style="background-color: #eee;">
    <div class="item-content">
      <h3>2. 管理学项目关键词共现网络</h3>
      <a href="./interactive/interactive_keyword_network_management.html" target="_blank" class="interactive-link">🔗 打开动态交互网络图</a>
    </div>
  </div>
  
  <div class="grid-item">
    <img src="./assets/images/keyword_co-occurrence_network_cross.png" alt="交叉学科项目关键词共现网络静态图预览" style="background-color: #eee;">
    <div class="item-content">
      <h3>3. 交叉学科项目关键词共现网络</h3>
      <a href="./interactive/interactive_keyword_network_cross.html" target="_blank" class="interactive-link">🔗 打开动态交互网络图</a>
    </div>
  </div>

</div>

<div class="text-section" style="text-align: center; margin-top: 2rem; color: #6c757d;">
  <p><em>分析与可视化 by Ryan, 2025-09-28</em></p>
</div>

</div>```

---
