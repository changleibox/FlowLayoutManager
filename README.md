# FlowLayoutManager 
[![Travis branch](https://img.shields.io/travis/rust-lang/rust/master.svg)](https://github.com/changleibox/FlowLayoutManager)<br>

这是一个实现流式布局的LayoutManager，配合RecyclerView使用，可实现标签效果；目前的问题是没有实现View的缓存，以后再补吧。

## 代码示例

```java
  FlowLayoutManager manager = (FlowLayoutManager) recyclerView.getLayoutManager();
  manager.setSpace(space, space);
  manager.setOrientation(FlowLayoutManager.HORIZONTAL);
```

## 项目运行效果

### 水平模式
<img width="324" height="574" src="https://github.com/changleibox/Images/raw/master/FlowLayoutManager2.jpg">

### 垂直模式
<img width="324" height="574" src="https://github.com/changleibox/Images/raw/master/FlowLayoutManager1.jpg">

## 参与者介绍
    项目由[@常磊](https://github.com/changleibox)个人开发，如有问题，欢迎指出，邮箱changleibox@sina.com。
    
## License
    Copyright © 2017 CHANGLEI. All rights reserved.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
