# sublime_thinkphp6

> Sublime Text 语法提示插件，支持 ThinkPHP6 框架

## 功能特性

| 特性 | 说明 |
|------|------|
| 代码片段 | 120+ 个代码片段 |
| 完整覆盖 | 覆盖 ThinkPHP6 核心功能 |
| 智能提示 | 支持 Tab 键快速补全 |
| 调试函数 | 内置常用调试方法 |

## 安装

### Sublime Text 安装

1. 打开 Sublime Text
2. 按 `Ctrl+Shift+P` 打开命令面板
3. 输入 `Package Control: Install Package`
4. 搜索 `thinkphp6` 并安装

### 手动安装

将项目克隆到 Sublime Text 的 Packages 目录：

```bash
git clone https://github.com/chenbool/sublime_thinkphp6.git
```

## 代码片段总览

| 分类 | 数量 | 说明 |
|------|------|------|
| Controller | 10 | 控制器 |
| Model | 5 | 模型 |
| DB | 25 | 数据库操作 |
| Request | 12 | 请求对象 |
| Route | 8 | 路由配置 |
| Validate | 4 | 验证器 |
| Middleware | 1 | 中间件 |
| Cache | 7 | 缓存 |
| Session | 4 | Session |
| Cookie | 3 | Cookie |
| Log | 4 | 日志 |
| View | 2 | 视图 |
| Url | 1 | URL |
| Bug | 4 | 调试 |

## 使用示例

```php
// 数据库查询
Db::table('user')->where('id', 1)->find();

// 模型
$user = User::find(1);

// 请求参数
request()->param('name');

// 路由
Route::get('hello/:name', 'index/hello');
```

## 相关项目

| 项目 | 仓库地址 |
|------|----------|
| sublime_swoole | https://github.com/chenbool/sublime_swoole |
| sublime_yaf | https://github.com/chenbool/sublime_yaf |
| sublime_thinkphp5 | https://github.com/chenbool/sublime_thinkphp5 |
| sublime_thinkphp6 | https://github.com/chenbool/sublime_thinkphp6 |
| sublime_thinkphp8 | https://github.com/chenbool/sublime_thinkphp8 |
| sublime_laravel | https://github.com/chenbool/sublime_laravel |
| sublime_workerman | https://github.com/chenbool/sublime_workerman |
| sublime_webman | https://github.com/chenbool/sublime_webman |
| sublime_fastadmin | https://github.com/chenbool/sublime_fastadmin |

## License

MIT License
