# Hotel Reservation Database System

## Project Overview
This project is a simple relational database system for managing hotel reservations using MySQL. It demonstrates core database concepts such as table design, relationships, and SQL queries.

## Technologies Used
- MySQL Community Server
- SQL (Structured Query Language)

## Database Structure

The system contains four main tables:
- customers
- rooms
- reservations
- payments

## Relationships
- A customer can make multiple reservations
- Each reservation is linked to one room
- Each reservation has a payment record

## Features Demonstrated
- Table creation with primary and foreign keys
- Data insertion
- JOIN queries across multiple tables
- Aggregation (total revenue calculation)
- Filtering data

## How to Use
1. Run `schema.sql` to create the database structure
2. Run `sample_data.sql` to insert test data
3. Run `queries.sql` to test functionality
------------------------------------
# سیستم پایگاه داده رزرو هتل

## بررسی اجمالی پروژه
این پروژه یک سیستم پایگاه داده رابطه‌ای ساده برای مدیریت رزرو هتل با استفاده از MySQL است. این پروژه مفاهیم اصلی پایگاه داده مانند طراحی جدول، روابط و پرس‌وجوهای SQL را نشان می‌دهد.

## فناوری‌های مورد استفاده
- سرور جامعه MySQL
- SQL (زبان پرس‌وجوی ساختاریافته)

## ساختار پایگاه داده

این سیستم شامل چهار جدول اصلی است:
- مشتریان
- اتاق‌ها
- رزروها
- پرداخت‌ها

## روابط
- یک مشتری می‌تواند چندین رزرو انجام دهد
- هر رزرو به یک اتاق مرتبط است
- هر رزرو دارای یک رکورد پرداخت است

## ویژگی‌های نمایش داده شده
- ایجاد جدول با کلیدهای اصلی و خارجی
- درج داده‌ها
- اتصال پرس‌وجوها در چندین جدول
- تجمیع (محاسبه کل درآمد)
- فیلتر کردن داده‌ها

## نحوه استفاده
۱. اجرای `schema.sql` برای ایجاد ساختار پایگاه داده
۲. اجرای `sample_data.sql` برای درج داده‌های آزمایشی
۳. اجرای `queries.sql` برای آزمایش عملکرد
