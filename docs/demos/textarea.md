## Textarea

### 演示

<img width="100" src="http://qr.topscan.com/api.php?text=http://aitter.oschina.io/#/textarea"/>

<a href="http://aitter.oschina.io/#/textarea" target="_blank" style="font-size:12px;color:#888;">demo 原始链接：http://aitter.oschina.io/#/textarea</a>

<div style="width:377px;height:667px;display:inline-block;border:1px dashed #ececec;border-radius:5px;overflow:hidden;">
  <iframe src="http://aitter.oschina.io/#/textarea" width="375" height="667" border="0" frameborder="0"></iframe>
</div>


### 使用示例

``` javascript
import React from 'react'
import { Textarea, Group } from 'mt-weui-react'
import Page from '../../component/page'
// import Autosize from 'autosize' // http://www.jacklmoore.com/autosize/

var Demo = React.createClass({
    getInitialState(){
      return {
        activeIndex: 0,
      }
    },
    render: function() {
      return (
        <Page title="Textarea">
          <Group title="基本使用">
            <Textarea placeholder="请填写详细信息"></Textarea>
          </Group>

          <Group title="显示计数器">
            <Textarea placeholder="请填写详细信息" maxLength="200" showCounter></Textarea>
          </Group>
        </Page>
      );
    },
});

export default Demo

```
