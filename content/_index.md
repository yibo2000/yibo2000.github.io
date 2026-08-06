---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: markdown
    id: hero
    content:
      title: ''
      text: |-
        <div class="hero">
          <div class="hero-top">
            <img class="hero-avatar" src="/uploads/avatar.webp?v=2" alt="Yibo He"
                 width="344" height="344" fetchpriority="high" decoding="async">
            <div>
              <h1 class="hero-name">Yibo He</h1>
              <p class="hero-role">Member of Technical Staff · <b>RL Team @ Moonshot AI (Kimi)</b><br>
              Ph.D. student · <b>School of Computer Science @ Peking University</b></p>
              <p class="hero-bio">I am a Member of Technical Staff at Moonshot AI (Kimi) and a Ph.D.
              student in Computer Science at Peking University, advised by Prof. <a href="https://taoxiease.github.io" target="_blank" rel="noopener">Tao Xie</a>.
              Prior to my Ph.D., I received my B.Sc. in Computer Science, also from
              Peking University. My current work focuses on post-training LLMs for coding agents,
              targeting challenging, long-horizon agentic tasks in real-world software engineering.
              This involves RL environments, synthetic data generation, trajectory filtering,
              SFT/RL, and evaluation across diverse coding domains.
              My research also spans compiler fuzzing, benchmarking code LLMs, and test generation.</p>
            </div>
          </div>
          <div class="hero-links">
            <a class="hpill" href="mailto:yibohe@pku.edu.cn">Email</a>
            <a class="hpill" href="https://github.com/yibo2000" target="_blank" rel="noopener">GitHub</a>
            <a class="hpill" href="https://orcid.org/0009-0002-1999-436X" target="_blank" rel="noopener">ORCID</a>
            <a class="hpill hpill-qr" href="/uploads/wechat-qr.jpg?v=2" target="_blank" rel="noopener">WeChat
              <img class="qr-pop" src="/uploads/wechat-qr.jpg?v=2" alt="WeChat QR code">
            </a>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["2.5rem", "0", "1rem", "0"]

  - block: markdown
    id: models
    content:
      title: ''
      text: |-
        <div class="strip-head">
          <div>
            <h2 class="sec-title">Models</h2>
            <p class="sec-sub">Foundation models I contribute to.</p>
          </div>
          <div class="strip-nav">
            <button class="strip-btn" type="button" aria-label="Scroll left"
              data-strip-scroll="-1" aria-controls="model-strip">←</button>
            <button class="strip-btn" type="button" aria-label="Scroll right"
              data-strip-scroll="1" aria-controls="model-strip">→</button>
          </div>
        </div>
        <div class="model-strip" id="model-strip">
          <a class="model-card" href="https://www.kimi.com/blog/kimi-k3" target="_blank" rel="noopener">
            <div class="model-cover">
              <img src="/uploads/kimi-k3.webp" alt="Kimi K3" loading="lazy">
              <div class="model-cover-meta">
                <span class="model-year">2026 · Moonshot AI</span>
                <h3>Kimi K3</h3>
              </div>
            </div>
            <div class="model-body">
              <p>Open frontier intelligence.</p>
              <span class="model-role">Contributor</span>
            </div>
          </a>
          <a class="model-card" href="https://www.kimi.com/resources/kimi-k2-7-code" target="_blank" rel="noopener">
            <div class="model-cover">
              <img src="/uploads/kimi-k27-official.webp" alt="Kimi K2.7" loading="lazy">
              <div class="model-cover-meta">
                <span class="model-year">2026 · Moonshot AI</span>
                <h3>Kimi K2.7 Code</h3>
              </div>
            </div>
            <div class="model-body">
              <p>Open-source agentic coding model.</p>
              <span class="model-role">Contributor</span>
            </div>
          </a>
          <a class="model-card" href="https://www.kimi.com/blog/kimi-k2-6" target="_blank" rel="noopener">
            <div class="model-cover">
              <img src="/uploads/kimi-k26.webp" alt="Kimi K2.6" loading="lazy">
              <div class="model-cover-meta">
                <span class="model-year">2026 · Moonshot AI</span>
                <h3>Kimi K2.6</h3>
              </div>
            </div>
            <div class="model-body">
              <p>Advancing open-source coding.</p>
              <span class="model-role">Contributor</span>
            </div>
          </a>
          <a class="model-card" href="https://www.kimi.com/blog/kimi-k2-5" target="_blank" rel="noopener">
            <div class="model-cover">
              <img src="/uploads/kimi-k25.webp" alt="Kimi K2.5" loading="lazy">
              <div class="model-cover-meta">
                <span class="model-year">2026 · Moonshot AI</span>
                <h3>Kimi K2.5</h3>
              </div>
            </div>
            <div class="model-body">
              <p>Visual agentic intelligence.</p>
              <span class="model-role">Contributor</span>
            </div>
          </a>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["2.5rem", "0", "2rem", "0"]

  - block: markdown
    id: experience
    content:
      title: ''
      text: |-
        <div class="two-col">
          <div class="col">
            <h2 class="sec-title">Experience</h2>
            <div class="exp-list">
              <div class="exp-item">
                <img class="exp-logo" src="/uploads/logos/moonshot.png" alt="Moonshot AI">
                <div class="exp-main">
                  <div class="exp-row">
                    <span class="exp-org">Moonshot AI · RL Team</span>
                    <span class="exp-date">Dec 2025 – Present</span>
                  </div>
                  <p class="exp-role">Intern → Member of Technical Staff</p>
                </div>
              </div>
              <div class="exp-item">
                <img class="exp-logo" src="/uploads/logos/wechat.svg" alt="WeChat">
                <div class="exp-main">
                  <div class="exp-row">
                    <span class="exp-org">Tencent · WXG</span>
                    <span class="exp-date">Summer 2025</span>
                  </div>
                  <p class="exp-role">Research Intern · Rhino-Bird Research Elite Program</p>
                </div>
              </div>
              <div class="exp-item">
                <img class="exp-logo" src="/uploads/logos/alibabadotcom.svg" alt="Alibaba DAMO Academy">
                <div class="exp-main">
                  <div class="exp-row">
                    <span class="exp-org">Alibaba · DAMO Academy</span>
                    <span class="exp-date">Jun 2024 – Jun 2025</span>
                  </div>
                  <p class="exp-role">Research Collaborator</p>
                </div>
              </div>
              <div class="exp-item">
                <img class="exp-logo" src="/uploads/logos/bytedance.png" alt="ByteDance">
                <div class="exp-main">
                  <div class="exp-row">
                    <span class="exp-org">ByteDance · Seed</span>
                    <span class="exp-date">Oct 2023 – Feb 2024</span>
                  </div>
                  <p class="exp-role">Research Intern</p>
                </div>
              </div>
              <div class="exp-item">
                <img class="exp-logo" src="/uploads/logos/alibabadotcom.svg" alt="Alibaba">
                <div class="exp-main">
                  <div class="exp-row">
                    <span class="exp-org">Alibaba · Taobao</span>
                    <span class="exp-date">Summer 2021</span>
                  </div>
                  <p class="exp-role">Development Intern</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col col-edu">
            <h2 class="sec-title">Education</h2>
            <div class="exp-list">
              <div class="exp-item">
                <img class="exp-logo" src="/uploads/logos/pku.png" alt="Peking University">
                <div class="exp-main">
                  <div class="exp-row">
                    <span class="exp-org">Peking University</span>
                    <span class="exp-date">2022 – 2027 (expected)</span>
                  </div>
                  <p class="exp-role">Ph.D. in Computer Science</p>
                  <p class="exp-desc">Advised by Prof. <a href="https://taoxiease.github.io" target="_blank" rel="noopener">Tao Xie</a>.</p>
                </div>
              </div>
              <div class="exp-item">
                <img class="exp-logo" src="/uploads/logos/pku.png" alt="Peking University">
                <div class="exp-main">
                  <div class="exp-row">
                    <span class="exp-org">Peking University</span>
                    <span class="exp-date">2018 – 2022</span>
                  </div>
                  <p class="exp-role">B.Sc. in Computer Science · Minor in Sociology</p>
                  <p class="exp-desc">Outstanding Undergraduate, Class of 2022.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["2.5rem", "0", "2rem", "0"]

  - block: markdown
    id: papers
    content:
      title: ''
      text: |-
        <h2 class="sec-title">Selected Publications</h2>
        <div class="pub-list">
          <div class="pub-item">
            <div class="pub-row">
              <a class="pub-title" href="https://arxiv.org/abs/2607.24653" target="_blank" rel="noopener">Kimi K3: Open Frontier Intelligence</a>
              <span class="pub-venue">Kimi 2026</span>
            </div>
            <p class="pub-meta">Kimi Team · Technical Report · <i>contributor</i></p>
          </div>
          <div class="pub-item">
            <div class="pub-row">
              <a class="pub-title" href="https://arxiv.org/abs/2602.02276" target="_blank" rel="noopener">Kimi K2.5: Visual Agentic Intelligence</a>
              <span class="pub-venue">Kimi 2026</span>
            </div>
            <p class="pub-meta">Kimi Team · Technical Report · <i>contributor</i></p>
          </div>
          <div class="pub-item">
            <div class="pub-row">
              <a class="pub-title" href="https://dl.acm.org/doi/10.1145/3719027.3744790" target="_blank" rel="noopener">RVISmith: Fuzzing Compilers for RVV Intrinsics</a>
              <span class="pub-venue">CCS 2025</span>
            </div>
            <p class="pub-meta"><b>Yibo He</b>, Cunjian Huang, Xianmiao Qu, Hongdeng Chen, Yang Wei, Tao Xie</p>
          </div>
          <div class="pub-item">
            <div class="pub-row">
              <a class="pub-title" href="https://arxiv.org/abs/2507.15224" target="_blank" rel="noopener">SimdBench: Benchmarking Large Language Models for SIMD-Intrinsic Code Generation</a>
              <span class="pub-venue">Preprint 2025</span>
            </div>
            <p class="pub-meta"><b>Yibo He</b>, Shuoran Zhao, Jiaming Huang, Yingjie Fu, Hao Yu, Peihua Zhang, Tao Xie</p>
          </div>
          <div class="pub-item">
            <div class="pub-row">
              <a class="pub-title" href="https://neurips.cc/virtual/2024/poster/97797" target="_blank" rel="noopener">InfiBench: Evaluating the Question-Answering Capabilities of Code Large Language Models</a>
              <span class="pub-venue">NeurIPS 2024</span>
            </div>
            <p class="pub-meta">Linyi Li, Shijie Geng, Zhenwen Li, <b>Yibo He</b>, Hao Yu, Ziyue Hua, Guanghan Ning, Siwei Wang, Tao Xie, Hongxia Yang</p>
          </div>
          <div class="pub-item">
            <div class="pub-row">
              <a class="pub-title" href="https://doi.org/10.1145/3660785" target="_blank" rel="noopener">An Empirical Study on Focal Methods in Deep-Learning-Based Approaches for Assertion Generation</a>
              <span class="pub-venue">FSE 2024</span>
            </div>
            <p class="pub-meta"><b>Yibo He</b>, Jiaming Huang, Hao Yu, Tao Xie</p>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["2.5rem", "0", "2rem", "0"]

  - block: markdown
    id: honors
    content:
      title: ''
      text: |-
        <div class="two-col">
          <div class="col">
            <h2 class="sec-title">Selected Honors</h2>
            <div class="mini-list">
              <div class="mini-item"><span>Outstanding Graduate</span><span class="mini-date">2022</span></div>
              <div class="mini-item"><span>Award for Scientific Research</span><span class="mini-date">2021</span></div>
              <div class="mini-item"><span>Suzhou Industrial Park Scholarship · Merit Student</span><span class="mini-date">2020</span></div>
              <div class="mini-item"><span>Third Prize Scholarship · Award for Academic Excellence</span><span class="mini-date">2019</span></div>
            </div>
            <p class="mini-note">All at Peking University.</p>
          </div>
          <div class="col col-edu">
            <h2 class="sec-title">Services</h2>
            <div class="mini-list">
              <div class="mini-line"><b>Sub-Reviewer</b> · ASE 2025, ISSTA 2025, FSE 2025, ICSE 2023</div>
              <div class="mini-line"><b>Teaching Assistant</b> · Introduction to Computing (B), Fall 2022; Scientific Writing, Spring 2025</div>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["2.5rem", "0", "2rem", "0"]

---
