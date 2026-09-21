# -VIBE-MARKDOWN-HT-DISTRIBUTION-LIB
使用HTML/CSS/JS的在线MARKDOWN笔记部署程序，可上传github io，程序主体使用DEEPSEEK编写

## 项目结构
```
/
├── index.html                 欢迎主页（读取 learn.xml 生成目录）
├── learn.html                 学习模块（读取 learn.xml + md）
├── learn.xml                  目录结构 / 关联 / 小测数据
├── test.html                  快速检测（读取 learn.xml 的 quizzes）
├── paipan.html                排盘软件（单文件，含算法修正）
├── css/
│   ├── common.css             变量 + 全局 + header + footer + 移动导航
│   ├── index.css
│   ├── learn.css
│   └── test.css
├── js/
│   ├── common.js              主题 / 路由 / 移动导航 / 工具
│   ├── index.js               读取 learn.xml 渲染首页目录
│   ├── learn.js               侧边栏树 + md 渲染 + 知识图谱 + 本页大纲
│   └── test.js                小测渲染与评分
├── img/
│   └── jiang.jpg
├── fonts/                     放置齐伋体字体文件（可选）
├── learning_notes/
│   ├── 东北派/
│   │   ├── 选牌与识牌.md
│   │   ├── 起卦与行持.md
│   │   ├── 整体结构.md
│   │   ├── 基本占断思路.md
│   │   ├── 分类占精讲.md
│   │   ├── 进阶资料理气内秘.md
│   │   ├── 实战入手思路.md
│   │   └── 秘传流运卦思路.md
│   ├── 西北派/
│   │   ├── 选牌与识牌.md
│   │   ├── 起卦.md
│   │   ├── 取象规律.md
│   │   ├── 演绎象法.md
│   │   ├── 九宫象法.md
│   │   ├── 后天卦/
│   │   │   ├── 后天枢要.md
│   │   │   └── 走卦名和落卦名.md
│   │   ├── 先天卦/
│   │   │   ├── 碰牌十法.md
│   │   │   ├── 换太极法.md
│   │   │   ├── 单宫定象法.md
│   │   │   ├── 秘传活八门九星八神之法.md
│   │   │   ├── 一卦多占与六亲分宫法.md
│   │   │   ├── 分类占的基本思路.md
│   │   │   └── 应期思路.md
│   │   ├── 三盘合参.md
│   │   ├── 十二宫终身卦思路.md
│   │   └── 补充资料/
│   │       └── 牌谱四种.md
│   └── 两派对照/
│       ├── 两派关键差异对照.md
│       └── 选学建议与学习路径.md
└── quizzes/
    ├── quiz-ne-1.xml
    ├── quiz-ne-2.xml
    ├── ...
    └── quiz-nw-9.xml
```
