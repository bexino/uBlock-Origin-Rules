# uBlock Origin Rules

这是我的个人 **uBlock Origin** 自定义过滤规则库。  
旨在通过深度拦截广告、追踪器、烦人的弹窗。

> [!IMPORTANT]
> - 规则仅基于我个人的浏览习惯定制。

---

## 快速入门

### 反代加速

```
https://fast.bexino.dpdns.org/https://raw.githubusercontent.com/xinggsf/Adblock-Plus-Rule/master/rule.txt
https://fast.bexino.dpdns.org/https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt
https://easylist-downloads.adblockplus.org/easylistchina.txt
https://easylist-downloads.adblockplus.org/easylist.txt
https://easylist-downloads.adblockplus.org/easyprivacy.txt
```

> [!WARNING]
> - 反代加速版使用了我个人的镜像站（cloudflare CDN）。  
> - 如果加速链接失效，请使用以下原始地址。

###  原始地址

```
https://raw.githubusercontent.com/xinggsf/Adblock-Plus-Rule/master/rule.txt
https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt
https://easylist-downloads.adblockplus.org/easylistchina.txt
https://easylist-downloads.adblockplus.org/easylist.txt
https://easylist-downloads.adblockplus.org/easyprivacy.txt
```

---

请按照以下步骤来应用：

1. 打开 uBlock Origin **设置选项**。

2. 切换到 **“过滤器列表” (Filter lists)** 标签页。

3. 滚动到页面底部，勾选 **“导入” (Import)**。

4. 在文本框中粘贴以上 URL。 

5. 点击上方绿色的 **“应用更改” (Apply changes)**。

---

## 规则

本仓库的规则如下：

| **规则库名称**         | **主要功能描述**                         | **侧重领域**               | **适用场景**                                   |
| ---------------------- | ---------------------------------------- | -------------------------- | ---------------------------------------------- |
| **EasyList**           | 全球基础规则库，广告拦截界的行业标准。   | 国际通用静态广告           | **必选**。拦截 90% 以上的全球通用广告插件。    |
| **EasyPrivacy**        | 隐私保护库，专注屏蔽后台统计与用户跟踪。 | 反追踪、个人隐私           | **必选**。防止行为被记录，减少“精准推送”广告。 |
| **EasyList China**     | EasyList 的官方中文补充包。              | 中文网页广告               | **国内用户必选**。针对中文网站环境深度优化。   |
| **乘风规则 (xinggsf)** | 针对国内视频网站与流氓弹窗的加强库。     | **视频广告**、恶意弹窗     | 经常看优爱腾视频、浏览国内资源下载站的用户。   |
| **CJX's Annoyance**    | 消除网页中不影响功能但让人烦心的元素。   | **视觉净化**、App 下载引导 | 讨厌“打开 App 阅读全文”、Cookie 弹窗的用户。   |

---

## 贡献

有更好的规则建议？欢迎提交 Pull Request。
