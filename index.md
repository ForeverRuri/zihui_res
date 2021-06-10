
## 自会系统效果展示

### 输入图片示例

<div align=center><img src="1.jpeg" ></div>

### Step 1 轮廓提取结果
<div align=center><img src="edges.jpg" ></div>

### Step 2 对图中文字进行检测

* #### 检测区域

<div align=center><img src="Aalst.jpg" ></div>
<div align=center><img src="DARK.jpg" ></div>
<div align=center><img src="CHOCOLATE.jpg" ></div>

* #### 检测结果置信度

|  字段   | 置信度  |
|  ----  | ----  |
| CHOCOLATE  | 0.9883 |
| DARK  | 0.9997 |
|8alst| 0.4264 |

* 使用自然语言处理技术对输入置信度较低(低于0.5)的部分进行改正，得到`CHOCOLATE`, `DARK`, `Aalst`等三个字段。
* 对指示产品内容的`CHOCOLATE`和对应品牌的`Aalst`进行分类。

**二者都属于`Food`类别，从而通过验证，确认当前输入是一食品包装，进行后续操作。**


### Step 3 对商标图片和产品示意图进行检测

* #### 商标
<div align=center><img src="logo_0.jpg" ></div>
<div align=center><img src="logo_1.jpg" ></div>

  
* #### 巧克力
<div align=center><img src="content.jpg" ></div>

### 可见面的信息融合结果
  
**对三个可见面的检测结果进行信息融合**  
**其中，黄色部分对应产品相关的宣传语，蓝色对应产品图，紫色对应商标图，红色对应商标名称**
**绿色对应背景中非空白部分的艺术设计部分**
**对不同类型所占区域的大小，相对位置进行调整，可得到不同效果的包装设计图**

* #### 面1的检测结果
<div align=center><img src="region0.jpg" ></div>

* #### 面2的检测结果
<div align=center><img src="region1.jpg" ></div>


* #### 面3的检测结果
<div align=center><img src="region2.jpg" ></div>


### [3D动态展示效果](https://foreverruri.github.io/zihui_dynamic_display/)

