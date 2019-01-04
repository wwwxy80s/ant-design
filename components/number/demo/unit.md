---
order: 0
title:
  zh-CN: 单位
  en-US: Unit
---

## zh-CN

简单的展示。

## en-US

Simplest Usage.

```jsx
import { Number, Row, Col } from 'antd';

ReactDOM.render(
  <Row gutter={16}>
    <Col span={12}>
      <Number title="账户余额" value={1128} precision={2} unit="元" />
    </Col>
    <Col span={12}>
      <Number title="待合并" value={93} unit="/ 100" />
    </Col>
  </Row>,
  mountNode
);
```
