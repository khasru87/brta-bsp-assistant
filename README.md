# BRTA BSP Assistant Android - Mobile Build

এটি ফোন থেকে GitHub Actions ব্যবহার করে APK বানানোর জন্য প্রস্তুত করা project।

মূল app features:
- Local Room database
- Applicant management
- BSP website launcher
- BSP registration launcher
- Manual CAPTCHA/OTP workflow

Mobile build:
- `.github/workflows/build-apk.yml` automatically builds a debug APK.
- বিস্তারিত `MOBILE_BUILD.md` দেখুন।

নিরাপত্তা:
BSP-এর CAPTCHA, OTP বা security controls bypass করা হয় না।
