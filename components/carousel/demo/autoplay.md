---
order: 3
title:
  zh-CN: 自动切换
  en-US: Scroll automatically
---

## zh-CN

定时切换下一张。

## en-US

Timing of scrolling to the next card/picture.

````jsx
import { Carousel } from 'antd';

ReactDOM.render(
  <Carousel autoplay>
    <div><h3>THE ONE</h3></div>
    <div><h3>THE SECEND</h3></div>
    <div><h3>第三章</h3></div>
    <div><h3>去你妈的</h3></div>
  </Carousel>,
  mountNode);
````

````css
/* For demo */
.ant-carousel .slick-slide {
  text-align: center;
  height: 160px;
  line-height: 160px;
  background: pink;
  overflow: hidden;
}

.ant-carousel .slick-slide h3 {
  color: #fff;
}
````
