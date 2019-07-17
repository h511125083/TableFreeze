# TableFreeze.js（基于JQuery的表格冻结插件）<br/>
<br/>
> 声明：该插件在原插件的基础上增加了冻结尾列的功能，由于此插件为github找不到开源地址，原始版本的插件作者及其修改信息如下：<br/>
/*********************************  <br/>
** 名称:JQeury实现表格行列冻结<br/>
** <br/>
** 作者:YJJ<br/>
** <br/>
** 时间:2014年4月16日<br/>
** <br/>
** 修改人：Allen<br/>
** <br/>
** 修改时间:2017-06-10<br/>
** <br/>
** 修改记录:兼容<br/>
** <br/>
** 描述:类似Excel中的冻结窗格功能.建议给出表头固定宽度,所有单元格的高度,指定表格宽度;<br/>
** <br/>
** 修改人：Christopher<br/>
** <br/>
** 修改时间:2018-08-05<br/>
** <br/>
** 修改记录:增加冻结右侧列的功能+兼容<br/>
** <br/>
** 描述:支持冻结函数传入第4个参数，用于冻结尾列;兼容ie下宽度和高度显示的问题<br/>
** <br/>
** 修改人：Zhanghuang<br/>
** <br/>
** 修改时间:2019-07-15<br/>
** <br/>
** 修改记录:增加兼容tableSort<br/>
** <br/>
** 描述:增加兼容tableSort<br/>
**        使用这个的时候，首先表头的列不能是 th  要用td，<br/>
**        这个插件需要在最后去调用，否则会缺少加载一些css，并且还会影响其他的插件<br/>
**      目前测试兼容： IE11 谷歌<br/>
**********************************/ <br/>
## 特性 <br/>
 <br/>
- 基于jQuery <br/>
 <br/>
## 使用 <br/>

```bash
<script type="text/javascript" src="./jquery.js"></script> <br/>
<script type="text/javascript" src="./jquery-migrate-1.2.1.js"></script> <br/>
<script type="text/javascript" src="./TableFreeze.js"></script> <br/>
<script type='text/javascript'> <br/>
    $(document).ready(function(){ <br/>
        // rowHead, rowFoot, colLeft, colRight 分别对应需要冻结的表格首行，尾行，首列和尾列 <br/>
        var rowHead = 1, rowFoot = 1, colLeft = 2, colRight = 2; <br/>
        $("#someId").tablesortFrozenTable(rowHead, rowFoot, colLeft, colRight); <br/>
    }); <br/>
</script> <br/>
``` <br/>

## License <br/>

This project is available under the MIT license. <br/>
