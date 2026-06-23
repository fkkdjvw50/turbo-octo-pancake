# turbo-octo-pancake
三江云起 嘉州入画
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>三江云起・嘉州入画</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="hero" id="home">
    <div class="hero-overlay"></div>
    <div class="hero-mesh"></div>
    <div class="hero-particles" id="heroParticles" aria-hidden="true"></div>
    <div class="hero-glow hero-glow-1"></div>
    <div class="hero-glow hero-glow-2"></div>

    <nav class="navbar">
      <div class="logo">三江云起</div>
      <ul class="nav-links">
        <li><a href="#intro">城市引入</a></li>
        <li><a href="#landmarks">山水入卷</a></li>
        <li><a href="#heritage">烟火传承</a></li>
        <li><a href="#routes">智慧路线</a></li>
        <li><a href="#green">绿色出行</a></li>
      </ul>
      <div class="theme-tools">
        <select id="colorThemeSelect" class="theme-select">
          <option value="theme-shanshui">山水青</option>
          <option value="theme-gold">佛光金</option>
          <option value="theme-bamboo">竹影绿</option>
          <option value="theme-warm">嘉州暖橙</option>
        </select>
        <button id="themeBtn" class="theme-btn">夜间模式</button>
      </div>
    </nav>

    <div class="hero-content">
      <div class="hero-left hero-parallax" data-depth="16">
        <div class="hero-line hero-animate delay-1">
          <span></span>
          <p>AI网页设计美育作品 · 乐山地域风情与文旅宣传</p>
        </div>

        <p class="hero-year hero-animate delay-1">2026 CREATIVE WEB DESIGN</p>

        <h1 class="hero-animate delay-2">三江云起<br>嘉州入画</h1>

        <p class="subtitle hero-animate delay-3">
          以数字艺术重构乐山山水意境，在网页交互中展开一幅兼具人文温度与文旅气质的嘉州长卷。
        </p>

        <div class="hero-buttons hero-animate delay-4">
          <a href="#intro" class="btn primary">展开长卷</a>
          <a href="#routes" class="btn secondary">智慧路线</a>
        </div>
      </div>

      <aside class="hero-right hero-parallax hero-animate delay-4" data-depth="10">
        <div class="hero-award-card">
          <p class="award-tag">DESIGN CONCEPT</p>
          <h3>一城山水 · 一页嘉州</h3>
          <p>
            以乐山大佛远景为核心视觉，结合金色光感、山水色系与地图式交互，
            让网页成为兼具文化传播、审美表达与数字体验的文旅展示窗口。
          </p>
        </div>
      </aside>
    </div>
  </header>

  <main>
    <section class="section intro-page-final" id="intro">
      <div class="intro-final-inner">
        <div class="section-heading section-heading-upgraded intro-final-heading force-left-title">
          <div class="section-heading-main">
            <span class="section-index">01</span>
            <h2>三江云起，嘉州入画</h2>
          </div>
          <p class="section-kicker">CITY PORTRAIT</p>
        </div>

        <div class="intro-final-layout">
          <div class="intro-final-left">
            <div class="intro-final-visual page-panel">
              <div class="intro-cube-slider" id="introCubeSlider">
                <div class="cube-stage">
                  <div class="cube-panel cube-current">
                    <img id="cubeCurrentImage" src="images/intro-main.jpg" alt="乐山山水轮播图" />
                  </div>
                  <div class="cube-panel cube-next">
                    <img id="cubeNextImage" src="images/culture-dafo.jpg" alt="乐山山水轮播图" />
                  </div>
                </div>
              </div>

              <div class="intro-final-visual-copy">
                <span class="mini-label">JIAZHOU LANDSCAPE</span>
                <h3>云起三江之间，展开嘉州长卷</h3>
                <p>从三江汇流的浩荡，到峨眉云海的空灵；从大佛临江的庄严，到街巷烟火的鲜活，嘉州之美在一屏之间徐徐入画。</p>
              </div>
            </div>

            <div class="intro-final-copy premium-panel">
              <div class="intro-copy-side">
                <div class="intro-copy-mark">嘉州</div>

                <div class="intro-copy-meta">
                  <span>JIAZHOU MEMORY</span>
                  <ul>
                    <li>山在城边</li>
                    <li>江从城过</li>
                    <li>烟火入巷</li>
                  </ul>
                </div>
              </div>

              <div class="intro-copy-main single-column">
                <div class="intro-copy-block">
                  <p>
                    乐山，古称嘉州。这里山在城边，江从城过，佛立山间，烟火藏于街巷。
                    三江汇流、峨眉云海、嘉州美食与非遗民俗，共同构成这座城市独特的山水气质与人文风貌。
                  </p>
                </div>

                <div class="intro-copy-block">
                  <p>
                    本作品以"乐山地域风情与文旅宣传"为主题，尝试以数字网页的方式重组城市记忆，
                    将自然景观、文化地标、生活烟火与智慧出行融入同一幅"云端长卷"。
                  </p>
                </div>

                <div class="intro-copy-quote">
                  <span>云起三江，城入长卷，嘉州之美不止可见，更可感知。</span>
                </div>
              </div>
            </div>
          </div>

          <div class="intro-final-right">
            <div class="intro-profile-final premium-panel">
              <span class="mini-label">CITY PROFILE</span>

              <div class="intro-profile-final-list">
                <div class="intro-profile-final-item">
                  <div>
                    <h4>山水之城</h4>
                    <p>三江汇流、峨眉叠翠、大佛临江，共同勾勒乐山最鲜明的自然轮廓。</p>
                  </div>
                  <span>NATURE</span>
                </div>

                <div class="intro-profile-final-item">
                  <div>
                    <h4>人文之城</h4>
                    <p>佛教文化、古城记忆、非遗民俗与地方技艺，延续着嘉州深厚文脉。</p>
                  </div>
                  <span>CULTURE</span>
                </div>

                <div class="intro-profile-final-item">
                  <div>
                    <h4>烟火之城</h4>
                    <p>跷脚牛肉、钵钵鸡、古镇茶馆与街巷灯火，让城市保有真实温度。</p>
                  </div>
                  <span>LIFE</span>
                </div>
              </div>

              <div class="intro-profile-stats">
                <span>三江汇流</span>
                <span>佛教名城</span>
                <span>烟火嘉州</span>
              </div>
            </div>

            <div class="intro-final-side-image page-panel">
              <img src="images/intro-food.jpg" alt="乐山街巷烟火与嘉州美食" />
              <div class="intro-final-side-overlay">
                <span>烟火嘉州</span>
                <p>从街巷美食到古镇茶馆，看见乐山最鲜活的生活日常。</p>
              </div>
            </div>
          </div>
        </div>

        <div class="intro-final-tags">
          <span>三江汇流</span>
          <span>峨眉云海</span>
          <span>乐山大佛</span>
          <span>嘉州美食</span>
          <span>非遗民俗</span>
        </div>
      </div>
    </section>

    <section class="section story-page landmarks-page" id="landmarks">
    <div class="story-page-inner">
      <div class="section-heading section-heading-upgraded force-left-title">
        <div class="section-heading-main">
          <span class="section-index">02</span>
          <h2>山水入卷</h2>
        </div>
        <p class="section-kicker">LANDMARKS</p>
      </div>

      <div class="story-page-body equal-column-page landmarks-page-body">
        <article
          class="page-panel landmark-card culture-card photo-card"
          data-title="乐山大佛"
          data-en="WORLD ICON"
          data-image="images/culture-dafo.jpg"
          data-lead="乐山大佛依山临江，气势恢宏，是中国古代石刻艺术与宗教文化融合的重要代表，也是乐山最具辨识度的文化地标。"
          data-highlight="大佛通高宏伟，临三江而立，兼具宗教信仰、工程智慧与石刻艺术价值。从山门、栈道到江面远眺，不同角度都能形成极具震撼力的视觉体验。"
          data-value="它不仅承载着嘉州深厚的历史文脉，也体现了中国古代工匠对于自然地形、雕刻技艺和精神信仰的综合理解，是乐山文化形象的重要象征。"
          data-experience="推荐白天近距离参观凌云寺与九曲栈道，再乘船从江面远眺大佛全貌，能够更完整地感受其山佛一体、江山相映的壮阔格局。"
          data-tags="乐山地标,世界文化景观,佛教文化,石刻艺术,三江汇流">
          <img src="images/culture-dafo.jpg" alt="乐山大佛" />
          <div class="landmark-card-overlay">
            <span class="card-label">WORLD ICON</span>
            <h3>乐山大佛</h3>
            <p>千年石刻与三江交汇，共同构成嘉州最具辨识度的文化地标。</p>
            <div class="landmark-card-meta">
              <span>石刻艺术</span>
              <span>佛教文化</span>
            </div>
          </div>
        </article>

        <article
          class="page-panel landmark-card culture-card photo-card"
          data-title="峨眉山"
          data-en="MOUNTAIN SPIRIT"
          data-image="images/culture-emei.jpg"
          data-lead="峨眉山兼具自然奇景与佛教文化，云海、金顶、古寺与山林共同构成富有东方诗意的山岳景观。"
          data-highlight="从低山森林到高处云海，峨眉山层次丰富，景观变化鲜明。晨雾、日出、古寺钟声与山路林影，共同塑造出极具审美气质的山岳空间。"
          data-value="它不仅是著名自然景观，也承载佛教文化传播、传统审美意象和生态价值，是乐山文旅体系中最具精神气质的一部分。"
          data-experience="推荐清晨观云海，白天游古寺、傍晚看山林光影变化。若时间充裕，可结合轻徒步与静观体验，更能感受峨眉山的空灵与沉静。"
          data-tags="峨眉云海,佛教名山,自然景观,山岳美学,东方意境">
          <img src="images/culture-emei.jpg" alt="峨眉山" />
          <div class="landmark-card-overlay">
            <span class="card-label">MOUNTAIN SPIRIT</span>
            <h3>峨眉山</h3>
            <p>秀甲天下的山岳风景，承载自然意境与人文精神。</p>
            <div class="landmark-card-meta">
              <span>峨眉云海</span>
              <span>东方意境</span>
            </div>
          </div>
        </article>
      </div>

      <div class="page-tags">
        <span>乐山大佛</span>
        <span>峨眉山</span>
        <span>佛教文化</span>
        <span>山岳美学</span>
        <span>城市地标</span>
      </div>
    </div>
  </section>

    <section class="section story-page heritage-page" id="heritage">
    <div class="story-page-inner">
      <div class="section-heading section-heading-upgraded force-left-title">
        <div class="section-heading-main">
          <span class="section-index">03</span>
          <h2>烟火成章</h2>
        </div>
        <p class="section-kicker">LOCAL HERITAGE</p>
      </div>

      <div class="story-page-body equal-column-page heritage-page-body">
        <article
          class="page-panel heritage-card culture-card photo-card"
          data-title="嘉州美食"
          data-en="CITY FLAVOR"
          data-image="images/culture-food.jpg"
          data-lead="乐山美食极具烟火气，跷脚牛肉、钵钵鸡、甜皮鸭、豆腐脑等都是城市味觉记忆的重要组成部分。"
          data-highlight="乐山饮食以鲜、香、麻、暖和街巷生活感见长，不同小吃共同构成城市最鲜活的日常风景，也最容易让游客建立对城市的亲近感。"
          data-value="嘉州美食不仅是味觉体验，更是地方生活方式、社交节奏与市井文化的体现，是乐山文旅传播中最有温度、最有参与感的内容之一。"
          data-experience="推荐在张公桥、苏稽古镇或街巷老店中边走边吃，既能感受本地人的生活节奏，也能在真实场景中体验乐山烟火城市的魅力。"
          data-tags="跷脚牛肉,钵钵鸡,甜皮鸭,豆腐脑,烟火乐山">
          <img src="images/culture-food.jpg" alt="嘉州美食" />
          <div class="heritage-card-overlay">
            <span class="card-label">CITY FLAVOR</span>
            <h3>嘉州美食</h3>
            <p>从街头巷尾到古镇茶馆，乐山的味道总是热烈而鲜活。</p>
            <div class="heritage-card-meta">
              <span>跷脚牛肉</span>
              <span>钵钵鸡</span>
              <span>甜皮鸭</span>
            </div>
          </div>
        </article>

        <article
          class="page-panel heritage-card culture-card photo-card"
          data-title="非遗民俗"
          data-en="LIVING HERITAGE"
          data-image="images/culture-folk.jpg"
          data-lead="乐山地区拥有丰富的地方民俗与非遗文化资源，如传统手工艺、茶文化与民间技艺等，是地方记忆的重要载体。"
          data-highlight="非遗内容往往保留着最细腻的地方生活印记，从竹编、手作到茶馆文化，它们不仅是技艺展示，更是人与土地、人与日常关系的延续。"
          data-value="这些民俗与技艺让乐山的文化表达不止停留在名山大佛，也让城市拥有更具体、更温暖、更可持续传播的人文内容。"
          data-experience="推荐在古镇街巷、手作空间或茶文化场景中进行沉浸式体验，通过观察、交流与参与，感受乐山文化在当代生活中的延续方式。"
          data-tags="非遗文化,竹编手作,茶文化,古镇记忆,地方民俗">
          <img src="images/culture-folk.jpg" alt="非遗民俗" />
          <div class="heritage-card-overlay">
            <span class="card-label">LIVING HERITAGE</span>
            <h3>非遗民俗</h3>
            <p>让传统技艺在当代传播中焕发新生，延续嘉州文化温度。</p>
            <div class="heritage-card-meta">
              <span>竹编手作</span>
              <span>茶馆文化</span>
              <span>古镇记忆</span>
            </div>
          </div>
        </article>
      </div>

      <div class="page-tags">
        <span>嘉州美食</span>
        <span>非遗民俗</span>
        <span>地方技艺</span>
        <span>古镇茶馆</span>
        <span>生活温度</span>
      </div>
    </div>
  </section>

    <section class="section route-section" id="routes">
      <div class="section-heading section-heading-upgraded force-left-title">
        <div class="section-heading-main">
          <span class="section-index">04</span>
          <h2>智慧路线入画</h2>
        </div>
        <p class="section-kicker">SMART ROUTE</p>
      </div>

      <div class="route-generator-layout">
        <div class="route-left-panel premium-panel">
          <span class="mini-label">AI TRAVEL LOGIC</span>
          <h3>从一座城市，到一条更聪明的路线</h3>
          <p>
            根据游览天数自动生成乐山文旅路线，将景点、美食、古镇、非遗与绿色出行组合成更清晰的时间轴。
            点击右侧任意行程节点，左侧图片会自动切换对应地点或美食画面。
          </p>

          <div class="route-form">
              <label for="routeDays">选择游览天数</label>
              <select id="routeDays">
                <option value="1">1 天游</option>
                <option value="2">2 天游</option>
                <option value="3" selected>3 天游</option>
              </select>
              <button id="generateRouteBtn" class="btn primary" type="button">生成路线</button>
            </div>

          <div class="route-preview-card">
            <img id="routePreviewImage" src="images/culture-dafo.jpg" alt="路线地点预览图" />
            <div class="route-preview-info">
              <span id="routePreviewLabel">WORLD ICON</span>
              <strong id="routePreviewTitle">乐山大佛</strong>
              <p id="routePreviewText">点击右侧行程中的景点、美食或文化节点，左侧将切换对应画面。</p>
            </div>
          </div>
        </div>

        <div class="route-result-panel premium-panel">
          <div class="route-result-head">
            <span class="mini-label">TRAVEL TIMELINE</span>
            <h3 id="routeResultTitle">3天深度游嘉州</h3>
            <p id="routeResultDesc">
              3天路线适合节奏舒缓的深度体验，从市区文化地标延伸到峨眉山自然疗愈，再以古镇烟火和非遗体验收束。
            </p>
          </div>

          <div class="route-result" id="routeResult"></div>
        </div>
      </div>
    </section>

    <section class="section green-page-balanced" id="green">
      <div class="green-balanced-inner">
      <div class="section-heading section-heading-upgraded force-left-title">
        <div class="section-heading-main">
          <span class="section-index">05</span>
          <h2>绿意同行</h2>
        </div>
        <p class="section-kicker">GREEN TRAVEL</p>
      </div>

        <div class="green-balanced-layout">
          <div class="green-balanced-left premium-panel">
            <span class="mini-label">SUSTAINABLE TRAVEL</span>
            <h3>让美景被看见，也被守护</h3>
            <p class="green-balanced-lead">
              在嘉州的山水之间，低碳不是一句口号，而是从路线选择、文明行为到垃圾分类的每一次具体行动。
            </p>

            <div class="green-balanced-strategy">
              <div class="green-strategy-item">
                <span>01</span>
                <div>
                  <h4>绿色出行</h4>
                  <p>优先公共交通，合理规划路线，减少无效往返。</p>
                </div>
              </div>

              <div class="green-strategy-item">
                <span>02</span>
                <div>
                  <h4>文明旅游</h4>
                  <p>遵守景区规范，尊重地方习俗与文化空间。</p>
                </div>
              </div>

              <div class="green-strategy-item">
                <span>03</span>
                <div>
                  <h4>垃圾分类</h4>
                  <p>将旅途中的垃圾正确投放，让环保意识真正落地。</p>
                </div>
              </div>
            </div>

            <div class="green-balanced-slogan">
              <span>LOW CARBON</span>
              <strong>一次有温度的旅行，也应是一场有责任感的出行。</strong>
            </div>

            <div class="green-balanced-tags">
              <span>绿色出行</span>
              <span>文明旅游</span>
              <span>垃圾分类</span>
            </div>
          </div>

          <div class="green-balanced-right premium-panel">
            <div class="green-game-panel">
              <div class="green-game-head">
                <div>
                  <span class="mini-label">LOW-CARBON CHALLENGE</span>
                  <h3>文明游嘉州小挑战</h3>
                </div>
                <div class="green-game-mark">互动任务</div>
              </div>

              <div class="game-status-balanced">
                <div class="game-score-card">
                  <span>当前得分</span>
                  <strong id="gameScore">0</strong>
                </div>
                <div class="game-score-card">
                  <span>当前进度</span>
                  <strong id="gameProgress">1 / 6</strong>
                </div>
              </div>

              <div class="trash-card-balanced" id="trashCard">
                <div class="trash-card-top">
                  <div class="trash-item-icon" id="trashItemIcon">PET</div>
                  <div class="trash-card-copy">
                    <span class="trash-card-label">当前物品</span>
                    <h4 id="trashItemName">矿泉水瓶</h4>
                  </div>
                </div>
                <p id="trashItemDesc">游客饮用后的空塑料瓶，应投入正确的分类桶中。</p>
              </div>

              <div class="bins-grid-balanced">
                <button class="bin-btn recyclable" data-bin="recyclable" type="button">
                  <span>可回收物</span>
                  <small>纸张 / 塑料 / 金属</small>
                </button>

                <button class="bin-btn kitchen" data-bin="kitchen" type="button">
                  <span>厨余垃圾</span>
                  <small>果皮 / 剩饭 / 茶渣</small>
                </button>

                <button class="bin-btn harmful" data-bin="harmful" type="button">
                  <span>有害垃圾</span>
                  <small>电池 / 灯管 / 药品</small>
                </button>

                <button class="bin-btn other" data-bin="other" type="button">
                  <span>其他垃圾</span>
                  <small>纸巾 / 餐盒 / 尘土</small>
                </button>
              </div>

              <div class="game-feedback" id="gameFeedback">
                请选择正确的垃圾分类桶开始挑战。
              </div>

              <div class="game-footer-balanced">
                <button id="restartGameBtn" class="btn primary game-restart-btn" type="button">重新开始</button>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>

  </main>

  <footer>
    <p>© 2026 三江云起・嘉州入画 | AI网页设计美育作品</p>
    <p>主题：乐山地域风情与文旅宣传</p>
  </footer>

  <div class="cert-modal" id="certModal" aria-hidden="true">
    <div class="cert-card">
      <button class="cert-close" id="closeCertModal" aria-label="关闭认证卡" type="button">×</button>
      <span class="mini-label">GREEN TRAVEL CERTIFICATE</span>
      <h3>嘉州低碳游客认证</h3>
      <p class="cert-score" id="certScore">得分 6 / 6</p>
      <p class="cert-desc" id="certDesc">
        你已完成"文明游嘉州小挑战"，在旅途中践行垃圾分类与绿色出行理念。
      </p>
      <div class="cert-badges">
        <span>文明旅游</span>
        <span>垃圾分类</span>
        <span>低碳出行</span>
      </div>
      <button id="certRestartBtn" class="btn primary" type="button">再挑战一次</button>
    </div>
  </div>

  <div class="modal" id="infoModal" aria-hidden="true">
    <div class="modal-content modal-feature">
      <button class="close-btn" id="closeModal" aria-label="关闭弹窗">×</button>

      <div class="modal-feature-layout">
        <div class="modal-feature-visual">
          <img id="modalImage" src="images/culture-dafo.jpg" alt="文化展示图" />
          <div class="modal-feature-overlay">
            <p class="modal-en-title" id="modalEnTitle">WORLD ICON</p>
            <h3 id="modalTitle">标题</h3>
          </div>
        </div>

        <div class="modal-feature-content">
          <p class="modal-lead" id="modalLead">内容概述</p>

          <div class="modal-body-stack">
            <div class="modal-block">
              <span class="modal-block-label">文化看点</span>
              <p id="modalHighlight">这里展示文化亮点内容。</p>
            </div>

            <div class="modal-block">
              <span class="modal-block-label">特色价值</span>
              <p id="modalValue">这里展示特色价值内容。</p>
            </div>

            <div class="modal-block">
              <span class="modal-block-label">推荐体验</span>
              <p id="modalExperience">这里展示推荐体验内容。</p>
            </div>
          </div>

          <div class="modal-tags" id="modalTags"></div>
        </div>
      </div>
    </div>
  </div>

  <button id="topBtn" class="top-btn" aria-label="返回顶部">↑</button>

  <script src="script.js"></script>
</body>
</html>
const cards = document.querySelectorAll(".culture-card");
const modal = document.getElementById("infoModal");
const modalTitle = document.getElementById("modalTitle");
const modalEnTitle = document.getElementById("modalEnTitle");
const modalLead = document.getElementById("modalLead");
const modalHighlight = document.getElementById("modalHighlight");
const modalValue = document.getElementById("modalValue");
const modalExperience = document.getElementById("modalExperience");
const modalTags = document.getElementById("modalTags");
const modalImage = document.getElementById("modalImage");
const closeModal = document.getElementById("closeModal");
const themeBtn = document.getElementById("themeBtn");
const colorThemeSelect = document.getElementById("colorThemeSelect");
const topBtn = document.getElementById("topBtn");
const daySelect = document.getElementById("daySelect");
const routeResult = document.getElementById("routeResult");
const heroParticles = document.getElementById("heroParticles");
const hero = document.querySelector(".hero");
const parallaxItems = document.querySelectorAll(".hero-parallax");

const routePlans = {
  one: `
    <div class="route-plan">
      <h4>1天精华游｜大佛文化与嘉州烟火</h4>
      <div class="route-summary">
        <div class="route-summary-item"><span>游玩天数</span><strong>1天</strong></div>
        <div class="route-summary-item"><span>总时长</span><strong>约9-10小时</strong></div>
        <div class="route-summary-item"><span>推荐出行</span><strong>公交 / 打车 / 步行</strong></div>
        <div class="route-summary-item"><span>适合人群</span><strong>首次来乐山游客</strong></div>
      </div>
      <div class="map-timeline">
        <div class="timeline-day">
          <div class="timeline-day-title">Day 1｜乐山城市精华路线</div>
          <div class="timeline-node">
            <span class="timeline-time">08:30 - 09:00</span>
            <h5>市区出发 → 乐山大佛景区</h5>
            <p>建议从酒店或车站出发，乘公交、旅游专线或打车前往乐山大佛景区。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">09:00 - 12:00</span>
            <h5>乐山大佛近距离游览</h5>
            <p>游览凌云寺、九曲栈道、大佛观景区，感受千年石刻艺术与三江汇流的壮阔。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">12:00 - 13:30</span>
            <h5>嘉州特色午餐</h5>
            <p>推荐品尝跷脚牛肉、豆腐脑、甜皮鸭等乐山代表性美食。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">14:00 - 15:20</span>
            <h5>乘船远眺大佛</h5>
            <p>从江面视角欣赏大佛全貌，更直观感受大佛依山临江的空间关系。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">16:00 - 18:00</span>
            <h5>张公桥美食街 / 嘉州街巷漫游</h5>
            <p>在城市街巷中体验乐山烟火气，适合拍照、休闲和美食打卡。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">18:30 - 20:00</span>
            <h5>沿江夜景与返程</h5>
            <p>晚餐后可沿江散步，欣赏乐山夜色，结束一日精华行程。</p>
          </div>
        </div>
      </div>
      <div class="transport-tip">
        <strong>出行规划：</strong>
        1日游建议以"市区公共交通 + 打车 + 步行"为主，减少换乘时间。若时间紧张，可优先选择"大佛景区 + 美食街"两大核心点。
      </div>
    </div>
  `,
  two: `
    <div class="route-plan">
      <h4>2天深度游｜大佛、古镇与峨眉山</h4>
      <div class="route-summary">
        <div class="route-summary-item"><span>游玩天数</span><strong>2天1晚</strong></div>
        <div class="route-summary-item"><span>总时长</span><strong>约2天</strong></div>
        <div class="route-summary-item"><span>推荐出行</span><strong>高铁 / 公交 / 景区车</strong></div>
        <div class="route-summary-item"><span>适合人群</span><strong>文化与自然爱好者</strong></div>
      </div>
      <div class="map-timeline">
        <div class="timeline-day">
          <div class="timeline-day-title">Day 1｜乐山大佛与城市烟火</div>
          <div class="timeline-node">
            <span class="timeline-time">09:00 - 12:00</span>
            <h5>乐山大佛景区</h5>
            <p>游览大佛、凌云寺、栈道等核心区域，了解乐山历史文化与石刻艺术。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">12:00 - 13:30</span>
            <h5>乐山特色午餐</h5>
            <p>推荐跷脚牛肉、钵钵鸡、豆腐脑等，感受城市烟火气。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">14:00 - 16:30</span>
            <h5>苏稽古镇</h5>
            <p>漫游古镇街巷，体验传统小吃、茶馆文化与地方生活节奏。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">17:00 - 20:00</span>
            <h5>张公桥美食街</h5>
            <p>夜晚适合进行美食打卡，体验乐山最有代表性的夜间烟火氛围。</p>
          </div>
        </div>
        <div class="timeline-day">
          <div class="timeline-day-title">Day 2｜峨眉山自然与人文体验</div>
          <div class="timeline-node">
            <span class="timeline-time">08:00 - 09:00</span>
            <h5>乐山市区 → 峨眉山</h5>
            <p>可乘高铁、旅游专线或打车前往峨眉山景区附近。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">09:30 - 12:00</span>
            <h5>报国寺 / 伏虎寺周边</h5>
            <p>适合轻松游览，感受峨眉山佛教文化与山林环境。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">12:00 - 13:30</span>
            <h5>峨眉山午餐</h5>
            <p>可选择峨眉素斋、豆花饭或当地农家菜。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">14:00 - 16:30</span>
            <h5>山林轻徒步 / 温泉休闲</h5>
            <p>根据体力选择轻徒步或温泉休闲，突出自然疗愈感。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">17:00以后</span>
            <h5>返程</h5>
            <p>乘车返回乐山市区或前往高铁站，结束2天深度游。</p>
          </div>
        </div>
      </div>
      <div class="transport-tip">
        <strong>出行规划：</strong>
        第一天建议集中在乐山市区和苏稽古镇，第二天前往峨眉山，路线层次更清晰。峨眉山路程较远，建议提前查询高铁或景区交通时间。
      </div>
    </div>
  `,
  three: `
    <div class="route-plan">
      <h4>3天慢游乐山｜山水、人文、美食完整体验</h4>
      <div class="route-summary">
        <div class="route-summary-item"><span>游玩天数</span><strong>3天2晚</strong></div>
        <div class="route-summary-item"><span>总时长</span><strong>约3天</strong></div>
        <div class="route-summary-item"><span>推荐出行</span><strong>高铁 / 公交 / 景区车 / 步行</strong></div>
        <div class="route-summary-item"><span>适合人群</span><strong>家庭、摄影、慢旅行游客</strong></div>
      </div>
      <div class="map-timeline">
        <div class="timeline-day">
          <div class="timeline-day-title">Day 1｜乐山大佛与嘉州历史</div>
          <div class="timeline-node">
            <span class="timeline-time">09:00 - 12:00</span>
            <h5>乐山大佛景区</h5>
            <p>深度游览大佛及周边文化景点，了解乐山最具代表性的文化符号。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">12:00 - 13:30</span>
            <h5>特色午餐</h5>
            <p>推荐跷脚牛肉、甜皮鸭、豆腐脑等地方美食。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">14:00 - 16:00</span>
            <h5>乘船远眺大佛</h5>
            <p>以江面视角观赏大佛全貌，适合摄影和城市形象展示。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">17:00 - 20:00</span>
            <h5>沿江散步与夜景</h5>
            <p>在城市滨江空间中感受嘉州山水城市的生活氛围。</p>
          </div>
        </div>
        <div class="timeline-day">
          <div class="timeline-day-title">Day 2｜峨眉山自然疗愈</div>
          <div class="timeline-node">
            <span class="timeline-time">08:00 - 09:00</span>
            <h5>前往峨眉山</h5>
            <p>从乐山市区出发，可乘高铁、公交或旅游接驳车。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">09:30 - 12:00</span>
            <h5>峨眉山景区游览</h5>
            <p>根据体力选择低山区游览或继续乘景区车前往更高海拔区域。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">12:00 - 13:30</span>
            <h5>山间午餐</h5>
            <p>品尝峨眉素斋、豆花饭或本地农家菜。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">14:00 - 17:30</span>
            <h5>云雾山林与寺院文化</h5>
            <p>体验峨眉山云海、古寺、林木与自然生态带来的疗愈感。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">晚上</span>
            <h5>峨眉山周边住宿</h5>
            <p>可选择温泉酒店或景区周边住宿，为第三天行程保留体力。</p>
          </div>
        </div>
        <div class="timeline-day">
          <div class="timeline-day-title">Day 3｜古镇、美食与非遗慢体验</div>
          <div class="timeline-node">
            <span class="timeline-time">09:00 - 11:00</span>
            <h5>返回乐山市区 / 前往苏稽古镇</h5>
            <p>选择较轻松的返程节奏，适合慢旅行和家庭游客。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">11:00 - 13:30</span>
            <h5>苏稽古镇美食体验</h5>
            <p>品尝钵钵鸡、米花糖、茶点等，感受古镇生活气息。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">14:00 - 16:00</span>
            <h5>非遗民俗与地方文化体验</h5>
            <p>了解地方手工艺、茶文化或民俗展示，让旅行更具文化深度。</p>
          </div>
          <div class="timeline-node">
            <span class="timeline-time">16:30以后</span>
            <h5>返程 / 自由活动</h5>
            <p>根据车次或个人安排返程，也可继续在市区购买伴手礼。</p>
          </div>
        </div>
      </div>
      <div class="transport-tip">
        <strong>出行规划：</strong>
        3天路线适合节奏舒缓的深度体验。建议第一天住乐山市区，第二天住峨眉山周边，第三天返回市区或古镇，减少往返消耗。
      </div>
    </div>
  `
};

cards.forEach(card => {
  card.addEventListener("click", () => {
    modalTitle.textContent = card.dataset.title || "";
    modalEnTitle.textContent = card.dataset.en || "";
    modalLead.textContent = card.dataset.lead || "";
    modalHighlight.textContent = card.dataset.highlight || "";
    modalValue.textContent = card.dataset.value || "";
    modalExperience.textContent = card.dataset.experience || "";

    if (modalImage) {
      modalImage.src = card.dataset.image || "";
      modalImage.alt = card.dataset.title || "文化展示图";
    }

    const tags = (card.dataset.tags || "")
      .split(",")
      .map(tag => tag.trim())
      .filter(Boolean);

    modalTags.innerHTML = tags.map(tag => `<span>${tag}</span>`).join("");

    modal.classList.add("show");
    modal.setAttribute("aria-hidden", "false");
  });
});

closeModal.addEventListener("click", () => {
  modal.classList.remove("show");
  modal.setAttribute("aria-hidden", "true");
});

modal.addEventListener("click", event => {
  if (event.target === modal) {
    modal.classList.remove("show");
    modal.setAttribute("aria-hidden", "true");
  }
});

document.addEventListener("keydown", event => {
  if (event.key === "Escape") {
    modal.classList.remove("show");
    modal.setAttribute("aria-hidden", "true");
  }
});

daySelect && daySelect.addEventListener("change", () => {
  const value = daySelect.value;

  if (!value) {
    routeResult.innerHTML = `<p class="empty-tip">请选择"1天 / 2天 / 3天"，系统将自动生成地图风格时间轴路线。</p>`;
    return;
  }

  routeResult.innerHTML = routePlans[value];
  routeResult.animate(
    [
      { opacity: 0, transform: "translateY(18px)" },
      { opacity: 1, transform: "translateY(0)" }
    ],
    { duration: 480, easing: "ease-out" }
  );
});

const dayThemes = ["theme-shanshui", "theme-gold", "theme-bamboo", "theme-warm"];

function applyDayTheme(themeName) {
  dayThemes.forEach(theme => {
    document.body.classList.remove(theme);
  });

  document.body.classList.add(themeName);

  if (colorThemeSelect) {
    colorThemeSelect.value = themeName;
  }
}

/* 默认日间主题 */
applyDayTheme("theme-shanshui");

/* 手动选择日间主题色 */
if (colorThemeSelect) {
  colorThemeSelect.addEventListener("change", () => {
    applyDayTheme(colorThemeSelect.value);
  });
}

/* 夜间 / 日间切换 */
themeBtn.addEventListener("click", () => {
  document.body.classList.toggle("dark");

  if (document.body.classList.contains("dark")) {
    themeBtn.textContent = "日间模式";

    if (colorThemeSelect) {
      colorThemeSelect.disabled = true;
      colorThemeSelect.style.opacity = "0.55";
    }
  } else {
    themeBtn.textContent = "夜间模式";

    if (colorThemeSelect) {
      colorThemeSelect.disabled = false;
      colorThemeSelect.style.opacity = "1";
      applyDayTheme(colorThemeSelect.value || "theme-shanshui");
    }
  }
});

window.addEventListener("scroll", () => {
  topBtn.classList.toggle("show", window.scrollY > 500);
});

topBtn.addEventListener("click", () => {
  window.scrollTo({ top: 0, behavior: "smooth" });
});

function createParticles() {
  const particleCount = 18;
  for (let index = 0; index < particleCount; index += 1) {
    const particle = document.createElement("span");
    particle.className = "particle";
    particle.style.left = `${Math.random() * 100}%`;
    particle.style.top = `${40 + Math.random() * 55}%`;
    particle.style.animationDuration = `${6 + Math.random() * 7}s`;
    particle.style.animationDelay = `${Math.random() * 5}s`;
    particle.style.opacity = `${0.2 + Math.random() * 0.5}`;
    heroParticles.appendChild(particle);
  }
}

function setupHeroParallax() {
  if (!hero || window.innerWidth < 900) {
    return;
  }

  hero.addEventListener("mousemove", event => {
    const rect = hero.getBoundingClientRect();
    const x = event.clientX - rect.left - rect.width / 2;
    const y = event.clientY - rect.top - rect.height / 2;

    parallaxItems.forEach(item => {
      const depth = Number(item.dataset.depth || 10);
      const moveX = (x / rect.width) * depth;
      const moveY = (y / rect.height) * depth;
      item.style.transform = `translate3d(${moveX}px, ${moveY}px, 0)`;
    });
  });

  hero.addEventListener("mouseleave", () => {
    parallaxItems.forEach(item => {
      item.style.transform = "translate3d(0, 0, 0)";
    });
  });
}

createParticles();
setupHeroParallax();

/* =========================
   滚动渐入动画
   ========================= */
const revealEls = document.querySelectorAll('[data-reveal]');

const revealObserver = new IntersectionObserver((entries) => {
  entries.forEach((entry) => {
    if (entry.isIntersecting) {
      entry.target.classList.add('is-visible');
      revealObserver.unobserve(entry.target);
    }
  });
}, {
  threshold: 0.15
});

revealEls.forEach((el) => revealObserver.observe(el));

/* =========================
   路线生成功能
   ========================= */
const routeData = {
  1: {
    title: "1天精华游嘉州",
    image: "./images/route-1.jpg",
    items: [
      { time: "08:30 - 11:30", title: "乐山大佛景区", desc: "深度游览大佛及周边文化景点。" },
      { time: "12:00 - 13:30", title: "特色午餐", desc: "品尝跷脚牛肉、钵钵鸡等乐山风味。" },
      { time: "14:00 - 17:00", title: "市区轻游", desc: "感受嘉州街巷与城市烟火气。" }
    ]
  },
  2: {
    title: "2天深度游嘉州",
    image: "./images/route-2.jpg",
    items: [
      { time: "Day 1", title: "乐山大佛 + 嘉州夜游", desc: "自然与城市夜景结合。" },
      { time: "Day 2", title: "峨眉山 + 茶文化体验", desc: "山水与禅意旅行结合。" }
    ]
  },
  3: {
    title: "3天慢游嘉州",
    image: "./images/route-3.jpg",
    items: [
      { time: "09:00 - 11:00", title: "苏稽古镇漫游", desc: "感受老街与地方生活史。" },
      { time: "11:30 - 13:00", title: "茶馆休憩", desc: "体验慢生活的本地节奏。" },
      { time: "13:00 - 14:30", title: "地方午餐与美食补充", desc: "补充乐山特色美食体验。" },
      { time: "15:00 - 17:00", title: "非遗民俗体验", desc: "通过手作、技艺了解乐山文化。" }
    ]
  }
};

function renderRoute(days) {
  const data = routeData[days];
  if (!data) return;

  const titleEl = document.getElementById('routeTitle');
  const listEl = document.getElementById('routeList');
  const imageEl = document.getElementById('routeImage');

  if (titleEl) titleEl.textContent = data.title;
  if (imageEl) imageEl.src = data.image;

  if (listEl) {
    listEl.innerHTML = data.items.map((item, index) => `
      <div class="timeline-item ${index === 0 ? 'is-active' : ''}" data-route-item>
        <div class="timeline-time">${item.time}</div>
        <div class="timeline-body">
          <h4>${item.title}</h4>
          <p>${item.desc}</p>
        </div>
      </div>
    `).join('');
  }
}

const tripDays = document.getElementById('tripDays');
const generateRoute = document.getElementById('generateRoute');

if (generateRoute) {
  generateRoute.addEventListener('click', () => {
    renderRoute(tripDays ? tripDays.value : '1');
  });
}

if (tripDays) {
  tripDays.addEventListener('change', () => {
    renderRoute(tripDays.value);
  });
}



/* =========================
   垃圾分类小游戏逻辑
   ========================= */
(function () {
  const trashPoolByType = {
    recyclable: [
      {
        name: "矿泉水瓶",
        desc: "游客饮用后的空塑料瓶，应投入正确的分类桶中。",
        bin: "recyclable",
        icon: "PET"
      },
      {
        name: "纸质门票",
        desc: "游览后废弃的纸质票据，属于可回收利用物。",
        bin: "recyclable",
        icon: "票"
      },
      {
        name: "宣传折页",
        desc: "景区发放后的纸质宣传页，通常属于可回收物。",
        bin: "recyclable",
        icon: "页"
      },
      {
        name: "塑料饮料杯",
        desc: "喝完饮品后的干净塑料杯，可投入可回收物。",
        bin: "recyclable",
        icon: "杯"
      },
      {
        name: "易拉罐",
        desc: "喝完饮料后的金属易拉罐，属于可回收物。",
        bin: "recyclable",
        icon: "罐"
      }
    ],
    kitchen: [
      {
        name: "果皮",
        desc: "旅行途中吃水果留下的果皮，属于易腐烂的厨余垃圾。",
        bin: "kitchen",
        icon: "果"
      },
      {
        name: "剩饭剩菜",
        desc: "用餐后剩下的食物残渣，属于厨余垃圾。",
        bin: "kitchen",
        icon: "餐"
      },
      {
        name: "茶渣",
        desc: "喝茶后剩下的茶叶残渣，属于厨余垃圾。",
        bin: "kitchen",
        icon: "茶"
      },
      {
        name: "香蕉皮",
        desc: "水果外皮属于典型厨余垃圾。",
        bin: "kitchen",
        icon: "蕉"
      }
    ],
    harmful: [
      {
        name: "废旧电池",
        desc: "废弃电池含有有害成分，需要单独分类投放。",
        bin: "harmful",
        icon: "电"
      },
      {
        name: "过期药片",
        desc: "废弃药品及其残留具有潜在危害，属于有害垃圾。",
        bin: "harmful",
        icon: "药"
      },
      {
        name: "废旧灯泡",
        desc: "废弃灯泡需要谨慎投放，通常归入有害垃圾处理。",
        bin: "harmful",
        icon: "灯"
      }
    ],
    other: [
      {
        name: "用过的纸巾",
        desc: "已经被污染、无法回收利用的纸巾，属于其他垃圾。",
        bin: "other",
        icon: "纸"
      },
      {
        name: "一次性餐盒",
        desc: "油污严重、难以回收处理的一次性餐盒，通常归为其他垃圾。",
        bin: "other",
        icon: "盒"
      },
      {
        name: "塑料吸管",
        desc: "体积小且难以有效回收，通常按其他垃圾处理。",
        bin: "other",
        icon: "管"
      },
      {
        name: "口罩",
        desc: "使用后的口罩不宜回收，通常归入其他垃圾。",
        bin: "other",
        icon: "罩"
      },
      {
        name: "一次性木竹签",
        desc: "用过的食物竹签通常沾有油污，按其他垃圾处理更稳妥。",
        bin: "other",
        icon: "签"
      }
    ]
  };

  const GAME_SIZE = 6;
  const TRASH_TYPES = ["recyclable", "kitchen", "harmful", "other"];

  function shuffleArray(array) {
    const result = [...array];
    for (let i = result.length - 1; i > 0; i -= 1) {
      const j = Math.floor(Math.random() * (i + 1));
      [result[i], result[j]] = [result[j], result[i]];
    }
    return result;
  }

  function takeRandomItems(pool, count) {
    return shuffleArray(pool).slice(0, Math.min(count, pool.length));
  }

  function createRandomGameItems() {
    const selected = [];

    TRASH_TYPES.forEach(type => {
      const picked = takeRandomItems(trashPoolByType[type], 1);
      selected.push(...picked);
    });

    const remainingSlots = GAME_SIZE - selected.length;

    if (remainingSlots > 0) {
      const remainingPool = TRASH_TYPES.flatMap(type =>
        trashPoolByType[type].filter(item =>
          !selected.some(selectedItem => selectedItem.name === item.name)
        )
      );

      selected.push(...takeRandomItems(remainingPool, remainingSlots));
    }

    return shuffleArray(selected);
  }

  const trashItemName = document.getElementById("trashItemName");
  const trashItemDesc = document.getElementById("trashItemDesc");
  const trashItemIcon = document.getElementById("trashItemIcon");
  const gameScore = document.getElementById("gameScore");
  const gameProgress = document.getElementById("gameProgress");
  const gameFeedback = document.getElementById("gameFeedback");
  const restartGameBtn = document.getElementById("restartGameBtn");
  const binButtons = document.querySelectorAll(".bin-btn");

  const certModal = document.getElementById("certModal");
  const certScore = document.getElementById("certScore");
  const certDesc = document.getElementById("certDesc");
  const closeCertModal = document.getElementById("closeCertModal");
  const certRestartBtn = document.getElementById("certRestartBtn");

  if (
    !trashItemName ||
    !trashItemDesc ||
    !gameScore ||
    !gameProgress ||
    !gameFeedback ||
    !restartGameBtn ||
    !binButtons.length
  ) {
    return;
  }

  let trashItems = createRandomGameItems();
  let gameIndex = 0;
  let score = 0;
  let gameLocked = false;

  function openCertModal() {
    if (!certModal) return;

    certScore.textContent = `得分 ${score} / ${GAME_SIZE}`;

    if (score === GAME_SIZE) {
      certDesc.textContent = "恭喜你完美完成「文明游嘉州小挑战」，已获得「嘉州低碳游客」认证。";
    } else if (score >= 4) {
      certDesc.textContent = "你已顺利完成挑战，具备良好的绿色出行与垃圾分类意识。";
    } else {
      certDesc.textContent = "挑战已完成，继续提升垃圾分类与文明旅游意识，下次争取更高分。";
    }

    certModal.classList.add("show");
    certModal.setAttribute("aria-hidden", "false");
  }

  function closeCertCard() {
    if (!certModal) return;
    certModal.classList.remove("show");
    certModal.setAttribute("aria-hidden", "true");
  }

  function updateTrashGameView() {
    const currentItem = trashItems[gameIndex];

    if (!currentItem) {
      trashItemName.textContent = "挑战完成";
      trashItemDesc.textContent = "你已完成文明游嘉州垃圾分类挑战，获得绿色出行积分结果。";

      if (trashItemIcon) {
        trashItemIcon.textContent = "GO";
      }

      gameProgress.textContent = `${GAME_SIZE} / ${GAME_SIZE}`;
      gameFeedback.textContent = `挑战完成，你的得分是 ${score} / ${GAME_SIZE}。`;
      gameFeedback.className = "game-feedback finish";

      binButtons.forEach((button) => {
        button.disabled = true;
      });

      setTimeout(openCertModal, 500);
      return;
    }

    trashItemName.textContent = currentItem.name;
    trashItemDesc.textContent = currentItem.desc;

    if (trashItemIcon) {
      trashItemIcon.textContent = currentItem.icon || "?";
    }

    gameProgress.textContent = `${gameIndex + 1} / ${GAME_SIZE}`;
    gameScore.textContent = String(score);
    gameFeedback.textContent = "请选择正确的垃圾分类桶开始挑战。";
    gameFeedback.className = "game-feedback";

    binButtons.forEach((button) => {
      button.disabled = false;
      button.classList.remove("correct", "wrong");
    });
  }

  function restartTrashGame() {
    closeCertCard();
    trashItems = createRandomGameItems();
    gameIndex = 0;
    score = 0;
    gameLocked = false;
    gameScore.textContent = "0";
    updateTrashGameView();
  }

  function handleBinChoice(selectedBin, buttonEl) {
    if (gameLocked || !trashItems[gameIndex]) {
      return;
    }

    const currentItem = trashItems[gameIndex];
    gameLocked = true;

    if (selectedBin === currentItem.bin) {
      score += 1;
      gameScore.textContent = String(score);
      buttonEl.classList.add("correct");
      gameFeedback.textContent = "分类正确，绿色积分 +1。";
      gameFeedback.className = "game-feedback success";
    } else {
      buttonEl.classList.add("wrong");
      gameFeedback.textContent = "分类错误，系统已高亮正确垃圾桶。";
      gameFeedback.className = "game-feedback error";

      const correctButton = document.querySelector(`.bin-btn[data-bin="${currentItem.bin}"]`);
      if (correctButton) {
        correctButton.classList.add("correct");
      }
    }

    binButtons.forEach((button) => {
      button.disabled = true;
    });

    setTimeout(() => {
      gameIndex += 1;
      gameLocked = false;
      updateTrashGameView();
    }, 1200);
  }

  updateTrashGameView();

  binButtons.forEach((button) => {
    button.addEventListener("click", () => {
      handleBinChoice(button.dataset.bin, button);
    });
  });

  restartGameBtn.addEventListener("click", restartTrashGame);

  if (closeCertModal) {
    closeCertModal.addEventListener("click", closeCertCard);
  }

  if (certRestartBtn) {
    certRestartBtn.addEventListener("click", restartTrashGame);
  }

  if (certModal) {
    certModal.addEventListener("click", (event) => {
      if (event.target === certModal) {
        closeCertCard();
      }
    });
  }
})();

/* =========================
   第一部分左上轮播 JS
   ========================= */
(function () {
  const slider = document.getElementById("introCubeSlider");
  const currentImage = document.getElementById("cubeCurrentImage");
  const nextImage = document.getElementById("cubeNextImage");

  if (!slider || !currentImage || !nextImage) {
    return;
  }

  const imageList = [
    "images/intro-main.jpg",
    "images/culture-dafo.jpg",
    "images/culture-emei.jpg",
    "images/culture-food.jpg",
    "images/culture-folk.jpg",
    "images/intro-food.jpg",
    "images/intro-folk.jpg",
    "images/view-guzhen.jpg",
    "images/view-teahouse.jpg",
    "images/view-riverside.jpg"
  ];

  let currentIndex = 0;
  let direction = 1;
  let animating = false;

  function getNextIndex() {
    if (currentIndex >= imageList.length - 1) {
      direction = -1;
    } else if (currentIndex <= 0) {
      direction = 1;
    }

    return currentIndex + direction;
  }

  function flipImage() {
    if (animating) {
      return;
    }

    const nextIndex = getNextIndex();
    animating = true;

    nextImage.src = imageList[nextIndex];

    slider.classList.remove("forward", "backward", "is-animating");
    slider.offsetHeight;
    slider.classList.add("is-animating", direction === 1 ? "forward" : "backward");

    setTimeout(() => {
      currentImage.src = imageList[nextIndex];
      currentIndex = nextIndex;
      slider.classList.remove("forward", "backward", "is-animating");
      animating = false;
    }, 1050);
  }

  currentImage.src = imageList[0];
  nextImage.src = imageList[1];

  setInterval(flipImage, 3200);
})();

/* =========================
   第3部分路线预览 JS
   ========================= */
(function () {
  const routeResult = document.getElementById("routeResult");
  const previewCard = document.querySelector(".route-preview-card");
  const previewImage = document.getElementById("routePreviewImage");
  const previewTitle = document.getElementById("routePreviewTitle");
  const previewText = document.getElementById("routePreviewText");
  const previewLabel = document.getElementById("routePreviewLabel");

  if (!routeResult || !previewCard || !previewImage || !previewTitle || !previewText || !previewLabel) {
    return;
  }

  const previewMap = [
    {
      keywords: ["乐山大佛", "大佛", "凌云寺", "九曲栈道", "乘船远眺大佛", "乘船远眺"],
      title: "乐山大佛",
      label: "WORLD ICON",
      text: "千年石刻临江而立，是乐山最具辨识度的文化地标。",
      image: "images/culture-dafo.jpg"
    },
    {
      keywords: ["峨眉山", "金顶", "峨眉", "云海", "自然疗愈"],
      title: "峨眉山",
      label: "MOUNTAIN SPIRIT",
      text: "云海、山林与古寺共同构成东方山岳美学。",
      image: "images/culture-emei.jpg"
    },
    {
      keywords: ["跷脚牛肉"],
      title: "跷脚牛肉",
      label: "LOCAL FLAVOR",
      text: "汤鲜味醇，是最具代表性的乐山在地味觉记忆之一。",
      image: "images/food-qiaojiao.jpg"
    },
    {
      keywords: ["钵钵鸡"],
      title: "钵钵鸡",
      label: "LOCAL FLAVOR",
      text: "冷串浸满红油与芝麻香气，体现乐山街头小吃的热烈个性。",
      image: "images/food-boboji.jpg"
    },
    {
      keywords: ["甜皮鸭"],
      title: "甜皮鸭",
      label: "LOCAL FLAVOR",
      text: "外皮酥亮、甜香浓郁，是嘉州饮食中极具辨识度的经典味道。",
      image: "images/food-tianpiduck.jpg"
    },
    {
      keywords: ["豆腐脑"],
      title: "乐山豆腐脑",
      label: "LOCAL FLAVOR",
      text: "绵密鲜香、层次丰富，最能体现乐山小吃的日常温度。",
      image: "images/food-doufunao.jpg"
    },
    {
      keywords: ["特色午餐", "嘉州美食", "美食", "午餐"],
      title: "嘉州美食",
      label: "CITY FLAVOR",
      text: "从街巷小吃到古镇餐馆，乐山的味道热烈而鲜活。",
      image: "images/culture-food.jpg"
    },
    {
      keywords: ["非遗", "民俗", "手作", "地方技艺"],
      title: "非遗民俗",
      label: "LIVING HERITAGE",
      text: "传统手作与地方技艺，延续着嘉州文化最细腻的生活纹理。",
      image: "images/folk-intangible.jpg"
    },
    {
      keywords: ["古镇", "苏稽古镇"],
      title: "古镇街巷",
      label: "ANCIENT TOWN",
      text: "老街巷与烟火店铺共同构成乐山日常生活的历史肌理。",
      image: "images/view-guzhen.jpg"
    },
    {
      keywords: ["茶馆", "喝茶", "茶文化"],
      title: "嘉州茶馆",
      label: "TEAHOUSE LIFE",
      text: "一盏清茶、一处街角，藏着最真实的嘉州慢生活气息。",
      image: "images/view-teahouse.jpg"
    },
    {
      keywords: ["三江", "滨江", "夜景", "沿江", "江景", "城市", "沿江散步与夜景"],
      title: "嘉州江岸",
      label: "RIVERSIDE VIEW",
      text: "三江汇流与城市灯火交织出嘉州山水城的日常风景。",
      image: "images/view-riverside.jpg"
    }
  ];

  function findPreviewByText(text) {
    return previewMap.find(item =>
      item.keywords.some(keyword => text.includes(keyword))
    );
  }

  function updatePreview(item) {
    previewCard.classList.add("is-changing");

    setTimeout(() => {
      previewImage.src = item.image;
      previewImage.alt = item.title;
      previewTitle.textContent = item.title;
      previewText.textContent = item.text;
      previewLabel.textContent = item.label;
      previewCard.classList.remove("is-changing");
    }, 180);
  }

  routeResult.addEventListener("click", event => {
    const clickable = event.target.closest(".timeline-node, .route-day-card, .route-step, .timeline-card, li, article, div");

    if (!clickable || !routeResult.contains(clickable)) {
      return;
    }

    const text = clickable.textContent.trim();
    const matchedPreview = findPreviewByText(text);

    if (!matchedPreview) {
      return;
    }

    routeResult.querySelectorAll(".route-preview-active").forEach(item => {
      item.classList.remove("route-preview-active");
    });

    clickable.classList.add("route-preview-active");
    updatePreview(matchedPreview);
  });
})();

/* =========================
   智慧路线生成：下拉选择 + 点击配图
   ========================= */
(function () {
  const routeDays = document.getElementById("routeDays");
  const generateRouteBtn = document.getElementById("generateRouteBtn");
  const routeResult = document.getElementById("routeResult");
  const routeResultTitle = document.getElementById("routeResultTitle");
  const routeResultDesc = document.getElementById("routeResultDesc");

  const previewCard = document.querySelector("#routes .route-preview-card");
  const previewImage = document.getElementById("routePreviewImage");
  const previewTitle = document.getElementById("routePreviewTitle");
  const previewText = document.getElementById("routePreviewText");
  const previewLabel = document.getElementById("routePreviewLabel");

  if (
    !routeDays ||
    !generateRouteBtn ||
    !routeResult ||
    !routeResultTitle ||
    !routeResultDesc ||
    !previewCard ||
    !previewImage ||
    !previewTitle ||
    !previewText ||
    !previewLabel
  ) {
    return;
  }

  const routeData = {
    1: {
      title: "1天精华游嘉州",
      desc: "1天路线适合时间有限的游客，以乐山大佛、嘉州美食与沿江夜景为核心，快速建立城市印象。",
      days: [
        {
          title: "Day 1｜嘉州精华速览",
          items: [
            {
              time: "08:30 - 11:30",
              title: "乐山大佛景区",
              desc: "深度游览大佛及周边文化景点，了解乐山最具代表性的文化符号。"
            },
            {
              time: "12:00 - 13:30",
              title: "特色午餐",
              desc: "推荐跷脚牛肉、甜皮鸭、豆腐脑等地方美食。"
            },
            {
              time: "14:00 - 16:00",
              title: "乘船远眺大佛",
              desc: "以江面视角观赏大佛全貌，适合摄影和城市形象展示。"
            },
            {
              time: "17:00 - 20:00",
              title: "沿江散步与夜景",
              desc: "在城市滨江空间中感受嘉州山水城市的生活氛围。"
            }
          ]
        }
      ]
    },
    2: {
      title: "2天山水人文游",
      desc: "2天路线适合周末游，在乐山大佛与峨眉山之间建立山水文化联系，兼顾城市烟火与自然疗愈。",
      days: [
        {
          title: "Day 1｜嘉州文化初印象",
          items: [
            {
              time: "08:30 - 11:30",
              title: "乐山大佛景区",
              desc: "深度游览大佛及周边文化景点，了解乐山最具代表性的文化符号。"
            },
            {
              time: "12:00 - 13:30",
              title: "特色午餐",
              desc: "推荐跷脚牛肉、甜皮鸭、豆腐脑等地方美食。"
            },
            {
              time: "14:00 - 16:00",
              title: "乘船远眺大佛",
              desc: "以江面视角观赏大佛全貌，适合摄影和城市形象展示。"
            },
            {
              time: "17:00 - 20:00",
              title: "沿江散步与夜景",
              desc: "在城市滨江空间中感受嘉州山水城市的生活氛围。"
            }
          ]
        },
        {
          title: "Day 2｜峨眉山自然疗愈",
          items: [
            {
              time: "08:00 - 09:00",
              title: "前往峨眉山",
              desc: "从乐山市区前往峨眉山景区，开启更偏自然与静观的旅程节奏。"
            },
            {
              time: "09:00 - 12:00",
              title: "山林漫游与寺院游览",
              desc: "感受山间云雾、古寺环境与峨眉山特有的自然人文交融气质。"
            },
            {
              time: "14:30 - 17:30",
              title: "云海与山岳风景体验",
              desc: "根据天气安排观景、轻徒步或静坐停留，形成自然疗愈体验。"
            }
          ]
        }
      ]
    },
    3: {
      title: "3天深度游嘉州",
      desc: "3天路线适合节奏舒缓的深度体验，从市区文化地标延伸到峨眉山自然疗愈，再以古镇烟火和非遗体验收束。",
      days: [
        {
          title: "Day 1｜嘉州文化初印象",
          items: [
            {
              time: "08:30 - 11:30",
              title: "乐山大佛景区",
              desc: "深度游览大佛及周边文化景点，了解乐山最具代表性的文化符号。"
            },
            {
              time: "12:00 - 13:30",
              title: "特色午餐",
              desc: "推荐跷脚牛肉、甜皮鸭、豆腐脑等地方美食。"
            },
            {
              time: "14:00 - 16:00",
              title: "乘船远眺大佛",
              desc: "以江面视角观赏大佛全貌，适合摄影和城市形象展示。"
            },
            {
              time: "17:00 - 20:00",
              title: "沿江散步与夜景",
              desc: "在城市滨江空间中感受嘉州山水城市的生活氛围。"
            }
          ]
        },
        {
          title: "Day 2｜峨眉山自然疗愈",
          items: [
            {
              time: "08:00 - 09:00",
              title: "前往峨眉山",
              desc: "从乐山市区前往峨眉山景区，开启更偏自然与静观的旅程节奏。"
            },
            {
              time: "09:00 - 12:00",
              title: "山林漫游与寺院游览",
              desc: "感受山间云雾、古寺环境与峨眉山特有的自然人文交融气质。"
            },
            {
              time: "14:30 - 17:30",
              title: "云海与山岳风景体验",
              desc: "根据体力与天气安排观景、轻徒步或静坐停留，形成自然疗愈体验。"
            }
          ]
        },
        {
          title: "Day 3｜古镇烟火与人文收束",
          items: [
            {
              time: "09:00 - 11:00",
              title: "苏稽古镇漫游",
              desc: "在老街、店铺与慢节奏空间中感受嘉州日常生活的历史肌理。"
            },
            {
              time: "11:30 - 13:00",
              title: "茶馆休憩",
              desc: "以一盏清茶和街巷观察，体验更贴近本地生活的文旅方式。"
            },
            {
              time: "13:00 - 14:30",
              title: "地方午餐与美食补充",
              desc: "继续体验钵钵鸡、跷脚牛肉或甜皮鸭等特色风味。"
            },
            {
              time: "15:00 - 17:00",
              title: "非遗民俗体验",
              desc: "通过竹编、手作或地方技艺体验，感受乐山文化的延续方式。"
            }
          ]
        }
      ]
    }
  };

  const previewMap = [
    {
      keywords: ["乐山大佛", "大佛", "乘船远眺"],
      title: "乐山大佛",
      label: "WORLD ICON",
      text: "千年石刻临江而立，是乐山最具辨识度的文化地标。",
      image: "images/culture-dafo.jpg"
    },
    {
      keywords: ["峨眉山", "山林", "寺院", "云海", "山岳"],
      title: "峨眉山",
      label: "MOUNTAIN SPIRIT",
      text: "云海、山林与古寺钟声共同构成东方山岳意境。",
      image: "images/culture-emei.jpg"
    },
    {
      keywords: ["跷脚牛肉"],
      title: "跷脚牛肉",
      label: "LOCAL FLAVOR",
      text: "汤鲜味醇，是最具代表性的乐山在地味觉记忆之一。",
      image: "images/food-qiaojiao.jpg"
    },
    {
      keywords: ["钵钵鸡"],
      title: "钵钵鸡",
      label: "LOCAL FLAVOR",
      text: "红油、芝麻与竹签串串构成乐山街头小吃的热烈个性。",
      image: "images/food-boboji.jpg"
    },
    {
      keywords: ["甜皮鸭"],
      title: "甜皮鸭",
      label: "LOCAL FLAVOR",
      text: "外皮酥亮、甜香浓郁，是嘉州饮食中极具辨识度的经典味道。",
      image: "images/food-tianpiduck.jpg"
    },
    {
      keywords: ["豆腐脑"],
      title: "乐山豆腐脑",
      label: "LOCAL FLAVOR",
      text: "绵密香、层次丰富，体现乐山小吃的日常温度。",
      image: "images/food-doufunao.jpg"
    },
    {
      keywords: ["特色午餐", "地方午餐", "美食", "午餐"],
      title: "嘉州美食",
      label: "CITY FLAVOR",
      text: "从街巷小吃到临江老店，乐山的味道热烈而鲜活。",
      image: "images/culture-food.jpg"
    },
    {
      keywords: ["苏稽古镇", "古镇"],
      title: "苏稽古镇",
      label: "ANCIENT TOWN",
      text: "老街巷与生活店铺共同构成嘉州烟火生活的历史肌理。",
      image: "images/view-guzhen.jpg"
    },
    {
      keywords: ["茶馆", "茶馆休憩", "茶文化"],
      title: "嘉州茶馆",
      label: "TEAHOUSE LIFE",
      text: "一盏清茶与街巷慢节奏，构成最真实的嘉州生活气息。",
      image: "images/view-teahouse.jpg"
    },
    {
      keywords: ["非遗", "民俗", "竹编", "手作", "技艺"],
      title: "非遗民俗",
      label: "LIVING HERITAGE",
      text: "传统技艺与地方日常共同延续着嘉州文化的细腻温度。",
      image: "images/folk-intangible.jpg"
    },
    {
      keywords: ["沿江", "夜景", "滨江", "江景"],
      title: "嘉州江岸",
      label: "RIVERSIDE VIEW",
      text: "三江汇流与城市灯火交织出嘉州山水城的日常风景。",
      image: "images/view-riverside.jpg"
    }
  ];

  function findPreview(text) {
    return previewMap.find(item =>
      item.keywords.some(keyword => text.includes(keyword))
    );
  }

  function updatePreview(item) {
    previewCard.classList.add("is-changing");

    setTimeout(() => {
      previewImage.src = item.image;
      previewImage.alt = item.title;
      previewTitle.textContent = item.title;
      previewText.textContent = item.text;
      previewLabel.textContent = item.label;
      previewCard.classList.remove("is-changing");
    }, 180);
  }

  function renderRoute() {
    const selected = routeData[routeDays.value];

    routeResultTitle.textContent = selected.title;
    routeResultDesc.textContent = selected.desc;

    routeResult.innerHTML = selected.days.map(day => `
      <div class="route-day-block">
        <div class="route-day-title">
          <span class="route-day-dot"></span>
          <h4>${day.title}</h4>
        </div>

        ${day.items.map(item => `
          <div class="route-step-card">
            <span class="route-step-time">${item.time}</span>
            <h5>${item.title}</h5>
            <p>${item.desc}</p>
          </div>
        `).join("")}
      </div>
    `).join("");
  }

  routeResult.addEventListener("click", event => {
    const card = event.target.closest(".route-step-card");

    if (!card) {
      return;
    }

    const matched = findPreview(card.textContent.trim());

    if (!matched) {
      return;
    }

    routeResult.querySelectorAll(".route-preview-active").forEach(item => {
      item.classList.remove("route-preview-active");
    });

    card.classList.add("route-preview-active");
    updatePreview(matched);
  });

  generateRouteBtn.addEventListener("click", renderRoute);
  routeDays.addEventListener("change", renderRoute);

  renderRoute();
})();
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:root {
  --bg: #f6f1e6;
  --text: #163847;
  --accent: #e7b85c;
  --accent-2: #2f5b4b;
  --muted: #63747b;
  --deep: #0f2f3f;
  --teal: #1f5b62;
  --gold: #f0c36c;
  --gold-soft: #f6deaa;
  --panel: rgba(255, 255, 255, 0.72);
  --panel-strong: rgba(255, 255, 255, 0.9);
  --shadow: 0 20px 40px rgba(28, 52, 60, 0.12);
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: "Microsoft YaHei", "PingFang SC", sans-serif;
  background: radial-gradient(circle at top, #fbf7ee, var(--bg) 58%);
  color: var(--text);
  line-height: 1.85;
  transition: background 0.4s, color 0.4s;
}

a {
  color: inherit;
  text-decoration: none;
}

.hero {
  position: relative;
  overflow: hidden;
  background:
    linear-gradient(180deg, rgba(10, 18, 24, 0.2), rgba(10, 18, 24, 0.68)),
    url("./images/hero.jpg") center/cover no-repeat;
  color: #fff;
  min-height: 100vh;
  isolation: isolate;
}

.hero::after {
  content: "";
  position: absolute;
  inset: 0;
  background:
    radial-gradient(circle at 70% 30%, rgba(255, 214, 140, 0.18), transparent 30%),
    radial-gradient(circle at 20% 25%, rgba(255, 255, 255, 0.1), transparent 26%);
  pointer-events: none;
}

.hero-title {
  position: relative;
  z-index: 1;
  font-size: clamp(52px, 8vw, 104px);
  line-height: 0.95;
  letter-spacing: -0.04em;
  text-shadow: 0 10px 30px rgba(0, 0, 0, 0.25);
}

.hero-card {
  position: relative;
  z-index: 1;
  backdrop-filter: blur(16px);
  background: rgba(255, 248, 238, 0.16);
  border: 1px solid rgba(255, 255, 255, 0.18);
  box-shadow: 0 16px 40px rgba(0, 0, 0, 0.18);
}

.card {
  border-radius: 28px;
  background: rgba(255, 255, 255, 0.82);
  border: 1px solid rgba(22, 56, 71, 0.06);
  box-shadow: 0 12px 30px rgba(28, 28, 28, 0.06);
  transition: transform 0.28s ease, box-shadow 0.28s ease, border-color 0.28s ease;
}

.card:hover {
  transform: translateY(-4px);
  box-shadow: 0 18px 48px rgba(28, 28, 28, 0.11);
  border-color: rgba(231, 184, 92, 0.32);
}

.card-title {
  color: var(--text);
  letter-spacing: -0.03em;
}

.card-subtitle,
.card-desc {
  color: rgba(22, 56, 71, 0.72);
  line-height: 1.7;
}

[data-reveal] {
  opacity: 0;
  transform: translateY(18px);
  transition: opacity 0.7s ease, transform 0.7s ease;
}

[data-reveal].is-visible {
  opacity: 1;
  transform: translateY(0);
}

.timeline-item {
  display: grid;
  grid-template-columns: 120px 1fr;
  gap: 16px;
  padding: 18px 20px;
  border-radius: 20px;
  background: rgba(255, 248, 238, 0.75);
  margin-bottom: 14px;
}

.timeline-item.is-active {
  background: linear-gradient(135deg, rgba(239, 210, 145, 0.32), rgba(255, 255, 255, 0.92));
  border: 1px solid rgba(231, 184, 92, 0.35);
}

.timeline-time {
  font-weight: 700;
  color: #5a604f;
}

.timeline-body h4 {
  margin: 0 0 6px;
  color: var(--text);
}

.timeline-body p {
  margin: 0;
  color: rgba(22, 56, 71, 0.72);
}

.section {
  width: 100%;
  display: flex;
  justify-content: center;
}

.section-inner {
  width: min(1440px, calc(100% - 120px));
  margin: 0 auto;
}

.section-header {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  margin-bottom: 28px;
}

.section-title-wrap {
  display: flex;
  align-items: center;
  gap: 18px;
}

.section-title-line {
  width: 92px;
  height: 3px;
  margin-top: 10px;
  background: linear-gradient(90deg, #e7b85c 0%, rgba(231, 184, 92, 0.15) 100%);
  border-radius: 999px;
}

.section-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 28px;
  align-items: start;
  justify-content: center;
}

.section-card {
  border-radius: 30px;
  overflow: hidden;
  box-shadow: 0 16px 40px rgba(20, 28, 34, 0.08);
  transition: transform 0.28s ease, box-shadow 0.28s ease;
}

.section-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 22px 52px rgba(20, 28, 34, 0.12);
}

.section-tags {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 22px;
}

.section-tag {
  padding: 10px 18px;
  border-radius: 999px;
  background: rgba(231, 184, 92, 0.16);
  color: #163847;
}

.hero-overlay {
  position: absolute;
  inset: 0;
  z-index: 1;
  background:
    radial-gradient(circle at 16% 24%, rgba(241, 196, 95, 0.24), transparent 24%),
    radial-gradient(circle at 78% 18%, rgba(255, 255, 255, 0.12), transparent 18%),
    linear-gradient(to top, rgba(6, 16, 24, 0.74), transparent 42%);
}

.hero-mesh {
  position: absolute;
  inset: 0;
  z-index: 1;
  opacity: 0.2;
  background-image:
    linear-gradient(rgba(255, 255, 255, 0.08) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255, 255, 255, 0.08) 1px, transparent 1px);
  background-size: 54px 54px;
  mask-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.18), rgba(0, 0, 0, 0));
}

.hero-particles {
  position: absolute;
  inset: 0;
  z-index: 2;
  pointer-events: none;
}

.particle {
  position: absolute;
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(255, 231, 170, 0.95), rgba(255, 231, 170, 0));
  box-shadow: 0 0 14px rgba(255, 220, 130, 0.5);
  animation: drift linear infinite;
  opacity: 0.55;
}

@keyframes drift {
  from {
    transform: translate3d(0, 16px, 0) scale(0.9);
    opacity: 0;
  }
  25% {
    opacity: 0.7;
  }
  75% {
    opacity: 0.45;
  }
  to {
    transform: translate3d(32px, -160px, 0) scale(1.15);
    opacity: 0;
  }
}

.hero-glow {
  position: absolute;
  border-radius: 50%;
  filter: blur(70px);
  z-index: 1;
  pointer-events: none;
}

.hero-glow-1 {
  width: 320px;
  height: 320px;
  top: 10%;
  left: -6%;
  background: rgba(240, 195, 108, 0.22);
}

.hero-glow-2 {
  width: 260px;
  height: 260px;
  bottom: 18%;
  right: -4%;
  background: rgba(255, 255, 255, 0.12);
}

.navbar {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 24px 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: relative;
  z-index: 5;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  letter-spacing: 3px;
}

.nav-links {
  display: flex;
  gap: 28px;
  list-style: none;
}

.nav-links a {
  font-size: 15px;
  opacity: 0.95;
  transition: 0.3s;
}

.nav-links a:hover {
  color: #ffe08a;
}

.theme-btn {
  border: 1px solid rgba(255,255,255,0.8);
  color: #fff;
  background: transparent;
  padding: 8px 16px;
  border-radius: 20px;
  cursor: pointer;
  transition: 0.3s;
}

.theme-btn:hover {
  background: rgba(255,255,255,0.18);
}

.hero-content {
  width: 90%;
  max-width: 1280px;
  margin: 90px auto 0;
  position: relative;
  z-index: 4;
  display: grid;
  grid-template-columns: 1fr 0.85fr;
  gap: 40px;
  align-items: center;
}

.hero-left {
  position: relative;
}

.hero-line {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 18px;
}

.hero-line span {
  width: 32px;
  height: 2px;
  background: linear-gradient(90deg, #ffe5ab, transparent);
}

.hero-line p {
  font-size: 13px;
  letter-spacing: 2px;
  color: rgba(255, 255, 255, 0.92);
}

.hero-year {
  display: inline-block;
  padding: 6px 14px;
  margin-bottom: 18px;
  border-radius: 999px;
  font-size: 13px;
  letter-spacing: 2px;
  color: #ffe7ab;
  background: rgba(240, 195, 108, 0.12);
  border: 1px solid rgba(240, 195, 108, 0.24);
}

.hero h1 {
  font-size: clamp(56px, 8vw, 102px);
  line-height: 0.96;
  letter-spacing: 4px;
  margin-bottom: 24px;
  text-shadow: 0 10px 30px rgba(0, 0, 0, 0.28);
  color: #fff;
}

.hero h1 span {
  color: #ffe2a0;
  text-shadow: 0 0 18px rgba(240, 195, 108, 0.3), 0 8px 24px rgba(0, 0, 0, 0.22);
}

.subtitle {
  max-width: 720px;
  font-size: 19px;
  color: rgba(255, 255, 255, 0.92);
  text-shadow: 0 3px 12px rgba(0, 0, 0, 0.24);
}

.hero-buttons {
  display: flex;
  gap: 18px;
  margin-top: 34px;
}

.btn {
  padding: 13px 30px;
  border-radius: 999px;
  font-weight: 700;
  letter-spacing: 1px;
  transition: transform 0.25s, box-shadow 0.25s, background 0.25s;
}

.primary {
  color: #1d2c33;
  background: linear-gradient(135deg, var(--gold), var(--gold-soft));
  box-shadow: 0 16px 30px rgba(240, 195, 108, 0.2);
}

.secondary {
  color: #fff;
  background: rgba(255, 255, 255, 0.08);
  border: 1px solid rgba(255, 255, 255, 0.28);
  backdrop-filter: blur(10px);
}

.btn:hover {
  transform: translateY(-4px);
  box-shadow: 0 18px 34px rgba(0, 0, 0, 0.18);
}

.hero-right {
  display: flex;
  justify-content: flex-end;
}

.hero-award-card {
  width: min(100%, 370px);
  padding: 28px 26px;
  border-radius: 28px;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.16), rgba(255, 255, 255, 0.08));
  border: 1px solid rgba(255, 255, 255, 0.16);
  backdrop-filter: blur(14px);
  box-shadow: 0 24px 50px rgba(0, 0, 0, 0.18);
}

.award-tag {
  margin-bottom: 10px;
  font-size: 12px;
  letter-spacing: 2px;
  color: #ffe5a0;
}

.hero-award-card h3 {
  font-size: 28px;
  line-height: 1.28;
  margin-bottom: 12px;
}

.hero-award-card p:last-child {
  font-size: 15px;
  color: rgba(255, 255, 255, 0.9);
}

.hero-data {
  width: min(92%, 1280px);
  margin: 40px auto 0;
  position: relative;
  z-index: 4;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
}

.data-card {
  padding: 20px 22px;
  border-radius: 24px;
  background: rgba(255, 255, 255, 0.1);
  border: 1px solid rgba(255, 255, 255, 0.14);
  backdrop-filter: blur(10px);
  box-shadow: 0 12px 26px rgba(0, 0, 0, 0.12);
}

.data-card span {
  display: block;
  margin-bottom: 8px;
  font-size: 13px;
  color: rgba(255, 255, 255, 0.72);
}

.data-card strong {
  font-size: 17px;
  line-height: 1.6;
}

.scroll-tip {
  position: absolute;
  left: 50%;
  bottom: 118px;
  transform: translateX(-50%);
  z-index: 4;
  font-size: 14px;
  letter-spacing: 2px;
  color: rgba(255, 255, 255, 0.9);
  animation: floatDown 1.8s ease-in-out infinite;
}

@keyframes floatDown {
  0%, 100% {
    transform: translateX(-50%) translateY(0);
  }
  50% {
    transform: translateX(-50%) translateY(8px);
  }
}

.wave {
  position: absolute;
  left: 0;
  bottom: -1px;
  width: 100%;
  height: 100px;
  z-index: 3;
  background: var(--bg);
  clip-path: polygon(0 45%, 18% 60%, 38% 34%, 61% 60%, 82% 42%, 100% 56%, 100% 100%, 0 100%);
}

.hero-animate {
  opacity: 0;
  transform: translateY(30px);
  animation: heroFadeUp 0.95s ease forwards;
}

.delay-1 { animation-delay: 0.2s; }
.delay-2 { animation-delay: 0.45s; }
.delay-3 { animation-delay: 0.7s; }
.delay-4 { animation-delay: 0.95s; }

@keyframes heroFadeUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.section {
  width: min(90%, 1180px);
  margin: 0 auto;
  padding: 92px 0;
}

.section-title {
  margin-bottom: 32px;
}

.section-title span {
  color: #b78035;
  font-size: 18px;
  font-weight: 700;
}

.section-title h2 {
  margin-top: 6px;
  font-size: 38px;
  color: var(--deep);
}

.intro-panel {
  padding: 34px;
  border-radius: 28px;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.82), rgba(255, 255, 255, 0.62));
  box-shadow: var(--shadow);
  border: 1px solid rgba(255, 255, 255, 0.66);
}

.intro-panel p + p {
  margin-top: 16px;
}

.feature-head {
  margin-bottom: 24px;
  color: var(--muted);
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 26px;
}

.culture-card {
  min-height: 310px;
  position: relative;
  overflow: hidden;
  border-radius: 30px;
  cursor: pointer;
  display: flex;
  align-items: flex-end;
  box-shadow: 0 24px 42px rgba(25, 44, 52, 0.16);
  transition: transform 0.35s, box-shadow 0.35s;
  isolation: isolate;
}

.culture-card::before {
  content: "";
  position: absolute;
  inset: 0;
  background:
    linear-gradient(to top, rgba(7, 17, 24, 0.84), rgba(7, 17, 24, 0.18) 46%, rgba(255, 255, 255, 0.02)),
    linear-gradient(135deg, rgba(255, 255, 255, 0.08), transparent);
  z-index: 1;
}

.culture-card::after {
  content: "";
  position: absolute;
  inset: 0;
  background-size: cover;
  background-position: center;
  transform: scale(1);
  transition: transform 0.5s ease;
  z-index: 0;
}

.culture-card.dafo::after {
  background-image:
    linear-gradient(130deg, rgba(46, 81, 90, 0.18), rgba(238, 188, 95, 0.08)),
    radial-gradient(circle at 80% 18%, rgba(255, 220, 142, 0.28), transparent 18%),
    linear-gradient(180deg, rgba(61, 82, 70, 0.3), rgba(26, 38, 45, 0.78)),
    url("imageshero.jpg");
}

.culture-card.emei::after {
  background-image:
    radial-gradient(circle at 20% 20%, rgba(199, 231, 229, 0.22), transparent 18%),
    linear-gradient(180deg, rgba(70, 111, 108, 0.2), rgba(20, 34, 43, 0.82)),
    linear-gradient(160deg, #6ba29d, #244655 68%);
}

.culture-card.food::after {
  background-image:
    radial-gradient(circle at 75% 20%, rgba(255, 197, 118, 0.34), transparent 18%),
    linear-gradient(180deg, rgba(134, 70, 34, 0.18), rgba(21, 20, 23, 0.84)),
    linear-gradient(160deg, #db8e44, #703d29 60%, #2a2324);
}

.culture-card.folk::after {
  background-image:
    radial-gradient(circle at 18% 18%, rgba(255, 226, 167, 0.26), transparent 16%),
    linear-gradient(180deg, rgba(130, 94, 53, 0.16), rgba(24, 22, 26, 0.84)),
    linear-gradient(150deg, #886749, #4d3e38 58%, #1e2327);
}

.culture-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 28px 48px rgba(18, 36, 44, 0.22);
}

.culture-card:hover::after {
  transform: scale(1.06);
}

.card-sheen {
  position: absolute;
  inset: auto -20% 18% auto;
  width: 180px;
  height: 180px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(240, 195, 108, 0.26), rgba(240, 195, 108, 0));
  filter: blur(8px);
  z-index: 1;
}

.card-meta {
  width: 100%;
  padding: 28px;
  position: relative;
  z-index: 2;
}

.card-label {
  display: inline-block;
  margin-bottom: 10px;
  padding: 6px 12px;
  border-radius: 999px;
  font-size: 12px;
  letter-spacing: 2px;
  color: #ffe5ab;
  background: rgba(255, 255, 255, 0.12);
  border: 1px solid rgba(255, 255, 255, 0.14);
}

.card-meta h3 {
  font-size: 30px;
  margin-bottom: 10px;
  color: #fff;
}

.card-meta p {
  color: rgba(255, 255, 255, 0.9);
}

.route-shell {
  display: grid;
  grid-template-columns: 0.9fr 1.35fr;
  gap: 24px;
  align-items: start;
}

.route-side {
  padding: 30px;
  border-radius: 30px;
  color: #fff;
  background: linear-gradient(160deg, #123646, #1a4d57 62%, #235e5e);
  box-shadow: 0 22px 42px rgba(18, 54, 70, 0.22);
}

.route-side-tag {
  margin-bottom: 10px;
  color: #ffe3a2;
  font-size: 12px;
  letter-spacing: 2px;
}

.route-side h3 {
  font-size: 30px;
  margin-bottom: 12px;
}

.route-control {
  margin-top: 24px;
  display: grid;
  gap: 10px;
}

.route-control label {
  color: #ffe3a2;
  font-weight: 700;
}

.route-control select {
  padding: 14px 18px;
  border: none;
  border-radius: 18px;
  font-size: 16px;
  font-weight: 700;
  color: var(--deep);
  background: #fff;
  outline: none;
}

.route-main {
  min-height: 100%;
}

.route-result {
  min-height: 290px;
  padding: 28px;
  border-radius: 30px;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.88), rgba(255, 255, 255, 0.66));
  border: 1px solid rgba(255, 255, 255, 0.72);
  box-shadow: var(--shadow);
}

.empty-tip {
  color: var(--muted);
}

.route-plan h4 {
  margin-bottom: 18px;
  font-size: 28px;
  color: var(--deep);
}

.route-summary {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 14px;
  margin-bottom: 24px;
}

.route-summary-item {
  padding: 16px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fff, #f3efe6);
  border: 1px solid rgba(20, 52, 66, 0.08);
}

.route-summary-item span {
  display: block;
  margin-bottom: 4px;
  color: var(--muted);
  font-size: 13px;
}

.route-summary-item strong {
  color: var(--deep);
  font-size: 16px;
}

.map-timeline {
  position: relative;
  padding-left: 32px;
}

.map-timeline::before {
  content: "";
  position: absolute;
  left: 11px;
  top: 14px;
  bottom: 16px;
  width: 3px;
  border-radius: 10px;
  background: linear-gradient(to bottom, var(--gold), rgba(31, 91, 98, 0.28));
}

.timeline-day {
  margin-bottom: 28px;
}

.timeline-day-title {
  margin-bottom: 14px;
  font-size: 20px;
  color: var(--deep);
}

.timeline-day-title::before {
  content: "📍";
  margin-right: 6px;
}

.timeline-node {
  position: relative;
  margin-bottom: 18px;
  padding: 16px 18px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fff, #f9f6ee);
  border: 1px solid rgba(20, 52, 66, 0.08);
  transition: transform 0.2s;
}

.timeline-node:hover {
  transform: translateX(4px);
}

.timeline-node::before {
  content: "";
  position: absolute;
  left: -24px;
  top: 20px;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: var(--gold);
  box-shadow: 0 0 0 4px rgba(240, 195, 108, 0.22);
}

.timeline-time {
  display: inline-block;
  padding: 4px 10px;
  margin-bottom: 6px;
  border-radius: 999px;
  font-size: 13px;
  font-weight: 700;
  color: #7a5e1e;
  background: rgba(240, 195, 108, 0.2);
}

.timeline-node h5 {
  margin-bottom: 4px;
  font-size: 17px;
  color: var(--deep);
}

.timeline-node p {
  color: #53646b;
}

.transport-tip {
  margin-top: 18px;
  padding: 18px 20px;
  border-left: 4px solid var(--gold);
  border-radius: 18px;
  background: linear-gradient(180deg, #fff9eb, #f7efdc);
  color: #6d5827;
}

.green-content {
  display: grid;
  grid-template-columns: 1.35fr 0.75fr;
  gap: 28px;
}

.green-text,
.ai-box {
  padding: 34px;
  border-radius: 28px;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.84), rgba(255, 255, 255, 0.66));
  box-shadow: var(--shadow);
  border: 1px solid rgba(255, 255, 255, 0.72);
}

.green-text h3 {
  margin-bottom: 12px;
  font-size: 28px;
  color: var(--teal);
}

.green-text ul {
  margin-top: 18px;
  padding-left: 20px;
}

.eco-card {
  padding: 34px;
  border-radius: 30px;
  background: linear-gradient(160deg, #5e9278, #8ab07f 60%, #c1d39d);
  color: #fff;
  display: flex;
  flex-direction: column;
  gap: 24px;
  justify-content: center;
  align-items: center;
  text-align: center;
  box-shadow: 0 20px 36px rgba(84, 123, 93, 0.2);
}

.eco-circle {
  width: 148px;
  height: 148px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 2px solid rgba(255, 255, 255, 0.78);
  background: rgba(255, 255, 255, 0.15);
  font-size: 34px;
  font-weight: 700;
}

.ai-box p + p {
  margin-top: 14px;
}

footer {
  padding: 32px 20px;
  text-align: center;
  color: #fff;
  background: linear-gradient(180deg, #123646, #0e2c39);
}

.modal {
  position: fixed;
  inset: 0;
  z-index: 20;
  display: none;
  align-items: center;
  justify-content: center;
  background: rgba(5, 12, 18, 0.52);
}

.modal.show {
  display: flex;
}

.modal-content {
  width: min(92%, 560px);
  padding: 34px;
  position: relative;
  border-radius: 28px;
  background: linear-gradient(180deg, #ffffff, #f4efe6);
  color: var(--text);
  animation: pop 0.28s ease;
  box-shadow: 0 24px 50px rgba(0, 0, 0, 0.2);
}

@keyframes pop {
  from {
    opacity: 0;
    transform: scale(0.92);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}

.modal-content h3 {
  margin-bottom: 14px;
  font-size: 28px;
  color: var(--deep);
}

.close-btn {
  position: absolute;
  top: 14px;
  right: 18px;
  border: none;
  background: none;
  font-size: 30px;
  cursor: pointer;
}

.top-btn {
  position: fixed;
  right: 24px;
  bottom: 24px;
  z-index: 15;
  width: 48px;
  height: 48px;
  border: none;
  border-radius: 50%;
  display: none;
  cursor: pointer;
  color: #20323b;
  background: linear-gradient(135deg, var(--gold), var(--gold-soft));
  box-shadow: 0 14px 26px rgba(0, 0, 0, 0.16);
}

.top-btn.show {
  display: block;
}

body.dark {
  --bg: #0d1d24;
  --text: #e6efef;
  --muted: #b5c3c7;
  --deep: #f0c36c;
  --teal: #9fd0c0;
  --panel: rgba(255, 255, 255, 0.08);
  --panel-strong: rgba(255, 255, 255, 0.1);
  background: radial-gradient(circle at top, #152833, #0d1d24 58%);
  color: #e6efef;
}

body.dark .wave {
  background: #0d1d24;
}

body.dark .intro-panel,
body.dark .route-result,
body.dark .green-text,
body.dark .ai-box,
body.dark .route-summary-item,
body.dark .timeline-node,
body.dark .modal-content {
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.08), rgba(255, 255, 255, 0.06));
  color: #e6efef;
  border-color: rgba(255, 255, 255, 0.08);
}

body.dark .timeline-node p,
body.dark .feature-head,
body.dark .empty-tip,
body.dark .route-summary-item span {
  color: #c8d5d8;
}

body.dark .transport-tip {
  background: rgba(240, 195, 108, 0.12);
  color: #f4deb0;
}

body.dark .route-control select {
  background: #102a35;
  color: #f1f4f4;
}

body.dark .timeline-time {
  background: rgba(240, 195, 108, 0.14);
  color: #ffe5ab;
}

body.dark .top-btn {
  color: #13232b;
}

@media (max-width: 1100px) {
  .hero-content,
  .route-shell,
  .green-content {
    grid-template-columns: 1fr;
  }

  .hero-right {
    justify-content: flex-start;
  }

  .hero-data {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 900px) {
  .nav-links {
    display: none;
  }

  .card-grid,
  .route-summary {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 640px) {
  .section {
    padding: 68px 0;
  }

  .hero-content {
    margin-top: 70px;
  }

  .hero h1 {
    letter-spacing: 2px;
    line-height: 1.02;
  }

  .subtitle {
    font-size: 16px;
  }

  .hero-buttons {
    flex-direction: column;
    align-items: flex-start;
  }

  .hero-award-card {
    width: 100%;
  }

  .card-grid,
  .route-summary {
    grid-template-columns: 1fr;
  }

  .route-side,
  .route-result,
  .green-text,
  .ai-box,
  .intro-panel {
    padding: 24px;
  }

  .route-control select {
    width: 100%;
  }

  .map-timeline {
    padding-left: 26px;
  }

  .timeline-node::before {
    left: -23px;
  }

  .scroll-tip {
    bottom: 102px;
  }
}

/* 路线模块文字可读性修复 */
.route-side {
  color: #f7f3e8;
}

.route-side p {
  color: rgba(247, 243, 232, 0.9);
}

.route-side h3 {
  color: #ffffff;
}

.route-side-tag {
  color: #ffe3a2;
}

.route-control label {
  color: #ffe3a2;
}

.route-result {
  color: #24363d;
}

.route-plan h4 {
  color: #123646;
}

.route-summary-item {
  background: linear-gradient(180deg, #fffdf8, #f3ecdf);
}

.route-summary-item span {
  color: #6f7f84;
}

.route-summary-item strong {
  color: #123646;
}

.timeline-day-title {
  color: #123646;
}

.timeline-node {
  background: linear-gradient(180deg, #fffdf9, #f6efe3);
}

.timeline-node h5 {
  color: #123646;
}

.timeline-node p {
  color: #4c5f66;
}

.timeline-time {
  background: #fff0c8;
  color: #8b6120;
}

.transport-tip {
  background: linear-gradient(180deg, #fff9ea, #f6edd7);
  color: #6d5827;
}

.empty-tip {
  color: #5c6f76;
}

/* 夜间模式下同步修复 */
body.dark .route-side {
  color: #eef5f5;
}

body.dark .route-side p {
  color: rgba(238, 245, 245, 0.9);
}

body.dark .route-result {
  color: #e8f1f2;
}

body.dark .route-plan h4,
body.dark .timeline-day-title,
body.dark .timeline-node h5,
body.dark .route-summary-item strong {
  color: #f6c667;
}

body.dark .timeline-node p,
body.dark .route-summary-item span,
body.dark .empty-tip {
  color: #d3e0e2;
}

body.dark .timeline-node,
body.dark .route-summary-item {
  background: linear-gradient(180deg, rgba(255,255,255,0.08), rgba(255,255,255,0.05));
}

body.dark .timeline-time {
  background: rgba(246, 198, 103, 0.14);
  color: #ffe3a2;
}

body.dark .transport-tip {
  background: rgba(246, 198, 103, 0.12);
  color: #f3dfb1;
}

/* 1、3、4、5部分统一美化 */
.deluxe-section {
  position: relative;
}

.deluxe-section::before {
  content: "";
  position: absolute;
  inset: 36px 0 auto 0;
  height: 1px;
  background: linear-gradient(to right, transparent, rgba(183, 128, 53, 0.28), transparent);
  pointer-events: none;
}

.section-heading {
  margin-bottom: 28px;
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
}

.section-index {
  display: inline-block;
  margin-bottom: 8px;
  color: #b78035;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: 2px;
}

.section-heading h2 {
  font-size: 38px;
  color: #123646;
}

.section-kicker {
  color: #90795f;
  font-size: 12px;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.premium-panel {
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.92), rgba(255, 255, 255, 0.72));
  border: 1px solid rgba(255, 255, 255, 0.72);
  box-shadow: 0 22px 42px rgba(25, 44, 52, 0.1);
  backdrop-filter: blur(10px);
}

/* 第1部分 */
.intro-layout {
  display: grid;
  grid-template-columns: 1.3fr 0.7fr;
  gap: 24px;
}

.intro-panel,
.intro-aside {
  padding: 34px;
  border-radius: 28px;
}

.intro-panel h3,
.intro-aside h3 {
  margin-bottom: 14px;
  color: #123646;
  font-size: 28px;
  line-height: 1.4;
}

.intro-panel p + p {
  margin-top: 16px;
}

.intro-aside {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.mini-label {
  display: inline-block;
  margin-bottom: 12px;
  color: #b78035;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 2px;
}

.intro-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 22px;
}

.intro-tags span {
  padding: 7px 12px;
  border-radius: 999px;
  color: #123646;
  background: #fff1cf;
  font-size: 13px;
  font-weight: 700;
}

/* 卡片样式 */
.upgraded-grid {
  gap: 28px;
}

.photo-card {
  min-height: 340px;
  position: relative;
  overflow: hidden;
  border-radius: 30px;
  cursor: pointer;
  display: flex;
  align-items: flex-end;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  box-shadow: 0 24px 42px rgba(25, 44, 52, 0.16);
  transition: transform 0.35s, box-shadow 0.35s;
}

.photo-card::before,
.photo-card::after {
  display: none;
}

.photo-card:hover {
  transform: translateY(-10px) scale(1.01);
  box-shadow: 0 28px 48px rgba(18, 36, 44, 0.22);
}

.card-overlay {
  position: absolute;
  inset: 0;
  background:
    linear-gradient(to top, rgba(6, 16, 24, 0.88), rgba(6, 16, 24, 0.22) 48%, rgba(255, 255, 255, 0.02)),
    linear-gradient(135deg, rgba(255, 255, 255, 0.06), transparent);
  z-index: 1;
}

.photo-card .card-meta {
  width: 100%;
  padding: 28px;
  position: relative;
  z-index: 2;
}

.photo-card .card-label {
  display: inline-block;
  margin-bottom: 10px;
  padding: 6px 12px;
  border-radius: 999px;
  font-size: 12px;
  letter-spacing: 2px;
  color: #ffe5ab;
  background: rgba(255, 255, 255, 0.12);
  border: 1px solid rgba(255, 255, 255, 0.14);
}

.photo-card .card-meta h3 {
  font-size: 32px;
  margin-bottom: 10px;
  color: #fff;
}

.photo-card .card-meta p {
  color: rgba(255, 255, 255, 0.9);
}

/* 第3部分 */
.route-shell-upgraded {
  align-items: stretch;
}

.route-side {
  position: relative;
  overflow: hidden;
  color: #f7f3e8;
  background:
    radial-gradient(circle at 80% 10%, rgba(246, 198, 103, 0.18), transparent 26%),
    linear-gradient(160deg, #0f2f3f, #184651 62%, #1f5757);
}

.route-side p {
  color: rgba(247, 243, 232, 0.9);
}

.route-side h3 {
  color: #ffffff;
}

.route-side-tag,
.route-control label {
  color: #ffe3a2;
}

.route-mini-list {
  display: grid;
  gap: 12px;
  margin-top: 26px;
}

.route-mini-list div {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 13px 14px;
  border-radius: 16px;
  background: rgba(255, 255, 255, 0.1);
}

.route-mini-list strong {
  color: #ffe3a2;
  font-size: 15px;
}

.route-mini-list span {
  color: rgba(255, 255, 255, 0.92);
  font-size: 14px;
}

.route-main-panel {
  padding: 0;
  border-radius: 30px;
}

.route-main-panel .route-result {
  min-height: 100%;
  background: transparent;
  box-shadow: none;
  border: none;
}

/* 路线模块文字可读性加强 */
.route-result {
  color: #24363d;
}

.route-plan h4 {
  color: #123646;
}

.route-summary-item {
  background: linear-gradient(180deg, #fffdf8, #f3ecdf);
}

.route-summary-item span {
  color: #6f7f84;
}

.route-summary-item strong {
  color: #123646;
}

.timeline-day-title {
  color: #123646;
}

.timeline-node {
  background: linear-gradient(180deg, #fffdf9, #f6efe3);
}

.timeline-node h5 {
  color: #123646;
}

.timeline-node p {
  color: #4c5f66;
}

.timeline-time {
  background: #fff0c8;
  color: #8b6120;
}

.transport-tip {
  background: linear-gradient(180deg, #fff9ea, #f6edd7);
  color: #6d5827;
}

.empty-tip {
  color: #5c6f76;
}

/* 第4部分 */
.green-layout {
  display: grid;
  grid-template-columns: 1.35fr 0.75fr;
  gap: 28px;
  align-items: stretch;
}

.green-text {
  padding: 34px;
  border-radius: 28px;
}

.green-text h3 {
  margin-bottom: 14px;
  color: #123646;
  font-size: 28px;
}

.green-actions {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 14px;
  margin-top: 24px;
}

.green-action {
  padding: 16px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fffdf8, #f5eddf);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.green-action strong {
  display: block;
  margin-bottom: 6px;
  color: #123646;
}

.green-action span {
  color: #53646b;
  font-size: 14px;
}

.eco-card-upgraded {
  position: relative;
  overflow: hidden;
  background:
    radial-gradient(circle at top, rgba(255, 255, 255, 0.2), transparent 30%),
    linear-gradient(160deg, #5c9076, #89b07f 60%, #bfd39f);
}

.eco-card-upgraded h3 {
  font-size: 28px;
  color: #fff;
}

.eco-orbit {
  width: 170px;
  height: 170px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 1px dashed rgba(255, 255, 255, 0.55);
}

/* 第5部分 */
.ai-layout {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 24px;
}

.ai-box-upgraded,
.ai-credit {
  padding: 34px;
  border-radius: 28px;
  position: relative;
  overflow: hidden;
}

.ai-box-upgraded::before,
.ai-credit::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  width: 6px;
  height: 100%;
  background: linear-gradient(180deg, #f0c36c, #b78035);
}

.ai-box-upgraded h3,
.ai-credit h3 {
  margin-bottom: 14px;
  color: #123646;
  font-size: 28px;
}

.ai-box-upgraded p,
.ai-credit p {
  position: relative;
  z-index: 1;
}

.ai-box-upgraded p + p,
.ai-credit p + p {
  margin-top: 14px;
}

/* 夜间模式适配 */
body.dark .section-heading h2,
body.dark .intro-panel h3,
body.dark .intro-aside h3,
body.dark .green-text h3,
body.dark .ai-box-upgraded h3,
body.dark .ai-credit h3 {
  color: #f0c36c;
}

body.dark .section-kicker,
body.dark .mini-label {
  color: #f0c36c;
}

body.dark .premium-panel,
body.dark .intro-panel,
body.dark .intro-aside,
body.dark .green-text,
body.dark .ai-box-upgraded,
body.dark .ai-credit,
body.dark .route-main-panel {
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.08), rgba(255, 255, 255, 0.05));
  border-color: rgba(255, 255, 255, 0.08);
}

body.dark .intro-tags span,
body.dark .green-action,
body.dark .route-summary-item,
body.dark .timeline-node {
  background: rgba(255, 255, 255, 0.07);
  color: #e8f1f2;
}

body.dark .green-action strong,
body.dark .route-plan h4,
body.dark .timeline-day-title,
body.dark .timeline-node h5,
body.dark .route-summary-item strong {
  color: #f6c667;
}

body.dark .green-action span,
body.dark .timeline-node p,
body.dark .route-summary-item span,
body.dark .empty-tip {
  color: #d3e0e2;
}

body.dark .timeline-time {
  background: rgba(246, 198, 103, 0.14);
  color: #ffe3a2;
}

body.dark .transport-tip {
  background: rgba(246, 198, 103, 0.12);
  color: #f3dfb1;
}

/* 响应式 */
@media (max-width: 980px) {
  .intro-layout,
  .green-layout,
  .ai-layout {
    grid-template-columns: 1fr;
  }

  .green-actions {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  .section-heading {
    align-items: flex-start;
  }

  .section-heading h2 {
    font-size: 30px;
  }

  .intro-panel,
  .intro-aside,
  .green-text,
  .ai-box-upgraded,
  .ai-credit {
    padding: 24px;
  }

  .intro-panel h3,
  .intro-aside h3,
  .green-text h3,
  .ai-box-upgraded h3,
  .ai-credit h3 {
    font-size: 24px;
  }
}

/* 强制恢复封面背景图 */
.hero {
  background:
    linear-gradient(115deg, rgba(6, 16, 24, 0.28), rgba(6, 16, 24, 0.78)),
    linear-gradient(180deg, rgba(8, 20, 28, 0.08), rgba(8, 20, 28, 0.58)),
    url("imageshero.jpg") center center / cover no-repeat !important;
}

/* =========================
   页面节奏优化：封面一屏显示 + 1-5部分整屏化
   ========================= */

/* 让每个正文大章节至少占满一屏，避免上一部分还没看完就露出下一部分 */
main > .section {
  min-height: 100svh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-top: 72px;
  padding-bottom: 72px;
}

/* 第3部分路线选择后内容可能变长，允许自然撑开 */
.route-section {
  justify-content: flex-start;
}

/* 第5部分内容不多，保持居中更稳 */
.ai-section {
  justify-content: center;
}

/* 封面整体压缩，让首页信息尽量一屏完整显示 */
.hero {
  min-height: 100svh;
}

.navbar {
  padding: 18px 0;
}

.hero-content {
  margin-top: clamp(42px, 7vh, 72px);
  gap: 32px;
}

.hero h1 {
  font-size: clamp(48px, 7vw, 86px);
  margin-bottom: 18px;
}

.subtitle {
  font-size: 17px;
  line-height: 1.75;
}

.hero-line {
  margin-bottom: 12px;
}

.hero-year {
  margin-bottom: 12px;
}

.hero-buttons {
  margin-top: 26px;
}

.hero-award-card {
  padding: 24px 24px;
}

.hero-award-card h3 {
  font-size: 24px;
}

.hero-award-card p:last-child {
  font-size: 14px;
  line-height: 1.75;
}

.hero-data {
  margin-top: 26px;
}

.data-card {
  padding: 16px 18px;
}

.data-card strong {
  font-size: 15px;
}

.scroll-tip {
  bottom: 88px;
}

.wave {
  height: 78px;
}

/* 正文标题区更规整 */
.section-heading {
  margin-bottom: 24px;
}

.section-heading h2 {
  line-height: 1.25;
}

/* 第1部分内容加大一点，避免显得太空 */
.intro-panel,
.intro-aside {
  min-height: 320px;
}

/* 第2部分图片卡高度统一，更像完整展示区 */
.photo-card {
  min-height: 360px;
}

/* 第4部分绿色模块撑开一些 */
.green-text,
.eco-card-upgraded {
  min-height: 420px;
}

/* 第5部分AI说明区域撑开一些 */
.ai-box-upgraded,
.ai-credit {
  min-height: 360px;
}

/* 笔记本屏幕高度较小时，进一步压缩封面 */
@media (max-height: 760px) {
  .navbar {
    padding: 14px 0;
  }

  .hero-content {
    margin-top: 30px;
  }

  .hero h1 {
    font-size: clamp(44px, 6.4vw, 74px);
    margin-bottom: 14px;
  }

  .subtitle {
    font-size: 16px;
    line-height: 1.65;
  }

  .hero-buttons {
    margin-top: 20px;
  }

  .btn {
    padding: 11px 24px;
  }

  .hero-award-card {
    padding: 20px 22px;
  }

  .hero-award-card h3 {
    font-size: 22px;
  }

  .hero-award-card p:last-child {
    font-size: 13px;
    line-height: 1.65;
  }

  .hero-data {
    margin-top: 18px;
  }

  .data-card {
    padding: 13px 16px;
  }

  .data-card span {
    margin-bottom: 4px;
  }

  .data-card strong {
    font-size: 14px;
  }

  .scroll-tip {
    bottom: 72px;
  }

  .wave {
    height: 62px;
  }
}

/* 更矮的屏幕，比如部分笔记本浏览器窗口没全屏时 */
@media (max-height: 680px) {
  .hero-content {
    margin-top: 22px;
  }

  .hero h1 {
    font-size: clamp(40px, 6vw, 66px);
  }

  .hero-line p,
  .hero-year {
    font-size: 12px;
  }

  .subtitle {
    font-size: 15px;
  }

  .hero-data {
    grid-template-columns: repeat(3, 1fr);
    gap: 12px;
  }

  .data-card {
    padding: 10px 12px;
  }

  .data-card span {
    font-size: 12px;
  }

  .data-card strong {
    font-size: 13px;
  }

  .scroll-tip {
    display: none;
  }
}

/* 手机端不强制每一部分一整屏，避免内容太长不好滑 */
@media (max-width: 640px) {
  main > .section {
    min-height: auto;
    padding-top: 68px;
    padding-bottom: 68px;
  }

  .hero {
    min-height: 100svh;
  }

  .hero-data {
    grid-template-columns: 1fr;
  }

  .photo-card {
    min-height: 300px;
  }

  .green-text,
  .eco-card-upgraded,
  .ai-box-upgraded,
  .ai-credit,
  .intro-panel,
  .intro-aside {
    min-height: auto;
  }
}

/* =========================
   终版修正：封面一屏化 + 去掉怪异底部设计 + 正文自然滚动
   ========================= */

/* 封面控制在更稳定的一屏视觉内 */
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
}

.navbar {
  padding: 16px 0;
}

.hero-content {
  width: min(92%, 1280px);
  margin: 52px auto 0;
  display: grid;
  grid-template-columns: 1.12fr 0.72fr;
  gap: 28px;
  align-items: center;
}

.hero h1 {
  font-size: clamp(48px, 6.5vw, 82px);
  line-height: 0.95;
  margin-bottom: 16px;
}

.subtitle {
  max-width: 700px;
  font-size: 16px;
  line-height: 1.75;
}

.hero-line {
  margin-bottom: 10px;
}

.hero-year {
  margin-bottom: 12px;
  font-size: 12px;
}

.hero-buttons {
  margin-top: 24px;
}

.btn {
  padding: 12px 26px;
}

.hero-award-card {
  max-width: 350px;
  padding: 22px 22px;
  border-radius: 24px;
}

.hero-award-card h3 {
  font-size: 24px;
  margin-bottom: 10px;
}

.hero-award-card p:last-child {
  font-size: 14px;
  line-height: 1.7;
}

/* 去掉底部多余占位 */
.hero-data {
  display: none !important;
}

.scroll-tip {
  display: none !important;
}

/* 波浪改轻一点，不要压得很怪 */
.wave {
  height: 54px;
  clip-path: polygon(0 58%, 16% 66%, 36% 52%, 58% 68%, 80% 55%, 100% 64%, 100% 100%, 0 100%);
}

/* 正文不要再强行每部分100vh了，恢复正常 */
main > .section {
  min-height: auto !important;
  display: block !important;
  padding-top: 78px;
  padding-bottom: 78px;
}

/* 第1、3、4、5部分做“接近一屏”的舒展感，但不强制 */
.intro-layout,
.route-shell,
.green-layout,
.ai-layout {
  align-items: stretch;
}

.intro-panel,
.intro-aside,
.route-side,
.route-main-panel,
.green-text,
.eco-card-upgraded,
.ai-box-upgraded,
.ai-credit {
  min-height: 340px;
}

/* 第2部分图片太大，压缩一点高度 */
.card-grid.upgraded-grid {
  grid-template-columns: repeat(2, 1fr);
  gap: 24px;
}

.photo-card {
  min-height: 300px;
}

.photo-card .card-meta {
  padding: 24px;
}

.photo-card .card-meta h3 {
  font-size: 28px;
  margin-bottom: 8px;
}

.photo-card .card-meta p {
  font-size: 15px;
  line-height: 1.7;
}

/* 第2部分标题和说明收一点，避免空太多 */
.cards-section .feature-head {
  margin-bottom: 20px;
}

/* 第1部分更像正式介绍区 */
.intro-panel h3,
.intro-aside h3,
.green-text h3,
.ai-box-upgraded h3,
.ai-credit h3 {
  font-size: 26px;
}

/* 路线区内容太多时自然展开 */
.route-result {
  min-height: 220px;
}

/* 页面整体顶部间距更统一 */
.section-heading {
  margin-bottom: 22px;
}

.section-heading h2 {
  font-size: 34px;
}

/* 高度较小屏幕，封面继续压缩 */
@media (max-height: 760px) {
  .hero-content {
    margin-top: 34px;
    gap: 22px;
  }

  .hero h1 {
    font-size: clamp(42px, 6vw, 72px);
  }

  .subtitle {
    font-size: 15px;
    line-height: 1.65;
  }

  .hero-buttons {
    margin-top: 18px;
  }

  .hero-award-card {
    padding: 18px 18px;
  }

  .hero-award-card h3 {
    font-size: 22px;
  }

  .hero-award-card p:last-child {
    font-size: 13px;
    line-height: 1.6;
  }

  .wave {
    height: 42px;
  }
}

/* 平板 */
@media (max-width: 980px) {
  .hero-content {
    grid-template-columns: 1fr;
    margin-top: 36px;
  }

  .hero-right {
    justify-content: flex-start;
  }

  .card-grid.upgraded-grid {
    grid-template-columns: 1fr;
  }

  .photo-card {
    min-height: 320px;
  }
}

/* 手机 */
@media (max-width: 640px) {
  .hero {
    min-height: auto;
    padding-bottom: 40px;
  }

  .hero-content {
    margin-top: 28px;
    gap: 20px;
  }

  .hero h1 {
    font-size: clamp(38px, 11vw, 58px);
    line-height: 1.02;
  }

  .subtitle {
    font-size: 15px;
  }

  .hero-buttons {
    flex-direction: column;
    align-items: flex-start;
  }

  .wave {
    height: 32px;
  }

  .section-heading h2 {
    font-size: 28px;
  }

  .photo-card {
    min-height: 260px;
  }

  .photo-card .card-meta {
    padding: 20px;
  }

  .photo-card .card-meta h3 {
    font-size: 24px;
  }

  .intro-panel,
  .intro-aside,
  .route-side,
  .route-main-panel,
  .green-text,
  .eco-card-upgraded,
  .ai-box-upgraded,
  .ai-credit {
    min-height: auto;
  }
}

/* 彻底修复封面底部怪异问题 */
header.hero .hero-data,
header.hero .scroll-tip,
header.hero .wave {
  display: none !important;
}

/* 封面底部不再使用波浪，改成干净自然的暗部过渡 */
.hero {
  min-height: 100vh !important;
  overflow: hidden !important;
  background:
    linear-gradient(115deg, rgba(6, 16, 24, 0.30), rgba(6, 16, 24, 0.76)),
    linear-gradient(180deg, rgba(8, 20, 28, 0.05), rgba(8, 20, 28, 0.68)),
    url("imageshero.jpg") center center / cover no-repeat !important;
}

.hero::after {
  content: "";
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  height: 130px;
  z-index: 2;
  pointer-events: none;
  background: linear-gradient(to bottom, transparent, rgba(6, 16, 24, 0.78));
}

/* 封面主体上移并压缩，避免一页放不下 */
.hero-content {
  margin-top: clamp(24px, 4vh, 48px) !important;
  gap: 28px !important;
  position: relative;
  z-index: 4;
}

.hero h1 {
  font-size: clamp(42px, 6.2vw, 76px) !important;
  line-height: 0.98 !important;
  margin-bottom: 14px !important;
}

.subtitle {
  font-size: 16px !important;
  line-height: 1.65 !important;
  max-width: 680px !important;
}

.hero-buttons {
  margin-top: 20px !important;
}

.hero-award-card {
  padding: 20px 22px !important;
}

.hero-award-card h3 {
  font-size: 22px !important;
}

.hero-award-card p:last-child {
  font-size: 13px !important;
  line-height: 1.6 !important;
}

/* =========================
   日间模式主题色手动切换
   ========================= */

.theme-tools {
  display: flex;
  align-items: center;
  gap: 12px;
}

.theme-select {
  border: 1px solid rgba(255,255,255,0.22);
  color: #fff;
  background: rgba(255,255,255,0.08);
  padding: 10px 16px;
  border-radius: 999px;
  cursor: pointer;
  backdrop-filter: blur(10px);
  outline: none;
  font-size: 14px;
}

.theme-select option {
  color: #23343b;
  background: #fff;
}

/* 默认：山水青 */
body.theme-shanshui {
  --bg: #f4efe3;
  --text: #23343b;
  --deep: #123646;
  --teal: #1f5b62;
  --gold: #f0c36c;
  --gold-soft: #f6deaa;
}

/* 佛光金 */
body.theme-gold {
  --bg: #f7f1e4;
  --text: #2d342f;
  --deep: #5a4627;
  --teal: #426b67;
  --gold: #d8a84f;
  --gold-soft: #f4d892;
}

/* 竹影绿 */
body.theme-bamboo {
  --bg: #eef4ea;
  --text: #223630;
  --deep: #1d473d;
  --teal: #3f7c63;
  --gold: #d7b766;
  --gold-soft: #efe0a6;
}

/* 嘉州暖橙 */
body.theme-warm {
  --bg: #f7eee5;
  --text: #2f3437;
  --deep: #543827;
  --teal: #536f68;
  --gold: #e59b55;
  --gold-soft: #f4c58c;
}

body:not(.dark) {
  background: radial-gradient(circle at top, #fffaf0, var(--bg) 58%);
  color: var(--text);
}

body:not(.dark) .section-heading h2,
body:not(.dark) .section-title h2,
body:not(.dark) .intro-panel h3,
body:not(.dark) .intro-aside h3,
body:not(.dark) .green-text h3,
body:not(.dark) .ai-box-upgraded h3,
body:not(.dark) .ai-credit h3,
body:not(.dark) .route-plan h4,
body:not(.dark) .timeline-day-title,
body:not(.dark) .timeline-node h5 {
  color: var(--deep);
}

body:not(.dark) .section-index,
body:not(.dark) .mini-label,
body:not(.dark) .section-kicker {
  color: var(--gold);
}

body:not(.dark) .primary,
body:not(.dark) .top-btn {
  background: linear-gradient(135deg, var(--gold), var(--gold-soft));
  color: #20323b;
}

body:not(.dark) .route-side {
  background:
    radial-gradient(circle at 80% 10%, rgba(246, 198, 103, 0.18), transparent 26%),
    linear-gradient(160deg, var(--deep), var(--teal) 62%, #2c6b64);
}

body:not(.dark) .intro-tags span,
body:not(.dark) .timeline-time {
  background: #fff1cf;
}

body:not(.dark) .ai-box-upgraded::before,
body:not(.dark) .ai-credit::before {
  background: linear-gradient(180deg, var(--gold), var(--deep));
}

/* ========================= 
    第6页左侧逻辑升级版 
    ========================= */ 
 
 .green-final-left { 
   display: flex; 
   flex-direction: column; 
 } 
 
 .green-final-intro p { 
   margin-bottom: 0; 
 } 
 
 .green-logic-list { 
   display: grid; 
   gap: 14px; 
   margin-top: 22px; 
 } 
 
 .green-logic-block { 
   position: relative; 
   padding: 18px 20px 16px; 
   border-radius: 22px; 
   background: 
     linear-gradient(180deg, rgba(255,255,255,0.92), rgba(255,247,225,0.84)); 
   border: 1px solid rgba(18, 54, 70, 0.08); 
   overflow: hidden; 
 } 
 
 .green-logic-block::after { 
   content: ""; 
   position: absolute; 
   right: -18px; 
   top: -18px; 
   width: 72px; 
   height: 72px; 
   border-radius: 50%; 
   background: rgba(240, 195, 108, 0.10); 
 } 
 
 .green-logic-head { 
   position: relative; 
   z-index: 1; 
   display: flex; 
   align-items: center; 
   gap: 12px; 
   margin-bottom: 8px; 
 } 
 
 .green-logic-head span { 
   width: 34px; 
   height: 34px; 
   border-radius: 50%; 
   display: inline-flex; 
   align-items: center; 
   justify-content: center; 
   background: #fff1cf; 
   color: #b78035; 
   font-size: 13px; 
   font-weight: 900; 
 } 
 
 .green-logic-head h4 { 
   margin: 0; 
   color: #123646; 
   font-size: 24px; 
   line-height: 1.2; 
 } 
 
 .green-logic-summary { 
   position: relative; 
   z-index: 1; 
   margin: 0 0 10px; 
   color: #607279; 
   font-size: 14px; 
   line-height: 1.7; 
 } 
 
 .green-logic-points { 
   position: relative; 
   z-index: 1; 
   display: grid; 
   gap: 8px; 
 } 
 
 .green-logic-points span { 
   position: relative; 
   display: block; 
   padding-left: 16px; 
   color: #50666d; 
   font-size: 14px; 
   line-height: 1.68; 
 } 
 
 .green-logic-points span::before { 
   content: ""; 
   position: absolute; 
   left: 0; 
   top: 10px; 
   width: 6px; 
   height: 6px; 
   border-radius: 50%; 
   background: #d1b75f; 
 } 
 
 .green-final-slogan { 
   margin-top: 18px !important; 
 } 
 
 .green-final-tags { 
   margin-top: 16px !important; 
 } 
 
 /* 暗色模式 */ 
 body.dark .green-logic-block { 
   background: rgba(255, 255, 255, 0.05); 
   border-color: rgba(255, 255, 255, 0.08); 
 } 
 
 body.dark .green-logic-head h4 { 
   color: #f0c36c; 
 } 
 
 body.dark .green-logic-summary, 
 body.dark .green-logic-points span { 
   color: #d3e0e2; 
 } 
 
 body.dark .green-logic-head span { 
   background: rgba(240, 195, 108, 0.14); 
   color: #f3dfb1; 
 } 
 
 /* 手机 */ 
 @media (max-width: 640px) { 
   .green-logic-block { 
     padding: 16px 16px 14px; 
   } 
 
   .green-logic-head h4 { 
     font-size: 20px; 
   } 
 }

/* 日间模式下选择器样式 */
body:not(.dark) .theme-select { 
  color: #fff;
  background: rgba(255,255,255,0.08);
}

/* 夜间模式下选择器 */
body.dark .theme-select {
  color: #f1f4f4;
  background: rgba(255,255,255,0.08);
  border-color: rgba(255,255,255,0.16);
}

/* 过渡更柔和 */
body,
.section-heading h2,
.intro-panel,
.intro-aside,
.green-text,
.ai-box-upgraded,
.ai-credit,
.route-side,
.primary,
.top-btn {
  transition:
    background 0.5s ease,
    color 0.5s ease,
    border-color 0.5s ease,
    box-shadow 0.5s ease;
}

@media (max-width: 900px) {
  .theme-tools {
    width: 100%;
    justify-content: flex-start;
    flex-wrap: wrap;
  }
}

@media (max-width: 640px) {
  .theme-tools {
    flex-direction: column;
    align-items: flex-start;
  }

  .theme-select {
    width: 100%;
  }
}

/* =========================
   第1-5部分日间主题色手动切换
   不影响封面 hero
   ========================= */

/* 主题选择器样式 */
.theme-tools {
  display: flex;
  align-items: center;
  gap: 12px;
}

.theme-select {
  border: 1px solid rgba(255,255,255,0.22);
  color: #fff;
  background: rgba(255,255,255,0.08);
  padding: 10px 16px;
  border-radius: 999px;
  cursor: pointer;
  backdrop-filter: blur(10px);
  outline: none;
  font-size: 14px;
}

.theme-select option {
  color: #23343b;
  background: #fff;
}

/* 四套日间主题变量 */
body.theme-shanshui {
  --page-bg: #f4efe3;
  --main-text: #23343b;
  --main-muted: #62737a;
  --main-deep: #123646;
  --main-accent: #1f5b62;
  --main-gold: #f0c36c;
  --main-soft: #fff1cf;
  --main-card: rgba(255, 255, 255, 0.88);
}

body.theme-gold {
  --page-bg: #f7f1e4;
  --main-text: #332b1f;
  --main-muted: #7a6a55;
  --main-deep: #5a4627;
  --main-accent: #8a6a2f;
  --main-gold: #d8a84f;
  --main-soft: #f8e6b8;
  --main-card: rgba(255, 250, 239, 0.9);
}

body.theme-bamboo {
  --page-bg: #eef4ea;
  --main-text: #223630;
  --main-muted: #5d756b;
  --main-deep: #1d473d;
  --main-accent: #3f7c63;
  --main-gold: #d7b766;
  --main-soft: #edf3d2;
  --main-card: rgba(250, 255, 248, 0.9);
}

body.theme-warm {
  --page-bg: #f7eee5;
  --main-text: #332923;
  --main-muted: #7b6658;
  --main-deep: #543827;
  --main-accent: #9a6040;
  --main-gold: #e59b55;
  --main-soft: #f8d7b2;
  --main-card: rgba(255, 248, 241, 0.9);
}

/* 只改变 main，也就是1-5部分，不改变封面 */
body:not(.dark) main {
  background:
    radial-gradient(circle at top, rgba(255,255,255,0.85), transparent 28%),
    var(--page-bg) !important;
  color: var(--main-text) !important;
}

/* 每个section的底色统一随主题变化 */
body:not(.dark) main > .section {
  background: transparent !important;
}

/* 第1-5部分标题颜色 */
body:not(.dark) main .section-heading h2,
body:not(.dark) main .section-title h2,
body:not(.dark) main .intro-panel h3,
body:not(.dark) main .intro-aside h3,
body:not(.dark) main .green-text h3,
body:not(.dark) main .ai-box-upgraded h3,
body:not(.dark) main .ai-credit h3,
body:not(.dark) main .route-plan h4,
body:not(.dark) main .timeline-day-title,
body:not(.dark) main .timeline-node h5 {
  color: var(--main-deep) !important;
}

/* 小标题、编号、英文标识 */
body:not(.dark) main .section-index,
body:not(.dark) main .mini-label,
body:not(.dark) main .section-kicker {
  color: var(--main-gold) !important;
}

/* 正文文字 */
body:not(.dark) main p,
body:not(.dark) main li,
body:not(.dark) main .feature-head,
body:not(.dark) main .timeline-node p,
body:not(.dark) main .green-action span,
body:not(.dark) main .route-summary-item span,
body:not(.dark) main .empty-tip {
  color: var(--main-muted) !important;
}

/* 主要卡片背景 */
body:not(.dark) main .premium-panel,
body:not(.dark) main .intro-panel,
body:not(.dark) main .intro-aside,
body:not(.dark) main .green-text,
body:not(.dark) main .ai-box-upgraded,
body:not(.dark) main .ai-credit,
body:not(.dark) main .route-main-panel,
body:not(.dark) main .route-result {
  background:
    linear-gradient(180deg, var(--main-card), rgba(255,255,255,0.68)) !important;
  border-color: rgba(255,255,255,0.75) !important;
  box-shadow: 0 22px 42px rgba(25, 44, 52, 0.10) !important;
}

/* 第3部分左侧路线面板 */
body:not(.dark) main .route-side {
  background:
    radial-gradient(circle at 80% 10%, color-mix(in srgb, var(--main-gold) 30%, transparent), transparent 28%),
    linear-gradient(160deg, var(--main-deep), var(--main-accent) 62%, var(--main-deep)) !important;
  color: #fff !important;
}

body:not(.dark) main .route-side h3,
body:not(.dark) main .route-side p,
body:not(.dark) main .route-mini-list span {
  color: rgba(255,255,255,0.92) !important;
}

body:not(.dark) main .route-side-tag,
body:not(.dark) main .route-control label,
body:not(.dark) main .route-mini-list strong {
  color: #ffe7ad !important;
}

/* 路线时间轴卡片 */
body:not(.dark) main .route-summary-item,
body:not(.dark) main .timeline-node,
body:not(.dark) main .green-action {
  background:
    linear-gradient(180deg, rgba(255,255,255,0.95), var(--main-soft)) !important;
  border-color: color-mix(in srgb, var(--main-deep) 12%, transparent) !important;
}

body:not(.dark) main .route-summary-item strong,
body:not(.dark) main .green-action strong {
  color: var(--main-deep) !important;
}

body:not(.dark) main .timeline-time {
  background: var(--main-soft) !important;
  color: var(--main-deep) !important;
}

body:not(.dark) main .map-timeline::before {
  background: linear-gradient(to bottom, var(--main-gold), color-mix(in srgb, var(--main-accent) 45%, transparent)) !important;
}

body:not(.dark) main .timeline-node::before {
  background: var(--main-gold) !important;
}

/* 标签 */
body:not(.dark) main .intro-tags span {
  background: var(--main-soft) !important;
  color: var(--main-deep) !important;
}

/* 第4部分低碳卡 */
body:not(.dark) main .eco-card-upgraded,
body:not(.dark) main .eco-card {
  background:
    radial-gradient(circle at top, rgba(255,255,255,0.22), transparent 32%),
    linear-gradient(160deg, var(--main-accent), color-mix(in srgb, var(--main-accent) 70%, var(--main-gold) 30%), var(--main-gold)) !important;
}

/* 第5部分AI说明左侧竖线 */
body:not(.dark) main .ai-box-upgraded::before,
body:not(.dark) main .ai-credit::before {
  background: linear-gradient(180deg, var(--main-gold), var(--main-deep)) !important;
}

/* 返回顶部按钮也跟随主题 */
body:not(.dark) .top-btn {
  background: linear-gradient(135deg, var(--main-gold), var(--main-soft)) !important;
  color: var(--main-deep) !important;
}

/* 过渡动画，让切换更明显 */
body:not(.dark) main,
body:not(.dark) main *,
body:not(.dark) .top-btn {
  transition:
    background 0.45s ease,
    color 0.45s ease,
    border-color 0.45s ease,
    box-shadow 0.45s ease !important;
}

/* 夜间模式下禁用日间主题影响 */
body.dark main {
  background: #0d1d24 !important;
}

/* 手机适配 */
@media (max-width: 900px) {
  .theme-tools {
    width: 100%;
    justify-content: flex-start;
    flex-wrap: wrap;
  }
}

@media (max-width: 640px) {
  .theme-tools {
    flex-direction: column;
    align-items: flex-start;
  }

  .theme-select {
    width: 100%;
  }
}

/* =========================
   封面标题改为书法风字体：华文行楷
   ========================= */

.hero h1 {
  font-family: "STXingkai", "STKaiti", "KaiTi", serif !important;
  font-weight: normal !important;
  font-size: clamp(58px, 7.4vw, 110px) !important;
  line-height: 1.02 !important;
  letter-spacing: 0px !important;
  margin-bottom: 18px !important;
  text-shadow:
    0 8px 24px rgba(0, 0, 0, 0.28),
    0 3px 10px rgba(0, 0, 0, 0.16) !important;
}

.hero h1 span {
  display: inline-block;
  margin-top: 6px;
  font-family: "STXingkai", "STKaiti", "KaiTi", serif !important;
  font-weight: normal !important;
  font-size: 0.9em !important;
  letter-spacing: 1px !important;
  color: #ffe1a0 !important;
  text-shadow:
    0 0 12px rgba(240, 195, 108, 0.2),
    0 6px 18px rgba(0, 0, 0, 0.22) !important;
}

/* 适配封面整体 */
.hero-left {
  max-width: 760px !important;
}

.subtitle {
  max-width: 650px !important;
  margin-top: 6px !important;
  font-size: 16px !important;
  line-height: 1.78 !important;
}

/* 右侧说明卡更协调 */
.hero-award-card {
  width: min(100%, 350px) !important;
  padding: 22px 22px !important;
}

.hero-award-card h3 {
  font-size: 24px !important;
  line-height: 1.35 !important;
}

.hero-award-card p:last-child {
  font-size: 14px !important;
  line-height: 1.72 !important;
}

/* 笔记本屏幕 */
@media (max-height: 820px) {
  .hero h1 {
    font-size: clamp(50px, 6.6vw, 90px) !important;
    margin-bottom: 14px !important;
  }

  .hero h1 span {
    margin-top: 4px;
  }

  .subtitle {
    font-size: 15px !important;
    line-height: 1.68 !important;
  }
}

/* 平板 */
@media (max-width: 980px) {
  .hero h1 {
    font-size: clamp(50px, 9vw, 88px) !important;
    line-height: 1.04 !important;
  }
}

/* 手机 */
@media (max-width: 640px) {
  .hero h1 {
    font-size: clamp(40px, 12vw, 64px) !important;
    line-height: 1.08 !important;
    margin-bottom: 12px !important;
  }

  .hero h1 span {
    margin-top: 2px;
    font-size: 0.9em !important;
    letter-spacing: 0px !important;
  }

  .subtitle {
    font-size: 15px !important;
    line-height: 1.7 !important;
  }
}

/* =========================
   第一部分图文并茂改版
   ========================= */

.intro-showcase {
  display: grid;
  grid-template-columns: 1.18fr 0.82fr;
  gap: 24px;
  align-items: stretch;
}

.intro-main-column,
.intro-side-column {
  display: grid;
  gap: 20px;
}

.intro-main-visual,
.intro-main-copy,
.intro-info-card,
.intro-sub-card {
  overflow: hidden;
  border-radius: 28px;
}

.intro-main-visual {
  position: relative;
  min-height: 360px;
  padding: 0;
}

.intro-main-visual img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}

.intro-visual-overlay {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  padding: 28px;
  background: linear-gradient(to top, rgba(8, 18, 26, 0.76), rgba(8, 18, 26, 0.08));
  color: #fff;
}

.intro-visual-overlay .mini-label {
  color: #ffe1a0;
}

.intro-visual-overlay h3 {
  margin-top: 8px;
  font-size: 30px;
  line-height: 1.35;
  color: #fff;
}

.intro-main-copy {
  padding: 28px 30px;
}

.intro-main-copy p {
  font-size: 17px;
  line-height: 1.9;
}

.intro-main-copy p + p {
  margin-top: 16px;
}

.intro-info-card {
  padding: 28px 28px 24px;
}

.intro-info-list {
  display: grid;
  gap: 18px;
  margin-top: 6px;
}

.intro-info-item {
  padding-bottom: 16px;
  border-bottom: 1px solid rgba(18, 54, 70, 0.08);
}

.intro-info-item:last-child {
  padding-bottom: 0;
  border-bottom: none;
}

.intro-info-item h4 {
  margin-bottom: 8px;
  font-size: 22px;
  color: #123646;
}

.intro-info-item p {
  font-size: 15px;
  line-height: 1.8;
  color: #7a8c95;
}

.intro-sub-visuals {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 18px;
}

.intro-sub-card {
  position: relative;
  min-height: 180px;
  padding: 0;
}

.intro-sub-card img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}

.intro-sub-overlay {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  padding: 16px 18px;
  background: linear-gradient(to top, rgba(8, 18, 26, 0.72), rgba(8, 18, 26, 0.06));
}

.intro-sub-overlay span {
  color: #fff;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: 1px;
}

.intro-tags-row {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 22px;
}

.intro-tags-row span {
  padding: 9px 14px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 14px;
  font-weight: 700;
}

body.dark .intro-main-copy,
body.dark .intro-info-card,
body.dark .intro-sub-card {
  background: linear-gradient(180deg, rgba(255,255,255,0.08), rgba(255,255,255,0.05));
  border-color: rgba(255,255,255,0.08);
}

body.dark .intro-info-item {
  border-bottom-color: rgba(255,255,255,0.08);
}

body.dark .intro-info-item h4 {
  color: #f0c36c;
}

body.dark .intro-info-item p,
body.dark .intro-main-copy p {
  color: #d3e0e2;
}

body.dark .intro-tags-row span {
  background: rgba(246, 198, 103, 0.14);
  color: #f3dfb1;
}

@media (max-width: 1100px) {
  .intro-showcase {
    grid-template-columns: 1fr;
  }

  .intro-sub-visuals {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 640px) {
  .intro-main-visual {
    min-height: 260px;
  }

  .intro-visual-overlay {
    padding: 20px;
  }

  .intro-visual-overlay h3 {
    font-size: 24px;
  }

  .intro-main-copy,
  .intro-info-card {
    padding: 22px;
  }

  .intro-main-copy p {
    font-size: 15px;
    line-height: 1.8;
  }

  .intro-info-item h4 {
    font-size: 20px;
  }

  .intro-sub-visuals {
    grid-template-columns: 1fr;
  }

  .intro-sub-card {
    min-height: 180px;
  }

  .intro-tags-row {
    margin-top: 18px;
    gap: 10px;
  }

  .intro-tags-row span {
    font-size: 13px;
  }
}

/* 第二页弹窗升级为左图右文 */
.modal-feature {
  width: min(94%, 1120px);
  padding: 0;
  border-radius: 32px;
  overflow: hidden;
  background: linear-gradient(180deg, #fffdf8, #f6efe4);
}

.modal-feature-layout {
  display: grid;
  grid-template-columns: 0.95fr 1.05fr;
  min-height: 620px;
}

.modal-feature-visual {
  position: relative;
  min-height: 100%;
  overflow: hidden;
}

.modal-feature-visual img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}

.modal-feature-visual::after {
  content: "";
  position: absolute;
  inset: 0;
  background:
    linear-gradient(to top, rgba(8, 18, 26, 0.82), rgba(8, 18, 26, 0.18)),
    linear-gradient(135deg, rgba(255,255,255,0.06), transparent);
}

.modal-feature-overlay {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 2;
  padding: 34px 30px;
}

.modal-en-title {
  margin-bottom: 10px;
  color: #ffe3a2;
  font-size: 12px;
  letter-spacing: 2px;
  font-weight: 700;
}

.modal-feature-overlay h3 {
  font-size: 54px;
  line-height: 1.08;
  color: #fff;
  margin: 0;
}

.modal-feature-content {
  padding: 42px 40px 34px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.modal-lead {
  margin-bottom: 24px;
  font-size: 18px;
  line-height: 1.95;
  color: #53646b;
}

.modal-body-stack {
  display: grid;
  gap: 16px;
}

.modal-block {
  padding: 20px 20px 18px;
  border-radius: 22px;
  background: linear-gradient(180deg, #ffffff, #f5eddf);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.modal-block-label {
  display: inline-block;
  margin-bottom: 10px;
  color: #b78035;
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 1px;
}

.modal-block p {
  color: #55676e;
  line-height: 1.85;
  font-size: 15px;
}

.modal-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 22px;
}

.modal-tags span {
  padding: 8px 14px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 13px;
  font-weight: 700;
}

.modal-feature .close-btn {
  position: absolute;
  top: 18px;
  right: 22px;
  z-index: 5;
  width: 42px;
  height: 42px;
  border-radius: 50%;
  color: #111;
  background: rgba(255,255,255,0.78);
  backdrop-filter: blur(8px);
  font-size: 30px;
  line-height: 1;
}

body.dark .modal-feature {
  background: linear-gradient(180deg, #142730, #102129);
}

body.dark .modal-lead,
body.dark .modal-block p {
  color: #d3e0e2;
}

body.dark .modal-block {
  background: rgba(255,255,255,0.06);
  border-color: rgba(255,255,255,0.08);
}

body.dark .modal-tags span {
  background: rgba(246, 198, 103, 0.14);
  color: #f3dfb1;
}

body.dark .modal-feature .close-btn {
  color: #fff;
  background: rgba(255,255,255,0.12);
}

@media (max-width: 980px) {
  .modal-feature-layout {
    grid-template-columns: 1fr;
    min-height: auto;
  }

  .modal-feature-visual {
    height: 300px;
  }

  .modal-feature-overlay h3 {
    font-size: 42px;
  }

  .modal-feature-content {
    padding: 28px 24px 24px;
  }
}

@media (max-width: 640px) {
  .modal-feature-visual {
    height: 240px;
  }

  .modal-feature-overlay {
    padding: 22px 20px;
  }

  .modal-feature-overlay h3 {
    font-size: 32px;
  }

  .modal-lead {
    font-size: 16px;
    line-height: 1.8;
  }

  .modal-block {
    padding: 16px;
  }
}

/* =========================
   第4部分：绿色低碳游嘉州 + 垃圾分类小游戏
   ========================= */

.green-game-layout {
  display: grid;
  grid-template-columns: 1.08fr 0.92fr;
  gap: 26px;
  align-items: stretch;
}

.green-game-shell {
  padding: 30px;
  border-radius: 30px;
}

.game-head h3 {
  margin: 10px 0 10px;
  color: #123646;
  font-size: 30px;
}

.game-head p {
  color: #7a8c95;
  line-height: 1.8;
}

.game-status {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
  margin-top: 22px;
}

.game-score-card {
  padding: 16px 18px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fffdf8, #f4eddc);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.game-score-card span {
  display: block;
  margin-bottom: 6px;
  color: #6c7d82;
  font-size: 13px;
}

.game-score-card strong {
  color: #123646;
  font-size: 24px;
}

.trash-card {
  margin-top: 18px;
  padding: 22px 22px 20px;
  border-radius: 24px;
  background:
    radial-gradient(circle at top right, rgba(240, 195, 108, 0.14), transparent 26%),
    linear-gradient(180deg, #ffffff, #f6f1e8);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.trash-card-top {
  display: flex;
  align-items: center;
  gap: 16px;
  margin-bottom: 10px;
}

.trash-item-icon {
  width: 74px;
  height: 74px;
  border-radius: 22px;
  display: flex;
  align-items: center;
  justify-content: center;
  background:
    radial-gradient(circle at top, rgba(255,255,255,0.35), transparent 34%),
    linear-gradient(160deg, #1f5b62, #5fa078);
  color: #fff;
  font-size: 20px;
  font-weight: 800;
  letter-spacing: 1px;
  box-shadow: 0 14px 28px rgba(18, 54, 70, 0.16);
  flex-shrink: 0;
}

.trash-card-copy {
  min-width: 0;
}

.trash-card-label {
  display: inline-block;
  margin-bottom: 8px;
  color: #b78035;
  font-size: 12px;
  letter-spacing: 2px;
  font-weight: 700;
}

.trash-card h4 {
  margin-bottom: 0;
  color: #123646;
  font-size: 28px;
}

.trash-card p {
  color: #5d7077;
  line-height: 1.8;
}

.bins-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
  margin-top: 18px;
}

.bin-btn {
  min-height: 82px;
  padding: 16px 18px;
  border: none;
  border-radius: 22px;
  cursor: pointer;
  text-align: left;
  transition: transform 0.22s, box-shadow 0.22s, background 0.22s, color 0.22s;
  box-shadow: 0 12px 24px rgba(18, 36, 44, 0.08);
}

.bin-btn span {
  display: block;
  margin-bottom: 5px;
  font-size: 18px;
  font-weight: 800;
}

.bin-btn small {
  font-size: 12px;
  opacity: 0.82;
}

.bin-btn:hover {
  transform: translateY(-3px);
}

.bin-btn.recyclable {
  background: linear-gradient(135deg, #d9efff, #a9d4ff);
  color: #184b76;
}

.bin-btn.kitchen {
  background: linear-gradient(135deg, #e0f6d5, #b9e28c);
  color: #2d6a28;
}

.bin-btn.harmful {
  background: linear-gradient(135deg, #ffd8d8, #ffaaaa);
  color: #842d2d;
}

.bin-btn.other {
  background: linear-gradient(135deg, #ececec, #cfcfcf);
  color: #4f575d;
}

.bin-btn.correct {
  box-shadow: 0 0 0 4px rgba(108, 190, 111, 0.22), 0 16px 28px rgba(34, 100, 40, 0.12);
  transform: translateY(-2px);
}

.bin-btn.wrong {
  box-shadow: 0 0 0 4px rgba(217, 86, 86, 0.18), 0 16px 28px rgba(120, 40, 40, 0.08);
}

.bin-btn:disabled {
  cursor: not-allowed;
}

.game-feedback {
  min-height: 58px;
  margin-top: 18px;
  padding: 16px 18px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fff9eb, #f7efdc);
  color: #6d5827;
  line-height: 1.7;
  border-left: 4px solid #f0c36c;
}

.game-feedback.success {
  background: linear-gradient(180deg, #eef9ea, #e0f3d7);
  color: #2f6a2a;
  border-left-color: #7ac16d;
}

.game-feedback.error {
  background: linear-gradient(180deg, #fff1f1, #fde1e1);
  color: #8c3333;
  border-left-color: #db6b6b;
}

.game-feedback.finish {
  background: linear-gradient(180deg, #eef7ff, #dfeeff);
  color: #26577e;
  border-left-color: #6aa8e8;
}

.game-footer {
  margin-top: 18px;
}

.game-restart-btn {
  padding: 10px 22px;
}

.green-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 22px;
}

.green-tags span {
  padding: 8px 14px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 13px;
  font-weight: 700;
}

/* 认证卡弹窗 */
.cert-modal {
  position: fixed;
  inset: 0;
  display: none;
  align-items: center;
  justify-content: center;
  padding: 24px;
  background: rgba(8, 18, 26, 0.56);
  backdrop-filter: blur(8px);
  z-index: 1200;
}

.cert-modal.show {
  display: flex;
}

.cert-card {
  position: relative;
  width: min(92%, 560px);
  padding: 34px 30px 30px;
  border-radius: 30px;
  background:
    radial-gradient(circle at top, rgba(255,255,255,0.28), transparent 34%),
    linear-gradient(180deg, #fffdf8, #f4eddc);
  box-shadow: 0 28px 54px rgba(18, 36, 44, 0.22);
  text-align: center;
  overflow: hidden;
}

.cert-card::before {
  content: "";
  position: absolute;
  inset: 0 auto 0 0;
  width: 8px;
  background: linear-gradient(180deg, #7ac16d, #f0c36c);
}

.cert-close {
  position: absolute;
  top: 16px;
  right: 18px;
  width: 42px;
  height: 42px;
  border: none;
  border-radius: 50%;
  background: rgba(18, 54, 70, 0.06);
  color: #123646;
  font-size: 28px;
  line-height: 1;
  cursor: pointer;
}

.cert-card h3 {
  margin: 12px 0 10px;
  color: #123646;
  font-size: 34px;
}

.cert-score {
  margin-bottom: 12px;
  color: #2d6a28;
  font-size: 24px;
  font-weight: 800;
}

.cert-desc {
  max-width: 420px;
  margin: 0 auto;
  color: #5e7077;
  line-height: 1.8;
}

.cert-badges {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  margin: 22px 0 24px;
}

.cert-badges span {
  padding: 8px 14px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 13px;
  font-weight: 700;
}

/* 夜间模式 */
body.dark .game-head h3,
body.dark .trash-card h4,
body.dark .game-score-card strong,
body.dark .cert-card h3 {
  color: #f0c36c;
}

body.dark .game-head p,
body.dark .trash-card p,
body.dark .game-score-card span,
body.dark .cert-desc {
  color: #d3e0e2;
}

body.dark .green-game-shell,
body.dark .trash-card,
body.dark .game-score-card,
body.dark .cert-card {
  background: linear-gradient(180deg, rgba(255,255,255,0.08), rgba(255,255,255,0.05));
  border-color: rgba(255,255,255,0.08);
}

body.dark .green-tags span,
body.dark .cert-badges span {
  background: rgba(246, 198, 103, 0.14);
  color: #f3dfb1;
}

body.dark .game-feedback {
  background: rgba(240, 195, 108, 0.12);
  color: #f3dfb1;
  border-left-color: #f0c36c;
}

body.dark .game-feedback.success {
  background: rgba(122, 193, 109, 0.14);
  color: #cfecc8;
  border-left-color: #7ac16d;
}

body.dark .game-feedback.error {
  background: rgba(219, 107, 107, 0.14);
  color: #ffd3d3;
  border-left-color: #db6b6b;
}

body.dark .game-feedback.finish {
  background: rgba(106, 168, 232, 0.14);
  color: #d8ebff;
  border-left-color: #6aa8e8;
}

body.dark .cert-close {
  background: rgba(255,255,255,0.08);
  color: #f1f4f4;
}

body.dark .cert-score {
  color: #bfe7b8;
}

@media (max-width: 1100px) {
  .green-game-layout {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  .green-game-shell,
  .green-text {
    padding: 24px;
  }

  .game-status,
  .bins-grid {
    grid-template-columns: 1fr;
  }

  .trash-card h4 {
    font-size: 24px;
  }

  .bin-btn {
    min-height: 70px;
  }

  .trash-card-top {
    align-items: flex-start;
  }

  .trash-item-icon {
    width: 64px;
    height: 64px;
    font-size: 18px;
    border-radius: 18px;
  }

  .cert-card {
    padding: 28px 22px 24px;
    border-radius: 24px;
  }

  .cert-card h3 {
    font-size: 28px;
  }

  .cert-score {
    font-size: 21px;
  }
}

/* 玩法说明样式 */
.game-guide {
  margin-top: 18px;
  padding: 16px 18px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fffaf0, #f6efdf);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.game-guide strong {
  display: block;
  margin-bottom: 8px;
  color: #123646;
  font-size: 16px;
}

.game-guide p {
  color: #607279;
  line-height: 1.75;
}

body.dark .game-guide {
  background: rgba(255,255,255,0.06);
  border-color: rgba(255,255,255,0.08);
}

body.dark .game-guide strong {
  color: #f0c36c;
}

body.dark .game-guide p {
  color: #d3e0e2;
}

/* =========================
   封面标题大屏适配加强版
   ========================= */

/* 上方小字和主标题拉开 */
.hero-line {
  margin-bottom: 28px !important;
}

.hero-year {
  margin-bottom: 20px !important;
}

/* 主标题放大，并给副标题留更多距离 */
.hero h1 {
  font-size: clamp(78px, 9vw, 168px) !important;
  line-height: 0.96 !important;
  margin-bottom: 34px !important;
  letter-spacing: 2px !important;
  max-width: 900px !important;
}

.hero h1 span {
  display: inline-block !important;
  margin-top: 18px !important;
  font-size: 0.92em !important;
  letter-spacing: 3px !important;
}

/* 副标题和主标题拉开 */
.subtitle {
  max-width: 980px !important;
  margin-top: 18px !important;
  font-size: 18px !important;
  line-height: 1.78 !important;
}

/* 按钮也顺着往下走一点，别贴太近 */
.hero-buttons {
  margin-top: 34px !important;
}

/* 左侧内容区放宽，适合大标题 */
.hero-left {
  max-width: 980px !important;
}

/* 整个封面内容位置稍微下移一点，更适合大屏 */
.hero-content {
  margin-top: clamp(42px, 7vh, 90px) !important;
  align-items: center !important;
}

/* 超大屏加强 */
@media (min-width: 1400px) {
  .hero-content {
    width: min(92%, 1440px) !important;
    margin-top: 78px !important;
  }

  .hero-line {
    margin-bottom: 34px !important;
  }

  .hero-year {
    margin-bottom: 24px !important;
  }

  .hero h1 {
    font-size: clamp(96px, 9.2vw, 188px) !important;
    line-height: 0.94 !important;
    margin-bottom: 42px !important;
    max-width: 980px !important;
  }

  .hero h1 span {
    margin-top: 20px !important;
    letter-spacing: 4px !important;
  }

  .subtitle {
    max-width: 1080px !important;
    margin-top: 22px !important;
    font-size: 20px !important;
    line-height: 1.85 !important;
  }

  .hero-buttons {
    margin-top: 40px !important;
  }
}

/* 普通笔记本也保持协调 */
@media (max-width: 1280px) {
  .hero-line {
    margin-bottom: 20px !important;
  }

  .hero-year {
    margin-bottom: 14px !important;
  }

  .hero h1 {
    font-size: clamp(64px, 8vw, 132px) !important;
    margin-bottom: 26px !important;
  }

  .hero h1 span {
    margin-top: 12px !important;
  }

  .subtitle {
    margin-top: 12px !important;
    font-size: 17px !important;
  }
}

/* 平板 */
@media (max-width: 980px) {
  .hero-content {
    margin-top: 44px !important;
  }

  .hero-line {
    margin-bottom: 16px !important;
  }

  .hero-year {
    margin-bottom: 12px !important;
  }

  .hero h1 {
    font-size: clamp(56px, 10vw, 96px) !important;
    line-height: 1.02 !important;
    margin-bottom: 22px !important;
  }

  .hero h1 span {
    margin-top: 10px !important;
    letter-spacing: 2px !important;
  }

  .subtitle {
    margin-top: 10px !important;
    font-size: 16px !important;
  }

  .hero-buttons {
    margin-top: 26px !important;
  }
}

/* 手机 */
@media (max-width: 640px) {
  .hero-line {
    margin-bottom: 12px !important;
  }

  .hero-year {
    margin-bottom: 10px !important;
  }

  .hero h1 {
    font-size: clamp(42px, 13vw, 68px) !important;
    line-height: 1.05 !important;
    margin-bottom: 18px !important;
    letter-spacing: 1px !important;
  }

  .hero h1 span {
    margin-top: 6px !important;
    letter-spacing: 1px !important;
  }

  .subtitle {
    margin-top: 8px !important;
    font-size: 15px !important;
    line-height: 1.7 !important;
  }

  .hero-buttons {
    margin-top: 22px !important;
  }
}

/* =========================
   第一部分成品页精修
   ========================= */
.refined-intro-showcase {
  grid-template-columns: 1.22fr 0.78fr;
  gap: 28px;
}

.refined-intro-showcase .intro-main-column,
.refined-intro-showcase .refined-side-column {
  gap: 22px;
}

.intro-main-visual {
  min-height: 420px;
}

.intro-visual-overlay {
  padding: 34px 34px 30px;
}

.intro-visual-overlay h3 {
  margin-top: 8px;
  margin-bottom: 10px;
  font-size: 40px;
  line-height: 1.2;
  color: #fff;
}

.intro-visual-overlay p {
  max-width: 700px;
  color: rgba(255, 255, 255, 0.9);
  font-size: 16px;
  line-height: 1.8;
}

.intro-main-copy {
  padding: 30px 32px;
}

.intro-copy-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 24px;
}

.intro-copy-grid p {
  font-size: 17px;
  line-height: 1.9;
  color: #7a8c95;
}

.refined-info-card {
  padding: 28px 28px 24px;
}

.refined-info-list {
  gap: 0;
  margin-top: 8px;
}

.refined-info-item {
  padding: 20px 0;
  border-bottom: 1px solid rgba(18, 54, 70, 0.08);
}

.refined-info-item:first-child {
  padding-top: 8px;
}

.refined-info-item:last-child {
  border-bottom: none;
  padding-bottom: 0;
}

.intro-info-head {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  gap: 16px;
  margin-bottom: 8px;
}

.intro-info-head h4 {
  margin: 0;
  font-size: 26px;
  color: #123646;
}

.intro-info-head span {
  color: #b78035;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 2px;
}

.refined-info-item p {
  font-size: 16px;
  line-height: 1.85;
  color: #7a8c95;
}

.refined-sub-visuals {
  grid-template-columns: 1fr 1fr;
  gap: 18px;
}

.wide-sub-card {
  min-height: 220px;
}

.wide-sub-card .intro-sub-overlay {
  padding: 18px 18px;
}

.wide-sub-card .intro-sub-overlay span {
  font-size: 20px;
  font-weight: 800;
}

.refined-tags-row {
  margin-top: 26px;
  gap: 12px;
}

.refined-tags-row span {
  padding: 10px 16px;
  font-size: 13px;
  letter-spacing: 0.5px;
}

/* 让第一部分整体更像完整展示页 */
#intro .section-heading {
  margin-bottom: 26px;
}

#intro .section-heading h2 {
  font-size: 64px;
  line-height: 1.06;
}

#intro .section-kicker {
  font-size: 13px;
  letter-spacing: 3px;
}

body.dark .intro-copy-grid p,
body.dark .refined-info-item p {
  color: #d3e0e2;
}

body.dark .intro-info-head h4 {
  color: #f0c36c;
}

body.dark .intro-info-head span {
  color: #f6d486;
}

/* 响应式 */
@media (max-width: 1280px) {
  #intro .section-heading h2 {
    font-size: 54px;
  }

  .intro-main-visual {
    min-height: 380px;
  }

  .intro-visual-overlay h3 {
    font-size: 34px;
  }

  .intro-copy-grid {
    grid-template-columns: 1fr;
    gap: 16px;
  }
}

@media (max-width: 1100px) {
  .refined-intro-showcase {
    grid-template-columns: 1fr;
  }

  .refined-sub-visuals {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 640px) {
  #intro .section-heading h2 {
    font-size: 40px;
  }

  .intro-main-visual {
    min-height: 280px;
  }

  .intro-visual-overlay {
    padding: 22px 22px 20px;
  }

  .intro-visual-overlay h3 {
    font-size: 26px;
    margin-bottom: 8px;
  }

  .intro-visual-overlay p {
    font-size: 14px;
    line-height: 1.7;
  }

  .intro-main-copy {
    padding: 22px;
  }

  .intro-copy-grid p,
  .refined-info-item p {
    font-size: 15px;
    line-height: 1.8;
  }

  .intro-info-head h4 {
    font-size: 22px;
  }

  .refined-sub-visuals {
    grid-template-columns: 1fr;
  }

  .wide-sub-card {
    min-height: 180px;
  }
}

/* 第一部分左上主图：立方翻页自动轮播终版 */
.intro-main-visual {
  position: relative;
  min-height: 420px;
  padding: 0;
  overflow: hidden;
  border-radius: 28px;
  perspective: 1800px;
  background: #102028;
}

.intro-cube-slider {
  position: absolute;
  inset: 0;
  overflow: hidden;
  border-radius: 28px;
}

.cube-stage {
  position: absolute;
  inset: 0;
  transform-style: preserve-3d;
}

.cube-panel {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden;
  transform-origin: center center;
}

.cube-panel img {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}

.cube-current {
  z-index: 2;
  transform: rotateY(0deg);
}

.cube-next {
  z-index: 1;
  transform: rotateY(90deg);
}

/* 向前翻 */
.intro-cube-slider.is-animating.forward .cube-current {
  animation: cubeCurrentOutForward 1.05s ease-in-out forwards;
}

.intro-cube-slider.is-animating.forward .cube-next {
  animation: cubeNextInForward 1.05s ease-in-out forwards;
}

/* 向后翻 */
.intro-cube-slider.is-animating.backward .cube-current {
  animation: cubeCurrentOutBackward 1.05s ease-in-out forwards;
}

.intro-cube-slider.is-animating.backward .cube-next {
  animation: cubeNextInBackward 1.05s ease-in-out forwards;
}

@keyframes cubeCurrentOutForward {
  0% {
    transform: perspective(1800px) rotateY(0deg);
    opacity: 1;
  }
  100% {
    transform: perspective(1800px) rotateY(-90deg);
    opacity: 1;
  }
}

@keyframes cubeNextInForward {
  0% {
    transform: perspective(1800px) rotateY(90deg);
    opacity: 1;
  }
  100% {
    transform: perspective(1800px) rotateY(0deg);
    opacity: 1;
  }
}

@keyframes cubeCurrentOutBackward {
  0% {
    transform: perspective(1800px) rotateY(0deg);
    opacity: 1;
  }
  100% {
    transform: perspective(1800px) rotateY(90deg);
    opacity: 1;
  }
}

@keyframes cubeNextInBackward {
  0% {
    transform: perspective(1800px) rotateY(-90deg);
    opacity: 1;
  }
  100% {
    transform: perspective(1800px) rotateY(0deg);
    opacity: 1;
  }
}

/* 统一色调 */
.intro-main-visual::before {
  content: "";
  position: absolute;
  inset: 0;
  z-index: 2;
  pointer-events: none;
  background:
    linear-gradient(135deg, rgba(255, 220, 150, 0.08), transparent 38%),
    linear-gradient(to top, rgba(8, 18, 26, 0.22), rgba(8, 18, 26, 0.03));
}

.intro-visual-overlay {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 3;
  padding: 34px 34px 30px;
  background: linear-gradient(to top, rgba(8, 18, 26, 0.68), rgba(8, 18, 26, 0.06));
}

.intro-visual-overlay h3 {
  margin-top: 8px;
  margin-bottom: 10px;
  font-size: 40px;
  line-height: 1.2;
  color: #fff;
}

.intro-visual-overlay p {
  max-width: 700px;
  color: rgba(255, 255, 255, 0.9);
  font-size: 16px;
  line-height: 1.8;
}

@media (max-width: 1280px) {
  .intro-main-visual {
    min-height: 380px;
  }

  .intro-visual-overlay h3 {
    font-size: 34px;
  }
}

@media (max-width: 640px) {
  .intro-main-visual {
    min-height: 280px;
  }

  .intro-visual-overlay {
    padding: 22px 22px 20px;
  }

  .intro-visual-overlay h3 {
    font-size: 26px;
    margin-bottom: 8px;
  }

  .intro-visual-overlay p {
    font-size: 14px;
    line-height: 1.7;
  }
}

/* 路线预览卡片 */
.route-preview-card {
  position: relative;
  width: 100%;
  height: 240px;
  border-radius: 22px;
  overflow: hidden;
  margin-bottom: 20px;
}

.route-preview-card img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
  transition: opacity 0.18s ease;
}

.route-preview-card.is-changing img {
  opacity: 0;
}

.route-preview-overlay {
  position: absolute;
  inset: 0;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  padding: 20px 22px 18px;
  background: linear-gradient(to top, rgba(8, 18, 26, 0.78) 0%, rgba(8, 18, 26, 0.12) 60%, transparent 100%);
}

.route-preview-overlay span {
  color: #ffe3a2;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 2px;
  margin-bottom: 6px;
}

.route-preview-overlay strong {
  color: #fff;
  font-size: 32px;
  line-height: 1.15;
  margin-bottom: 8px;
}

.route-preview-overlay p {
  color: rgba(255, 255, 255, 0.88);
  font-size: 14px;
  line-height: 1.7;
  max-width: 320px;
}

.route-result .route-preview-active {
  background: rgba(240, 195, 108, 0.18);
  border-radius: 12px;
}

@media (max-width: 1100px) {
  .route-preview-card {
    height: 200px;
  }

  .route-preview-overlay strong {
    font-size: 26px;
  }
}

@media (max-width: 640px) {
  .route-preview-card {
    height: 180px;
    margin-bottom: 16px;
  }

  .route-preview-overlay {
    padding: 16px 18px 14px;
  }

  .route-preview-overlay strong {
    font-size: 22px;
  }

  .route-preview-overlay p {
    font-size: 13px;
  }
}

/* =========================
   修正：不要强制把内容裁进一屏
   ========================= */

.story-page {
  min-height: 100vh;
  padding: 72px 0;
  display: flex;
  align-items: flex-start;
  overflow: visible;
  position: relative;
}

.story-page-inner {
  width: min(92%, 1360px);
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}

.story-page .section-heading {
  flex: 0 0 auto;
  margin-bottom: 28px;
}

.story-page .section-heading h2 {
  font-size: clamp(42px, 4.6vw, 72px);
  line-height: 1.08;
}

.story-page .section-index {
  display: inline-block;
  margin-bottom: 10px;
}

.story-page-body {
  display: grid;
  gap: 28px;
}

.two-column-page {
  grid-template-columns: 1.08fr 0.92fr;
  align-items: start;
}

.equal-column-page {
  grid-template-columns: 1fr 1fr;
  align-items: start;
}

.three-column-page {
  grid-template-columns: 0.95fr 1fr 0.95fr;
  align-items: start;
}

.page-panel {
  border-radius: 28px;
}

.page-scroll {
  overflow: visible;
  padding-right: 0;
}

/* 不再默认限制所有卡片高度 */
.story-page .premium-panel,
.story-page .intro-info-card,
.story-page .route-main-panel,
.story-page .green-text,
.story-page .green-game-shell,
.story-page .ai-box-upgraded,
.story-page .ai-credit {
  max-height: none;
}

@media (max-width: 980px) {
  .story-page {
    padding: 64px 0;
  }

  .story-page-body,
  .two-column-page,
  .equal-column-page,
  .three-column-page {
    grid-template-columns: 1fr;
  }
}

.page-scroll::-webkit-scrollbar {
  width: 6px;
}

.page-scroll::-webkit-scrollbar-thumb {
  background: rgba(18, 54, 70, 0.22);
  border-radius: 999px;
}

.page-scroll::-webkit-scrollbar-track {
  background: transparent;
}

/* 卡片内部如果内容多，只让内部滚动，不把整页撑高 */
.story-page .premium-panel,
.story-page .intro-info-card,
.story-page .route-main-panel,
.story-page .green-text,
.story-page .green-game-shell,
.story-page .ai-box-upgraded,
.story-page .ai-credit {
  max-height: 100%;
}

/* 统一图片填充 */
.full-image-card {
  position: relative;
  overflow: hidden;
  border-radius: 28px;
}

.full-image-card img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}

.full-image-card::after {
  content: "";
  position: absolute;
  inset: 0;
  pointer-events: none;
  background: linear-gradient(to top, rgba(8, 18, 26, 0.58), rgba(8, 18, 26, 0.08));
}

/* 页面底部标签统一控制高度 */
.page-tags {
  flex: 0 0 auto;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 20px;
}

.page-tags span {
  padding: 8px 14px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 13px;
  font-weight: 700;
}

/* 防止正文页上下间距过大 */
.section.story-page {
  margin: 0 !important;
}

/* 平板和手机：正文页允许自然高度，避免内容被裁掉 */
@media (max-width: 980px) {
  .story-page {
    height: auto;
    min-height: 100vh;
    padding: 64px 0;
    overflow: visible;
  }

  .story-page-inner {
    height: auto;
  }

  .story-page-body,
  .two-column-page,
  .equal-column-page,
  .three-column-page {
    grid-template-columns: 1fr;
  }

  .page-scroll {
    overflow: visible;
    padding-right: 0;
  }
}

@media (max-width: 640px) {
  .story-page {
    padding: 52px 0;
  }

  .story-page .section-heading {
    margin-bottom: 22px;
  }

  .story-page .section-heading h2 {
    font-size: 38px;
  }
}

/* =========================
   第一步正文页：01 城市引入
   ========================= */

.intro-page .story-page-inner {
  gap: 0;
}

.intro-page-body {
  min-height: 0;
}

.intro-main-stack,
.intro-side-stack {
  min-height: 0;
  display: grid;
  gap: 22px;
}

.intro-main-stack {
  grid-template-rows: 1.18fr 0.82fr;
}

.intro-side-stack {
  grid-template-rows: 1fr 0.46fr;
}

.intro-hero-card,
.intro-side-image-card {
  position: relative;
  overflow: hidden;
  border-radius: 30px;
}

.intro-hero-card img,
.intro-side-image-card img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}

.intro-hero-card::after,
.intro-side-image-card::after {
  content: "";
  position: absolute;
  inset: 0;
  pointer-events: none;
}

.intro-hero-card::after {
  background:
    linear-gradient(to top, rgba(8, 18, 26, 0.72), rgba(8, 18, 26, 0.08)),
    linear-gradient(135deg, rgba(255, 220, 150, 0.08), transparent 42%);
}

.intro-side-image-card::after {
  background: linear-gradient(to top, rgba(8, 18, 26, 0.58), rgba(8, 18, 26, 0.05));
}

.intro-hero-overlay {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 2;
  padding: 30px 30px 26px;
}

.intro-hero-overlay h3 {
  margin: 8px 0 10px;
  color: #ffffff !important;
  text-shadow: 0 3px 12px rgba(0, 0, 0, 0.6) !important;
  font-size: clamp(28px, 2.8vw, 42px);
  line-height: 1.18;
}

.intro-hero-overlay p {
  max-width: 700px;
  color: rgba(255, 255, 255, 0.9) !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.55) !important;
  font-size: 15px;
  line-height: 1.8;
}

.intro-copy-card {
  padding: 26px 28px;
  display: flex;
  align-items: center;
}

.intro-copy-columns {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 22px;
  width: 100%;
}

.intro-copy-columns p {
  color: #7a8c95;
  font-size: 16px;
  line-height: 1.9;
}

.intro-profile-card {
  padding: 26px 28px 24px;
  display: flex;
  flex-direction: column;
  min-height: 0;
}

.intro-profile-list {
  display: grid;
  gap: 0;
  margin-top: 6px;
  min-height: 0;
}

.intro-profile-item {
  padding: 18px 0;
  border-bottom: 1px solid rgba(18, 54, 70, 0.08);
}

.intro-profile-item:first-child {
  padding-top: 10px;
}

.intro-profile-item:last-child {
  padding-bottom: 0;
  border-bottom: none;
}

.intro-profile-head {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  gap: 12px;
  margin-bottom: 8px;
}

.intro-profile-head h4 {
  margin: 0;
  color: #123646;
  font-size: 24px;
}

.intro-profile-head span {
  color: #b78035;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 2px;
}

.intro-profile-item p {
  color: #7a8c95;
  font-size: 15px;
  line-height: 1.8;
}

.intro-side-image-overlay {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 2;
  padding: 18px 20px;
}

.intro-side-image-overlay span {
  color: #fff;
  font-size: 22px;
  font-weight: 800;
  letter-spacing: 1px;
}

.intro-page-tags {
  margin-top: 18px;
}

body.dark .intro-copy-columns p,
body.dark .intro-profile-item p {
  color: #d3e0e2;
}

body.dark .intro-profile-head h4 {
  color: #f0c36c;
}

body.dark .intro-profile-head span {
  color: #f6d486;
}

@media (max-width: 1280px) {
  .intro-main-stack {
    grid-template-rows: 1.08fr 0.92fr;
  }

  .intro-side-stack {
    grid-template-rows: 1fr 0.42fr;
  }

  .intro-copy-columns {
    grid-template-columns: 1fr;
    gap: 14px;
  }

  .intro-copy-columns p {
    font-size: 15px;
    line-height: 1.82;
  }

  .intro-profile-head h4 {
    font-size: 22px;
  }
}

@media (max-width: 980px) {
  .intro-main-stack,
  .intro-side-stack {
    grid-template-rows: auto;
  }

  .intro-side-image-card {
    min-height: 220px;
  }

  .intro-copy-columns {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  .intro-hero-overlay {
    padding: 22px 22px 20px;
  }

  .intro-hero-overlay p {
    font-size: 14px;
    line-height: 1.7;
  }

  .intro-copy-card,
  .intro-profile-card {
    padding: 22px;
  }

  .intro-profile-head h4 {
    font-size: 20px;
  }

  .intro-profile-item p,
  .intro-copy-columns p {
    font-size: 14px;
    line-height: 1.75;
  }

  .intro-side-image-overlay span {
    font-size: 18px;
  }
}

/* =========================
   第二步正文页：02 山水地标
   ========================= */

.landmarks-page-body {
  min-height: 0;
}

.landmark-card {
  position: relative;
  overflow: hidden;
  border-radius: 32px;
  cursor: pointer;
  background: #102028;
  min-height: 0;
}

.landmark-card img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
  transition: transform 0.8s ease;
}

.landmark-card::after {
  content: "";
  position: absolute;
  inset: 0;
  pointer-events: none;
  background:
    linear-gradient(to top, rgba(8, 18, 26, 0.86), rgba(8, 18, 26, 0.18)),
    linear-gradient(135deg, rgba(255, 222, 162, 0.08), transparent 42%);
}

.landmark-card:hover img {
  transform: scale(1.05);
}

.landmark-card-overlay {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 2;
  padding: 34px 32px 30px;
}

.landmark-card-overlay .card-label {
  display: inline-block;
  margin-bottom: 14px;
  color: #ffe1a0 !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.5) !important;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 2px;
}

.landmark-card-overlay h3 {
  margin: 0 0 12px;
  color: #ffffff !important;
  text-shadow: 0 3px 12px rgba(0, 0, 0, 0.6) !important;
  font-size: clamp(34px, 3vw, 52px);
  line-height: 1.08;
}

.landmark-card-overlay p {
  max-width: 620px;
  color: rgba(255, 255, 255, 0.9) !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.55) !important;
  font-size: 16px;
  line-height: 1.78;
}

.landmark-card-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 18px;
}

.landmark-card-meta span {
  padding: 8px 14px;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.14);
  color: #fff;
  font-size: 13px;
  font-weight: 700;
  backdrop-filter: blur(10px);
}

@media (max-width: 980px) {
  .landmark-card {
    min-height: 420px;
  }
}

@media (max-width: 640px) {
  .landmark-card {
    min-height: 320px;
    border-radius: 24px;
  }

  .landmark-card-overlay {
    padding: 24px 22px 22px;
  }

  .landmark-card-overlay h3 {
    font-size: 30px;
  }

  .landmark-card-overlay p {
    font-size: 14px;
    line-height: 1.7;
  }
}

/* =========================
   第四步正文页：04 智慧路线生成
   ========================= */

.route-page-body {
  min-height: 0;
}

.route-left-stack,
.route-right-stack {
  min-height: 0;
  display: grid;
  gap: 22px;
}

.route-left-stack {
  grid-template-rows: 0.88fr 1.12fr;
}

.route-right-stack {
  grid-template-rows: auto 1fr;
}

.route-intro-card,
.route-control-card,
.route-timeline-card {
  padding: 26px 28px;
}

.route-intro-card h3,
.route-control-card h3 {
  margin: 10px 0 12px;
  color: #123646;
  font-size: 30px;
  line-height: 1.22;
}

.route-intro-card p,
.route-summary-text {
  color: #7a8c95;
  font-size: 15px;
  line-height: 1.82;
}

.route-capability-list {
  display: grid;
  gap: 12px;
  margin-top: 18px;
}

.route-capability-item {
  padding: 14px 16px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fffdf8, #f4eddc);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.route-capability-item strong {
  display: block;
  margin-bottom: 6px;
  color: #123646;
  font-size: 16px;
}

.route-capability-item span {
  color: #7a8c95;
  font-size: 14px;
  line-height: 1.7;
}

.route-preview-card {
  position: relative;
  overflow: hidden;
  border-radius: 28px;
  background: #102028;
  min-height: 0;
}

.route-preview-card img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
  transition: opacity 0.35s ease, transform 0.55s ease;
}

.route-preview-card.is-changing img {
  opacity: 0.24;
  transform: scale(1.04);
}

.route-preview-card::after {
  content: "";
  position: absolute;
  inset: 0;
  background:
    linear-gradient(to top, rgba(8, 18, 26, 0.82), rgba(8, 18, 26, 0.08)),
    linear-gradient(135deg, rgba(255, 220, 150, 0.08), transparent 40%);
  pointer-events: none;
}

.route-preview-info {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 2;
  padding: 22px 22px 24px;
}

.route-preview-info span {
  display: block;
  margin-bottom: 8px;
  color: #ffe1a0;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 2px;
}

.route-preview-info strong {
  display: block;
  margin-bottom: 8px;
  color: #fff;
  font-size: 28px;
  line-height: 1.2;
}

.route-preview-info p {
  color: rgba(255, 255, 255, 0.88);
  font-size: 14px;
  line-height: 1.72;
}

.route-day-switch {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 16px 0 14px;
}

.route-day-chip {
  padding: 9px 14px;
  border: none;
  border-radius: 999px;
  background: #f6edd8;
  color: #123646;
  font-size: 13px;
  font-weight: 700;
}

.route-day-chip.active {
  background: #123646;
  color: #fff;
}

.route-timeline-card {
  min-height: 0;
}

.route-timeline-scroll,
.route-detail-scroll {
  height: auto;
}

.route-day-title {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 18px;
}

.route-day-dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: #f0c36c;
  box-shadow: 0 0 0 6px rgba(240, 195, 108, 0.18);
}

.route-day-title h4 {
  color: #123646;
  font-size: 28px;
}

.route-step-card {
  padding: 22px 22px 20px;
  border-radius: 24px;
  background: linear-gradient(180deg, #fffefb, #f8efd9);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.route-step-card + .route-step-card {
  margin-top: 16px;
}

.route-step-time {
  display: inline-block;
  margin-bottom: 12px;
  padding: 8px 14px;
  border-radius: 999px;
  background: #ffefc6;
  color: #123646;
  font-size: 14px;
  font-weight: 800;
}

.route-step-card h5 {
  margin-bottom: 10px;
  color: #123646;
  font-size: 26px;
  line-height: 1.2;
}

.route-step-card p {
  color: #7a8c95;
  font-size: 15px;
  line-height: 1.8;
}

.route-clickable-card {
  cursor: pointer;
  transition: transform 0.22s ease, box-shadow 0.22s ease, outline 0.22s ease;
}

.route-clickable-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 16px 30px rgba(18, 54, 70, 0.12);
}

.route-clickable-card.route-preview-active {
  outline: 3px solid rgba(240, 195, 108, 0.42);
  box-shadow: 0 16px 34px rgba(18, 54, 70, 0.14);
}

body.dark .route-intro-card h3,
body.dark .route-control-card h3,
body.dark .route-day-title h4,
body.dark .route-step-card h5,
body.dark .route-capability-item strong {
  color: #f0c36c;
}

body.dark .route-intro-card p,
body.dark .route-summary-text,
body.dark .route-step-card p,
body.dark .route-capability-item span {
  color: #d3e0e2;
}

body.dark .route-capability-item,
body.dark .route-step-card {
  background: rgba(255, 255, 255, 0.06);
  border-color: rgba(255, 255, 255, 0.08);
}

body.dark .route-day-chip {
  background: rgba(255, 255, 255, 0.08);
  color: #f3dfb1;
}

body.dark .route-day-chip.active {
  background: #f0c36c;
  color: #123646;
}

body.dark .route-step-time {
  background: rgba(240, 195, 108, 0.16);
  color: #f3dfb1;
}


@media (max-width: 1280px) {
  .route-left-stack {
    grid-template-rows: auto 1fr;
  }

  .route-right-stack {
    grid-template-rows: auto 1fr;
  }

  .route-step-card h5 {
    font-size: 22px;
  }
}

@media (max-width: 980px) {
  .route-preview-card {
    min-height: 280px;
  }

  .route-day-title h4 {
    font-size: 24px;
  }
}

@media (max-width: 640px) {
  .route-intro-card,
  .route-control-card,
  .route-timeline-card {
    padding: 22px;
  }

  .route-intro-card h3,
  .route-control-card h3 {
    font-size: 24px;
  }

  .route-day-title h4 {
    font-size: 22px;
  }

  .route-step-card {
    padding: 18px 18px 16px;
  }

  .route-step-card h5 {
    font-size: 20px;
  }

  .route-step-card p,
  .route-intro-card p,
  .route-summary-text {
    font-size: 14px;
    line-height: 1.72;
  }
}

.heritage-page-body {
  min-height: 0;
}

.heritage-card {
  position: relative;
  overflow: hidden;
  border-radius: 32px;
  cursor: pointer;
  background: #1b1a18;
  min-height: 0;
}

.heritage-card img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
  transition: transform 0.8s ease;
}

.heritage-card::after {
  content: "";
  position: absolute;
  inset: 0;
  pointer-events: none;
  background:
    linear-gradient(to top, rgba(20, 14, 10, 0.84), rgba(20, 14, 10, 0.18)),
    linear-gradient(135deg, rgba(255, 201, 120, 0.08), transparent 44%);
}

.heritage-card:hover img {
  transform: scale(1.05);
}

.heritage-card-overlay {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 2;
  padding: 34px 32px 30px;
}

.heritage-card-overlay .card-label {
  display: inline-block;
  margin-bottom: 14px;
  color: #ffe1a0 !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.5) !important;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 2px;
}

.heritage-card-overlay h3 {
  margin: 0 0 12px;
  color: #ffffff !important;
  text-shadow: 0 3px 12px rgba(0, 0, 0, 0.6) !important;
  font-size: clamp(34px, 3vw, 52px);
  line-height: 1.08;
}

.heritage-card-overlay p {
  max-width: 620px;
  color: rgba(255, 255, 255, 0.9) !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.55) !important;
  font-size: 16px;
  line-height: 1.78;
}

.heritage-card-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 18px;
}

.heritage-card-meta span {
  padding: 8px 14px;
  border-radius: 999px;
  background: rgba(255, 241, 207, 0.18);
  color: #fff4d7;
  font-size: 13px;
  font-weight: 700;
  backdrop-filter: blur(10px);
}

@media (max-width: 980px) {
  .heritage-card {
    min-height: 420px;
  }
}

@media (max-width: 640px) {
  .heritage-card {
    min-height: 320px;
    border-radius: 24px;
  }

  .heritage-card-overlay {
    padding: 24px 22px 22px;
  }

  .heritage-card-overlay h3 {
    font-size: 30px;
  }

  .heritage-card-overlay p {
    font-size: 14px;
    line-height: 1.7;
  }
}

/* =========================
   第五步正文页：05 深度行程展开
   ========================= */

.route-detail-body {
  min-height: 0;
}

.route-detail-left,
.route-detail-right {
  min-height: 0;
  display: grid;
  gap: 22px;
}

.route-detail-left {
  grid-template-rows: auto 1fr;
}

.route-detail-right {
  grid-template-rows: 1fr;
}

.route-detail-intro,
.route-detail-timeline-card {
  padding: 26px 28px;
}

.route-detail-intro h3 {
  margin: 10px 0 12px;
  color: #123646;
  font-size: 30px;
  line-height: 1.22;
}

.route-detail-intro p {
  color: #7a8c95;
  font-size: 15px;
  line-height: 1.82;
}

.route-detail-note {
  margin-top: 18px;
  padding: 16px 18px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fffaf0, #f6efdf);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.route-detail-note strong {
  display: block;
  margin-bottom: 8px;
  color: #123646;
  font-size: 16px;
}

.route-detail-note span {
  color: #7a8c95;
  font-size: 14px;
  line-height: 1.72;
}

.route-detail-preview-card {
  min-height: 0;
}

.route-detail-scroll {
  height: auto;
}

.route-day-title-detail h4 {
  font-size: 28px;
}

.route-day-gap {
  margin-top: 28px;
}

.pink-dot {
  background: #ff2f92;
  box-shadow: 0 0 0 6px rgba(255, 47, 146, 0.16);
}

.route-detail-clickable {
  cursor: pointer;
  transition: transform 0.22s ease, box-shadow 0.22s ease, outline 0.22s ease;
}

.route-detail-clickable:hover {
  transform: translateY(-2px);
  box-shadow: 0 16px 30px rgba(18, 54, 70, 0.12);
}

.route-detail-clickable.route-preview-active {
  outline: 3px solid rgba(240, 195, 108, 0.42);
  box-shadow: 0 16px 34px rgba(18, 54, 70, 0.14);
}

.route-advice-box {
  margin-top: 22px;
  padding: 18px 18px 16px;
  border-radius: 22px;
  background: linear-gradient(180deg, #fff9ec, #f7efd9);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.route-advice-box .mini-label {
  display: inline-block;
  margin-bottom: 10px;
}

.route-advice-box p {
  color: #7a8c95;
  font-size: 15px;
  line-height: 1.8;
}

body.dark .route-detail-intro h3,
body.dark .route-detail-note strong {
  color: #f0c36c;
}

body.dark .route-detail-intro p,
body.dark .route-detail-note span,
body.dark .route-advice-box p {
  color: #d3e0e2;
}

body.dark .route-detail-note,
body.dark .route-advice-box {
  background: rgba(255, 255, 255, 0.06);
  border-color: rgba(255, 255, 255, 0.08);
}

@media (max-width: 1280px) {
  .route-day-title-detail h4 {
    font-size: 24px;
  }
}

@media (max-width: 980px) {
  .route-detail-preview-card {
    min-height: 280px;
  }
}

@media (max-width: 640px) {
  .route-detail-intro,
  .route-detail-timeline-card {
    padding: 22px;
  }

  .route-detail-intro h3 {
    font-size: 24px;
  }

  .route-day-title-detail h4 {
    font-size: 22px;
  }

  .route-advice-box p,
  .route-detail-intro p,
  .route-detail-note span {
    font-size: 14px;
    line-height: 1.72;
  }
}

/* =========================
   第六步正文页：06 绿色低碳互动
   ========================= */

.green-page-body {
  min-height: 0;
}

.green-text,
.green-game-shell {
  padding: 28px 30px;
  min-height: 0;
}

.green-text {
  display: flex;
  flex-direction: column;
}

.green-text h3,
.game-head h3 {
  margin: 10px 0 12px;
  color: #123646;
  font-size: 32px;
  line-height: 1.2;
}

.green-text p,
.game-head p {
  color: #7a8c95;
  font-size: 15px;
  line-height: 1.82;
}

.green-actions {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
  margin-top: 22px;
}

.green-action {
  padding: 18px 18px 16px;
  border-radius: 20px;
  background: linear-gradient(180deg, #fffdf8, #f4eddc);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.green-action strong {
  display: block;
  margin-bottom: 8px;
  color: #123646;
  font-size: 18px;
}

.green-action span {
  color: #7a8c95;
  font-size: 14px;
  line-height: 1.72;
}

.green-visual-note {
  margin-top: auto;
  padding: 24px;
  border-radius: 26px;
  background:
    radial-gradient(circle at top, rgba(255, 255, 255, 0.24), transparent 36%),
    linear-gradient(145deg, #1f5b62, #d5ba63);
  color: #fff;
}

.green-visual-note span {
  display: block;
  margin-bottom: 12px;
  color: rgba(255, 255, 255, 0.72);
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 3px;
}

.green-visual-note strong {
  display: block;
  max-width: 520px;
  font-size: 26px;
  line-height: 1.35;
}

.green-game-shell {
  display: flex;
  flex-direction: column;
}

.game-guide {
  margin-top: 14px;
  padding: 14px 16px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fffaf0, #f6efdf);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.game-guide strong {
  display: block;
  margin-bottom: 6px;
  color: #123646;
  font-size: 15px;
}

.game-guide p {
  color: #7a8c95;
  font-size: 14px;
  line-height: 1.65;
}

.game-status {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
  margin-top: 16px;
}

.game-score-card {
  padding: 14px 16px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fffdf8, #f4eddc);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.game-score-card span {
  display: block;
  margin-bottom: 5px;
  color: #6c7d82;
  font-size: 13px;
}

.game-score-card strong {
  color: #123646;
  font-size: 24px;
}

.trash-card {
  margin-top: 16px;
  padding: 18px 18px 16px;
  border-radius: 22px;
  background:
    radial-gradient(circle at top right, rgba(240, 195, 108, 0.14), transparent 26%),
    linear-gradient(180deg, #ffffff, #f6f1e8);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.trash-card-top {
  display: flex;
  align-items: center;
  gap: 14px;
  margin-bottom: 8px;
}

.trash-item-icon {
  width: 64px;
  height: 64px;
  border-radius: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  background:
    radial-gradient(circle at top, rgba(255,255,255,0.35), transparent 34%),
    linear-gradient(160deg, #1f5b62, #5fa078);
  color: #fff;
  font-size: 18px;
  font-weight: 800;
  letter-spacing: 1px;
  box-shadow: 0 14px 28px rgba(18, 54, 70, 0.16);
  flex-shrink: 0;
}

.trash-card-label {
  display: inline-block;
  margin-bottom: 6px;
  color: #b78035;
  font-size: 12px;
  letter-spacing: 2px;
  font-weight: 700;
}

.trash-card h4 {
  color: #123646;
  font-size: 26px;
}

.trash-card p {
  color: #5d7077;
  font-size: 14px;
  line-height: 1.7;
}

.bins-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
  margin-top: 16px;
}

.bin-btn {
  min-height: 74px;
  padding: 14px 16px;
  border: none;
  border-radius: 20px;
  cursor: pointer;
  text-align: left;
  transition: transform 0.22s, box-shadow 0.22s;
  box-shadow: 0 12px 24px rgba(18, 36, 44, 0.08);
}

.bin-btn span {
  display: block;
  margin-bottom: 4px;
  font-size: 17px;
  font-weight: 800;
}

.bin-btn small {
  font-size: 12px;
  opacity: 0.82;
}

.bin-btn:hover {
  transform: translateY(-3px);
}

.bin-btn.recyclable {
  background: linear-gradient(135deg, #d9efff, #a9d4ff);
  color: #184b76;
}

.bin-btn.kitchen {
  background: linear-gradient(135deg, #e0f6d5, #b9e28c);
  color: #2d6a28;
}

.bin-btn.harmful {
  background: linear-gradient(135deg, #ffd8d8, #ffaaaa);
  color: #842d2d;
}

.bin-btn.other {
  background: linear-gradient(135deg, #ececec, #cfcfcf);
  color: #4f575d;
}

.bin-btn.correct {
  box-shadow: 0 0 0 4px rgba(108, 190, 111, 0.22), 0 16px 28px rgba(34, 100, 40, 0.12);
  transform: translateY(-2px);
}

.bin-btn.wrong {
  box-shadow: 0 0 0 4px rgba(217, 86, 86, 0.18), 0 16px 28px rgba(120, 40, 40, 0.08);
}

.bin-btn:disabled {
  cursor: not-allowed;
}

.game-feedback {
  min-height: 52px;
  margin-top: 14px;
  padding: 14px 16px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fff9eb, #f7efdc);
  color: #6d5827;
  line-height: 1.7;
  border-left: 4px solid #f0c36c;
}

.game-feedback.success {
  background: linear-gradient(180deg, #eef9ea, #e0f3d7);
  color: #2f6a2a;
  border-left-color: #7ac16d;
}

.game-feedback.error {
  background: linear-gradient(180deg, #fff1f1, #fde1e1);
  color: #8c3333;
  border-left-color: #db6b6b;
}

.game-feedback.finish {
  background: linear-gradient(180deg, #eef7ff, #dfeeff);
  color: #26577e;
  border-left-color: #6aa8e8;
}

.game-footer {
  margin-top: 14px;
}

.game-restart-btn {
  padding: 10px 22px;
}

/* 认证卡 */
.cert-modal {
  position: fixed;
  inset: 0;
  display: none;
  align-items: center;
  justify-content: center;
  padding: 24px;
  background: rgba(8, 18, 26, 0.56);
  backdrop-filter: blur(8px);
  z-index: 1200;
}

.cert-modal.show {
  display: flex;
}

.cert-card {
  position: relative;
  width: min(92%, 560px);
  padding: 34px 30px 30px;
  border-radius: 30px;
  background:
    radial-gradient(circle at top, rgba(255,255,255,0.28), transparent 34%),
    linear-gradient(180deg, #fffdf8, #f4eddc);
  box-shadow: 0 28px 54px rgba(18, 36, 44, 0.22);
  text-align: center;
  overflow: hidden;
}

.cert-card::before {
  content: "";
  position: absolute;
  inset: 0 auto 0 0;
  width: 8px;
  background: linear-gradient(180deg, #7ac16d, #f0c36c);
}

.cert-close {
  position: absolute;
  top: 16px;
  right: 18px;
  width: 42px;
  height: 42px;
  border: none;
  border-radius: 50%;
  background: rgba(18, 54, 70, 0.06);
  color: #123646;
  font-size: 28px;
  line-height: 1;
  cursor: pointer;
}

.cert-card h3 {
  margin: 12px 0 10px;
  color: #123646;
  font-size: 34px;
}

.cert-score {
  margin-bottom: 12px;
  color: #2d6a28;
  font-size: 24px;
  font-weight: 800;
}

.cert-desc {
  max-width: 420px;
  margin: 0 auto;
  color: #5e7077;
  line-height: 1.8;
}

.cert-badges {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  margin: 22px 0 24px;
}

.cert-badges span {
  padding: 8px 14px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 13px;
  font-weight: 700;
}

/* 夜间模式 */
body.dark .green-text h3,
body.dark .game-head h3,
body.dark .game-score-card strong,
body.dark .trash-card h4,
body.dark .cert-card h3 {
  color: #f0c36c;
}

body.dark .green-text p,
body.dark .game-head p,
body.dark .trash-card p,
body.dark .game-score-card span,
body.dark .cert-desc,
body.dark .game-guide p {
  color: #d3e0e2;
}

body.dark .green-action,
body.dark .game-score-card,
body.dark .trash-card,
body.dark .game-guide,
body.dark .cert-card {
  background: rgba(255, 255, 255, 0.06);
  border-color: rgba(255, 255, 255, 0.08);
}

body.dark .green-action strong,
body.dark .game-guide strong {
  color: #f0c36c;
}

body.dark .green-visual-note {
  background:
    radial-gradient(circle at top, rgba(255, 255, 255, 0.08), transparent 36%),
    linear-gradient(145deg, #1a4a50, #9a7a30);
}

body.dark .game-feedback {
  background: rgba(240, 195, 108, 0.12);
  color: #f3dfb1;
  border-left-color: #f0c36c;
}

body.dark .game-feedback.success {
  background: rgba(122, 193, 109, 0.14);
  color: #cfecc8;
  border-left-color: #7ac16d;
}

body.dark .game-feedback.error {
  background: rgba(219, 107, 107, 0.14);
  color: #ffd3d3;
  border-left-color: #db6b6b;
}

body.dark .game-feedback.finish {
  background: rgba(106, 168, 232, 0.14);
  color: #d8ebff;
  border-left-color: #6aa8e8;
}

body.dark .cert-close {
  background: rgba(255, 255, 255, 0.08);
  color: #f1f4f4;
}

body.dark .cert-score {
  color: #bfe7b8;
}

body.dark .cert-badges span {
  background: rgba(246, 198, 103, 0.14);
  color: #f3dfb1;
}

@media (max-width: 980px) {
  .green-actions {
    grid-template-columns: 1fr;
  }

  .green-visual-note {
    margin-top: 22px;
  }
}

@media (max-width: 640px) {
  .green-text,
  .green-game-shell {
    padding: 22px;
  }

  .green-text h3,
  .game-head h3 {
    font-size: 26px;
  }

  .game-status,
  .bins-grid {
    grid-template-columns: 1fr;
  }

  .trash-card h4 {
    font-size: 22px;
  }

  .bin-btn {
    min-height: 66px;
  }

  .cert-card {
    padding: 28px 22px 24px;
  }

  .cert-card h3 {
    font-size: 28px;
  }

  .cert-score {
    font-size: 21px;
  }
}

/* =========================
   01 城市引入：左上主图立方翻页轮播
   ========================= */

.intro-hero-card {
  position: relative;
  overflow: hidden;
  perspective: 1800px;
  background: #102028;
}

.intro-cube-slider {
  position: absolute;
  inset: 0;
  overflow: hidden;
  border-radius: inherit;
}

.cube-stage {
  position: absolute;
  inset: 0;
  transform-style: preserve-3d;
}

.cube-panel {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden;
  transform-origin: center center;
}

.cube-panel img {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}

.cube-current {
  z-index: 2;
  transform: rotateY(0deg);
}

.cube-next {
  z-index: 1;
  transform: rotateY(90deg);
}

.intro-cube-slider.is-animating.forward .cube-current {
  animation: introCubeCurrentOutForward 1.05s ease-in-out forwards;
}

.intro-cube-slider.is-animating.forward .cube-next {
  animation: introCubeNextInForward 1.05s ease-in-out forwards;
}

.intro-cube-slider.is-animating.backward .cube-current {
  animation: introCubeCurrentOutBackward 1.05s ease-in-out forwards;
}

.intro-cube-slider.is-animating.backward .cube-next {
  animation: introCubeNextInBackward 1.05s ease-in-out forwards;
}

@keyframes introCubeCurrentOutForward {
  0% {
    transform: perspective(1800px) rotateY(0deg);
    opacity: 1;
  }
  100% {
    transform: perspective(1800px) rotateY(-90deg);
    opacity: 1;
  }
}

@keyframes introCubeNextInForward {
  0% {
    transform: perspective(1800px) rotateY(90deg);
    opacity: 1;
  }
  100% {
    transform: perspective(1800px) rotateY(0deg);
    opacity: 1;
  }
}

@keyframes introCubeCurrentOutBackward {
  0% {
    transform: perspective(1800px) rotateY(0deg);
    opacity: 1;
  }
  100% {
    transform: perspective(1800px) rotateY(90deg);
    opacity: 1;
  }
}

@keyframes introCubeNextInBackward {
  0% {
    transform: perspective(1800px) rotateY(-90deg);
    opacity: 1;
  }
  100% {
    transform: perspective(1800px) rotateY(0deg);
    opacity: 1;
  }
}

/* 让轮播图仍然保持统一暗部和文字可读性 */
.intro-hero-card::after {
  z-index: 2;
}

.intro-hero-overlay {
  z-index: 3;
}

/* =========================
   智慧路线：下拉选择 + 点击配图
   ========================= */

.route-section {
  min-height: 100vh;
  padding: 72px 0;
}

.route-section .section-heading,
.route-generator-layout {
  width: min(92%, 1360px);
  margin-left: auto;
  margin-right: auto;
}

.route-section .section-heading {
  margin-bottom: 30px;
}

.route-generator-layout {
  display: grid;
  grid-template-columns: 0.86fr 1.14fr;
  gap: 28px;
  align-items: start;
}

.route-left-panel,
.route-result-panel {
  padding: 30px;
  border-radius: 30px;
}

.route-left-panel {
  position: sticky;
  top: 86px;
}

.route-left-panel h3,
.route-result-head h3 {
  margin: 12px 0 12px;
  color: #123646;
  font-size: 34px;
  line-height: 1.2;
}

.route-left-panel p,
.route-result-head p {
  color: #7a8c95;
  font-size: 16px;
  line-height: 1.85;
}

.route-form {
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 12px;
  margin-top: 22px;
  align-items: end;
}

.route-form label {
  grid-column: 1 / -1;
  color: #123646;
  font-weight: 800;
}

.route-form select {
  width: 100%;
  height: 50px;
  padding: 0 16px;
  border: 1px solid rgba(18, 54, 70, 0.12);
  border-radius: 16px;
  background: #fffdf8;
  color: #123646;
  font-size: 16px;
  font-weight: 700;
}

.route-form .btn {
  height: 50px;
  padding: 0 22px;
}

.route-preview-card {
  position: relative;
  min-height: 340px;
  margin-top: 24px;
  overflow: hidden;
  border-radius: 26px;
  background: #102028;
}

.route-preview-card img {
  width: 100%;
  height: 100%;
  min-height: 340px;
  display: block;
  object-fit: cover;
  transition: opacity 0.35s ease, transform 0.55s ease;
}

.route-preview-card.is-changing img {
  opacity: 0.25;
  transform: scale(1.04);
}

.route-preview-card::after {
  content: "";
  position: absolute;
  inset: 0;
  background:
    linear-gradient(to top, rgba(8, 18, 26, 0.84), rgba(8, 18, 26, 0.12)),
    linear-gradient(135deg, rgba(255, 220, 150, 0.08), transparent 40%);
  pointer-events: none;
}

.route-preview-info {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 2;
  padding: 24px;
}

.route-preview-info span {
  display: block;
  margin-bottom: 8px;
  color: #ffe1a0;
  font-size: 12px;
  font-weight: 800;
  letter-spacing: 2px;
}

.route-preview-info strong {
  display: block;
  margin-bottom: 8px;
  color: #fff;
  font-size: 30px;
  line-height: 1.2;
}

.route-preview-info p {
  color: rgba(255,255,255,0.88);
  font-size: 14px;
  line-height: 1.75;
}

.route-result {
  margin-top: 22px;
}

.route-day-block + .route-day-block {
  margin-top: 34px;
}

.route-day-title {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 18px;
}

.route-day-dot {
  width: 13px;
  height: 13px;
  border-radius: 50%;
  background: #f0c36c;
  box-shadow: 0 0 0 7px rgba(240, 195, 108, 0.18);
}

.route-day-title h4 {
  color: #123646;
  font-size: 30px;
  line-height: 1.2;
}

.route-step-card {
  padding: 22px 24px;
  border-radius: 24px;
  background: linear-gradient(180deg, #fffefb, #f8efd9);
  border: 1px solid rgba(18, 54, 70, 0.08);
  cursor: pointer;
  transition: transform 0.22s ease, box-shadow 0.22s ease, outline 0.22s ease;
}

.route-step-card + .route-step-card {
  margin-top: 16px;
}

.route-step-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 16px 30px rgba(18, 54, 70, 0.12);
}

.route-step-card.route-preview-active {
  outline: 3px solid rgba(240, 195, 108, 0.45);
  box-shadow: 0 16px 34px rgba(18, 54, 70, 0.14);
}

.route-step-time {
  display: inline-block;
  margin-bottom: 12px;
  padding: 8px 14px;
  border-radius: 999px;
  background: #ffefc6;
  color: #123646;
  font-size: 14px;
  font-weight: 800;
}

.route-step-card h5 {
  margin-bottom: 10px;
  color: #123646;
  font-size: 25px;
  line-height: 1.2;
}

.route-step-card p {
  color: #7a8c95;
  font-size: 15px;
  line-height: 1.8;
}

body.dark .route-left-panel h3,
body.dark .route-result-head h3,
body.dark .route-day-title h4,
body.dark .route-step-card h5,
body.dark .route-form label {
  color: #f0c36c;
}

body.dark .route-left-panel p,
body.dark .route-result-head p,
body.dark .route-step-card p {
  color: #d3e0e2;
}

body.dark .route-form select,
body.dark .route-step-card {
  background: rgba(255,255,255,0.06);
  border-color: rgba(255,255,255,0.08);
  color: #f3dfb1;
}

body.dark .route-step-time {
  background: rgba(240, 195, 108, 0.16);
  color: #f3dfb1;
}

@media (max-width: 980px) {
  .route-generator-layout {
    grid-template-columns: 1fr;
  }

  .route-left-panel {
    position: relative;
    top: auto;
  }

  .route-preview-card,
  .route-preview-card img {
    min-height: 280px;
  }
}

@media (max-width: 640px) {
  .route-section {
    padding: 54px 0;
  }

  .route-left-panel,
  .route-result-panel {
    padding: 22px;
  }

  .route-left-panel h3,
  .route-result-head h3 {
    font-size: 26px;
  }

  .route-form {
    grid-template-columns: 1fr;
  }

  .route-day-title h4 {
    font-size: 24px;
  }

  .route-step-card h5 {
    font-size: 21px;
  }
}

/* =========================
   第一部分：卡片文字浅色化优化
   ========================= */

/* 1. 主视觉大图上的文字 */
.intro-visual-overlay h3 {
  color: #ffffff !important;
  text-shadow: 0 2px 10px rgba(0, 0, 0, 0.5) !important;
}

.intro-visual-overlay .mini-label {
  color: #ffe1a0 !important;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3) !important;
}

/* 2. 右侧小卡图上的标签 */
.intro-sub-overlay span {
  color: #ffffff !important;
  text-shadow: 0 2px 6px rgba(0, 0, 0, 0.5) !important;
}

/* 3. 右侧信息卡片（纯色背景卡片）的文字优化 */
body.dark .intro-info-item h4 {
  color: #f0c36c !important;
}

body.dark .intro-info-item p {
  color: #d3e0e2 !important;
}

/* 4. 底部圆角标签 (石刻艺术/佛教文化等) */
.intro-tags-row span,
.intro-sub-overlay span,
.intro-sub-card .intro-sub-overlay span {
  background: rgba(255, 255, 255, 0.15) !important;
  backdrop-filter: blur(10px);
  color: #ffffff !important;
  border: 1px solid rgba(255, 255, 255, 0.3) !important;
  text-shadow: 0 1px 3px rgba(0, 0, 0, 0.5) !important;
}

/* 特殊处理：即使在浅色模式下，图片上的字也是白的 */
.intro-main-visual .intro-visual-overlay h3,
.intro-sub-card .intro-sub-overlay span {
  color: #ffffff !important;
}

/* 5. 优化文字的对比度，防止背景太亮导致白色看不清 */
.intro-visual-overlay,
.intro-sub-overlay {
  background: linear-gradient(to top, rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0)) !important;
}

/* =========================
   图片卡片上的说明小字统一改为浅色
   ========================= */

/* 山水地标页：大佛、峨眉山卡片小字 */
.landmark-card-overlay p {
  color: rgba(255, 255, 255, 0.9) !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.55) !important;
}

/* 烟火传承页：美食、非遗卡片小字 */
.heritage-card-overlay p {
  color: rgba(255, 255, 255, 0.9) !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.55) !important;
}

/* 第一页左上轮播图上的说明小字 */
.intro-hero-overlay p {
  color: rgba(255, 255, 255, 0.9) !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.55) !important;
}

/* 如果你还有旧版 intro-visual-overlay，也一起覆盖 */
.intro-visual-overlay p {
  color: rgba(255, 255, 255, 0.9) !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.55) !important;
}

/* 标签上方的英文小标签保持金色清晰 */
.landmark-card-overlay .card-label,
.heritage-card-overlay .card-label,
.intro-hero-overlay .mini-label,
.intro-visual-overlay .mini-label {
  color: #ffe1a0 !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.5) !important;
}

/* 中文大标题也统一加一点阴影，防止浅色图片区域发虚 */
.landmark-card-overlay h3,
.heritage-card-overlay h3,
.intro-hero-overlay h3,
.intro-visual-overlay h3 {
  color: #ffffff !important;
  text-shadow: 0 3px 12px rgba(0, 0, 0, 0.6) !important;
}

/* =========================
   最终版：图片卡片文字浅色清晰优化
   适用于日间 / 夜间模式
   ========================= */

/* 一、所有压在图片上的说明小字统一改为浅色 */
.landmark-card-overlay p,
.heritage-card-overlay p,
.intro-hero-overlay p,
.intro-visual-overlay p,
.intro-sub-overlay p,
.route-preview-info p {
  color: #f7efe0 !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.62) !important;
}

/* 二、所有压在图片上的中文大标题统一白色 */
.landmark-card-overlay h3,
.heritage-card-overlay h3,
.intro-hero-overlay h3,
.intro-visual-overlay h3,
.intro-sub-overlay h3,
.route-preview-info strong {
  color: #ffffff !important;
  text-shadow: 0 3px 14px rgba(0, 0, 0, 0.68) !important;
}

/* 三、所有压在图片上的英文小标签统一淡金色 */
.landmark-card-overlay .card-label,
.heritage-card-overlay .card-label,
.intro-hero-overlay .mini-label,
.intro-visual-overlay .mini-label,
.intro-sub-overlay .mini-label,
.route-preview-info span {
  color: #ffe1a0 !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.58) !important;
}

/* 四、山水地标页底部圆角标签 */
.landmark-card-meta span {
  color: #ffffff !important;
  background: rgba(20, 24, 28, 0.46) !important;
  border: 1px solid rgba(255, 255, 255, 0.26) !important;
  text-shadow: 0 2px 6px rgba(0, 0, 0, 0.55) !important;
  backdrop-filter: blur(10px);
}

/* 五、烟火传承页底部圆角标签 */
.heritage-card-meta span {
  color: #ffffff !important;
  background: rgba(20, 18, 14, 0.46) !important;
  border: 1px solid rgba(255, 255, 255, 0.26) !important;
  text-shadow: 0 2px 6px rgba(0, 0, 0, 0.55) !important;
  backdrop-filter: blur(10px);
}

/* 六、第一页右下辅助图上的文字 */
.intro-side-image-overlay span,
.intro-sub-overlay span {
  color: #ffffff !important;
  text-shadow: 0 3px 12px rgba(0, 0, 0, 0.65) !important;
}

/* 七、给所有图片卡片底部增强深色渐变，保证浅色文字永远看得清 */
.landmark-card::after,
.heritage-card::after,
.intro-hero-card::after,
.intro-side-image-card::after,
.intro-main-visual::after,
.intro-sub-card::after,
.route-preview-card::after {
  background:
    linear-gradient(to top, rgba(5, 10, 14, 0.86), rgba(5, 10, 14, 0.32), rgba(5, 10, 14, 0.04)) !important;
}

/* 八、避免日间模式把图片上的文字重新改成深色 */
body:not(.dark) .landmark-card-overlay p,
body:not(.dark) .heritage-card-overlay p,
body:not(.dark) .intro-hero-overlay p,
body:not(.dark) .intro-visual-overlay p,
body:not(.dark) .route-preview-info p,
body:not(.dark) .intro-final-visual-copy p,
body:not(.dark) .intro-final-side-overlay p {
  color: #f7efe0 !important;
}

body:not(.dark) .landmark-card-overlay h3,
body:not(.dark) .heritage-card-overlay h3,
body:not(.dark) .intro-hero-overlay h3,
body:not(.dark) .intro-visual-overlay h3,
body:not(.dark) .route-preview-info strong {
  color: #ffffff !important;
}

body:not(.dark) .landmark-card-overlay .card-label,
body:not(.dark) .heritage-card-overlay .card-label,
body:not(.dark) .intro-hero-overlay .mini-label,
body:not(.dark) .intro-visual-overlay .mini-label,
body:not(.dark) .route-preview-info span {
  color: #ffe1a0 !important;
}

/* 九、夜间模式也保持一致，不再变灰变暗 */
body.dark .landmark-card-overlay p,
body.dark .heritage-card-overlay p,
body.dark .intro-hero-overlay p,
body.dark .intro-visual-overlay p,
body.dark .route-preview-info p,
body.dark .intro-final-visual-copy p,
body.dark .intro-final-side-overlay p {
  color: #f7efe0 !important;
}

body.dark .landmark-card-overlay h3,
body.dark .heritage-card-overlay h3,
body.dark .intro-hero-overlay h3,
body.dark .intro-visual-overlay h3,
body.dark .route-preview-info strong {
  color: #ffffff !important;
}

body.dark .landmark-card-overlay .card-label,
body.dark .heritage-card-overlay .card-label,
body.dark .intro-hero-overlay .mini-label,
body.dark .intro-visual-overlay .mini-label,
body.dark .route-preview-info span {
  color: #ffe1a0 !important;
}

/* 图片卡片文字兜底覆盖 */
.photo-card p,
.landmark-card p,
.heritage-card p,
.intro-hero-card p,
.intro-main-visual p,
.route-preview-card p {
  color: #f7efe0 !important;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.62) !important;
}

/* =========================
   第6页最终版：绿色低碳互动页
   ========================= */

.green-page-final {
  min-height: 100vh;
  padding: 72px 0;
  background:
    radial-gradient(circle at 14% 18%, rgba(240, 195, 108, 0.14), transparent 28%),
    radial-gradient(circle at 86% 72%, rgba(95, 160, 120, 0.14), transparent 30%),
    linear-gradient(180deg, #f4f1e8 0%, #eef4ec 100%);
}

.green-final-inner {
  width: min(92%, 1360px);
  margin: 0 auto;
}

.green-final-heading {
  margin-bottom: 28px;
}

.green-final-heading h2 {
  font-size: clamp(44px, 4.6vw, 72px);
  line-height: 1.08;
}

.green-final-layout {
  display: grid;
  grid-template-columns: 0.94fr 1.06fr;
  gap: 28px;
  align-items: stretch;
}

.green-final-left,
.green-final-right {
  border-radius: 34px;
  padding: 30px;
}

.green-final-left {
  display: flex;
  flex-direction: column;
}

.green-final-intro h3,
.green-game-top h3 {
  margin: 10px 0 12px;
  color: #123646;
  font-size: 32px;
  line-height: 1.22;
}

.green-final-intro p {
  color: #607279;
  font-size: 15px;
  line-height: 1.82;
}

.green-action-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
  margin-top: 22px;
}

.green-action-card {
  position: relative;
  padding: 18px 18px 16px;
  border-radius: 22px;
  background:
    linear-gradient(180deg, rgba(255, 255, 255, 0.92), rgba(255, 247, 225, 0.82));
  border: 1px solid rgba(18, 54, 70, 0.08);
  overflow: hidden;
}

.green-action-card::after {
  content: "";
  position: absolute;
  right: -18px;
  bottom: -22px;
  width: 78px;
  height: 78px;
  border-radius: 50%;
  background: rgba(240, 195, 108, 0.14);
}

.green-action-index {
  display: inline-block;
  margin-bottom: 10px;
  color: #c28b37;
  font-size: 13px;
  font-weight: 800;
  letter-spacing: 2px;
}

.green-action-card strong {
  display: block;
  margin-bottom: 8px;
  color: #123646;
  font-size: 18px;
}

.green-action-card p {
  position: relative;
  z-index: 1;
  color: #607279;
  font-size: 14px;
  line-height: 1.68;
}

.green-final-slogan {
  margin-top: 20px;
  padding: 24px;
  border-radius: 28px;
  background:
    radial-gradient(circle at top left, rgba(255, 255, 255, 0.26), transparent 34%),
    linear-gradient(135deg, #1f5b62 0%, #6f936d 48%, #d4b95d 100%);
  color: #fff;
  box-shadow: 0 20px 40px rgba(31, 91, 98, 0.18);
}

.green-final-slogan span {
  display: block;
  margin-bottom: 10px;
  color: rgba(255, 255, 255, 0.76);
  font-size: 12px;
  font-weight: 800;
  letter-spacing: 4px;
}

.green-final-slogan strong {
  display: block;
  max-width: 620px;
  color: #fff;
  font-size: 25px;
  line-height: 1.38;
}

.green-final-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 18px;
}

.green-final-tags span {
  padding: 9px 15px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 13px;
  font-weight: 800;
}

.green-final-right {
  display: flex;
  flex-direction: column;
  background:
    radial-gradient(circle at top right, rgba(240, 195, 108, 0.12), transparent 28%),
    rgba(255, 255, 255, 0.78);
}

.green-game-top {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 18px;
}

.green-game-top h3 {
  margin-bottom: 0;
}

.green-game-badge {
  flex: 0 0 auto;
  padding: 9px 14px;
  border-radius: 999px;
  background: #123646;
  color: #fff;
  font-size: 13px;
  font-weight: 800;
}

.game-guide-final {
  margin-top: 16px;
  padding: 14px 16px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fffaf0, #f6efdf);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.game-guide-final strong {
  display: block;
  margin-bottom: 6px;
  color: #123646;
  font-size: 15px;
}

.game-guide-final p {
  color: #607279;
  font-size: 14px;
  line-height: 1.65;
}

.game-status-final {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
  margin-top: 16px;
}

.game-score-card {
  padding: 14px 16px;
  border-radius: 18px;
  background: linear-gradient(180deg, #fffdf8, #f4eddc);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.game-score-card span {
  display: block;
  margin-bottom: 5px;
  color: #6c7d82;
  font-size: 13px;
}

.game-score-card strong {
  color: #123646;
  font-size: 24px;
}

.trash-card-final {
  margin-top: 16px;
  padding: 18px;
  border-radius: 24px;
  background:
    radial-gradient(circle at top right, rgba(240, 195, 108, 0.16), transparent 30%),
    linear-gradient(180deg, #ffffff, #f7f1e5);
  border: 1px solid rgba(18, 54, 70, 0.08);
}

.trash-card-top {
  display: flex;
  align-items: center;
  gap: 14px;
  margin-bottom: 8px;
}

.trash-item-icon {
  width: 66px;
  height: 66px;
  border-radius: 21px;
  display: flex;
  align-items: center;
  justify-content: center;
  background:
    radial-gradient(circle at top, rgba(255, 255, 255, 0.35), transparent 34%),
    linear-gradient(160deg, #1f5b62, #5fa078);
  color: #fff;
  font-size: 18px;
  font-weight: 900;
  letter-spacing: 1px;
  box-shadow: 0 14px 28px rgba(18, 54, 70, 0.16);
  flex-shrink: 0;
}

.trash-card-label {
  display: inline-block;
  margin-bottom: 6px;
  color: #b78035;
  font-size: 12px;
  letter-spacing: 2px;
  font-weight: 800;
}

.trash-card-final h4 {
  margin: 0;
  color: #123646;
  font-size: 27px;
  line-height: 1.2;
}

.trash-card-final p {
  color: #5d7077;
  font-size: 14px;
  line-height: 1.7;
}

.bins-grid-final {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
  margin-top: 16px;
}

.bin-btn {
  min-height: 74px;
  padding: 14px 16px;
  border: none;
  border-radius: 20px;
  cursor: pointer;
  text-align: left;
  transition: transform 0.22s, box-shadow 0.22s;
  box-shadow: 0 12px 24px rgba(18, 36, 44, 0.08);
}

.bin-btn span {
  display: block;
  margin-bottom: 4px;
  font-size: 17px;
  font-weight: 900;
}

.bin-btn small {
  font-size: 12px;
  opacity: 0.82;
}

.bin-btn:hover {
  transform: translateY(-3px);
}

.bin-btn.recyclable {
  background: linear-gradient(135deg, #d9efff, #a9d4ff);
  color: #184b76;
}

.bin-btn.kitchen {
  background: linear-gradient(135deg, #e0f6d5, #b9e28c);
  color: #2d6a28;
}

.bin-btn.harmful {
  background: linear-gradient(135deg, #ffd8d8, #ffaaaa);
  color: #842d2d;
}

.bin-btn.other {
  background: linear-gradient(135deg, #ececec, #cfcfcf);
  color: #4f575d;
}

.bin-btn.correct {
  box-shadow: 0 0 0 4px rgba(108, 190, 111, 0.22), 0 16px 28px rgba(34, 100, 40, 0.12);
  transform: translateY(-2px);
}

.bin-btn.wrong {
  box-shadow: 0 0 0 4px rgba(217, 86, 86, 0.18), 0 16px 28px rgba(120, 40, 40, 0.08);
}

.bin-btn:disabled {
  cursor: not-allowed;
}

.game-feedback {
  min-height: 50px;
  margin-top: 14px;
  padding: 13px 16px;
  border-radius: 16px;
  background: linear-gradient(180deg, #fff9eb, #f7efdc);
  color: #6d5827;
  font-size: 14px;
  line-height: 1.65;
  border-left: 4px solid #f0c36c;
}

.game-feedback.success {
  background: linear-gradient(180deg, #eef9ea, #e0f3d7);
  color: #2f6a2a;
  border-left-color: #7ac16d;
}

.game-feedback.error {
  background: linear-gradient(180deg, #fff1f1, #fde1e1);
  color: #8c3333;
  border-left-color: #db6b6b;
}

.game-feedback.finish {
  background: linear-gradient(180deg, #eef7ff, #dfeeff);
  color: #26577e;
  border-left-color: #6aa8e8;
}

.game-footer-final {
  margin-top: 14px;
}

.game-restart-btn {
  padding: 10px 22px;
}

/* 认证卡弹窗 */
.cert-modal {
  position: fixed;
  inset: 0;
  display: none;
  align-items: center;
  justify-content: center;
  padding: 24px;
  background: rgba(8, 18, 26, 0.56);
  backdrop-filter: blur(8px);
  z-index: 1200;
}

.cert-modal.show {
  display: flex;
}

.cert-card {
  position: relative;
  width: min(92%, 560px);
  padding: 34px 30px 30px;
  border-radius: 30px;
  background:
    radial-gradient(circle at top, rgba(255, 255, 255, 0.28), transparent 34%),
    linear-gradient(180deg, #fffdf8, #f4eddc);
  box-shadow: 0 28px 54px rgba(18, 36, 44, 0.22);
  text-align: center;
  overflow: hidden;
}

.cert-card::before {
  content: "";
  position: absolute;
  inset: 0 auto 0 0;
  width: 8px;
  background: linear-gradient(180deg, #7ac16d, #f0c36c);
}

.cert-close {
  position: absolute;
  top: 16px;
  right: 18px;
  width: 42px;
  height: 42px;
  border: none;
  border-radius: 50%;
  background: rgba(18, 54, 70, 0.06);
  color: #123646;
  font-size: 28px;
  line-height: 1;
  cursor: pointer;
}

.cert-card h3 {
  margin: 12px 0 10px;
  color: #123646;
  font-size: 34px;
}

.cert-score {
  margin-bottom: 12px;
  color: #2d6a28;
  font-size: 24px;
  font-weight: 900;
}

.cert-desc {
  max-width: 420px;
  margin: 0 auto;
  color: #5e7077;
  line-height: 1.8;
}

.cert-badges {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  margin: 22px 0 24px;
}

.cert-badges span {
  padding: 8px 14px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 13px;
  font-weight: 800;
}

/* 夜间模式 */
body.dark .green-page-final {
  background:
    radial-gradient(circle at 14% 18%, rgba(240, 195, 108, 0.08), transparent 28%),
    radial-gradient(circle at 86% 72%, rgba(95, 160, 120, 0.10), transparent 30%),
    linear-gradient(180deg, #102129 0%, #0d1b22 100%);
}

body.dark .green-final-intro h3,
body.dark .green-game-top h3,
body.dark .green-action-card strong,
body.dark .game-guide-final strong,
body.dark .trash-card-final h4,
body.dark .game-score-card strong,
body.dark .cert-card h3 {
  color: #f0c36c;
}

body.dark .green-final-intro p,
body.dark .green-action-card p,
body.dark .game-guide-final p,
body.dark .trash-card-final p,
body.dark .game-score-card span,
body.dark .cert-desc {
  color: #d3e0e2;
}

body.dark .green-action-card,
body.dark .game-guide-final,
body.dark .game-score-card,
body.dark .trash-card-final,
body.dark .cert-card {
  background: rgba(255, 255, 255, 0.06);
  border-color: rgba(255, 255, 255, 0.08);
}

body.dark .green-final-tags span,
body.dark .cert-badges span {
  background: rgba(240, 195, 108, 0.14);
  color: #f3dfb1;
}

body.dark .green-game-badge {
  background: #f0c36c;
  color: #123646;
}

body.dark .game-feedback {
  background: rgba(240, 195, 108, 0.12);
  color: #f3dfb1;
  border-left-color: #f0c36c;
}

body.dark .game-feedback.success {
  background: rgba(122, 193, 109, 0.14);
  color: #cfecc8;
  border-left-color: #7ac16d;
}

body.dark .game-feedback.error {
  background: rgba(219, 107, 107, 0.14);
  color: #ffd3d3;
  border-left-color: #db6b6b;
}

body.dark .game-feedback.finish {
  background: rgba(106, 168, 232, 0.14);
  color: #d8ebff;
  border-left-color: #6aa8e8;
}

body.dark .cert-close {
  background: rgba(255, 255, 255, 0.08);
  color: #f1f4f4;
}

/* 响应式 */
@media (max-width: 1180px) {
  .green-final-layout {
    grid-template-columns: 1fr;
  }

  .green-final-left,
  .green-final-right {
    padding: 26px;
  }
}

@media (max-width: 720px) {
  .green-page-final {
    padding: 54px 0;
  }

  .green-action-grid,
  .game-status-final,
  .bins-grid-final {
    grid-template-columns: 1fr;
  }

  .green-game-top {
    flex-direction: column;
  }

  .green-final-slogan strong {
    font-size: 21px;
  }

  .green-final-left,
  .green-final-right {
    padding: 22px;
    border-radius: 26px;
  }

  .green-final-intro h3,
  .green-game-top h3 {
    font-size: 26px;
  }

  .trash-card-final h4 {
    font-size: 23px;
  }
}

/* =========================
   第1部分最终版：城市引入页重排
   ========================= */

.intro-page-final {
  min-height: 100vh;
  padding: 72px 0 64px;
  background:
    radial-gradient(circle at 16% 16%, rgba(240, 195, 108, 0.12), transparent 28%),
    radial-gradient(circle at 86% 72%, rgba(31, 91, 98, 0.08), transparent 32%),
    linear-gradient(180deg, #f7f4ec 0%, #f2efe7 100%);
}

.intro-final-inner {
  width: min(92%, 1360px);
  margin: 0 auto;
}

.intro-final-heading {
  margin-bottom: 28px;
}

.intro-final-heading h2 {
  font-size: clamp(46px, 5vw, 76px);
  line-height: 1.06;
}

.intro-final-layout {
  display: grid;
  grid-template-columns: 1.08fr 0.92fr;
  gap: 28px;
  align-items: stretch;
}

.intro-final-left,
.intro-final-right {
  display: grid;
  gap: 22px;
}

.intro-final-left {
  grid-template-rows: 440px auto;
}

.intro-final-right {
  grid-template-rows: auto 300px;
}

/* 左上动态主图 */
.intro-final-visual {
  position: relative;
  overflow: hidden;
  border-radius: 34px;
  background: #102028;
  perspective: 1800px;
  box-shadow: 0 24px 48px rgba(18, 36, 44, 0.14);
}

.intro-final-visual::after {
  content: "";
  position: absolute;
  inset: 0;
  z-index: 2;
  pointer-events: none;
  background:
    linear-gradient(to top, rgba(5, 10, 14, 0.86), rgba(5, 10, 14, 0.22), rgba(5, 10, 14, 0.04)),
    linear-gradient(135deg, rgba(255, 222, 162, 0.08), transparent 42%);
}

.intro-cube-slider {
  position: absolute;
  inset: 0;
  overflow: hidden;
  border-radius: inherit;
}

.cube-stage {
  position: absolute;
  inset: 0;
  transform-style: preserve-3d;
}

.cube-panel {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden;
  transform-origin: center center;
}

.cube-panel img {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}

.cube-current {
  z-index: 2;
  transform: rotateY(0deg);
}

.cube-next {
  z-index: 1;
  transform: rotateY(90deg);
}

.intro-cube-slider.is-animating.forward .cube-current {
  animation: introCubeCurrentOutForward 1.05s ease-in-out forwards;
}

.intro-cube-slider.is-animating.forward .cube-next {
  animation: introCubeNextInForward 1.05s ease-in-out forwards;
}

.intro-cube-slider.is-animating.backward .cube-current {
  animation: introCubeCurrentOutBackward 1.05s ease-in-out forwards;
}

.intro-cube-slider.is-animating.backward .cube-next {
  animation: introCubeNextInBackward 1.05s ease-in-out forwards;
}

@keyframes introCubeCurrentOutForward {
  0% {
    transform: perspective(1800px) rotateY(0deg);
  }
  100% {
    transform: perspective(1800px) rotateY(-90deg);
  }
}

@keyframes introCubeNextInForward {
  0% {
    transform: perspective(1800px) rotateY(90deg);
  }
  100% {
    transform: perspective(1800px) rotateY(0deg);
  }
}

@keyframes introCubeCurrentOutBackward {
  0% {
    transform: perspective(1800px) rotateY(0deg);
  }
  100% {
    transform: perspective(1800px) rotateY(90deg);
  }
}

@keyframes introCubeNextInBackward {
  0% {
    transform: perspective(1800px) rotateY(-90deg);
  }
  100% {
    transform: perspective(1800px) rotateY(0deg);
  }
}

.intro-final-visual-copy {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 3;
  padding: 34px 36px 32px;
}

.intro-final-visual-copy h3 {
  margin: 10px 0 10px;
  color: #fff;
  font-size: clamp(34px, 3.2vw, 50px);
  line-height: 1.12;
  text-shadow: 0 3px 14px rgba(0, 0, 0, 0.68);
}

.intro-final-visual-copy p {
  max-width: 760px;
  color: #f7efe0 !important;
  font-size: 16px;
  line-height: 1.75;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.62) !important;
}

/* 左下文案卡 */
.intro-final-copy {
  position: relative;
  display: grid;
  grid-template-columns: 210px 1fr;
  gap: 34px;
  align-items: stretch;
  padding: 32px 34px;
  border-radius: 32px;
  overflow: hidden;
  background:
    radial-gradient(circle at right bottom, rgba(240, 195, 108, 0.10), transparent 22%),
    linear-gradient(180deg, rgba(255,255,255,0.96), rgba(255,255,255,0.92));
  box-shadow: 0 22px 44px rgba(18, 36, 44, 0.08);
}

.intro-final-copy::before {
  content: "";
  position: absolute;
  left: 210px;
  top: 32px;
  bottom: 32px;
  width: 1px;
  background: linear-gradient(to bottom, rgba(18,54,70,0.08), rgba(18,54,70,0.02));
}

/* 背景装饰竖排大字 */
.intro-final-copy::after {
  content: "JIAZHOU";
  position: absolute;
  right: 18px;
  bottom: 10px;
  z-index: 0;
  color: rgba(18, 54, 70, 0.04);
  font-size: 82px;
  font-weight: 900;
  letter-spacing: 12px;
  writing-mode: vertical-rl;
  pointer-events: none;
  user-select: none;
}

.intro-copy-side {
  position: relative;
  z-index: 1;
  display: flex;
  flex-direction: column;
  gap: 18px;
  align-items: flex-start;
}

.intro-copy-mark {
  width: 126px;
  height: 126px;
  border-radius: 36px;
  display: flex;
  align-items: center;
  justify-content: center;
  background:
    radial-gradient(circle at top, rgba(255,255,255,0.25), transparent 34%),
    linear-gradient(145deg, #1f5b62, #d1b75f);
  color: #fff;
  font-size: 42px;
  font-weight: 900;
  letter-spacing: 4px;
  writing-mode: vertical-rl;
  box-shadow: 0 18px 34px rgba(18, 54, 70, 0.16);
}

.intro-copy-meta span {
  display: block;
  margin-bottom: 10px;
  color: #b78035;
  font-size: 12px;
  font-weight: 900;
  letter-spacing: 3px;
}

.intro-copy-meta ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: grid;
  gap: 10px;
}

.intro-copy-meta li {
  position: relative;
  padding-left: 16px;
  color: #607279;
  font-size: 15px;
  font-weight: 700;
  line-height: 1.5;
}

.intro-copy-meta li::before {
  content: "";
  position: absolute;
  left: 0;
  top: 10px;
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background: #d1b75f;
}

.intro-copy-main.single-column {
  display: grid;
  grid-template-columns: 1fr;
  gap: 18px;
  align-content: start;
}

.intro-copy-main.single-column .intro-copy-block p {
  color: #607279;
  font-size: 16px;
  line-height: 1.9;
  margin: 0;
}

.intro-copy-quote {
  grid-column: 1 / -1;
  margin-top: 4px;
  padding-top: 18px;
  border-top: 1px solid rgba(18, 54, 70, 0.08);
}

.intro-copy-quote span {
  display: inline-block;
  color: #123646;
  font-size: 22px;
  font-weight: 800;
  line-height: 1.5;
  letter-spacing: 1px;
}

/* 暗色模式 */
body.dark .intro-final-copy {
  background:
    radial-gradient(circle at right bottom, rgba(240, 195, 108, 0.08), transparent 22%),
    linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.03));
}

body.dark .intro-final-copy::before {
  background: linear-gradient(to bottom, rgba(255,255,255,0.08), rgba(255,255,255,0.02));
}

body.dark .intro-copy-meta li,
body.dark .intro-copy-block p {
  color: #d3e0e2;
}

body.dark .intro-copy-quote span {
  color: #f0c36c;
}

body.dark .intro-copy-meta span {
  color: #f6d486;
}

/* 响应式 */
@media (max-width: 980px) {
  .intro-final-copy {
    grid-template-columns: 1fr;
    gap: 24px;
  }

  .intro-final-copy::before {
    display: none;
  }

  .intro-copy-side {
    flex-direction: row;
    align-items: center;
    gap: 20px;
  }

  .intro-copy-main {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  .intro-final-copy {
    padding: 24px;
  }

  .intro-copy-side {
    flex-direction: column;
    align-items: flex-start;
  }

  .intro-copy-mark {
    width: 104px;
    height: 104px;
    font-size: 34px;
    writing-mode: horizontal-tb;
  }

  .intro-copy-block p {
    font-size: 15px;
    line-height: 1.8;
  }

  .intro-copy-quote span {
    font-size: 18px;
  }
}

/* 右上城市身份卡 */
.intro-profile-final {
  padding: 30px 32px;
  border-radius: 34px;
}

.intro-profile-final-list {
  margin-top: 12px;
}

.intro-profile-final-item {
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 20px;
  padding: 19px 0;
  border-bottom: 1px solid rgba(18, 54, 70, 0.08);
}

.intro-profile-stats {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 18px;
}

.intro-profile-stats span {
  padding: 8px 12px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 12px;
  font-weight: 800;
}

.intro-profile-final-item:first-child {
  padding-top: 6px;
}

.intro-profile-final-item:last-child {
  padding-bottom: 0;
  border-bottom: none;
}

.intro-profile-final-item h4 {
  margin: 0 0 8px;
  color: #123646;
  font-size: 28px;
  line-height: 1.2;
}

.intro-profile-final-item p {
  color: #607279;
  font-size: 15px;
  line-height: 1.76;
}

.intro-profile-final-item > span {
  align-self: center;
  color: #b78035;
  font-size: 12px;
  font-weight: 900;
  letter-spacing: 3px;
}

/* 右下图片 */
.intro-final-side-image {
  position: relative;
  overflow: hidden;
  border-radius: 34px;
  background: #102028;
  box-shadow: 0 20px 42px rgba(18, 36, 44, 0.12);
}

.intro-final-side-image img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}

.intro-final-side-image::after {
  content: "";
  position: absolute;
  inset: 0;
  background:
    linear-gradient(to top, rgba(5, 10, 14, 0.84), rgba(5, 10, 14, 0.18), rgba(5, 10, 14, 0.04));
}

.intro-final-side-overlay {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 2;
  padding: 26px 28px;
}

.intro-final-side-overlay span {
  display: block;
  margin-bottom: 8px;
  color: #fff;
  font-size: 30px;
  font-weight: 900;
  text-shadow: 0 3px 12px rgba(0, 0, 0, 0.65);
}

.intro-final-side-overlay p {
  color: #f7efe0 !important;
  font-size: 14px;
  line-height: 1.7;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.62) !important;
}

/* 底部标签：贴近主体，不悬空 */
.intro-final-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 22px;
}

.intro-final-tags span {
  padding: 10px 18px;
  border-radius: 999px;
  background: #fff1cf;
  color: #123646;
  font-size: 14px;
  font-weight: 900;
  box-shadow: 0 10px 22px rgba(18, 54, 70, 0.06);
}

/* 暗色模式 */
body.dark .intro-page-final {
  background:
    radial-gradient(circle at 16% 16%, rgba(240, 195, 108, 0.08), transparent 28%),
    radial-gradient(circle at 86% 72%, rgba(31, 91, 98, 0.12), transparent 32%),
    linear-gradient(180deg, #102129 0%, #0d1b22 100%);
}

body.dark .intro-profile-final-item h4 {
  color: #f0c36c;
}

body.dark .intro-profile-final-item p,
body.dark .intro-copy-text p {
  color: #d3e0e2;
}

body.dark .intro-profile-final-item > span {
  color: #f6d486;
}

body.dark .intro-final-tags span {
  background: rgba(240, 195, 108, 0.14);
  color: #f3dfb1;
}

/* 响应式 */
@media (max-width: 1180px) {
  .intro-final-layout {
    grid-template-columns: 1fr;
  }

  .intro-final-left {
    grid-template-rows: 420px auto;
  }

  .intro-final-right {
    grid-template-rows: auto 280px;
  }
}

@media (max-width: 760px) {
  .intro-page-final {
    padding: 54px 0;
  }

  .intro-final-copy {
    grid-template-columns: 1fr;
  }

  .intro-copy-mark {
    width: 96px;
    height: 96px;
    font-size: 28px;
    writing-mode: horizontal-tb;
  }

  .intro-copy-text {
    grid-template-columns: 1fr;
  }

  .intro-profile-final-item {
    grid-template-columns: 1fr;
  }

  .intro-profile-final-item > span {
    align-self: flex-start;
  }

  .intro-final-visual {
    min-height: 340px;
  }

  .intro-final-left {
    grid-template-rows: auto;
  }

  .intro-final-visual-copy {
    padding: 26px 24px 24px;
  }

  .intro-final-visual-copy h3 {
    font-size: 30px;
  }

  .intro-profile-final,
  .intro-final-copy {
    padding: 24px;
  }

  .intro-profile-final-item h4 {
    font-size: 24px;
  }
}

/* 第4部分右边小游戏区布局 */
.green-final-layout {
  display: grid;
  grid-template-columns: 0.92fr 1.08fr;
  gap: 28px;
  align-items: stretch;
}

.green-final-right {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  min-height: 100%;
  padding: 30px;
}

.green-game-top {
  margin-bottom: 18px;
}

.game-status-final {
  margin-bottom: 16px;
}

.trash-card-final {
  margin-bottom: 18px;
  min-height: 160px;
}

.bins-grid-final {
  margin-bottom: 16px;
}

.game-feedback {
  margin-bottom: 18px;
  min-height: 56px;
}

.game-footer-final {
  margin-top: auto;
}

/* ========================= 
   第4/6部分最终平衡版：左侧删减 + 右侧收紧 
   ========================= */ 
 
 .green-page-balanced { 
   min-height: 100vh; 
   padding: 72px 0 64px; 
   background: 
     radial-gradient(circle at 14% 18%, rgba(240, 195, 108, 0.12), transparent 28%), 
     radial-gradient(circle at 86% 72%, rgba(95, 160, 120, 0.12), transparent 30%), 
     linear-gradient(180deg, #f4f1e8 0%, #eef4ec 100%); 
 } 
 
 .green-balanced-inner { 
   width: min(92%, 1360px); 
   margin: 0 auto; 
 } 
 
 .green-balanced-heading { 
   margin-bottom: 28px; 
 } 
 
 .green-balanced-heading h2 { 
   font-size: clamp(44px, 4.6vw, 72px); 
   line-height: 1.08; 
 } 
 
 .green-balanced-layout { 
   display: grid; 
   grid-template-columns: 0.82fr 1.18fr; 
   gap: 28px; 
   align-items: start; 
 } 
 
 /* 左侧：删减后更轻 */ 
 .green-balanced-left { 
   padding: 30px 32px; 
   border-radius: 34px; 
 } 
 
 .green-balanced-left h3 { 
   margin: 10px 0 12px; 
   color: #123646; 
   font-size: 32px; 
   line-height: 1.22; 
 } 
 
 .green-balanced-lead { 
   color: #607279; 
   font-size: 15px; 
   line-height: 1.82; 
   margin-bottom: 20px; 
 } 
 
 .green-balanced-strategy { 
   display: grid; 
   gap: 12px; 
 } 
 
 .green-strategy-item { 
   display: grid; 
   grid-template-columns: 46px 1fr; 
   gap: 14px; 
   align-items: start; 
   padding: 16px 18px; 
   border-radius: 22px; 
   background: 
     linear-gradient(180deg, rgba(255,255,255,0.92), rgba(255,247,225,0.78)); 
   border: 1px solid rgba(18, 54, 70, 0.08); 
 } 
 
 .green-strategy-item > span { 
   width: 42px; 
   height: 42px; 
   border-radius: 50%; 
   display: inline-flex; 
   align-items: center; 
   justify-content: center; 
   background: #fff1cf; 
   color: #b78035; 
   font-size: 14px; 
   font-weight: 900; 
 } 
 
 .green-strategy-item h4 { 
   margin: 0 0 6px; 
   color: #123646; 
   font-size: 22px; 
   line-height: 1.2; 
 } 
 
 .green-strategy-item p { 
   margin: 0; 
   color: #607279; 
   font-size: 14px; 
   line-height: 1.65; 
 } 
 
 .green-balanced-slogan { 
   margin-top: 18px; 
   padding: 22px 24px; 
   border-radius: 26px; 
   background: 
     radial-gradient(circle at top left, rgba(255, 255, 255, 0.24), transparent 34%), 
     linear-gradient(135deg, #1f5b62 0%, #6f936d 48%, #d4b95d 100%); 
   color: #fff; 
   box-shadow: 0 18px 36px rgba(31, 91, 98, 0.16); 
 } 
 
 .green-balanced-slogan span { 
   display: block; 
   margin-bottom: 8px; 
   color: rgba(255, 255, 255, 0.75); 
   font-size: 12px; 
   font-weight: 800; 
   letter-spacing: 4px; 
 } 
 
 .green-balanced-slogan strong { 
   display: block; 
   color: #fff; 
   font-size: 22px; 
   line-height: 1.42; 
 } 
 
 .green-balanced-tags { 
   display: flex; 
   flex-wrap: wrap; 
   gap: 10px; 
   margin-top: 16px; 
 } 
 
 .green-balanced-tags span { 
   padding: 9px 15px; 
   border-radius: 999px; 
   background: #fff1cf; 
   color: #123646; 
   font-size: 13px; 
   font-weight: 900; 
 } 
 
 /* 右侧：重新收成完整游戏面板 */ 
 .green-balanced-right { 
   padding: 30px 32px; 
   border-radius: 34px; 
   min-height: auto !important; 
   height: auto !important; 
 } 
 
 .green-game-panel { 
   max-width: 820px; 
   margin: 0 auto; 
   display: grid; 
   gap: 16px; 
 }
 
 .green-game-head { 
   display: flex; 
   align-items: flex-start; 
   justify-content: space-between; 
   gap: 18px; 
 } 
 
 .green-game-head h3 { 
   margin: 10px 0 0; 
   color: #123646; 
   font-size: 32px; 
   line-height: 1.2; 
 } 
 
 .green-game-mark { 
   flex: 0 0 auto; 
   padding: 9px 14px; 
   border-radius: 999px; 
   background: #123646; 
   color: #fff; 
   font-size: 13px; 
   font-weight: 900; 
 } 
 
 .game-status-balanced { 
   display: grid; 
   grid-template-columns: 1fr 1fr; 
   gap: 14px; 
 } 
 
 .game-score-card { 
   padding: 14px 16px; 
   border-radius: 18px; 
   background: linear-gradient(180deg, #fffdf8, #f4eddc); 
   border: 1px solid rgba(18, 54, 70, 0.08); 
 } 
 
 .game-score-card span { 
   display: block; 
   margin-bottom: 5px; 
   color: #6c7d82; 
   font-size: 13px; 
 } 
 
 .game-score-card strong { 
   color: #123646; 
   font-size: 24px; 
 } 
 
 .trash-card-balanced { 
   padding: 20px; 
   border-radius: 26px; 
   background: 
     radial-gradient(circle at top right, rgba(240, 195, 108, 0.16), transparent 30%), 
     linear-gradient(180deg, #ffffff, #f7f1e5); 
   border: 1px solid rgba(18, 54, 70, 0.08); 
 } 
 
 .trash-card-top { 
   display: flex; 
   align-items: center; 
   gap: 14px; 
   margin-bottom: 8px; 
 } 
 
 .trash-item-icon { 
   width: 68px; 
   height: 68px; 
   border-radius: 22px; 
   display: flex; 
   align-items: center; 
   justify-content: center; 
   background: 
     radial-gradient(circle at top, rgba(255,255,255,0.35), transparent 34%), 
     linear-gradient(160deg, #1f5b62, #5fa078); 
   color: #fff; 
   font-size: 18px; 
   font-weight: 900; 
   letter-spacing: 1px; 
   box-shadow: 0 14px 28px rgba(18, 54, 70, 0.16); 
   flex-shrink: 0; 
 } 
 
 .trash-card-label { 
   display: inline-block; 
   margin-bottom: 6px; 
   color: #b78035; 
   font-size: 12px; 
   letter-spacing: 2px; 
   font-weight: 900; 
 } 
 
 .trash-card-balanced h4 { 
   margin: 0; 
   color: #123646; 
   font-size: 28px; 
   line-height: 1.2; 
 } 
 
 .trash-card-balanced p { 
   color: #5d7077; 
   font-size: 14px; 
   line-height: 1.7; 
 } 
 
 .bins-grid-balanced { 
   display: grid; 
   grid-template-columns: 1fr 1fr; 
   gap: 14px; 
 } 
 
 .bin-btn { 
   min-height: 76px; 
   padding: 15px 16px; 
   border: none; 
   border-radius: 20px; 
   cursor: pointer; 
   text-align: left; 
   transition: transform 0.22s, box-shadow 0.22s; 
   box-shadow: 0 12px 24px rgba(18, 36, 44, 0.08); 
 } 
 
 .bin-btn span { 
   display: block; 
   margin-bottom: 4px; 
   font-size: 18px; 
   font-weight: 900; 
 } 
 
 .bin-btn small { 
   font-size: 12px; 
   opacity: 0.82; 
 } 
 
 .bin-btn:hover { 
   transform: translateY(-3px); 
 } 
 
 .bin-btn.recyclable { 
   background: linear-gradient(135deg, #d9efff, #a9d4ff); 
   color: #184b76; 
 } 
 
 .bin-btn.kitchen { 
   background: linear-gradient(135deg, #e0f6d5, #b9e28c); 
   color: #2d6a28; 
 } 
 
 .bin-btn.harmful { 
   background: linear-gradient(135deg, #ffd8d8, #ffaaaa); 
   color: #842d2d; 
 } 
 
 .bin-btn.other { 
   background: linear-gradient(135deg, #ececec, #cfcfcf); 
   color: #4f575d; 
 } 
 
 .game-feedback { 
   min-height: 52px; 
   padding: 13px 16px; 
   border-radius: 16px; 
   background: linear-gradient(180deg, #fff9eb, #f7efdc); 
   color: #6d5827; 
   font-size: 14px; 
   line-height: 1.65; 
   border-left: 4px solid #f0c36c; 
 } 
 
 .game-feedback.success { 
   background: linear-gradient(180deg, #eef9ea, #e0f3d7); 
   color: #2f6a2a; 
   border-left-color: #7ac16d; 
 } 
 
 .game-feedback.error { 
   background: linear-gradient(180deg, #fff1f1, #fde1e1); 
   color: #8c3333; 
   border-left-color: #db6b6b; 
 } 
 
 .game-feedback.finish { 
   background: linear-gradient(180deg, #eef7ff, #dfeeff); 
   color: #26577e; 
   border-left-color: #6aa8e8; 
 } 
 
 .game-footer-balanced { 
   display: flex; 
   justify-content: flex-start; 
   margin-top: 2px; 
 } 
 
 .game-restart-btn { 
   padding: 10px 24px; 
 } 
 
 /* 防止旧样式把按钮推到底部 */ 
 .green-balanced-right .game-footer-final, 
 .green-balanced-right .game-footer-balanced { 
   margin-top: 0 !important; 
 } 
 
 .green-balanced-right .game-footer-final { 
   margin-top: 0 !important; 
 } 
 
 /* 暗色模式 */ 
 body.dark .green-page-balanced { 
   background: 
     radial-gradient(circle at 14% 18%, rgba(240, 195, 108, 0.08), transparent 28%), 
     radial-gradient(circle at 86% 72%, rgba(95, 160, 120, 0.10), transparent 30%), 
     linear-gradient(180deg, #102129 0%, #0d1b22 100%); 
 } 
 
 body.dark .green-balanced-left h3, 
 body.dark .green-game-head h3, 
 body.dark .green-strategy-item h4, 
 body.dark .trash-card-balanced h4, 
 body.dark .game-score-card strong { 
   color: #f0c36c; 
 } 
 
 body.dark .green-balanced-lead, 
 body.dark .green-strategy-item p, 
 body.dark .trash-card-balanced p, 
 body.dark .game-score-card span { 
   color: #d3e0e2; 
 } 
 
 body.dark .green-strategy-item, 
 body.dark .game-score-card, 
 body.dark .trash-card-balanced { 
   background: rgba(255, 255, 255, 0.06); 
   border-color: rgba(255, 255, 255, 0.08); 
 } 
 
 body.dark .green-game-mark { 
   background: #f0c36c; 
   color: #123646; 
 } 
 
 /* 响应式 */ 
 @media (max-width: 1100px) { 
   .green-balanced-layout { 
     grid-template-columns: 1fr; 
   } 
 
   .green-game-panel { 
     max-width: none; 
   } 
 } 
 
 @media (max-width: 720px) { 
   .green-page-balanced { 
     padding: 54px 0; 
   } 
 
   .green-balanced-left, 
   .green-balanced-right { 
     padding: 24px; 
     border-radius: 28px; 
   } 
 
   .game-status-balanced, 
   .bins-grid-balanced { 
     grid-template-columns: 1fr; 
   } 
 
   .green-game-head { 
     flex-direction: column; 
   } 
 
   .green-balanced-left h3, 
   .green-game-head h3 { 
     font-size: 26px; 
   } 
 
   .green-balanced-slogan strong { 
     font-size: 20px; 
   } 
 }
 
 /* 清除旧版绿色页造成的右侧大空白 */ 
 .green-balanced-right, 
 .green-game-panel { 
   height: auto !important; 
   min-height: auto !important; 
 } 
 
 .green-balanced-right { 
   display: block !important; 
 } 
 
 .green-game-panel { 
   display: grid !important; 
   align-content: start !important; 
 } 
 
 .green-balanced-right .game-footer, 
 .green-balanced-right .game-footer-final, 
 .green-balanced-right .game-footer-balanced { 
   margin-top: 0 !important; 
 }

/* ========================= 
   全站章节标题系统：统一字号、对齐、气质 
   ========================= */ 
 
 .section-heading-upgraded { 
   width: 100%; 
   display: flex; 
   align-items: flex-end; 
   justify-content: space-between; 
   gap: 28px; 
   margin-bottom: 30px; 
   position: relative; 
 } 
 
 .section-heading-main { 
   display: flex; 
   align-items: flex-start; 
   gap: 18px; 
   min-width: 0; 
 } 
 
 .section-heading-upgraded .section-index { 
   flex: 0 0 auto; 
   display: inline-flex; 
   align-items: center; 
   justify-content: center; 
   min-width: 54px; 
   height: 54px; 
   margin-top: 8px; 
   border-radius: 50%; 
   background: linear-gradient(145deg, #fff4d4, #f5deb0); 
   color: #c08a33; 
   font-size: 24px; 
   font-weight: 900; 
   letter-spacing: 1px; 
   box-shadow: 0 10px 20px rgba(192, 138, 51, 0.10); 
 } 
 
 .section-heading-upgraded h2 { 
   margin: 0; 
   color: #123646; 
   font-size: clamp(48px, 5.2vw, 84px); 
   line-height: 1.04; 
   font-weight: 900; 
   letter-spacing: -0.03em; 
   text-wrap: balance; 
 } 
 
 .section-heading-upgraded .section-kicker { 
   flex: 0 0 auto; 
   margin: 0 2px 10px 0; 
   color: #f0c36c; 
   font-size: 15px; 
   font-weight: 800; 
   letter-spacing: 5px; 
   text-transform: uppercase; 
   white-space: nowrap; 
   opacity: 0.95; 
 } 
 
 /* 让标题下方有更高级的呼吸感 */ 
 .section-heading-upgraded::after { 
   content: ""; 
   position: absolute; 
   left: 74px; 
   bottom: -14px; 
   width: 120px; 
   height: 2px; 
   border-radius: 999px; 
   background: linear-gradient(90deg, rgba(240,195,108,0.9), rgba(240,195,108,0)); 
 } 
 
 /* 页面容器里统一标题对齐 */ 
 .intro-final-heading, 
 .landmarks-page .section-heading, 
 .heritage-page .section-heading, 
 .route-section .section-heading, 
 .green-final-heading, 
 .ai-page .section-heading { 
   margin-bottom: 32px !important; 
 } 
 
 /* 暗色模式 */ 
 body.dark .section-heading-upgraded h2 { 
   color: #f4efe4; 
 } 
 
 body.dark .section-heading-upgraded .section-index { 
   background: rgba(240, 195, 108, 0.16); 
   color: #f3dfb1; 
   box-shadow: none; 
 } 
 
 body.dark .section-heading-upgraded .section-kicker { 
   color: #f0c36c; 
 } 
 
 body.dark .section-heading-upgraded::after { 
   background: linear-gradient(90deg, rgba(240,195,108,0.95), rgba(240,195,108,0)); 
 } 
 
 /* 如果某页标题过长，自动缩一点但保持统一感 */ 
 .route-section .section-heading-upgraded h2, 
 .intro-page-final .section-heading-upgraded h2 { 
   font-size: clamp(44px, 4.8vw, 76px); 
 } 
 
 /* 中等屏幕 */ 
 @media (max-width: 1100px) { 
   .section-heading-upgraded { 
     gap: 20px; 
     margin-bottom: 26px; 
   } 
 
   .section-heading-upgraded .section-index { 
     min-width: 48px; 
     height: 48px; 
     font-size: 21px; 
     margin-top: 6px; 
   } 
 
   .section-heading-upgraded h2 { 
     font-size: clamp(40px, 5vw, 64px); 
   } 
 
   .section-heading-upgraded .section-kicker { 
     font-size: 13px; 
     letter-spacing: 4px; 
     margin-bottom: 8px; 
   } 
 
   .section-heading-upgraded::after { 
     left: 66px; 
     width: 96px; 
   } 
 } 
 
 /* 手机端 */ 
 @media (max-width: 720px) { 
   .section-heading-upgraded { 
     flex-direction: column; 
     align-items: flex-start; 
     gap: 10px; 
     margin-bottom: 22px; 
   } 
 
   .section-heading-main { 
     gap: 14px; 
   } 
 
   .section-heading-upgraded .section-index { 
     min-width: 42px; 
     height: 42px; 
     font-size: 18px; 
     margin-top: 4px; 
   } 
 
   .section-heading-upgraded h2 { 
     font-size: 34px; 
     line-height: 1.1; 
     letter-spacing: -0.02em; 
   } 
 
   .section-heading-upgraded .section-kicker { 
     margin-left: 56px; 
     margin-bottom: 0; 
     font-size: 12px; 
     letter-spacing: 3px; 
   } 
 
   .section-heading-upgraded::after { 
    left: 56px; 
    bottom: -10px; 
    width: 74px; 
  } 
}

/* ========================= 
   封面主标题 - 淡金色效果 
   ========================= */ 
 
 .hero h1 { 
   color: #f5e6c8 !important; 
   text-shadow: 
     0 0 8px rgba(245, 230, 200, 0.6), 
     0 4px 16px rgba(0, 0, 0, 0.4); 
 }

/* ========================= 
   五个部分标题统一左对齐 
   ========================= */ 
 
 .section-heading.section-heading-upgraded { 
   width: 100% !important; 
   max-width: none !important; 
   margin-left: 0 !important; 
   margin-right: 0 !important; 
   padding-left: 0 !important; 
   justify-content: space-between; 
   align-items: flex-end; 
 } 
 
 .section-heading-upgraded .section-heading-main { 
   display: flex !important; 
   align-items: flex-start !important; 
   justify-content: flex-start !important; 
   gap: 18px !important; 
   margin-left: 0 !important; 
   padding-left: 0 !important; 
 } 
 
 .section-heading-upgraded .section-index { 
   margin-left: 0 !important; 
 } 
 
 .section-heading-upgraded h2 { 
   text-align: left !important; 
   margin-left: 0 !important; 
 } 
 
 .section-heading-upgraded .section-kicker { 
   text-align: right; 
   margin-left: auto !important; 
 } 
 
 /* 把标题下方金线也统一从左边开始 */ 
 .section-heading-upgraded::after { 
   left: 74px !important; 
 } 
 
 /* 各页标题容器统一不要再单独偏移 */ 
 .intro-final-heading, 
 .landmarks-page .section-heading, 
 .heritage-page .section-heading, 
 .route-section .section-heading, 
 .green-final-heading, 
 .ai-page .section-heading { 
   width: 100% !important; 
   margin-left: 0 !important; 
   padding-left: 0 !important; 
 } 
 
 /* 页面总容器如果有给标题单独缩进，也取消 */ 
 .intro-final-inner, 
 .green-final-inner, 
 .route-section .section-heading, 
 .route-generator-layout { 
   margin-left: auto; 
   margin-right: auto; 
 } 
 
 /* 手机端依然左对齐 */ 
 @media (max-width: 720px) { 
   .section-heading.section-heading-upgraded { 
     align-items: flex-start !important; 
   } 
 
   .section-heading-upgraded .section-kicker { 
     margin-left: 56px !important; 
     text-align: left !important; 
   } 
 
   .section-heading-upgraded::after { 
     left: 56px !important; 
   } 
 }

/* 标题整体左移，让编号圆章更靠近左侧 */
.section-heading-upgraded .section-heading-main {
   transform: translateX(-18px); 
 } 
 
 @media (max-width: 720px) { 
   .section-heading-upgraded .section-heading-main { 
     transform: none; 
   } 
 }

/* ========================= 
   五个部分标题严格对齐 
   ========================= */ 
 
 /* 确保所有页面容器padding一致 */ 
 .intro-final-inner, 
 .story-page-inner, 
 .route-section, 
 .green-balanced-inner { 
   padding-left: 0 !important; 
   padding-right: 0 !important; 
 } 
 
 /* 确保所有标题容器margin一致 */ 
 .intro-page-final .section-heading, 
 .landmarks-page .section-heading, 
 .heritage-page .section-heading, 
 .route-section .section-heading, 
 .green-page-balanced .section-heading { 
   margin-left: 0 !important; 
   margin-right: 0 !important; 
 } 
 
 /* 编号圆章固定尺寸和位置 */ 
 .section-heading-upgraded .section-index { 
   flex-shrink: 0 !important; 
   width: 54px !important; 
   height: 54px !important; 
   margin-top: 8px !important; 
 } 
 
 /* 标题文字对齐基线 */ 
 .section-heading-upgraded h2 { 
   line-height: 1.04 !important; 
   padding-top: 8px !important; 
 } 
 
 /* 所有section容器统一padding */ 
 .intro-page-final, 
 .landmarks-page, 
 .heritage-page, 
 .route-section, 
 .green-page-balanced { 
   padding-left: 0 !important; 
   padding-right: 0 !important; 
 }

/* ========================= 
   标题往左偏移，形成更强的章节开头气势 
   ========================= */ 
 
 #intro .force-left-title, 
 #landmarks .force-left-title, 
 #heritage .force-left-title, 
 #routes .force-left-title, 
 #green .force-left-title { 
   transform: translateX(-18px) !important; 
 } 
 
 @media (max-width: 720px) { 
   #intro .force-left-title, 
   #landmarks .force-left-title, 
   #heritage .force-left-title, 
   #routes .force-left-title, 
   #green .force-left-title { 
     transform: none !important; 
   } 
 }
