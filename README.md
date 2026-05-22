# portswigger-notes

هذا المشروع يحتوي على ملاحظاتي في مجال الأمن السيبراني، خصوصاً دروس PortSwigger.

## المحتويات:
- XSS
- SQL Injection
- Authentication
- Notes and Labs

## الهدف:
فهم الثغرات وتطبيقها بشكل عملي أثناء التعلم.

01-XSS.md

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