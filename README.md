# news-queen-skills

《新闻女王》系列 Skill 仓库。由 [女娲 · Skill 造人术](https://github.com/alchaincyf/nuwa-skill) 生成。

包含三种不同形式的思维框架，覆盖 TVB 剧集《新闻女王》第一部（2023）与第二部（2025）。

## 仓库内容

```
news-queen-skills/
├── news-queen-framework/       # 多角色视角切换框架
├── news-queen-vgpt5.6terra/   # 主题分析框架 + 角色镜片
└── news-queen-vgpt-ds/         # 主题型深度蒸馏框架
```

---

## 三个 Skill 的定位与选型

| Skill | 定位 | 适合谁 | 心智模型结构 | 防漂移 | 研究深度 |
|-------|------|--------|-------------|--------|---------|
| **news-queen-framework** | 多角色视角切换 | 想用角色身份看问题 | 8角色 × 3-5个模型 | 无 | 无独立研究文件 |
| **news-queen-vgpt5.6terra** | 主题框架+角色镜片 | 分析新闻伦理/AI/平台议题 | 6个跨角色概念模型 | 无 | 内置来源标注 |
| **news-queen-vgpt-ds** | 纯主题分析框架 | 分析现实职场/组织/权力问题 | 6个跨作品概念模型 | 完整（三锚机制） | 19份研究文件 |

详细对比见每个子目录内的 SKILL.md。

---

## 安装

将对应子目录放入 `.claude/skills/` 或 `.zcode/skills/` 即可。

```
cp -r news-queen-framework ~/.claude/skills/
# 或
cp -r news-queen-vgpt5.6terra ~/.claude/skills/
# 或
cp -r news-queen-vgpt-ds ~/.claude/skills/
```

## License

MIT
