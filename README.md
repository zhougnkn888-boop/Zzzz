# Zzzz · 女装运营工具箱

收录可复用的女装运营技能与业务资料。

## 女装热点选题 Skill
覆盖抖音女装、大码女装、直播电商和平台规则变化，将核实后的趋势转成可拍摄选题、分镜与直播承接话术。无实时证据时明确给出常青选题，不编造榜单或规则。

- [技能入口](.agents/skills/womenswear-trend-topics/SKILL.md)
- [使用说明](docs/usage.md)
- [输出模板与示例输入输出](.agents/skills/womenswear-trend-topics/references/output-examples.md)
- [来源与规则核验](.agents/skills/womenswear-trend-topics/references/source-policy.md)
- [现有聚水潭资料](聚水潭)

## 快速开始
在支持仓库技能的 Codex 环境中打开本仓库，调用：

```text
使用 $womenswear-trend-topics，查近7天抖音女装热点，给我5个选题。
主推半身裙，不是大码，不出镜。给开场、分镜、直播承接和来源。
```

技能位于 `.agents/skills/womenswear-trend-topics/`。写入 GitHub 不等于已安装到所有聊天环境；环境未识别时，可明确要求读取该目录的 SKILL.md 后执行。

最新热点和规则需要检索能力；本仓库不包含后台凭据，不自动获取私有账号数据，不自动启动监控或发布。

