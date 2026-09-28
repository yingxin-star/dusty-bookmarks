# Steam 手机确认与账户安全设置

> 内容类型：操作说明  
> 最近核对：2026-09-28  
> 适用场景：Steam 交易报价、CS2 箱子市场上架与登录确认

Steam 交易报价和市场上架有最终确认步骤。启用 Steam 手机令牌后，确认请求会进入官方 Steam Mobile 应用；网络加速器只帮助应用连接，不代替 Steam 确认，也不能解除交易限制。[Steam 官方：交易与市场确认](https://help.steampowered.com/zh-cn/faqs/view/2E6E-A02C-5581-8904)

![倒余额交易和 Steam 手机确认流程示意图](diagram/Steam倒余额操作流程@2x.png)

## 一、客户端下载地址

请通过下表中的官方商店、产品官网或开发者仓库下载。不要从搜索广告、网盘或陌生人发来的安装包获取客户端。

| 用途 | 官方下载入口 | 说明 |
| --- | --- | --- |
| Steam Mobile（iPhone/iPad） | [Apple App Store](https://apps.apple.com/app/steam-mobile/id495369748) | 开发者应显示 Valve；应用内含 Steam Guard、交易与市场确认 |
| Steam Mobile（Android） | [Google Play](https://play.google.com/store/apps/details?id=com.valvesoftware.android.steam.community) | 开发者应显示 Valve；若设备不能使用 Google Play，可从 [Steam 官方移动应用页面](https://store.steampowered.com/mobile)查看官方 Android 下载入口 |
| 小黑盒加速器（手机端） | [小黑盒加速器官网](https://acc.xiaoheihe.cn/)；[App Store 页面](https://apps.apple.com/sc/app/%E5%B0%8F%E9%BB%91%E7%9B%92%E5%8A%A0%E9%80%9F%E5%99%A8/id1450920208) | 官网提供 Android/iOS 客户端入口；应用商店页面说明支持 Steam。仅在 Steam 手机应用连接不畅时按需启用 |
| Steam++ / Watt Toolkit（PC） | [开发者 GitHub 仓库](https://github.com/BeyondDimension/SteamTools)；[GitHub Releases](https://github.com/BeyondDimension/SteamTools/releases) | 项目现名 Watt Toolkit，原名 Steam++；仓库列出的其他入口可从 README 进入 |

Steam Mobile 与加速器是两个不同应用：Steam Mobile 是 Valve 官方的令牌和确认工具；小黑盒加速器、Watt Toolkit 是第三方网络工具。Steam++ 项目仓库注明其现名 Watt Toolkit，并提供 GitHub 发行版下载。[Watt Toolkit 项目说明](https://github.com/BeyondDimension/SteamTools)

### 按设备选择网络连接方式

- **手机上使用 Steam Mobile：**如果 Steam 页面或确认请求加载困难，可以从小黑盒加速器官网或官方应用商店安装手机端客户端，在客户端内查找 Steam 并按界面提示启动加速。加速器不用 Steam 密码，也不需要读取手机令牌。
- **电脑上使用 Steam：**从 Watt Toolkit 的开发者 GitHub 仓库或 Releases 获取安装包，打开加速服务，选择 Steam 及需要的社区、市场等服务，再按当前版本提示启动。界面名称可能随版本变化；加速器需运行才能保持其网络处理生效。
- **加速器不是交易前置条件。**如果 Steam 本身可以正常连接，不必为了交易额外安装加速器；加速也不会缩短物品限制、市场暂挂或账户冷却时间。

## 二、设置 Steam Guard 手机令牌

1. 安装并打开官方 Steam Mobile，用自己的 Steam 账号登录。
2. 进入底部导航中的盾牌图标（Steam Guard），选择“添加验证器 / Add Authenticator”。界面文字可能会随应用语言和版本略有不同。
3. 按提示绑定可接收短信的手机号码并输入短信验证码。若页面提供无手机号的替代流程，可按 Steam 官方指引继续。
4. 设置成功后，记下 Steam 显示的**恢复码 / Recovery Code**，离线保存在安全位置。不要把恢复码截图发给他人或放在公开网盘。
5. 确认 Steam Guard 页面能显示动态安全码，并熟悉 Steam 手机端的确认入口。

Steam 官方设置指南列出的流程也是登录 Steam Mobile、添加验证器、验证手机号码并保存恢复码；丢失手机或令牌时，恢复码可用于账号恢复。[Steam 官方：设置手机令牌](https://help.steampowered.com/zh-cn/faqs/view/6891-E071-C9D9-0134) Steam 安全码会定期更新；不要向任何人透露当前码。[Steam 官方：Steam Guard 手机令牌常见问题](https://help.steampowered.com/zh-cn/faqs/view/7EFD-3CAE-64D3-1C31)

## 三、确认交易报价和市场上架

在悠悠有品购买箱子并通过 Steam 交易收货，或从 Steam 库存创建市场出售单后，按需要完成 Steam 的确认步骤：

1. 打开 Steam Mobile，进入“Steam Guard / 确认”页面，查看待处理请求。不同版本可能把“确认”放在 Steam Guard 页面内或其子菜单中。
2. 对于**交易报价**，核对交易对象、你送出的物品、你收到的物品和数量；若页面显示交易内容与你预期不同，取消请求。
3. 对于**市场上架**，核对箱子名称、出售数量、你填写的价格，以及 Steam 预计到账金额。
4. 只有请求确实由你刚才的操作产生、信息完全一致时才批准。若收到自己没有发起的请求，拒绝它，并按[Steam 官方账号安全建议](https://help.steampowered.com/zh-cn/faqs/view/6639-EB3C-EC79-FF60)检查账号和邮箱安全。

Steam 官方说明，发送或接受交易报价、创建市场上架都需要通过手机应用或电子邮件确认；未确认的交易不会完成，市场物品也不会上架。使用手机令牌保护账号时，确认会自动发送到 Steam Mobile。[Steam 官方：交易与市场确认](https://help.steampowered.com/zh-cn/faqs/view/2E6E-A02C-5581-8904)

## 四、交易限制中的两种“7 天”

不要把以下两个规则混为一谈：

1. **手机令牌的账号级规则：**手机令牌启用未满 7 天时创建的交易或市场上架，Steam 可能暂挂最多 15 天；已经产生的暂挂不会因后来启用令牌而缩短。令牌移除后，Steam 也会对市场和交易施加限制。[Steam 官方：交易与市场暂挂](https://help.steampowered.com/zh-cn/faqs/view/34A1-EA3F-83ED-54AB)
2. **CS2 物品的物品级规则：**通过交易等方式收到的 CS2 物品有 7 天 Trade Protected 保护期，保护期内不能再次转移或重新上架，且交易可能被撤销。它与手机令牌是否启用是不同规则，详见[Steam 官方 Trade Protected 说明](https://help.steampowered.com/zh-cn/faqs/view/365F-4BEE-2AE2-7BDD)。

因此，刚设置令牌的新账号即使已经完成手机确认，也可能碰到账户暂挂；已经收进库存的 CS2 物品也可能仍在 Trade Protected 期内。分别查看 Steam 的交易状态和库存物品提示，不要仅凭“手机上已确认”推断物品马上可以再次交易或出售。

## 五、账户安全检查清单

- Steam Mobile 只从 App Store、Google Play 或 Steam 官方页面安装；Watt Toolkit 只从项目仓库链接的发布渠道获取。
- 为 Steam 和绑定邮箱设置独立密码，并开启邮箱本身的双重验证；Steam 官方建议先验证联系邮箱并使用 Steam Guard。[Steam 官方：账号安全建议](https://help.steampowered.com/zh-cn/faqs/view/6639-EB3C-EC79-FF60)
- 在 Steam Mobile 或账号安全页面检查已授权设备，撤销自己不认识的登录设备。
- 不把密码、动态安全码、短信码、恢复码或手机确认交给悠悠有品卖家、加速器客服、第三方生成器或所谓 Steam 客服。Steam Support 不会索要 Steam Guard 验证码。
- 登录和确认前检查域名；Steam 登录只在 `steampowered.com`、`steamcommunity.com` 等 Valve 官方域名内完成。Steam Bulk Sell 自述只读取公开库存、不需要密码或令牌，并会在浏览器本地保存个人资料标识；这不是独立审计结论。我无法保证其安全，对网站有顾虑时不要使用，可直接在 Steam 库存逐件出售。[网站公开说明](https://steambulksell.com/guides/public-inventory.html)
- 换手机时优先使用 Steam Mobile 的“转移验证器 / Move Authenticator”流程，不要贸然移除令牌。Steam 官方说明，令牌移除后市场与交易可能受限 15 天；通过转移流程恢复时也可能有短期交易限制。[Steam 官方：手机令牌常见问题](https://help.steampowered.com/zh-cn/faqs/view/7EFD-3CAE-64D3-1C31)

## 官方说明链接

- [Steam Mobile 官方下载页](https://store.steampowered.com/mobile)
- [Steam Guard：设置手机令牌](https://help.steampowered.com/zh-cn/faqs/view/6891-E071-C9D9-0134)
- [Steam Guard 手机令牌常见问题](https://help.steampowered.com/zh-cn/faqs/view/7EFD-3CAE-64D3-1C31)
- [Steam 交易与市场确认](https://help.steampowered.com/zh-cn/faqs/view/2E6E-A02C-5581-8904)
- [Steam 交易与市场暂挂](https://help.steampowered.com/zh-cn/faqs/view/34A1-EA3F-83ED-54AB)
- [Steam 账号安全建议](https://help.steampowered.com/zh-cn/faqs/view/6639-EB3C-EC79-FF60)
