<template>
  <div class="site-shell">
    <section class="hero">
      <div class="hero-copy">
        <p class="eyebrow">Hearts of Iron IV Code Studio</p>
        <h1>HOICS</h1>
        <p class="lead">
          一个面向 HOI4 Mod 开发的现代化工作台，目标是把项目管理、脚本编辑、资料整理与 AI
          辅助放进同一个流畅界面里。
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
            <div class="mock-file">common / ideas / industry.txt</div>
            <pre>idea_category = {
  industrial_push = {
    picture = industrial_push
    modifier = {
      production_factory_max_efficiency_factor = 0.05
      industrial_capacity_factory = 0.1
    }
  }
}</pre>
          </div>
        </div>
      </div>
    </section>

    <section id="features" class="section">
      <div class="section-heading">
        <p class="eyebrow">核心方向</p>
        <h2>让 HOI4 Mod 开发更顺手</h2>
      </div>

      <div class="feature-grid">
        <article class="feature-card">
          <h3>项目工作台</h3>
          <p>围绕 Mod 项目组织目录、配置、依赖与常用入口，减少在文件夹和工具之间来回切换。</p>
        </article>

        <article class="feature-card">
          <h3>脚本编辑体验</h3>
          <p>面向 Paradox 脚本语境设计的编辑与预览能力，让修改、检查和定位问题更直接。</p>
        </article>

        <article class="feature-card">
          <h3>文档与资料整合</h3>
          <p>把常用规则、说明和开发资料收在同一界面里，写脚本时不用频繁切屏检索。</p>
        </article>

        <article class="feature-card">
          <h3>AI 辅助开发</h3>
          <p>为规划、问答、代码生成和任务拆解预留统一入口，后续会逐步完善接线与交互体验。</p>
        </article>
      </div>
    </section>

    <section class="section split-section">
      <div class="split-card">
        <p class="eyebrow">当前状态</p>
        <h2>还在持续迭代</h2>
        <p>
          HOICS 现在更像一个正在成形的开发平台：基础界面和部分能力已经落地，更多高级特性会继续补完。
        </p>
      </div>

      <div class="split-card">
        <p class="eyebrow">下一步</p>
        <ul class="roadmap-list">
          <li>整理官网内容与下载入口</li>
          <li>补充截图、演示和路线图</li>
          <li>继续打磨 AI 与编辑器相关体验</li>
          <li>完善对 HOI4 Mod 工作流的支持</li>
        </ul>
      </div>
    </section>

    <section class="section cta-section">
      <div>
        <p class="eyebrow">Get involved</p>
        <h2>关注项目进展</h2>
        <p>
          如果你对 HOI4 Mod 工具、脚本体验或 AI 辅助开发感兴趣，可以先从仓库和后续更新开始关注。
        </p>
      </div>

      <a class="button primary" href="https://github.com/cyberlieflife/HOI4-Code-Studio" target="_blank" rel="noreferrer">
        前往仓库
      </a>
    </section>
  </div>
</template>
