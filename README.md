# anti-defensive-writing

> 学术写作反防御性写作 Skill —— 适配华为云码道（CodeArts）二开版

## 这是什么

一个纯方法论指导 Skill，用于在论文写作、修改、压缩和实验组织全流程中阻止**防御性写作**。

核心原则：**论文是一场学术发布会，不是项目总结、实验日志或自我审查报告。**
你的任务不是平均呈现这项工作的所有方面，而是识别其中最值得发表的价值，
并围绕这一价值建立最有利、最完整、最有说服力的叙事。

## 适用场景

- 论文润色与修改
- 写摘要、引言、结论
- 压缩论文篇幅
- 准备 rebuttal
- 识别并消除防御性写作
- 实验结果不理想时如何组织叙事

## 在华为云码道（CodeArts）中安装

### 方式一：上传到华为云技能市场

将本仓库打包为 zip（`SKILL.md` 必须在根目录），通过 `uploadUserSkillToHuawei` 工具上传：

```
uploadUserSkillToHuawei(
  skillName="anti-defensive-writing",
  skillFilePath="<zip 路径>",
  scene="通用场景",
  category="学习成长"
)
```

上传后在 `skills.huaweicloud.com/community` 公开市场可检索。

### 方式二：直接复制提示词

将 `SKILL.md` 正文内容粘贴到任何 AI 编码助手的对话上下文中，作为方法论指导使用。
本 Skill 无运行时依赖，不依赖 slash commands、hooks 或 subagent 编排，任何 AI 助手通用。

## Skill 内容概览

| 章节 | 作用 |
|------|------|
| 一句话原则 | 确立"学术发布会"而非"项目总结"的叙事定位 |
| 一、叙事规则 | 只围绕优势组织论文，6 条规则 |
| 二、语言规则 | 防自我削弱，禁用"遗憾的是""效果有限"等表达 |
| 三、实验规则 | 实验作为论证工具而非结果仓库，4 项职责 |
| 四、结构规则 | 摘要引言=发布会开场，结论只强化记忆点 |
| 五、默认决策规则 | 遇不理想材料时按 7 级优先级处理 |
| 六、交稿前自查 | 8 项自查问题，不给审稿人递刀子 |

## 触发词

论文润色、论文修改、写摘要、写引言、写结论、压缩论文、rebuttal、防御性写作、心虚

## 出处

基于 [Adkid-Zephyr/anti-defensive-writing-Skill](https://github.com/Adkid-Zephyr/anti-defensive-writing-Skill) 二开，适配华为云码道（CodeArts）Skill 格式。