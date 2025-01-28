# Setup Notes

```bash
mkdir my-new-vitepress-demo
cd my-new-vitepress-demo
npm init -y
npm add -D vitepress

# You can choose the docs folder as `docs` thus all your npm scripts in package.json will be have name of this folder i.e., `docs` in the end e.g., `vitepress dev docs`, `vitepress build docs` and `vitepress preview docs`.
npx vitepress init

npm run docs:dev
```
