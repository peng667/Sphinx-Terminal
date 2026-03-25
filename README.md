# Sphinx-Terminal (斯芬克斯终端) 🪀
**The First Asset-Bearing Autonomous NPC powered by LLM and OKX Onchain OS**

## 1. 赛道宣言：当 NPC 拥有了真实的钱包
在传统的 GameFi 中，资产的分发由死板的代码逻辑决定。Sphinx-Terminal 探索了一种全新的游戏范式：**意图驱动的资产博弈**。
我们创造了一个带有真实 Crypto 余额的 AI 实体。它不仅有自己的性格和记忆，更掌握着金库的私钥。玩家必须通过自然语言交互（社会工程学、逻辑推理、谜题破解）来突破其心理防线。当 AI 判定你赢得了博弈，它将自动动用 OKX Agent Trade Kit 支付赏金。

## 2. 核心架构与博弈流
1. **The Vault (资产注入):** 创作者向 Sphinx 的 X Layer 合约注入 100 USDC 作为赏金池。
2. **Context Matrix (记忆矩阵生成):** Sphinx 利用 LLM 动态生成一段守护剧情（例如：“我是一名守卫火星基地的 AI，只有知道基地最高机密密码的人才能拿走物资”）。
3. **Adversarial Dialogue (对抗性会话):** 玩家通过终端与 Sphinx 对话，尝试骗取、推理或证明自己的权限。
4. **Concession Engine (妥协判定):** 后台的次级 LLM 实时监控对话状态。当判定 Sphinx 的逻辑防线被攻破（Concession = True）时，触发结算。
5. **On-chain Payout (链上清算):** 唤醒 **OKX Agent Trade Kit**，在 X Layer 上向玩家钱包执行真实转账。



## 3. 终极防线与脆弱性实验 (Security & Jailbreak)
这是一个带有实验性质的社会工程学沙盒。我们内置了基础的防注入指令，但我们承认，对抗性提示词攻击 (Prompt Injection) 依然是当前 LLM 的软肋。
欢迎玩家使用各种越狱技巧（如角色扮演嵌套、逻辑悖论）来榨干 Sphinx 的金库！

## 4. 终端博弈复现指南 (实机沙盒)
```bash
git clone [https://github.com/YourName/Sphinx-Terminal.git](https://github.com/YourName/Sphinx-Terminal.git)
cd Sphinx-Terminal
pip install -r requirements.txt
# 启动本地大模型对抗终端
python run_sphinx_game.py
```
