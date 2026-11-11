# Dragoon — RU Closed Beta

本仓库用于 Dragoon 俄军版本的私有内测分发和问题反馈。

## 下载与安装

1. 接受仓库邀请，并登录受邀的 GitHub 账号。
2. 打开本仓库的 **Releases**，下载 `Dragoon_RU_Beta_20261111_Full.zip`。GitHub 自动生成的 `Source code` ZIP 不包含完整 MOD。
3. 正常退出 Company of Heroes 2。
4. 将整包中的 `mods` 文件夹合并到自己的“文档/My Games/Company of Heroes 2”目录。
5. 如有旧版 Dragoon/Purple Dragon，先移出该 MOD 的旧副本，取消退役资源分卷订阅，避免相同身份的版本冲突。

安装完成后应有三个文件：

```text
mods/tuning/Dragoon.sga
mods/assets/Dragoon_Assets.sga
mods/gamemode/Dragoon_Commanders.sga
```

建立自定义对局时，调校选择 **Dragoon | RU Beta**，胜利条件选择 **Dragoon Commanders - Victory Points** 或 **Dragoon Commanders - Annihilation**。俄军使用原版苏军阵营入口。

## 测试范围

这是 2026-11-11 的完整 RU 内测快照；CH 内容未并入。本次发布沿用现有整包，没有重新压缩模型、贴图或动画。

三个 SGA 的 ZIP CRC 和 SHA-256 已核对；SGA 内容与此前通过原生校验的完整三包一致。这些属于文件校验，测试员电脑上的安装、显示和玩法仍需实机验证。

已知未完成项沿用整包说明：2B9 Vasilek、自选指挥官与原生头像/五格教义栏动态绑定，以及本轮部分 UI 修后显示。

遇到问题，请在 Issues 中写明地图、阵营、单位、操作步骤，并附截图或报错；闪退请说明发生在加载、部署前还是对局中。

## 分发状态

当前为私有内测。获得仓库链接不等于获得访问权限，测试员须先接受邀请。

完整成品作为 Release 附件分发，不放进 Git 历史。本仓库目前提供安装说明、校验记录和反馈入口；尚未导入完整工程源码，也未添加公开开源许可证。
