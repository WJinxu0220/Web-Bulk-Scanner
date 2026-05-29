# web批量访问器
一个使用Python/Tkinter构建的用户友好的GUI工具，用于批量测试web url的可访问性。

##核心功能
✅批量URL可访问性检测（支持HTTP/HTTPS， GET/POST/HEAD方法）
✅并发请求处理（可自定义线程数）
✅灵活的配置（超时控制、重定向跟踪、请求重试）
✅丰富的错误反馈（超时/连接失败/SSL错误等）
✅结果导出（CSV/JSON格式）
✅线程安全的GUI更新（在并发执行期间不会崩溃）
✅跨平台支持（Windows/macOS/Linux）

## 核心功能
✅ 批量URL可达性检测（支持HTTP/HTTPS、GET/POST/HEAD请求方法）
✅ 并发请求处理（可自定义线程数）
✅ 灵活配置（超时控制、跟随跳转、请求重试）
✅ 丰富的错误反馈（超时/连接失败/SSL错误等）
✅ 结果导出（CSV/JSON格式）
✅ 线程安全的GUI更新（并发执行时不崩溃）
✅ 跨平台支持（Windows/macOS/Linux）

## Quick Start
1. Install dependencies: `pip install -r requirements.txt`
2. Run the tool: `python url_tester.py`
3. Prepare CSV file (required column: `url`, optional: `method`, `headers`, `cookies`)
4. Select CSV file → Configure parameters → Click "Start"

## 快速开始
1. 安装依赖：`pip install -r requirements.txt`
2. 运行工具：`python url_tester.py`
3. 准备CSV文件（必填列：`url`，可选列：`method`、`headers`、`cookies`）
4. 选择CSV文件 → 配置参数 → 点击"开始运行"
