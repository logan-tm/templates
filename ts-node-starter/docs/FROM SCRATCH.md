### Setting up node and typescript

(Assuming nvm is installed)

1. `echo "20" > .nvmrc && nvm use` (or whatever version you require)
2. `npm init` (follow prompts)
3. `npm i tsx && npm i -D typescript @types/node`
4. `echo "function main() { console.log('Hello, TypeScript Node.js Starter!'); }\n\nmain();" > main.ts`

### Setting up biome.js for formatting and linting

1. `npm i -D --save-exact @biomejs/biome`
2. `npx @biomejs/biome init`
