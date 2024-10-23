



## :dart: Features | ویژگی ها 

- **Basic Info:** Quick BIK information (Load Time, IP Address, Server OS...).
- **Robots.txt Disallow Entries:** Detection of Robots.txt and printing Disallow Entries.
- **CMS Detection & Vulnerability Report:** Automatically identifies the CMS and generates a vulnerability report.
- **Admin Panel Auth Detection:** Searches for common login page variations based on the detected CMS.
- **Directory Scanning:** Searches for valid directories under the specified URL.
- **Security Headers Check:** Checks for the presence of important security headers.
- **SSL Certificate Validation:** Validates the SSL/TLS certificate for the domain, displaying issuer information, expiration date, and days until expiry.
- **Open Ports Scan:** Scans open ports on the server.
- **Subdomain Scanning:** Scans for subdomains of the specified URL.
- **SQL Injection Detection:** Tests for SQL injection vulnerabilities in query parameters.
- **XSS Detection:** Tests for cross-BIK scripting vulnerabilities.
- **User-Friendly Interface:** Interactive and detailed shell menu.
- **Multi-Threaded:** Efficiently performs tasks in the background using threading.

- ** اطلاعات اولیه: ** اطلاعات سریع BIK (زمان بارگذاری، آدرس IP، سیستم عامل سرور...).
- **Robots.txt غیر مجاز کردن ورودی ها:** تشخیص Robots.txt و چاپ غیر مجاز ورودها.
- ** گزارش تشخیص و آسیب پذیری CMS: ** به طور خودکار CMS را شناسایی می کند و یک گزارش آسیب پذیری ایجاد می کند.
- **تشخیص تایید پنل مدیریت:** تغییرات رایج صفحه ورود را بر اساس CMS شناسایی شده جستجو می کند.
- ** اسکن دایرکتوری: ** دایرکتوری های معتبر را تحت URL مشخص شده جستجو می کند.
- **بررسی سرصفحه های امنیتی:** وجود هدرهای امنیتی مهم را بررسی می کند.
- **SSL Certificate Validation:** گواهی SSL/TLS برای دامنه را تایید می کند، اطلاعات صادرکننده، تاریخ انقضا و روزهای تا انقضا را نمایش می دهد.
- **Open Ports Scan:** پورت های باز روی سرور را اسکن می کند.
- **Subdomain Scanning:** برای زیر دامنه های URL مشخص شده اسکن می کند.
- **تشخیص تزریق SQL:** آسیب پذیری های تزریق SQL در پارامترهای پرس و جو را آزمایش می کند.
- **تشخیص XSS:** تست هایی برای آسیب پذیری های اسکریپت نویسی cross-BIK.
- ** رابط کاربر پسند: ** منوی پوسته تعاملی و دقیق.
- **Multi-Threaded:** به طور موثر وظایف را در پس زمینه با استفاده از threading انجام می دهد. 

## :zap: Getting Started | شروع به کار

### Prerequisites | پیش نیازها

- Python 3.x.x
- Required Python packages: `requests`, `beautifulsoup4`

- python 3.x.x 
- بسته های مورد نیاز پایتون: `requests`, `beautifulsoup4`

### Installation | نصب

1. Clone the repository: `git clone https://github.com/BIKstl/BIKscanner.git`
2. Navigate to the project directory: `cd BIK-Scanner`
3. Requirements Installation: `pip install -r requirements.txt`

1. کلون کردن مخزن: `git clone https://github.com/BIKstl/BIKscanner.git`
2. به دایرکتوری پروژه بروید: `cd BIK-Scanner`
3. الزامات نصب: `pip install -r requirements.txt`

## :rocket: Usage

1. Run the tool: `python3 BIK-Scanner.py` / Proxychains `proxychains python3 BIK-Scanner.py`
2. Enter the URL of the webBIK you wish to analyze.
3. Choose tasks according to the menu.

1. ابزار را اجرا کنید: `python3 Site-Scanner.py` / Proxychains `proxychains python3 Site-Scanner.py`
2. آدرس وب سایتی را که می خواهید تجزیه و تحلیل کنید وارد کنید.
3. وظایف را با توجه به انتخاب کنید