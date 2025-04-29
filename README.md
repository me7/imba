## imba
[imba](https://imba.io) is the language that combine html, css and javascript in one
- frontend: best choice, it [memoize dom](https://imba.io/guides/rendering) make state management needless. [css](https://imba.io/docs/css) also better than tailwind
- backend: wait for officail v2, better use [bun](https://bun.sh) and [elysia](https://elysiajs.com) for now

## get started
- you should have [degit](https://www.npmjs.com/package/degit) available `bun add -g degit`
- `degit me7/imba/vite PROJ-NAME` to get frontend [vite](https://vitejs.dev) template ([original template](https://github.com/imba/imba/tree/master/packages/imba/templates/vite)) 
- `bun update --latest` to install dependencies
- `bun dev` to start development server
- `bun run build` to build html, js, css files