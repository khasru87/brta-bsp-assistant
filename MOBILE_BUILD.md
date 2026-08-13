# মোবাইল থেকে APK Build

## পদ্ধতি: GitHub Actions

1. ফোনের browser থেকে GitHub-এ login করুন।
2. New repository তৈরি করুন, যেমন `brta-bsp-assistant`.
3. এই project-এর সব file repository-তে upload করুন।
4. `main` branch-এ upload হলে GitHub Actions নিজে build শুরু করবে।
5. GitHub → Actions → `Build Android APK` → সর্বশেষ successful run খুলুন।
6. নিচে `Artifacts` থেকে `BRTA-BSP-Assistant-debug` download করুন।
7. ZIP extract করে `app-debug.apk` ফোনে install করুন।

## যদি Actions automatic না চলে
GitHub → Actions → Build Android APK → Run workflow চাপুন।

## গুরুত্বপূর্ণ
এই workflow debug APK তৈরি করে। Production/public release-এর আগে signing key, secure storage, authentication, privacy policy এবং release build configuration যোগ করা উচিত।
