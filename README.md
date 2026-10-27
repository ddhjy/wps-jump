# wps-jump

https 链接 → WPS 协作 `ksoxz://` 深链的跳转页。

- 单聊：`?t=user&id=<WPS 用户 ID>` → `ksoxz://xz.wps.cn/chat?user_id=<id>`
- 群聊/会话：`?t=chat&id=<chat_id>` → `ksoxz://xz.wps.cn/chat?chat_id=<id>`
- 原始深链：`?u=<URL 编码的 ksoxz 链接>`，只放行 `ksoxz://xz.wps.cn/chat` 与 `/open`
- 无参数：链接生成器

协议来源：[WPS 协作 Deeplink 协议](https://open.wps.cn/documents/app-integration-dev/wps365/client/deeplink)
