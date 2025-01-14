# bundle

<a href="https://www.producthunt.com/posts/bundle-6?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-bundle-6" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=300568&theme=dark" alt="bundle - An online npm package bundle size checker | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a> [![Open In Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/okikio/bundle/blob/main/README.md)

A small online tool for checking the gzipped and minified size of npm packages.

I used [monaco-editor](https://github.com/microsoft/monaco-editor) for the code-editor, [esbuild](https://github.com/evanw/esbuild) and [rollup](https://github.com/rollup/rollup) as bundler and treeshaker respectively, [pako](https://github.com/nodeca/pako) as a js port of the zlib and gzip libraries, [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) to convert the gzip size to human readable values, and [countapi-js](https://github.com/mlomb/countapi-js) to keep track of the number of page visits, in a private and secure way.

This project was greatly influenced by hardfists [neo-tools](https://github.com/hardfist/neo-tools) and mizchi's [uniroll](https://github.com/mizchi/uniroll) project.

**bundle** is a quick and easy way to bundle your projects, minify and see it's gzip size, it's similar to [bundlephobia](https://bundlephobia.com) but does all the work locally on you computer and can treeshake and bundle multiple packages (both commonjs and esm) together, it currently doesn't support JSX, but packages without JSX are good.

The project isn't perfect, and I am still working on an autocomplete, hover intellisence, better mobile support and the high memory usage of **esbuild** and **monaco** as well as some edge case packages, e.g. **monaco-editor**.

If there is something I missed, a mistake, or a feature you would like added please create an issue or a pull request and I'll try to get to it. You can contribute to this project at [okikio/bundle](https://github.com/okikio/bundle).

**bundle** uses [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) as the style of commit, and the [Commitizen CLI](http://commitizen.github.io/cz-cli/) to make commits easier.

You can join the discussion on [github discussions](https://github.com/okikio/bundle/discussions).
