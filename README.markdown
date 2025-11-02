# Fibonacci Sequence Generator

---

## English

### Overview
**Fibonacci Sequence Generator** is a **beautiful, modern desktop application** built with **PyQt6** that **generates and visualizes the Fibonacci sequence** with **mathematical elegance and educational clarity**.

Featuring **4 languages**, **5 stunning themes**, **RTL support**, **real-time output**, and **professional UI design**, this tool is perfect for **students, teachers, mathematicians, and developers** exploring the beauty of recursive mathematics.

---

### Key Features
- **Instant Fibonacci Generation** up to **1,000 terms**
- **Real-time Output** with indexed notation: `F(n) = value`
- **Mathematical Relations Displayed**:
  - `F(n) = F(n-1) + F(n-2)`
  - Base cases: `F(0)=0`, `F(1)=1`
  - Approaches the **Golden Ratio** (φ ≈ 1.6180339887)
- **Multilingual Interface**:
  - English, Persian (فارسی), Chinese (中文), Russian (Русский)
  - Full **RTL layout support** for Persian
- **5 Elegant Themes**:
  - System Default
  - Light
  - Dark
  - Red
  - Blue
- **Custom Styled Widgets**:
  - Gradient headers
  - Rounded corners
  - Hover effects
  - Modern Windows 11 aesthetic
- **Clipboard Integration** – One-click copy
- **Responsive & Scalable** UI
- **No external dependencies** beyond PyQt6

---

### Requirements
- Python 3.8+
- PyQt6

---

### Installation
1. Install PyQt6:
   ```bash
   pip install PyQt6
   ```
2. Save the script as `fibonacci_generator.py`
3. Run:
   ```bash
   python fibonacci_generator.py
   ```

---

### Usage
1. Select **language** and **theme**
2. Enter the **number of terms** (1–1000)
3. Click **"Generate Sequence"**
4. View the sequence in the output area
5. Use **"Copy to Clipboard"** to export
6. Explore the **mathematical relations** below

> **Educational Tip**: Watch how the ratio between consecutive terms approaches the **Golden Ratio** as `n` increases.

---

### Project Structure
- `fibonacci_generator.py` – Complete standalone application
- No config files or assets required

---

### Advanced Functions (Included in Code)
- `fibonacci_closed_form(n)` – Binet’s formula
- `fibonacci_extended(n)` – Negative indices support
- `fibonacci_modulo(n, m)` – Modular arithmetic
- `pisano_period(m)` – Pisano period calculation

---

### Contributing
Contributions are welcome!  
Ideas:
- Add **graph visualization** (matplotlib)
- Export to **CSV/PDF**
- Add **Lucas numbers**
- Support **Fibonacci primes**
- Add **animation** of growth

Submit a **Pull Request** with clear documentation.

---

### License
Released under the **MIT License**. Free for personal, educational, and commercial use.

---

## فارسی

### نمای کلی
**تولیدکننده دنباله فیبوناچی** یک برنامه دسکتاپ **زیبا و حرفه‌ای** است که با **PyQt6** ساخته شده و **دنباله فیبوناچی** را با **زیبایی ریاضی و وضوح آموزشی** تولید و نمایش می‌دهد.

با **۴ زبان**، **۵ تم خیره‌کننده**، **پشتیبانی از راست‌به‌چپ**، **خروجی لحظه‌ای** و **طراحی رابط کاربری حرفه‌ای**، این ابزار برای **دانش‌آموزان، معلمان، ریاضیدانان و برنامه‌نویسان** ایده‌آل است.

---

### ویژگی‌های کلیدی
- **تولید فوری دنباله** تا **۱۰۰۰ عدد**
- **نمایش لحظه‌ای** با فرمول: `F(n) = مقدار`
- **نمایش روابط ریاضی**:
  - `F(n) = F(n-1) + F(n-2)`
  - مقادیر پایه: `F(0)=0`, `F(1)=1`
  - نزدیک شدن به **نسبت طلایی** (φ ≈ ۱.۶۱۸۰۳۳۹۸۸۷)
- **رابط چندزبانه**:
  - فارسی، انگلیسی، چینی، روسی
  - پشتیبانی کامل از **چیدمان راست‌به‌چپ**
- **۵ تم زیبا**:
  - پیش‌فرض سیستم
  - روشن
  - تیره
  - قرمز
  - آبی
- **ویجت‌های سفارشی**:
  - سرصفحه گرادیانی
  - گوشه‌های گرد
  - افکت‌ها هنگام هاور
  - ظاهر مدرن ویندوز ۱۱
- **کپی در کلیپ‌بورد** با یک کلیک
- **رابط کاربری پاسخگو و مقیاس‌پذیر**
- **بدون وابستگی خارجی** جز PyQt6

---

### پیش‌نیازها
- پایتون ۳.۸ یا بالاتر
- PyQt6

---

### نصب
1. نصب PyQt6:
   ```bash
   pip install PyQt6
   ```
2. فایل را با نام `fibonacci_generator.py` ذخیره کنید
3. اجرا:
   ```bash
   python fibonacci_generator.py
   ```

---

### نحوه استفاده
1. **زبان** و **تم** را انتخاب کنید
2. **تعداد اعضا** را وارد کنید (۱ تا ۱۰۰۰)
3. روی **«تولید دنباله»** کلیک کنید
4. دنباله را در ناحیه خروجی ببینید
5. از **«کپی در کلیپ‌بورد»** برای خروجی گرفتن استفاده کنید
6. **روابط ریاضی** زیر را مطالعه کنید

> **نکته آموزشی**: ببینید چگونه نسبت بین اعداد متوالی با افزایش `n` به **نسبت طلایی** نزدیک می‌شود.

---

### ساختار پروژه
- `fibonacci_generator.py` – برنامه کامل و مستقل
- بدون نیاز به فایل تنظیمات یا منابع خارجی

---

### توابع پیشرفته (در کد موجود)
- `fibonacci_closed_form(n)` – فرمول بسته بینه
- `fibonacci_extended(n)` – پشتیبانی از اندیس منفی
- `fibonacci_modulo(n, m)` – عملیات مدولار
- `pisano_period(m)` – دوره پیزانو

---

### مشارکت
مشارکت شما بسیار ارزشمند است!  
ایده‌ها:
- افزودن **نمودار بصری** (matplotlib)
- خروجی به **CSV/PDF**
- افزودن **اعداد لوکاس**
- پشتیبانی از **اعداد اول فیبوناچی**
- افزودن **انیمیشن رشد**

درخواست کشش (Pull Request) با مستندات واضح ارسال کنید.

---

### مجوز
تحت **مجوز MIT** منتشر شده است. آزاد برای استفاده شخصی، آموزشی و تجاری.

---

## 中文

### 项目概览
**斐波那契数列生成器** 是一款**优雅现代的桌面应用程序**，使用 **PyQt6** 构建，以**数学美感和教育清晰度**生成并展示**斐波那契数列**。

支持 **4 种语言**、**5 种精美主题**、**从右到左布局**、**实时输出**和**专业级界面设计**，适用于**学生、教师、数学家和开发者**探索递归数学之美。

---

### 核心功能
- **即时生成**多达 **1,000 项**
- **实时输出**，格式：`F(n) = 值`
- **显示数学关系**：
  - `F(n) = F(n-1) + F(n-2)`
  - 基础情况：`F(0)=0`, `F(1)=1`
  - 趋近于**黄金比例** (φ ≈ 1.6180339887)
- **多语言界面**：
  - 中文、英语、波斯语、俄语
  - 完整支持**从右到左 (RTL)** 布局
- **5 种优雅主题**：
  - 系统默认
  - 浅色
  - 深色
  - 红色
  - 蓝色
- **自定义美化组件**：
  - 渐变标题栏
  - 圆角设计
  - 悬停动画
  - 现代 Windows 11 风格
- **一键复制到剪贴板**
- **响应式与可缩放**界面
- **仅依赖 PyQt6**

---

### 系统要求
- Python 3.8+
- PyQt6

---

### 安装步骤
1. 安装 PyQt6：
   ```bash
   pip install PyQt6
   ```
2. 将脚本保存为 `fibonacci_generator.py`
3. 运行：
   ```bash
   python fibonacci_generator.py
   ```

---

### 使用指南
1. 选择**语言**和**主题**
2. 输入**项数**（1–1000）
3. 点击**“生成序列”**
4. 在输出区查看数列
5. 使用**“复制到剪贴板”**导出
6. 阅读下方**数学关系**

> **教育提示**：观察相邻项的比率如何随 `n` 增大而趋近于**黄金比例**。

---

### 项目结构
- `fibonacci_generator.py` – 完整独立应用程序
- 无需配置文件或外部资源

---

### 高级函数（代码中包含）
- `fibonacci_closed_form(n)` – 比内公式
- `fibonacci_extended(n)` – 支持负索引
- `fibonacci_modulo(n, m)` – 模运算
- `pisano_period(m)` – 皮萨诺周期

---

### 贡献代码
我们欢迎贡献！  
建议：
- 添加**可视化图表**（matplotlib）
- 导出为 **CSV/PDF**
- 添加**卢卡斯数列**
- 支持**斐波那契素数**
- 添加**增长动画**

请提交带有详细说明的 **Pull Request**。

---

### 许可证
基于 **MIT 许可证**发布。个人、教育和商业用途完全免费。