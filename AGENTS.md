# pc-parts-price-tracker

PC 装机配件全网比价看板：抓取京东 / 淘宝 / 拼多多 / 闲鱼的硬件价格，输出价格趋势看板与各品类最低价 Top10 店铺信息。

## Agent skills

### Issue tracker

需求与 spec 以 GitHub Issues 形式存放于 `875778261/pc-parts-price-tracker`，通过 `gh` CLI 读写。详见 `docs/agents/issue-tracker.md`。

### Triage labels

五个规范 triage 角色，与标签名 1:1 对应：`needs-triage`、`needs-info`、`ready-for-agent`、`ready-for-human`、`wontfix`。详见 `docs/agents/triage-labels.md`。

### Domain docs

单上下文（single-context）：仓库根 `GLOSSARY.md` + `docs/adr/`。详见 `docs/agents/domain.md`。
