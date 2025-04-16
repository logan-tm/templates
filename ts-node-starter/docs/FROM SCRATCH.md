### Setting up node and typescript

(Assuming nvm is installed)
`nvm use 20` (or whatever version you require)
`npm init` (follow prompts)
`touch main.ts`
`npm i tsx && npm i -D typescript @types/node`

### Setting up biome.js for formatting and linting

`npm i -D --save-exact @biomejs/biome`
`npx @biomejs/biome init`
Update package.json with start, watch, and format commands
