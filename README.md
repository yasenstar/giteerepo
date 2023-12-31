# ontology 本体模型

## 通过网页查看模型

[https://service.tib.eu/webvowl/](https://service.tib.eu/webvowl/)


## 化学知识本体模型

文件：chemistry.rdf

下面是部分Protege工具内的界面截屏，供参考。

#### 主要的“类”列表

![001](/img/chem/001.png)

主要包括：
- 元素 Element：元素周期表中的所以元素
- 元素周期表：安装不同维度对元素周期表进行分类
- 化合物：化合物分子式、名称，还有相关的化学反应式
- 知识结构：安装思维导图书籍进行的知识整理
- Styly, Type, 分析方法等：不同的维度

#### 元素与相关子类

![004](/img/chem/004.png)

在每个元素的子类（树状结构）中，是引用的在其他部分--如知识结构--中的有关的部分。

在屏幕右下的描述部分，可以看到这个元素是作为哪些其他类的子类。

#### 元素周期表的具体维度

![006](/img/chem/006.png)

#### 化合物与化学反应式

![002](/img/chem/002.png)

在化合物的子类中连接了其包含的元素单质：

![003](/img/chem/003.png)

选择化合物名称，在右上的Annotations部分可以看到整理的与其有关的化学反应式。

注：由于Protege的输入是纯文本方式，注意在分子式的写法上上标和下标都是直接用同样字号的文本连续书写的。如`硫酸：H2SO4`。

#### 知识结构

这里可以灵活的整理各种知识，目前参考《高中化学考点思维导图》的脉络在整理。

![007](/img/chem/007.png)

#### 相关维度的定义

维度是用来对具体知识内容进行分类所定义的，以下是目前看到的相关维度，可以根据需要随时添加更多的维度：

![005](/img/chem/005.png)

展开不同维度类，可以看到与其相关的类（即使用SubClass Of）引用到此维度类的知识部分。

#### 使用OntoGraf可视化浏览和查询

单击左边的类树各个节点，会在右边显示点击的类；若这个节点的左上角有“+”号，双击加号可以直接展开其所有的子类：

![008](/img/chem/008.png)

鼠标放到你感兴趣的节点之上，不用点击，就会显示出与之相关的注解(Annotation)以及相关类的信息：

![009](/img/chem/009.png)

在Search框中输入任意内容，回车（或点击Search按钮）可以直接显示搜索结构的可视化：

![010](/img/chem/010.png)

可以设定搜索的方式：

![011](/img/chem/011.png)
