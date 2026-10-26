# 第三方依赖与许可

本项目的 `index.html` 内嵌了以下开源库的代码（通过 `importmap` + `data:` URL）。它们分别遵循各自的 MIT 许可，版权归原作者所有。

## three.js r168

- 官网：https://threejs.org/
- 仓库：https://github.com/mrdoob/three.js
- 许可：MIT
- 用途：WebGL 渲染器、相机、几何体、PBR 材质、灯光、阴影、Raycaster、PMREM 环境贴图
- 内嵌文件：`build/three.module.min.js`

### three.js 示例模块（examples/jsm）

| 文件 | 用途 | 许可 |
| --- | --- | --- |
| `controls/OrbitControls.js` | 轨道相机控制 | MIT |
| `exporters/OBJExporter.js` | OBJ 导出 | MIT |
| `exporters/STLExporter.js` | STL 导出 | MIT |

## three-mesh-bvh 0.8.3

- 仓库：https://github.com/gkjohnson/three-mesh-bvh
- 作者：Garrett Johnson
- 许可：MIT
- 用途：为几何体构建 BVH，加速三角形求交和 CSG
- 内嵌文件：`build/index.module.js`

## three-bvh-csg 0.0.17

- 仓库：https://github.com/gkjohnson/three-bvh-csg
- 作者：Garrett Johnson
- 许可：MIT
- 用途：基于 BVH 的并集 / 差集 / 交集布尔运算
- 内嵌文件：`build/index.module.js`

## 应用自身代码

`index.html` 中的界面、节点图、材质面板、布局与交互逻辑由本项目作者编写。仓库暂未附带独立许可证；如需开源，请补充 `LICENSE` 文件。

## MIT 许可摘要

以上第三方项目均以 MIT 许可发布，允许使用、复制、修改、合并、出版、分发、再许可和/或销售软件的副本，但要求在副本中保留版权声明和许可声明。完整文本请参见各项目仓库中的 `LICENSE` 文件。
