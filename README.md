# Vite VS Code Extension Template

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg)](http://opensource.org/licenses/MIT)

An extension to add highlight support for the vue syntax in the [tagged template string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals#tagged_templates) with specific tags. Supported tag are `vue`, `template` and `component`.

For example, the string below should be highlighted:
```js
const vue = String.raw
const template = vue`
<ContextMenu v-if="show">
    <button class="btn-primary btn-sm" @click="onClick">context menu</button>
</ContextMenu>
`
```
Note that this extension is not resposible for the highlighting, you should use another extension that support vue syntax highlight, such as [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar), to make the highlight actually work.
