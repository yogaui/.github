<p align="center">
  <a href="https://yogaui.github.io"><img src="https://raw.githubusercontent.com/yogaui/yoga/main/docs/assets/logo.svg" alt="Yoga" width="96"></a>
</p>

<h3 align="center">A from-scratch, cross-platform UI framework in Go.</h3>

<p align="center">
  <a href="https://yogaui.github.io">Website</a> ·
  <a href="https://yogaui.github.io/docs/">Docs</a> ·
  <a href="https://github.com/yogaui/yoga">Source</a>
</p>

**Yoga** draws native desktop apps and browser apps from the same Go code. It renders with WebGPU (GLFW and wgpu-native on the desktop, the browser's WebGPU from WebAssembly) and lays out with a pure-Go flex, grid and stack engine. Apps describe their UI as a tree of views rebuilt every frame, with real widgets for the parts that keep state: tables, trees, file trees, virtual lists and a code editor.

```sh
git clone https://github.com/yogaui/yoga && cd yoga
go run ./example/todo
```

| Repository | |
|---|---|
| [yoga](https://github.com/yogaui/yoga) | The framework: runtime, layout, widgets, themes, and the `yoga` packaging CLI |
| [editor](https://github.com/yogaui/editor) | The code editor widget, with Tree-sitter highlighting and language servers |
| [yogaui.github.io](https://github.com/yogaui/yogaui.github.io) | [yogaui.github.io](https://yogaui.github.io) and its docs; fixes to the docs are welcome |

Yoga is open source under the MIT License. It powers [Hm](https://usehm.dev) and [Chapar](https://chapar.rest).
