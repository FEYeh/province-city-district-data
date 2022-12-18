# province-city-district-data
🚀🔥2022年中华人民共和国行政区划代码（更新时间：2022-03-21 15:12 来源：民政部门户网站）  
**antd的级联组件直接可用**
## antd 使用方法

```ts
import React from 'react';
import { Cascader } from 'antd';
import cities from "province-city-district-data";

const onChange = (value: string[]) => {
  console.log(value);
};

const App: React.FC = () => (
  <Cascader options={cities} onChange={onChange} />
);

export default App;
```
