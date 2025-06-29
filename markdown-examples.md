# Markdown 扩展功能示例

本文展示了一些由 VitePress 内置的 Markdown 扩展功能。

## 语法高亮

VitePress 提供基于 [Shiki](https://github.com/shikijs/shiki) 的语法高亮功能，并支持行号高亮等特性：

**输入**

```js{4}
export default {
  data () {
    return {
      msg: '已高亮显示！'
    }
  }
}
```

**输出**

```js{4}
export default {
  data () {
    return {
      msg: '已高亮显示！'
    }
  }
}
```

## 自定义容器

**输入**

::: info
这是一个信息提示框。
:::

::: tip
这是一个小技巧提示。
:::

::: warning
这是一个警告提示。
:::

::: danger
这是一个危险警告提示。
:::

::: details
这是一个可折叠详情区块。
:::

**输出**

::: info
这是一个信息提示框。
:::

::: tip
这是一个小技巧提示。
:::

::: warning
这是一个警告提示。
:::

::: danger
这是一个危险警告提示。
:::

::: details
这是一个可折叠详情区块。
:::

## 更多功能

查看文档了解 [完整的 Markdown 扩展功能列表](https://vitepress.dev/guide/markdown)。
