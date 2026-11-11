# 领航爆品带货 Skill

每个 Skill 对应一个单品，按商品名查找。

| 单品 | 爆品 Skill 作者 | 使用资料 |
|---|---|---|
| 《孩子为你自己读书吧》 | 微辣 | [单品手册](skills/haizi-wei-ni-ziji-dushu-ba/references/playbook.md) · [学员工作单](skills/haizi-wei-ni-ziji-dushu-ba/assets/workbook.md) |

### 第一次安装：复制这一句到 Codex

> 安装领航爆品带货 Skill《孩子为你自己读书吧》

本仓库是腾云猫维护的「领航爆品带货 Skill」库。目前只有《孩子为你自己读书吧》这一款，爆品 Skill 作者：微辣。按仓库中的单品目录安装到个人技能目录即可。

如果 Codex 没找到仓库，把这一句发给它：

> 从 https://github.com/yangtudeputi/tengyunmao-baopin-skills 安装领航爆品带货 Skill《孩子为你自己读书吧》。

### 豆包工作、Kimi 和 WorkBuddy

[下载这一本书的 Skill 安装包（ZIP）](https://raw.githubusercontent.com/yangtudeputi/tengyunmao-baopin-skills/main/downloads/haizi-wei-ni-ziji-dushu-ba.zip)。这是单品包，里面包含 `SKILL.md`、手册、工作单和图片，不用下载整个仓库。以下为平台提供的导入方式，不代表仅发书名就一定能搜到。

- **豆包工作**：在技能管理里使用「导入本地技能文件」；若入口让你选文件夹，先解压，再选含 `SKILL.md` 的目录。[功能介绍](https://www.feishu.cn/content/article/7677519271848610746)
- **Kimi**：把[单品技能链接](https://github.com/yangtudeputi/tengyunmao-baopin-skills/tree/main/skills/haizi-wei-ni-ziji-dushu-ba)发给 Kimi 并要求安装；Kimi Work 桌面端也支持上传 ZIP。[Kimi 技能说明](https://www.kimi.com/features/skills)
- **WorkBuddy 桌面端**：进入「专家·技能·连接器 → 技能 → 添加技能 → 上传技能」，选择上面的单品包。[WorkBuddy 技能说明](https://www.codebuddy.cn/docs/workbuddy/From-Beginner-to-Expert-Guide/Function-Description/Skills-Market)

导入后可直接说：**用《孩子为你自己读书吧》的 Skill，带我做第一条带货视频。**

也可以在终端安装（需 Node.js/npm）：

```sh
npx skills add https://github.com/yangtudeputi/tengyunmao-baopin-skills --skill haizi-wei-ni-ziji-dushu-ba --agent codex --global --copy --yes
```

再次使用时直接说：“用《孩子为你自己读书吧》的 Skill 看看我的开头，这是书页和初稿。”如果当前对话没有发现刚安装的 Skill，新开对话即可。旧版安装名为 weila-book，新版按书名安装；原有作业无需迁移。
