# Frankenstein Admin

[Frankenstein](https://github.com/halohub/frankenstein) 管理后台前端。

[English](./README.md) | **中文**

## 基于

本项目基于 [vue-element-plus-admin](https://github.com/kailong321200875/vue-element-plus-admin) 的 **mini** 分支开发，遵循 MIT 许可证。

| | |
|---|---|
| 上游仓库 | https://github.com/kailong321200875/vue-element-plus-admin |
| 基础分支 | `mini` |
| 上游 README | [README.origin.md](./README.origin.md) |

在模板基础上，对接 Frankenstein 后端（`/admin/api_v1`）、登录鉴权、动态菜单与 RBAC 等能力。

## 技术栈

Vue 3、Vite、TypeScript、Element Plus、Pinia、Vue Router。

## 环境要求

- Node.js >= 18
- pnpm >= 8.1

## 本地开发

后端默认 `http://localhost:9001`。先启动 [Frankenstein](https://github.com/halohub/frankenstein) 后端，再执行：

```bash
pnpm install
pnpm dev
```

前端开发地址：`http://localhost:5173`（Vite 默认）。

在 `.env.base` 中配置接口地址：

```env
VITE_API_BASE_PATH=http://localhost:9001
VITE_USE_MOCK=false
```

## 构建

```bash
pnpm build:pro
```

## 许可证

[MIT](./LICENSE) — 保留 vue-element-plus-admin 版权声明。
