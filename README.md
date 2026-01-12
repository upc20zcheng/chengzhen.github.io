<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>程振 (Cheng Zhen) | 学术主页</title>
    <style>
        /* 全局设置 */
        :root {
            --primary-blue: #003366; /* 沉稳的学术蓝 */
            --accent-color: #b03535; /* 强调色 */
            --bg-color: #f9f9f9;
            --text-main: #333;
            --text-light: #666;
            --sidebar-width: 280px;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            margin: 0;
            display: flex;
            min-height: 100vh;
        }

        /* 侧边栏样式 */
        aside {
            width: var(--sidebar-width);
            background: #fff;
            border-right: 1px solid #e0e0e0;
            position: fixed;
            height: 100%;
            padding: 40px 20px;
            box-sizing: border-box;
            text-align: center;
            overflow-y: auto;
        }

        /* 头像占位符 */
        .avatar {
            width: 150px;
            height: 150px;
            background-color: #eee;
            border-radius: 50%;
            margin: 0 auto 20px;
            background-image: url('photo.jpg'); /* 请替换为您的照片文件名 */
            background-size: cover;
            background-position: center;
            border: 4px solid #fff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            color: #999;
            font-size: 14px;
        }

        aside h1 {
            font-size: 1.4em;
            margin: 10px 0 5px;
            color: var(--primary-blue);
        }

        aside .title {
            font-size: 0.9em;
            color: var(--text-light);
            margin-bottom: 20px;
        }

        aside .contact-info {
            font-size: 0.85em;
            text-align: left;
            margin-top: 30px;
            line-height: 1.8;
        }

        aside .contact-info a {
            color: var(--primary-blue);
            text-decoration: none;
        }

        /* 主内容区域 */
        main {
            margin-left: var(--sidebar-width);
            flex: 1;
            padding: 60px 80px;
            max-width: 900px;
        }

        section {
            margin-bottom: 50px;
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.02);
        }

        h2 {
            font-size: 1.5em;
            color: var(--primary-blue);
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 10px;
            margin-top: 0;
        }

        h3 {
            font-size: 1.1em;
            margin-bottom: 10px;
            color: #444;
        }

        /* 标签样式 */
        .tag {
            display: inline-block;
            background: #eef4fa;
            color: var(--primary-blue);
            padding: 4px 10px;
            border-radius: 4px;
            font-size: 0.9em;
            margin-right: 8px;
            margin-bottom: 8px;
        }

        /* 列表样式 */
        ul {
            padding-left: 20px;
        }
        
        li {
            margin-bottom: 10px;
        }

        /* 论文列表 */
        .publication-item {
            margin-bottom: 15px;
            text-align: justify;
        }

        .journal-badge {
            font-weight: bold;
            color: var(--accent-color);
            font-size: 0.9em;
        }

        /* 移动端适配 */
        @media (max-width: 768px) {
            body {
                flex-direction: column;
            }
            aside {
                position: relative;
                width: 100%;
                height: auto;
                border-right: none;
                border-bottom: 1px solid #e0e0e0;
            }
            main {
                margin-left: 0;
                padding: 30px 20px;
            }
        }
    </style>
</head>
<body>

    <aside>
        <div class="avatar">
            <span>照片区域<br>(请替换)</span>
        </div>
        <h1>程振 (Cheng Zhen)</h1>
        <div class="title">管理学博士 | 讲师 | 硕导</div>
        
        <div style="margin-top: 20px;">
            <strong>阜阳师范大学 商学院</strong>
        </div>

        <div class="contact-info">
            <p><strong>Email:</strong><br>
            <a href="mailto:202406038@fynu.edu.cn">202406038@fynu.edu.cn</a><br>
            <a href="mailto:13237494718@163.com">13237494718@163.com</a></p>
            
            <p><strong>地址:</strong><br>
            安徽省阜阳市清河东路741号<br>
            邮编: 236041</p>
        </div>
    </aside>

    <main>
        <section id="about">
            <h2>个人简介</h2>
            [cite_start]<p>程振，1993年生，安徽利辛人。2024年6月毕业于<strong>中国石油大学（华东）</strong>管理科学与工程专业，获得管理学博士学位 [cite: 1][cite_start]。现任阜阳师范大学商学院讲师、硕士生导师 [cite: 1]。</p>
            [cite_start]<p>主要从事环境制度与公司财务、数字化治理等领域的教学与研究工作。担任 <em>Environmental Engineering and Management Journal</em>、<em>PLOS ONE</em> 等期刊审稿人 [cite: 1]。</p>
            
            <h3>研究方向</h3>
            <div>
                <span class="tag">环境制度与公司财务</span>
                <span class="tag">环境会计与财务管理</span>
                <span class="tag">数字化治理与企业绿色合规</span>
                <span class="tag">资源环境治理与政策创新</span>
            </div>
        </section>

        <section id="publications">
            <h2>代表性论文 (Selected Publications)</h2>
            <div class="publication-item">
                1. <strong>Cheng, Z. (第一作者)</strong>, et al. Energy use rights trading and carbon emissions. [cite_start]<em>Energy</em>, 2025, 315: 134360. <span class="journal-badge">[SCI一区, IF 9.0]</span> [cite: 1, 2]
            </div>
            <div class="publication-item">
                2. <strong>Cheng, Z. (第一作者)</strong>, et al. Can environmental information disclosure promote urban carbon emission reduction? Quasi-experimental evidence from China. [cite_start]<em>Journal of Cleaner Production</em>, 2025, 489: 144698. <span class="journal-badge">[SCI一区, IF 9.8]</span> [cite: 1, 3]
            </div>
            <div class="publication-item">
                3. <strong>程振 (通讯作者兼第二作者)</strong>. 中国环境保护税法对企业劳动雇佣的影响. <em>中国人口·资源与环境</em>, 2023, 33(01): 61-73. [cite_start]<span class="journal-badge">[CSSCI, 国家自科B类]</span> [cite: 1]
            </div>
            <div class="publication-item">
                4. <strong>程振 (通讯作者兼第二作者)</strong>. 国家低碳战略提高了企业全要素生产率吗?——基于低碳城市试点的准自然实验. <em>产业经济研究</em>, 2021, (06): 101-115. [cite_start]<span class="journal-badge">[CSSCI]</span> [cite: 1]
            </div>
            <div class="publication-item">
                5. <strong>程振 (通讯作者兼第三作者)</strong>. 黄河流域数字经济、生态保护与高质量发展时空耦合及其驱动因素. <em>经济问题探索</em>, 2022, (08): 135-148. [cite_start]<span class="journal-badge">[CSSCI]</span> [cite: 1]
            </div>
            <div style="margin-top:15px; font-size:0.9em; color:#666;">
                * [cite_start]近五年在Energy, Journal of Cleaner Production等国内外学术期刊发表论文8余篇 [cite: 1]。
            </div>
        </section>

        <section id="projects">
            <h2>科研项目 (Projects)</h2>
            <ul>
                [cite_start]<li><strong>主持</strong>：安徽省社科规划青年项目“‘源头—过程—末端’低碳数字技术创新驱动安徽省工业企业绿色转型的机制与政策研究”（AHSKYQ2024D022），2025-2027 [cite: 1]。</li>
                [cite_start]<li><strong>参与</strong>：国家社科基金青年项目“中国地方债务可持续性的测度、影响因素与实现路径研究” [cite: 1]。</li>
                [cite_start]<li><strong>参与</strong>：国家社科基金一般项目“黄河流域制造业双重价值链高质量嵌入研究” [cite: 1]。</li>
            </ul>
        </section>

        <section id="teaching">
            <h2>教学与招生 (Teaching & Admissions)</h2>
            <h3>主讲课程</h3>
            <ul>
                [cite_start]<li>本科生：《管理定量分析：方法与技术》 [cite: 1]</li>
                [cite_start]<li>研究生：《统计分析方法》 [cite: 1]</li>
            </ul>
            
            <div style="background-color: #f0f7ff; padding: 15px; border-left: 4px solid var(--primary-blue); margin-top: 20px;">
                <h3>研究生招生</h3>
                [cite_start]<p style="margin: 0;">欢迎具有<strong>管理、经济、计算机、能源环境经济与管理</strong>等专业背景的同学报考硕士研究生。有意向者请将简历发送至电子邮箱 [cite: 1]。</p>
            </div>
        </section>
        
        <section id="awards">
            <h2>获奖情况 (Honors)</h2>
            <ul>
                [cite_start]<li>2023年4月：第七届营销科学与创新国际高峰论坛（MSI 2023）“优秀论文二等奖” [cite: 1]。</li>
                [cite_start]<li>2022年9月：能源与气候变化国际大赛（CECC）学术赛道优胜奖 (Excellence Award) [cite: 1]。</li>
            </ul>
        </section>
    </main>

</body>
</html>
