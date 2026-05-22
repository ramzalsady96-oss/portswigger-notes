# XSS - Cross Site Scripting

## ما هي الثغرة؟
هي ثغرة تسمح للمهاجم بإدخال JavaScript في الموقع.

## الأنواع:
- Reflected XSS
- Stored XSS
- DOM XSS

## مثال:
```html
<script>alert('XSS')</script>