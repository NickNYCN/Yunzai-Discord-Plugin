# TRSS-Yunzai Discord Plugin

TRSS-Yunzai Discord Bot 适配器 插件

## 安装教程

1. 准备：[TRSS-Yunzai](../../../Yunzai)
2. 复制粘贴以下代码：
```
cd plugins
git clone https://github.com/NickNYCN/Yunzai-Discord-Plugin
cd ..
pnpm install
```
3. 打开：[Discord Developer Portal](https://discord.com/developers) 创建 Bot：  
① New Application  
② Bot → Privileged Gateway Intents → 全部开启  
③ Bot → Reset Token → 得到 `Token`  
④ OAuth2 → URL Generator → SCOPES 选择 `bot` → BOT PERMISSIONS 选择 `Administrator` → 打开 GENERATED URL → 邀请 Bot 进入服务器  
4. 输入：`#DC设置Token`

## 使用教程

- #DC账号
- #DC设置 + `Token`
- #DC代理/反代 + `scheme://[userinfo@]host[:port]`
