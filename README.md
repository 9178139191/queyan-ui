# 确演UI框架 · QueYan UI Framework

版本 1.0.0    |    许可证 AGPL v3    |    声明式UI    |    毛玻璃渲染

确演UI框架为确演OS之图形用户界面渲染引擎，采用声明式UI范式与差异化更新算法。渲染管线基于场景图与图层合成，实现毛玻璃效果的实时高斯模糊。手势识别器采用有限状态机模型，支持12种离散与连续手势。动画引擎基于贝塞尔插值，支持中断与继承。

技术特征

- 差异化更新采用最长递增子序列算法，DOM操作次数最小化
- 毛玻璃效果采用backdrop-filter与WebGL混合渲染
- 手势识别实现触摸点聚类与速度估算，支持多点触控
- 主题系统支持CSS变量动态注入与样式隔离

组件清单

GlassPanel · DesktopIcon · FolderView · DockBar · PageIndicator · ContextMenu · ModalDialog · Toast · Drawer · Carousel

编译与部署

git clone https://github.com/9178139191/queyan-ui
cd queyan-ui
npm install
npm run build

---

English Abstract

QueYan UI Framework is a declarative UI rendering engine featuring differential updates with LIS algorithm, real-time Gaussian blur via backdrop-filter and WebGL compositing, and a finite-state machine gesture recognizer supporting 12 gesture types. The animation engine uses Bezier interpolation with interruption and inheritance support.

GNU Affero General Public License v3.0

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along with this program. If not, see https://www.gnu.org/licenses/.

Copyright © 2026 确演OS. 保留所有权利。
