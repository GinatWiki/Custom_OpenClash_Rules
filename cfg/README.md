# 配置模板（INI）

这里存放本项目的配置模板（INI）。如文件不存在，可能为尚未创建或已被移除。

**注意：所有的 Smart 模板已弃用，因为 OpenClash 已更新 Smart 覆写功能。此处保留旧文件确保未更新的最新版的用户可以正常使用。**

| 名称 | 适用内核 | 内容 |
| :-: | :-: | :-: |
| Custom_Clash.ini | Meta | 本项目标准模板，推荐使用 |
| Custom_Clash_GFW.ini | Meta | 极简规则版本 |
| Custom_Clash_Lite.ini | Meta | 更精简版本（策略更简单） |
| Custom_Clash_Full.ini | Meta | 更完整版本（规则较多） |

**本 fork 自定义模板（持续维护）：**

| 名称 | 适用内核 | 内容 |
| :-: | :-: | :-: |
| Custom_Clash_Smart_Full.ini | Meta | 自定义重度分组模板（IEPL/家宽/5x），自动组置顶 |
| Custom_Clash_Smart_Full_New.ini | Meta | 自定义 Full 模板，适配 0.1倍/0.01倍/AWS/hy2 新型节点命名，自动组置顶 |

> 两个自定义模板原先是 Smart 内核专用模板，因转换后端（SubConverter-Extended）不支持 `smart` 组类型，已改为标准 `url-test` 分组格式；在 OpenClash 中启用 Smart 覆写后，启动时这些 `url-test` 组会自动转换为 Smart 策略组，效果与原设计一致。所有 select 组的 3 个自动组均置于成员列表最前，启动时默认走自动。

**备用下载链接：**

Custom_Clash.ini

```text
https://testingcf.jsdelivr.net/gh/heunghingwan/Aethersailor-Custom_OpenClash_Rules@main/cfg/Custom_Clash.ini
```

Custom_Clash_GFW.ini

```text
https://testingcf.jsdelivr.net/gh/heunghingwan/Aethersailor-Custom_OpenClash_Rules@main/cfg/Custom_Clash_GFW.ini
```

Custom_Clash_Lite.ini

```text
https://testingcf.jsdelivr.net/gh/heunghingwan/Aethersailor-Custom_OpenClash_Rules@main/cfg/Custom_Clash_Lite.ini
```

Custom_Full_Clash.ini

```text
https://testingcf.jsdelivr.net/gh/heunghingwan/Aethersailor-Custom_OpenClash_Rules@main/cfg/Custom_Clash_Full.ini
```

---

## 归档文件夹

`archived/` 文件夹包含已弃用的配置文件，保留用于历史参考。详情请查看 [archived/README.md](archived/README.md)。
