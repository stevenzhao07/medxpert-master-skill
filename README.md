# MedXpert Master Skill

> 医疗器械全生命周期总入口 · 只装这一个，就能用到全部11个Skill的能力

---

## 🧰 MedXpert Full Lifecycle Skill Series

这是 **MedXpert 医疗器械全生命周期Skill系列** 的总入口路由器。

**同一个体系：LGD（有籍有证有门禁）· 同一个团队：MedXpert · 同一个风格：纯开源MIT协议**

---

## 这是什么？

你不需要装11个Skill——只需要装这一个Master Skill。

它就像一个路由器：你问任何医疗器械相关的问题，它自动判断该用哪个子Skill来回答。

---

## 路由表

| 你问什么 | 它自动调用 |
|---------|-----------|
| 这个产品走哪条注册路径？ | → 路径决策Skill |
| 提交前帮我自查一遍 | → 申报前自查Skill |
| 发补信怎么回？ | → 发补回复Skill |
| 临床评价怎么做？ | → 临床评价Skill |
| AI/SaMD怎么分类？ | → 医疗AI专用Skill |
| 标签/说明书(IFU)怎么写？ | → 标签说明书Skill |
| 风险管理报告怎么写？ | → 风险管理Skill |
| 第三方检测怎么选？ | → 检测机构选择Skill |
| 找代工厂要注意什么？ | → 委托生产Skill |
| 医院进院怎么进？ | → 医院招投标Skill |
| 不良事件怎么报？ | → 上市后监督Skill |

---

## 安装

```bash
npx skills add https://github.com/stevenzhao07/medxpert-master-skill
```

安装后直接说：

```text
我的骨科产品想做FDA注册，帮我看看
```

Master Skill会自动判断：这个问题应该用路径决策Skill来回答。

---

> ⚠️ **免责声明**：本Skill仅供AI Agent辅助路由，不构成合规意见。
>
> 📄 MIT 协议开源。
