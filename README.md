# Architectural Shadow Study

一个用于 Codex 的建筑图片风格转换 Skill：把建筑照片、SketchUp 模型截图或效果图转成极简、高反差的“只看影子”建筑研究图。

## 它能做什么

- 保留原始构图、相机透视和建筑体量
- 去除材质、颜色、天空与环境噪声
- 将受光面压到纸白，将背光面和投影压成深炭灰
- 保留拱券、百叶、柱网、悬挑、连桥等几何节奏
- 检查建筑身份，避免随意增删楼层、开口或构件
- 提供 SketchUp 单色阴影出图流程

它不是普通黑白滤镜，也不是漫画线稿。目标是得到适合建筑作品集、体量分析和阴影研究的图像。

## 安装

将仓库克隆或下载到 Codex skills 目录：

```bash
git clone https://github.com/5Yuechang/architectural-shadow-study.git ~/.codex/skills/architectural-shadow-study
```

重新打开 Codex 对话后即可调用。

## 使用

```text
$architectural-shadow-study 把这张建筑图转成只看影子风格，保持原构图和建筑结构。
```

也可以直接描述需求：

```text
把这张 SketchUp 模型截图做成极简建筑阴影研究图，保留百叶、连桥和楼层关系。
```

## 适用场景

- 建筑图片风格转换
- 建筑阴影分析
- SketchUp 单色阴影出图
- 建筑作品集表达
- 黑白体量研究
- AI 建筑表现

## 隐私与素材

仓库不包含第三方参考图片。使用时请上传你有权处理的目标图片；用户提供的风格参考优先于 Skill 的默认视觉规范。

## 文件结构

```text
architectural-shadow-study/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    └── workflow.md
```

