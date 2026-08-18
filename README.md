# Frontend Taste Library

一个会持续积累前端参考、记录你的审美判断，并在后续建站任务中复用这些规律的开源 Codex Skill。

> 它不会修改模型权重。它通过可读、可维护的 Skill 与参考目录保存长期设计偏好。

## 它能做什么

- 浏览你提交的网站并检查桌面端、移动端与关键交互。
- 拆解信息层级、网格、字体、色彩、影像、组件、动效、响应式与性能边界。
- 区分 `observed`、`approved` 和 `rejected`，避免把“看过”误写成“喜欢”。
- 在新的网站任务中筛选最多三个匹配参考，把规律翻译成当前项目的设计系统。
- 记录值得借鉴的设计逻辑，同时排除原网站的可访问性、性能和响应式缺陷。

## 使用 Codex 一句话安装

把下面这段直接发给 Codex：

```text
使用 $skill-installer 安装这个 Skill：
https://github.com/zeqi22408-oss/frontend-taste-library/tree/main/frontend-taste-library
```

安装完成后，Skill 会在下一个对话回合可用。

## 手动安装

将仓库中的 `frontend-taste-library` 文件夹复制到：

```text
$CODEX_HOME/skills/frontend-taste-library
```

重新启动或刷新 Codex，使 Skill 被重新发现。

## 使用

学习并保存参考：

```text
学习这个网站并加入我的前端设计库：https://example.com/
```

调用设计库：

```text
使用我的前端设计库，为这个项目设计一个首页。
```

明确反馈：

```text
把这个参考标记为喜欢。
这个方向不喜欢，记录原因并以后避开。
```

## 目录

```text
frontend-taste-library/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    └── catalog.md
```

## 隐私

公开仓库只保留公共网址与可公开的设计观察。本地文件路径、私人反馈和未公开项目不应上传；请将它们保留在自己的本地 catalog 中。

## License

本项目基于 [MIT License](./LICENSE) 开源。

## 当前版本

`v1.0.1`
