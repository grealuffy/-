# 代码的实现逻辑
## html文件的编写
    我们通过五个html文件(页面一~页面五)描述Web页面的结构和内容。
    它们的主要作用是定义页面的结构，包括标题、段落、列表、表格等。
    其中含有的一系列标签构建了页面的结构，但并不涉及页面的样式和交互行为。
![这是页面1html文件的部分截图](https://github.com/grealuffy/-/assets/143927752/4dc3abb2-0aa6-42df-83af-f04357eab204)

在vscode中打开页面一.html右键点击open with live server产生运行结果如下图
![数独游戏](https://github.com/grealuffy/-/assets/143927752/6b4c9fac-5cfa-4654-9731-f00b6cef2afb)
## css文件的编写
    我们使用了style1-4四个CSS文件用于控制Web页面的样式和布局。
    它通过选择器和属性来选择页面中的元素，比如“一键解题”、“重新生成”等按钮等，并为其应用样式。
    css改变元素的颜色、字体、大小、边框等外观属性，同时还可以控制元素的位置、布局和动画效果。
    CSS使得我们能够对页面进行精确的样式控制，从而实现更好玩家的游戏交互体验。
![styles.css的部分截图](https://github.com/grealuffy/-/assets/143927752/f4a48bef-bde2-4c9e-8112-99290f86f2c7)

## JavaScript代码的编写
    JavaScript是一种脚本语言，我们将其用于为Web页面添加交互行为和动态功能。
    它可以响应玩家的操作，例如点击按钮、输入数据等，然后通过对页面进行操作来改变页面的内容、样式和行为。
    JavaScript可以实现复杂的逻辑、数据处理、动画效果、数据请求等功能，使得Web页面更加动态和灵活。
    该部分实现的算法是本次数独游戏中最重要的部分，
    它的可行性：通过递归和回溯，算法能够在每个空格中尝试填入数字并验证，一步一步逼近最终解，确保每个数字唯一。
    它的高效性：由于递归的特性，算法能够有效地减少搜索空间，提高解题效率。在每个空格填入合适的数字后，算法会递归地继续解决下一个空格，直到找到完整的解决方案。、
    上述内容均由JavaScript编写完成
![sudoku_difficlut.js文件的部分截图](https://github.com/grealuffy/-/assets/143927752/83da2120-80c9-4987-b1ed-edaa3c16bf25)

# 综合以上三者
我们可制作出完整的九宫格游戏，其运行方式如下图所示
## 点击解压后的html文件夹，从页面一开始，右键在菜单栏中找到打开选择浏览器打开（建议用Edge），如果页面没有声音，可在设置调网站自动播放，才会出现背景音乐，如下图（以edge为例）
![%%V0WUNY6Z)%%616R`~PNRL](https://github.com/grealuffy/-/assets/143927752/e057a208-1d0d-4a10-a184-2ca6b05fcf4f)
![image](https://github.com/grealuffy/-/assets/143927752/30cc4ccc-2f05-4c37-9664-016a8dae390f)
![image](https://github.com/grealuffy/-/assets/143927752/c3d3f2b7-9d11-44d1-ae42-3175be86f13a)
## 进入游戏后运行界面如下图
![image-4](https://github.com/grealuffy/-/assets/143927752/0bc09bfc-ca61-493c-937e-d8271a8d2b9c)
![image-5](https://github.com/grealuffy/-/assets/143927752/d6cd02e6-6e4d-40b6-9af1-18d2e15800fd)
### 选择为简单模式
![image-6](https://github.com/grealuffy/-/assets/143927752/c4f912de-1559-4f98-a2c8-bce4474ea433)
![image-7](https://github.com/grealuffy/-/assets/143927752/1fcbbb7c-89f7-428c-8d88-38fbd52e8f26)
![image-8](https://github.com/grealuffy/-/assets/143927752/3bfcd77e-10e8-4cc9-9049-1766f3dbb6bd)
![image-9](https://github.com/grealuffy/-/assets/143927752/6266e798-d1a5-4bdc-929d-ec5dfa966e40)
### 选择为困难模式
![image-10](https://github.com/grealuffy/-/assets/143927752/bffe4491-ce73-444a-b25b-ebc252a05c60)
![image-11](https://github.com/grealuffy/-/assets/143927752/68d6284f-35c2-4001-86fb-c300dabe7e7b)
