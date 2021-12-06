<h1 align="center"> wgsl-intellij-syntax</h1>
<div align="center">
  <strong>Syntax highlighting for WGSL files in IntelliJ</strong>
</div>
<div align="center">
  A highlighter using TextMate
</div>

<div align="center">
  <img src="https://img.shields.io/badge/stability-experimental-orange.svg?style=flat-square" 
      alt="Stability" />
</div>



## Description

This is a TextMate bundle which can be used in IntelliJ to enable syntax highlighting for WGSL. It also works for CLion, which is often used when developing using Rust. The TextMate bundle is adopted from [PolyMeilex/vscode-wgsl](https://github.com/PolyMeilex/vscode-wgsl).

Example:

![](./docs/syntax.png)


It also works when injecting languages:

![](./docs/syntax_inject.png)


## Installation

* Download this repostiory and extract its contents into a directory
* Import it like described [here](https://www.jetbrains.com/help/idea/textmate.html#import-textmate-bundles)

## Features

* Add syntax highlighting to .wgsl files

## Non-Features

* Autocompletion
* Syntax of semantics error checking