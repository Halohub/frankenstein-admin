# Frankenstein Admin

Admin frontend for [Frankenstein](https://github.com/halohub/frankenstein).

**English** | [中文](./README.zh-CN.md)

## Based on

This project is derived from [vue-element-plus-admin](https://github.com/kailong321200875/vue-element-plus-admin) (**mini** branch), MIT License.

| | |
|---|---|
| Upstream | https://github.com/kailong321200875/vue-element-plus-admin |
| Base branch | `mini` |
| Upstream README | [README.origin.md](./README.origin.md) |

Customizations include integration with the Frankenstein backend (`/admin/api_v1`), auth, dynamic menus, and RBAC pages.

## Tech stack

Vue 3, Vite, TypeScript, Element Plus, Pinia, Vue Router.

## Prerequisites

- Node.js >= 18
- pnpm >= 8.1

## Development

Backend API runs at `http://localhost:9001` by default. Start the [Frankenstein](https://github.com/halohub/frankenstein) backend first, then:

```bash
pnpm install
pnpm dev
```

Frontend dev server: `http://localhost:5173` (Vite default).

Configure API base URL in `.env.base`:

```env
VITE_API_BASE_PATH=http://localhost:9001
VITE_USE_MOCK=false
```

## Build

```bash
pnpm build:pro
```

## License

[MIT](./LICENSE) — includes copyright notice for vue-element-plus-admin.
