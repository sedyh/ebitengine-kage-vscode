## <img align="left" width="100px" src="https://user-images.githubusercontent.com/19890545/179967638-6b0e4e7d-7f8c-412a-b87d-47ba8e694477.png" alt="ebitengine-kage-support" /> Ebitengine Kage support for Visual Studio Code

Basic syntax and snippet support for the Ebitengine Kage shading language. 

<br>

Ebitengine adopts an original shading language 'Kage'. This has a compatible syntax with Go, but the details are different. Kage has high portability. Ebitengine uses graphics libraries like OpenGL or Metal and this depends on environments, but Kage is compiled on the fly so that this works equally everywhere.

### Installation

[![](https://img.shields.io/badge/get%20it%20from-555555?style=for-the-badge&logo=visualstudiocode&logoColor=72a9d4)![](https://img.shields.io/badge/marketplace-72a9d4?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=sedyh.ebitengine-kage)

<details><summary>Manual installation</summary><br>
  
  Install `vsce` from `npm`.
  
  ```
  npm install --global vsce
  ```

  Package extension in `.vsix` archive.

  ```
  vsce package
  ```

  Run this command to install package from `.vsix`, replace `ebitengine-kage.vsix` with your path.

  ```
  code --install-extension ebitengine-kage.vsix
  ```

</details>

### Other editors
[![](https://img.shields.io/badge/source-555555?style=for-the-badge&logo=sublimetext&logoColor=ba9759)](https://github.com/sedyh/ebitengine-kage-sublime)[![](https://img.shields.io/badge/download-ba9759?style=for-the-badge)](https://packagecontrol.io)<br>
[![](https://img.shields.io/badge/source-555555?style=for-the-badge&logo=vim&logoColor=60b371)](https://github.com/sedyh/ebitengine-kage-vim)[![](https://img.shields.io/badge/download-60b371?style=for-the-badge)](https://www.vim.org/scripts/script.php?script_id=6021)

### Features

- [Basic syntax highlighting](#basic-syntax-highlighting)
- [Quick start](#quick-start)
- [Short documentation](#short-documentation)
- [List of all built-in functions](#list-of-all-built-in-functions)

### Basic syntax highlighting

<a href="#features"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> This plugin provides basic Kage language support for Ebitengine. It includes keywords, types, literals and snippets.

![feature-syntax](https://user-images.githubusercontent.com/19890545/177754828-9ab585c9-56be-4304-92e5-dafa0b10ba97.png)

### Quick start

<a href="#features"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> To quickly start writing a shader, you can type "fragment" or "package".

![feature-quickstart](https://user-images.githubusercontent.com/19890545/177755034-58f14b63-f92d-4bba-8e7e-3e740cd81e60.png)

### Short documentation

<a href="#features"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> The plugin provides a short help for each feature in Kage.

![feature-description](https://user-images.githubusercontent.com/19890545/177755312-77153cff-16a7-46ce-b962-c002fc92c2ff.png)

### List of all built-in functions

<a href="#features"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> You can see a list of all built-in functions by typing "kage".

![feature-help](https://user-images.githubusercontent.com/19890545/177755430-0f020abf-abcc-4b02-8138-410695e09fbd.png)

## Known Issues

The plugin will highlight complex numbers despite the fact that, at the moment, Kage does not support them.
