JSON
====

JavaScript对象表示法（JavaScript Object Notation，简称json）是一种轻量级的数据交换格式。它基于JavaScript的对象字面量表示法，那么JavaScript最精华的部分之一。尽管只是JavaScript的一个子集，但它与语言无关。它可以被用于在所有以现代编程语言的程序之间交换数据。它是一种文本格式，所以可以被人和机器阅读。它易于实现且易于使用。大量关于JSON的资料都可以在[http://www.JSON.org/](http://www.JSON.org/)中找到。

## JSON

json有6中类型的值： 对象、数组、字符串、数字、布尔值（true和false）和特殊值null。空白（空格符、制表符、回车符和换行符）可被插到任何值的前后。这可以使得JSON文本更容易本人阅读。为了减少传输和存储成本，空白可以被省略。

JSON对象是一个容纳"名/值"对的无序集合。名字可以是任何字符串。值可以是任何类型的JSON值，包括数组和对象。JSON对象可以被无限层地嵌套，但一般涞水保持其结构的相对扁平是搞笑的。大多数语言都有容易被映射为JSON对象的数据类型，比如对象（object）、结构（struct）、字典（dictionary）、哈希表（hash table）、属性列表（property list）或关联数组（associative array）。

JSON数组使一个值的有序序列。其值可以是任何类型的JSON值，包括数组和对象。大多数语言都有容易被映射为JSON数组的数据类型。比如数组（array）、向量（vector）、列表（list）或序列（sequence）。

JSON字符串要被保卫在一堆双引号之间。\字符被用于转义。JSON允许/字符被转义，所以JSON可以被嵌入HTML的<script>标签之中。除非</script>标签初始化，否则HTML不允许实用</字符序列。但JSON允许使用<\/，它能产生同样的结构却不会与HTML混淆。

JSON数字与JavaScript的数字相似。整数的首位不允许为0，因为一些语言用它来标示八进制，这种技术的混乱在数据交换格式中是不可取的。数字可以是整数、实数或科学计数。

就是这样。这就是JSON的全部。JSON的设计目标是称为一个极简的、轻便的和文本式的JavaScript子集。实现互通所需要的共识越少，互通就越容易实现。

## 安全的使用JSON



