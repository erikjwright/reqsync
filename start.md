bun create next-app@latest --name reqsync
cd reqsync
bun add -D @types/node@22
bun add -D --save-exact @biomejs/biome
bun biome init
bun add -D vitest @vitejs/plugin-react vite-tsconfig-paths @testing-library/react jsdom
bun add -D vitepress
bun vitepress init
