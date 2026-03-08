<template>
  <div class="site-shell">
    <section class="hero">
      <div class="hero-copy">
        <p class="eyebrow">Hearts of Iron IV Code Studio</p>
        <h1>HOICS</h1>
        <p class="lead">
          一个使用Tauri+ Vue 的面向 HOI4 Mod 开发的现代化非Vscode分支IDE，目标是可视化编程与直接代码共存的HOI4 Mod编写。
        </p>

        <div class="hero-actions">
          <a class="button primary" href="https://github.com/cyberlieflife/HOI4-Code-Studio" target="_blank" rel="noreferrer">
            查看 GitHub
          </a>
          <a class="button secondary" href="#features">了解功能</a>
        </div>
      </div>

      <div class="hero-card">
        <div class="window-dots">
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="mock-panel">
          <div class="mock-sidebar">
            <div class="mock-pill active">Project</div>
            <div class="mock-pill">Editor</div>
            <div class="mock-pill">AI</div>
            <div class="mock-pill">Docs</div>
          </div>
          <div class="mock-editor">
            <div class="mock-file">common / bop / RSC_BOP.txt</div>
            <pre>RSC_KDR_bop = {
	initial_value = 0.5
	left_side = RSC_build_side
	right_side = RSC_science_side
	decision_category = RSC_KDR_bop_category
	
	range = {
		id = mid_range
		min = -0.25
		max = 0.25
	</pre>
          </div>
        </div>
      </div>
    </section>

    <section id="features" class="section">
      <div class="section-heading">
        <p class="eyebrow">核心方向</p>
        <h2>让 HOI4 Mod 开发更快速</h2>
      </div>

      <div class="feature-grid">
        <article class="feature-card">
          <h3>依赖项</h3>
          <p>面向Sub Mod开发者与本地化翻译，快速查找原Mod内容或.yml文件以校对或更改。</p>
        </article>

        <article class="feature-card">
          <h3>预览支持</h3>
          <p>以Vscode插件为参考的将预览功能从需要单独查找插件下载移植为内置组件，支持国策/MIO/科技树/事件关系/地图/特殊格式图片/gfx预览。</p>
        </article>

        <article class="feature-card">
          <h3>国策预览和编辑</h3>
          <p>让你可以在国策预览界面快速的增删国策和修改国策，同时自动抓取本地化文件并显示本地化内容。</p>
        </article>

        <article class="feature-card">
          <h3>语法补全/模板插入</h3>
          <p>索引依赖项，项目内，游戏本体的Tag和Idea和关键字进行语法补全，同时允许你在特定文件夹内插入模板以快速填充编写Mod。</p>
        </article>
      </div>
    </section>

    <section class="section split-section">
      <div class="split-card">
        <p class="eyebrow">当前状态</p>
        <h2>还在持续迭代</h2>
        <p>
          HOICS 仍旧在更新与修复新BUG 同时我们欢迎您发起issue PR 或讨论以改进HOICS。
        </p>
      </div>

      <div class="split-card">
        <p class="eyebrow">下一步</p>
        <ul class="roadmap-list">
          <li>国际化......</li>
          <li>完善错误提示和语法补全......</li>
          <li>完善扩展功能......</li>
        </ul>
      </div>
    </section>

    <section class="section cta-section">
      <div>
        <p class="eyebrow">Get involved</p>
        <h2>关注项目进展</h2>
        <p>
          如果你对 本工具开发感兴趣，烦请从仓库和后续更新关注后续走向。
        </p>
      </div>

      <a class="button primary" href="https://github.com/cyberlieflife/HOI4-Code-Studio" target="_blank" rel="noreferrer">
        前往仓库
      </a>
    </section>
  </div>
</template>
