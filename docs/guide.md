---
title: forten - guide
lang: en-US
---

## guide


[[toc]]


::: tip
This is a tip
:::

::: warning
This is a warning
:::

::: danger
This is a dangerous warning
:::

::: details
This is a details block, which does not work in IE / Edge
:::


``` html
<ul>
  <li
    v-for="todo in todos"
    :key="todo.id"
  >
    {{ todo.text }}
  </li>
</ul>
```

## header 
this text should be pink

### sub header

``` js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```