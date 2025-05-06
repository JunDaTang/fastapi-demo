- https://fastapi.tiangolo.com/zh/tutorial/#fastapi

### 第一步

```shell
fastapi dev tutorial\01-first-steps.py
```

* 导入 `FastAPI`。
* 创建一个 `app` 实例。
* 编写一个 **路径操作装饰器** ，如 `@app.get("/")`。
* 定义一个 **路径操作函数** ，如 `def root(): ...`。
* 使用命令 `fastapi dev` 运行开发服务器。


### 路径参数

通过简短、直观的 Python 标准类型声明，**FastAPI** 可以获得：

* 编辑器支持：错误检查，代码自动补全等
* 数据**解析**
* 数据校验
* API 注解和 API 文档

只需要声明一次即可。

这可能是除了性能以外，**FastAPI** 与其它框架相比的主要优势。



### 查询参数

本例中有 3 个查询参数：

* `needy`，必选的 `str` 类型参数
* `skip`，默认值为 `0` 的 `int` 类型参数
* `limit`，可选的 `int` 类型参数
