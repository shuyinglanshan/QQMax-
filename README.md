# QQMax增强模块
适用于QQ Max_M2.5版本的增强模块，包含临时会话、QQ动态、自动回复、定时消息、防撤回、发送文件、HTTP服务、原生功能修复、QQ邮箱和插件系统等功能，旨在拓展手表QQ的功能，为用户带来更好的使用体验

## 📖 模块使用教程
支持环境：**LSPosed / EdXposed / LSPatch**

### ✅ 已Root设备
#### 方案一：LSPosed（推荐）
1. Magisk 开启 Zygisk，刷入 `LSPosed‑Zygisk.zip`，重启设备
2. 安装本模块APK，打开 LSPosed 管理器
3. 在模块列表找到「QQMax增强模块」，勾选作用域：**QQMax**，保存设置
4. 完全关闭并重启 QQMax，模块即可生效

> 备选(LSP‑Riru)：使用Riru版本LSPosed，**不需要开启Zygisk**，其余操作一致。

#### 方案二：EdXposed（旧方案，不推荐）
> ⚠️ EdXposed已经停止维护，仅适合老旧ROM
1. Magisk模块刷入 `Riru.zip`，重启
2. 再刷入 `EdXposed.zip`，重启
3. 安装 EdXposed Manager
4. 安装本模块APK，管理器内勾选目标应用 QQMax
5. 重启手机完成生效

---

### ✅ 无Root设备｜LSPatch
> ⚠️ 注意：修补后**必须卸载原版QQMax**，不能共存
1. 安装 LSPatch Manager
2. 新建修补任务，选择原版 QQMax APK，注入模式选择【嵌入】
3. 导入并勾选本增强模块
4. 执行修补；修补完成，卸载设备上原来的QQMax，安装修补后的APK
5. 直接启动修补版QQMax，模块自动生效
