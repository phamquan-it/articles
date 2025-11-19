# Hướng dẫn Lập trình Node.js từ Cơ bản đến Nâng cao

![Node.js Logo](https://nodejs.org/static/images/logo.svg)

## Giới thiệu

Chào mừng bạn đến với series hướng dẫn lập trình Node.js toàn diện! Đây là lộ trình hoàn hảo cho những ai muốn trở thành Node.js Developer chuyên nghiệp.

> **📌 Lưu ý:** Series này phù hợp cho cả người mới bắt đầu và những developer muốn củng cố kiến thức Node.js.

## 🎯 Mục tiêu khóa học

Sau khi hoàn thành series này, bạn sẽ:

- ✅ Hiểu rõ kiến trúc và cách hoạt động của Node.js
- ✅ Xây dựng ứng dụng web với Express.js
- ✅ Làm việc với database (MongoDB, MySQL)
- ✅ Triển khai ứng dụng lên production
- ✅ Viết code clean, bảo mật và hiệu suất cao

## 📚 Nội dung chính

### Phần 1: Nhập môn Node.js
1. **Giới thiệu Node.js & Ecosystem**
   - Node.js là gì? Tại sao nên sử dụng?
   - Kiến trúc Event-Driven và Non-blocking I/O
   - Cài đặt môi trường phát triển

2. **JavaScript Fundamentals cho Node.js**
   ```javascript
   // ES6+ Features quan trọng
   const asyncFunction = async () => {
     const result = await fetchData();
     return result;
   };

   // Module system
   const express = require('express');
   import { Router } from 'express';
