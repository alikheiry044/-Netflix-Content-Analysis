
# -Netflix-Content-Analysis
README (English)
🎬 Netflix Content Analysis

This project explores the Netflix Titles dataset using Python, Pandas, and Matplotlib. The goal is to clean the data, perform exploratory data analysis (EDA), and visualize trends in Netflix movies and TV shows.

📊 Project Overview

The notebook covers:

Data loading and inspection
Data cleaning and preprocessing
Missing value handling
Date conversion and feature engineering
Content duration analysis
Content type distribution (Movies vs TV Shows)
Yearly content growth analysis
Genre analysis
Country-wise content distribution
Rating distribution analysis
Movie duration distribution
TV Show season distribution
🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
📂 Dataset

Dataset used:

Netflix Titles Dataset

Contains information about Netflix Movies and TV Shows.
Features include:
Title
Type
Director
Cast
Country
Date Added
Release Year
Rating
Duration
Genre
🔧 Data Cleaning

The following preprocessing steps were performed:

Removed duplicate records
Converted date_added to datetime format
Filled missing values in:
Director
Cast
Country
Rating
Removed rows with missing duration or date information
Extracted:
Added Year
Duration Type (Minutes / Seasons)
Duration Value
📈 Visualizations
1. Content Type Distribution

Comparison between:

Movies
TV Shows
2. Content Added Per Year

Trend of Netflix content growth over time.

3. Top Genres

Most popular genres available on Netflix.

4. Top Countries

Countries producing the highest amount of Netflix content.

5. Rating Analysis

Distribution of content ratings such as:

TV-MA
TV-14
PG-13
R
Others
6. Movie Duration Distribution

Histogram of movie lengths.

7. TV Show Seasons Distribution

Analysis of the number of seasons in TV Shows.

8. Rating by Content Type

Comparison of ratings across Movies and TV Shows.

9. Content Growth by Type

Yearly growth trend for Movies and TV Shows.

📌 Key Insights
Movies significantly outnumber TV Shows on Netflix.
Netflix content experienced rapid growth after 2015.
Drama and International Movies are among the most common genres.
The United States contributes the largest share of content.
Most content is targeted toward mature audiences (TV-MA, TV-14).
Most movies have durations between 80 and 120 minutes.
🚀 How to Run
pip install pandas numpy matplotlib seaborn

Open the notebook:

jupyter notebook Netflix.ipynb

Run all cells sequentially.

README (فارسی)
🎬 تحلیل محتوای نتفلیکس

این پروژه به بررسی و تحلیل داده‌های نتفلیکس با استفاده از پایتون، Pandas و Matplotlib می‌پردازد. هدف پروژه پاکسازی داده‌ها، تحلیل اکتشافی (EDA) و استخراج بینش‌های مفید از فیلم‌ها و سریال‌های موجود در نتفلیکس است.

📊 معرفی پروژه

در این نوت‌بوک موارد زیر بررسی شده‌اند:

بارگذاری و بررسی اولیه داده‌ها
پاکسازی داده‌ها
مدیریت داده‌های گمشده
تبدیل تاریخ‌ها
استخراج ویژگی‌های جدید
تحلیل مدت زمان محتوا
مقایسه فیلم‌ها و سریال‌ها
بررسی رشد محتوای نتفلیکس در طول زمان
تحلیل ژانرها
تحلیل کشورهای تولیدکننده محتوا
تحلیل رده‌بندی سنی (Rating)
🛠 ابزارهای استفاده شده
Python
Pandas
NumPy
Matplotlib
Seaborn
📂 دیتاست

دیتاست مورد استفاده شامل اطلاعات فیلم‌ها و سریال‌های نتفلیکس است.

ویژگی‌های اصلی:

عنوان (Title)
نوع محتوا (Movie / TV Show)
کارگردان
بازیگران
کشور تولیدکننده
تاریخ اضافه شدن به نتفلیکس
سال انتشار
رده‌بندی سنی
مدت زمان
ژانر
🔧 مراحل پاکسازی داده‌ها

در این پروژه:

داده‌های تکراری بررسی شدند.
ستون date_added به فرمت تاریخ تبدیل شد.

مقادیر گمشده در ستون‌های:

Director
Cast
Country
Rating

تکمیل شدند.

رکوردهای فاقد تاریخ یا مدت زمان حذف شدند.

ویژگی‌های جدیدی مانند:

سال اضافه شدن محتوا
نوع مدت زمان (دقیقه یا فصل)
مقدار عددی مدت زمان

استخراج شدند.

📈 تحلیل‌ها و نمودارها
1. تعداد فیلم‌ها و سریال‌ها

مقایسه تعداد Movie و TV Show.

2. تعداد محتوا در هر سال

بررسی روند رشد نتفلیکس در سال‌های مختلف.

3. محبوب‌ترین ژانرها

نمایش ۱۰ ژانر برتر نتفلیکس.

4. کشورهای برتر تولیدکننده محتوا

بررسی بیشترین سهم تولید محتوا بر اساس کشور.

5. تحلیل رده‌بندی سنی

بررسی فراوانی Ratingهای مختلف.

6. توزیع مدت زمان فیلم‌ها

بررسی طول فیلم‌ها با استفاده از هیستوگرام.

7. توزیع تعداد فصل‌های سریال‌ها

تحلیل تعداد فصل‌های TV Showها.

8. مقایسه Rating بر اساس نوع محتوا

مقایسه فیلم‌ها و سریال‌ها از نظر رده‌بندی سنی.

9. روند رشد فیلم و سریال در طول زمان

مقایسه روند اضافه شدن Movies و TV Shows در سال‌های مختلف.

📌 نتایج مهم
تعداد فیلم‌ها بیشتر از سریال‌ها است.
رشد محتوای نتفلیکس پس از سال 2015 افزایش چشمگیری داشته است.
ژانرهای Drama و International Movies جزو محبوب‌ترین دسته‌ها هستند.
آمریکا بیشترین سهم تولید محتوا را دارد.
بخش بزرگی از محتوا دارای رده‌بندی TV-MA و TV-14 است.
بیشتر فیلم‌ها بین 80 تا 120 دقیقه زمان دارند.
▶️ اجرا

ابتدا کتابخانه‌ها را نصب کنید:

pip install pandas numpy matplotlib seaborn

سپس نوت‌بوک را اجرا کنید:

jupyter notebook Netflix.ipynb

و سلول‌ها را به ترتیب اجرا نمایید.
