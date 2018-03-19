# vue-pdfjs
vue.js pdf viewer

## Install
```
npm install --save vue-pdfjs
```

## Example - basic
```
<template>
  <vue-pdfjs url="url.pdf" :type="1"></vue-pdfjs>
</template>

<script>
import vuePdfjs from 'vue-pdfjs'

export default {
  components: {
    vuePdfjs
  }
}
```

## API

### Props

#### :src <sup>String - default: ''<sup>
PDF 路径

#### :type <sup>Number - default: 0<sup>
PDF显示效果默认简洁，可选参数0 or 1
