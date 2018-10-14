---
title: Finding a Remainder in JavaScript
localeTitle: العثور على البقية في جافا سكريبت
---
يعطي _عامل الباقي_ `%` الباقي من قسم رقمين.

## مثال

 `5 % 2 = 1 because 
 Math.floor(5 / 2) = 2 (Quotient) 
 2 * 2 = 4 
 5 - 4 = 1 (Remainder) 
` 

## استعمال

في الرياضيات ، يمكن التحقق من الرقم حتى أو فردي عن طريق التحقق من الجزء المتبقي من تقسيم الرقم إلى 2.

 `17 % 2 = 1 (17 is Odd) 
 48 % 2 = 0 (48 is Even) 
` 

**ملاحظة** لا تخلط بينه وبين _modulus_ `%` لا يعمل بشكل جيد مع الأرقام السالبة.