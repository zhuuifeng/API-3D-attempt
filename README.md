-使用Three.js创建和渲染3D场景。
-跨多个浏览器窗口同步3D场景。
-使用localStorage的动态窗口管理和状态同步。

Thanks to https://github.com/bgstaal/multipleWindow3dScene
结构和组件
-`index.html`：设置html结构的入口点，包括Three.js库和主脚本。
-`WindowManager.js`：管理跨多个窗口的窗口创建、同步和状态管理的核心类。
-`main.js`：包含初始化3D场景、处理窗口事件和渲染场景的逻辑。
-“three.r124.min.js”：用于3D图形渲染的three.js库的小型化版本。
详细功能
-`WindowManager.js`处理多个浏览器窗口的生命周期，包括创建、同步和删除。它使用localStorage跨窗口维护状态。
-`main.js`使用Three.js初始化3D场景，管理窗口的调整大小事件，并根据窗口交互更新场景。


[zhuifeng     X    _nonfigurativ_]