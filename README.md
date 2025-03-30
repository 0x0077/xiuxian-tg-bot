# 修仙 Telegram Bot 🔮

一款基于中国神话世界观的修仙题材 Telegram 小游戏机器人。玩家可通过修炼、探索和渡劫，不断提升境界，踏上飞升之路。

## 游戏特色 ✨

- 丰富的修仙境界系统
- 多样化的修炼方式
- 独特的装备系统
- 探索副本玩法
- 采集与制造系统
- 排行榜竞技

## 境界体系 🌟

游戏设有九大境界，依次为：

1. 练气期
2. 筑基期
3. 金丹期
4. 元婴期
5. 化神期
6. 炼虚期
7. 合体期
8. 大乘期
9. 渡劫期

每个境界都需要积累足够的经验值才能突破。突破后会提升灵力上限，增强战斗能力。

## 主要功能 🎮

### 基础修炼
- `/dazuo` - 打坐修炼，获取经验和恢复灵力
- `/status` - 查看当前状态
- `/xiuxian` - 查看修仙指南

### 探索采集
- `/caiyao` - 采集药材
- `/mine` - 矿洞采矿
- `/beibao` - 查看背包物品

### 装备系统
- `/wuqi` - 访问铁匠铺
- `/maiwuqi` - 购买武器
- `/zhuangbei` - 装备武器
- `/qianghua` - 强化武器
- `/check_weapon` - 查看武器属性

### 副本挑战
- `/elsevier` - 挑战爱思唯尔秘境，包含多个难度的关卡

### 商店系统
- `/zahuo` - 访问杂货铺，购买各类物品

### 排行系统
- `/paihang` - 查看修仙者排行榜

## 游戏特色地图 🗺️

### 采药地点
- 凡人村落 (练气期)
- 初级灵药园 (筑基期)
- 中级灵药园 (金丹期)
- 高级灵药园 (元婴期)
- 仙药园 (化神期)
- 荒古禁地 (合体期)
- 仙域秘境 (大乘期)

### 矿洞系统
- 浅层矿洞 (练气期)
- 中层矿洞 (筑基期)
- 深层矿洞 (金丹期)
- 地心矿洞 (元婴期)
- 神秘矿洞 (化神期)
- 荒古矿脉 (合体期)
- 仙域矿境 (大乘期)

### 爱思唯尔秘境
- 道经殿
- 源天长廊
- 帝经密室
- 神王殿
- 太古圣殿

## 物品系统 💎

### 武器类型
- 剑类：天青木剑、紫电剑、龙纹剑等
- 刀类：炎阳刀、青虹刀等
- 枪类：寒冰枪、天罡枪、寒魄枪等
- 其他：裂山斧、星陨锤、破天锤等

### 材料收集
- 药材：普通药草、灵气草、仙药等
- 矿石：灵石、神品灵石、混沌神金等

## 游戏机制 ⚙️

- 每次打坐有60秒冷却时间
- 采药有180秒冷却时间
- 采矿有120秒冷却时间
- 副本挑战有600秒冷却时间
- 突破境界会恢复满灵力并提升灵力上限
- 装备武器可以提升攻击力
- 不同境界开启不同的地图和功能

## 开发技术 🛠️

- Python
- Telegram Bot API
- Supabase 数据库
- 异步处理机制

## 安装与部署 📦

1. 克隆仓库
```bash
git clone https://github.com/yourusername/xiuxian-tg-bot.git
cd xiuxian-tg-bot
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 配置环境变量
```bash
export TELEGRAM_BOT_TOKEN="your_bot_token"
export SUPABASE_URL="your_supabase_url"
export SUPABASE_KEY="your_supabase_key"
```

4. 运行机器人
```bash
python main.py
```

## 贡献指南 🤝

欢迎提交 Issue 和 Pull Request 来帮助改进游戏。

## 许可证 📄

MIT License
