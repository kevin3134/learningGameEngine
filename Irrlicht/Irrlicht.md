
# 鬼火引擎
一个基于c++的3D开源游戏引擎,跨平台，支持D3D， Opengl和其自带软渲染器  

website: http://irrlicht.sourceforge.net/

现状：  
鬼火已经很长时间没更新了，上次更新在2016.07.09。鬼火2006年首次发布，在现在已经很多东西没有随着时代更新，如其opengl使用版本还是opengl1.5，很多后期更新的api没有使用。这样在功能丰富性和效率上会有缺陷。因此主要学习点是其结构设计。

特点：  
1，简短易读，适合学习   
2，精悍的引擎框架    
3，开发时没有GUI，游戏开发代码量也不小  
4，主要内容包括 渲染器，简单的GUI功能（碰撞检测和事件接收器）


一些实现：  
Occlusion Queries  
是内置的一种优化方案，在正式通过shader渲染前先进行一次简单的预渲染，判断遮挡关系，这样避免绘制遮挡物体，可以提高效率  


# Irrlicht Engine 1.8.4
The Irrlicht Engine is an open source realtime 3D engine written in C++. It is cross-platform, using D3D, OpenGL and its own software renderers.

