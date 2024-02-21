**vue3_TS_cli 介绍**

`vue3_Ts_cli` 是一个基于 Vue 3 的脚手架工具，旨在提供快速、高效的开发环境和构建工具。通过整合 Vite、Vue 3、Vue Router 等技术栈，使得开发者能够更便捷地进行 Vue 3 项目的开发、构建和测试。

该脚手架具备以下特点和功能：

- **开发环境启动与项目构建：** 使用 Vite 进行本地开发，通过命令快速启动开发服务器；同时，利用 Vite 进行项目构建，生成生产环境所需的文件。
- **项目预览与单元测试：** 提供了项目构建预览命令，方便开发者查看构建结果。单元测试方面使用 Vitest 进行测试，保证代码质量。
- **代码格式化与检查：** 集成 Prettier 进行代码格式化，通过 eslint 进行代码检查与修复，确保代码整洁规范。
- **提交规范与 Git 钩子：** 使用 Commitizen 进行规范的提交，通过 Husky 管理 Git 钩子，维护代码提交的一致性。
- **依赖和开发依赖管理：** 提供清晰的依赖管理，方便开发者管理项目所需的依赖和开发依赖。
- **代码风格与配置：** 使用 eslint-plugin-prettier、@vue/eslint-config-prettier、@vue/eslint-config-typescript 等进行代码风格配置，保证项目的一致性。
- **Commitizen 配置：** 提供了 Commitizen 的配置文件，方便规范的提交消息。

此外，项目结构清晰，拓展性强，为 Vue 3 项目的开发提供了一套完善的工具链。

**1. 开发环境启动：**

- 使用 `vite` 命令进行本地开发

```
npm run dev
```

**2. 项目构建：**

- 利用 `vite` 进行项目构建

```
npm run build
```

**3. 预览构建结果：**

- 使用 `vite` 进行项目构建并预览

```
npm run preview
```

**4. 单元测试：**

- 运行单元测试

```
npm run test:unit
```

**5. 代码格式化：**

- 使用 `prettier` 进行代码格式化

```
npm run prettier
```

**6. 代码检查与修复：**

- 使用 `eslint` 对 `.vue`, `.js`, `.jsx`, `.cjs`, `.mjs` 文件进行检查与修复

```
npm run lint
```

**7. 提交规范：**

- 使用 `commitizen` 进行规范化的提交

```
npm run commit
```

**8. 依赖管理：**管理项目依赖，如 `pinia`, `vue`, `vue-router` 等

**9. 开发依赖管理：**管理开发时依赖，如 `@commitlint/cli`, `@commitlint/config-conventional`, `@vitejs/plugin-vue` 等

**10. 单元测试工具：** 使用 `vitest` 进行单元测试 `bash npm test`

**11. 代码风格：** 使用 `eslint-plugin-prettier`, `@vue/eslint-config-prettier`, `@vue/eslint-config-typescript` 等进行代码风格配置

**12. Git 钩子：** 使用 `husky` 进行 Git 钩子管理

**13. Commitizen 配置：** 使用 `cz-conventional-changelog` 进行规范的 Commitizen 配置

**14. 项目配置：** 配置文件 `commitizen` 路径 `json "commitizen": { "path": "./node_modules/cz-conventional-changelog" }`
