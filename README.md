# ajax-module
原生ajax库，实现jsonp跨域，短小精悍。

```bash
ajax({
    type:"get",
    url:"", 
    timeOut:5000,
    before:function(){
      
    },
    success:function(str){
        
    },
    error:function(){
        
    }
});
```

参数表：

| 参数 | 默认值 | 描述 | 可选值 |
|:----|:----|:----|:----|
| url | "" | 请求的链接 | string |
| type | get | 请求的方法 | get,post |
| data | null | 请求的数据 | object,string |
| contentType | "" | 请求头 | string |
| dataType | "" | 请求的类型 | jsonp |
| async | true | 是否异步 | blooean |
| timeOut | undefined | 超时时间 | number |
| before | function(){} | 发送之前执行的函数 | function |
| error | function(){} | 请求报错执行的函数 | function |
| success | function(){} | 请求成功的回调函数 | function |


