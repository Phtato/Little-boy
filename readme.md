注：是b站霜狼_may的视频学习笔记，结合着毛星云总结的《Real-Time Rendering 3rd》提炼总结一起看的

## **第一章**
### 1.1 渲染管线 ###
  数据通过渲染管线变成画面，在这个管线中所有环节环环相扣，上一个的输出是下一个的输入。分为以下几步
    <div align="center"> 应用阶段->几何阶段->光栅化阶段->逐片元操作（->后处理）</div>
    
  应用阶段：这个是图像渲染管线上的第一个阶段，这段是完全软件实现的，所以可以完全控制。视频中提到的有粗粒度剔除，渲染设置，准备基础数据。都很不难理解
