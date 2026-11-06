LUCKY WIN — Android Studio Project

এই ZIP-টি Android Studio-তে খোলার জন্য Android app source project।
এটি এখনো তৈরি করা APK ফাইল নয়।

APK বানানোর ধাপ:
1. কম্পিউটারে Android Studio ইনস্টল করুন।
2. Android Studio থেকে Open নির্বাচন করে এই ZIP extract করা LuckyWin ফোল্ডারটি খুলুন।
3. Gradle sync শেষ হতে দিন।
4. Build > Build Bundle(s) / APK(s) > Build APK(s) নির্বাচন করুন।
5. সফল হলে app/build/outputs/apk/debug/app-debug.apk পাওয়া যাবে।

অ্যাপটি WebView-এর ভেতরে স্থানীয় index.html চালায়। তাই বর্তমান গেমগুলো offline-এ চলে।
Online mode বোতামটি আপাতত demo toggle মাত্র; কোনো cloud account বা server sync নেই।
Email/Phone/Google login-ও demo UI; বাস্তব Authentication এখনো যুক্ত নয়।
বাস্তব লগইন চালু করতে Firebase Authentication বা নিরাপদ backend, OAuth configuration,
OTP provider এবং database security rules সেটআপ করতে হবে।

এই প্রজেক্ট build করতে Android Studio, Android SDK এবং JDK 17 প্রয়োজন।
