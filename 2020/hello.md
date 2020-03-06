---
layout: post
title: Hello, world!
date: 2020-03-05 10:27:32
update: 2020-03-06 15:57:29
tags: [文章]
---

这是一篇测试.

# Headline 1 - 一级标题

## Headline 2 - 二级标题

### Headline 3 - 三级标题

#### Headline 4 - 四级标题

##### Headline 5 - 五级标题

###### Headline 6 - 六级标题

这里有一堆分割线

---

----

***

*****

这是**加粗字**, 这是*倾体字*, 这是***加粗斜体字***, 这是~删除线~, 这是 `print("Python")` 行内代码. ~~还有<u>下划线</u>~~

代码高亮测试

```c
#include <stdio.h>

int main(void)
{   
    // print A-Z
    for (int i = 65; i < 91; i++)
        printf("%c\n", i);

    return 0;
}
```

```python
def quick_sort(array):
    # sort from small to big
    if len(array) <= 1:
        return array

    return (quick_sort([item for item in array[1:] if item <= array[0]])
         + [array[0]]
         + quick_sort([item for item in array[1:] if item > array[0]]))

print(quick_sort([0, 1, 3, 11, 4, 2, 0, 1]))
```

> 引用
> 
> > 引用嵌套
> > 
> > > 引用再嵌套
> > > 
> > > > 引用千层饼

有序列表

1. 项目 1
2. 项目 2
3. 项目 3
4. 项目 5

无序列表

- 项目 1
- 项目 2
+ 项目 3
* 项目 5

嵌套列表

1. 一级有序
   1. 二级有序
   2. 二级有序 2
2. 一级有序 2
   - 二级无序
   - 二级无序 2

TODO List

- [ ] TODO List

- [ ] TODO List2

然后来测试图片
![GitHub](https://www.jsdelivr.com/img/landing/github.png "GitHub")

超链接
[超链接](https://www.jsdelivr.com "title")

第二种图片链接测试
![GitHub][1]
[1]: https://www.jsdelivr.com/img/landing/github.png

第二种链接测试

[Google][2]

[2]: https://google.com

| 表头1 | 表头2 | 表头3 |
|:--- |:---:| ---:|
| 内容  | 内容  | 内容  |
| 内容  | 内容  | 内容  |

迎来了 LaTeX 测试

$$
Maxwell's equations\\
\mu_0\varepsilon_0  \frac{\partial^2 \mathbf{E}}{\partial t^2} - \nabla^2 \mathbf{E} = 0 \\
\mu_0\varepsilon_0 \frac{\partial^2 \mathbf{B}}{\partial t^2} - \nabla^2 \mathbf{B} = 0 \\
\mu_0\varepsilon_0 = \frac{1}{c^2}
$$

以及表格内嵌 LaTeX

| 名称       | 积分形式                                                                                                                                                                                                                                      | 微分形式                                                                                                               |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| 高斯定律     | $\mathbf{E}\cdot\mathrm{d}\mathbf{S} = \frac{1}{\varepsilon_0} \iiint_\Omega \rho \,\mathrm{d}V$                                                                                                                                          | $\nabla \cdot \mathbf{E} = \frac {\rho} {\varepsilon_0}$                                                           |
| 磁场高斯定律   | $\mathbf{B}\cdot\mathrm{d}\mathbf{S} = 0$                                                                                                                                                                                                 | $\nabla \cdot \mathbf{B} = 0$                                                                                      |
| 法拉第定律    | $\oint_{\partial \Sigma} \mathbf{E} \cdot \mathrm{d}\boldsymbol{l}  = - \operatorname{\frac{d}{dt}} \iint_{\Sigma} \mathbf{B} $                                                                                                           | $\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}} {\partial t}$                                              |
| 闭合电路安培定律 | $\oint_{\partial \Sigma}{\mathbf{B} \cdot \mathrm{d}\boldsymbol{l} } = \mu_0 (\iint_{\Sigma} \mathbf{J} \cdot \mathrm{d}\mathbf{S} + \varepsilon_0 \frac{\mathrm{d}}{\mathrm{d}t} \iint_{\Sigma} \mathbf{E} \cdot \mathrm{d}\mathbf{S} )$ | $\nabla \times \mathbf{B} = \mu_0\left(\mathbf{J} + \varepsilon_0 \frac{\partial \mathbf{E}} {\partial t} \right)$ |

参考: [https://en.wikipedia.org/wiki/Maxwell%27s_equations](https://en.wikipedia.org/wiki/Maxwell%27s_equations)
