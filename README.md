# vue-tab - swipe tab simplify
---

> This component is already used in production env.
## Overview

vue-tab is a touch swipe tab for vue.js.

## Install

```

```

### Import using module
```
import { Tabs, Tab }  from 'Tab';
```

## Usage

```
import { Tabs, Tab }  from './Tab';

methods: {
    changePage(idx) {
        console.log(idx);
    }
}

<template>
    <div class="app">
        <Tabs @changePage="changeFunc">
            <Tab name="好友榜" hash="friend" fontsize="36" tabheight="90">
                <div class="first"></div>
            </Tab>
            <Tab name="全省榜" hash="convince" fontsize="36" tabheight="90">
                <div class="second"></div>
            </Tab>
            <Tab name="全国榜" hash="country" fontsize="36" tabheight="90">
                <div class="three"></div>
            </Tab>
        </Tabs>
    </div>
</template>
```


# Options

Here list Props on swipe component

| Option | Description |
| ----- | ----- |
| name | Required, the text of tab header |
| hash | Required, the hash of tab page |
| fontSize | String, the fontSize of tab Header, is caculated by rem |
| tabheight | String, the tabHeight of tabHeader, is caculated by rem |
| changePage | Event, it will be fired after the page change, you can get the currentPage index in the callback function |

## Live Demo

  https://zhangxiang958.github.io/Lazyload/demo/index.html

## License

MIT License

Copyright (c) 2017 Shawn Cheung

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

#### Contact
- Mail [958033967@qq.com](mailto 958033967@qq.com)
- Blog [zhangxiang958.github.io](http://zhangxiang958.github.io "shawn")
