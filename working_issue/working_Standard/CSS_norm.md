## CSS编写规范

> 编码：@charset "utf-8"

------

> 头部增加项目创建日期信息 
>> - `/*xm_name  20180913 */ ` 

------ 

> class与id的使用：纯写样式控制时，一般都使用class，特殊的除外，这么做是因为id的优先级高，在协同开发时不利于样式重置

------

> css简写，用以提升下载速度，减少文件大小，代码简洁可读

>> -  ~~`margin-top：0; margin-right:10px; margin-bottom:10px; margin-left:0;`~~
   * __`margin:0 10px 10px 0;`__
>> - ~~`border-width:2px; border-style:solid; border-color:#000`~~
   * __`border:2px solid #000;`__
>> - border四边不一样时：~~`border-top-width:1px; border-right-width:4px; border-bottom-width:5px; border-left-width:3px;`~~
   * __`border-width:1px 4px 5px 3px;`__
>> - 同样的border可以只设置某几边的样式不一，应当先定义border的整体样式，再进行修改: ~~`border-right:2px solid #000; border-bottom:3px solid #000;`~~
   * __`border:1px solid #000; border-width:1px 2px 3px 1px;`__
   



    