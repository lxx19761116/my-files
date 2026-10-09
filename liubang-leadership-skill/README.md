# 刘邦·用人破局 Skill

把刘邦式的识人、授权、分利与资源整合转化为可执行建议。版本：0.1.2。

## 两种模式

| Skill | 作用 | 调用示例 |
|---|---|---|
| liubang-leadership | 现代团队分工、授权与资源整合 | 刘邦，帮我排兵布阵。 |
| liubang-skill | 基于历史资料的刘邦视角模拟顾问 | 用刘邦的视角帮我分析这个团队。 |

## 安装

对支持 Skill 安装的助手说：

> 帮我安装这个仓库中的刘邦两个 Skill：https://github.com/lxx19761116/my-files/tree/main/liubang-leadership-skill/skills

使用 Codex 自带的 skill-installer 时，指定仓库 `lxx19761116/my-files`，并传入两个路径：

```text
liubang-leadership-skill/skills/liubang-leadership
liubang-leadership-skill/skills/liubang-skill
```

也可以将 `skills/` 下两个目录完整复制到所用助手的 skills 目录，保留各自的 references。已有同名 Skill 时先比较版本，避免直接覆盖。

## 文件结构

```text
liubang-leadership-skill/
  plugin.json
  .codex-plugin/plugin.json
  README.md
  SOURCE.md
  NOTICE.md
  skills/
    liubang-leadership/
      SKILL.md
      references/person-task-matrix.md
    liubang-skill/
      SKILL.md
      references/framework.md
      references/research/01-06-*.md
  source/liubang-skill/
    LICENSE
    README.md
    tests/
```

## 使用

- 刘邦，这件事我该自己做还是授权？
- 刘邦，我资源不够，怎么借力破局？
- 用刘邦的视角，帮我判断这个人适合什么岗位。
- 退出角色，切回正常模式。

现代分工模式输出目标、瓶颈、负责人、权限、验收标准及下一步动作。历史视角模式使用模拟表达，并区分史料、现代概括和推断。

## 来源与验证

历史视角材料来自 [eiDear/liubang-skill](https://github.com/eiDear/liubang-skill)，固定提交见 SOURCE.md，原 MIT 许可保留在 source/liubang-skill/LICENSE。

本次完成文件结构、frontmatter、JSON 元数据、版本和引用文件检查。source 中的测试记录为上游资料，不代表本次重新执行了历史准确性或模型行为测试。历史材料保留上游内容，引用前仍需核对出处。

## 0.1.2 更新

- 将本机已有的两种刘邦模式与研究资料同步封装到 GitHub。
- 补齐 Codex 插件清单、安装路径、来源和许可证说明。
- 保留原有运行边界与角色退出规则。
