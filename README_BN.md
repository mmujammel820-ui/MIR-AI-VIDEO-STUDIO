# MIR AI VIDEO STUDIO — প্রাথমিক Android প্রজেক্ট

## গুরুত্বপূর্ণ
এটি একটি প্রাথমিক Android অ্যাপের UI ও cloud-build source। Text-to-Video, Image-to-Video, Face Swap, Talking Photo-এর আসল AI মডেল/সার্ভার এখনো যুক্ত করা হয়নি। তাই এই APK-টি এখনই AI ভিডিও তৈরি বা Face Swap করতে পারবে না। কোনো AI সার্ভিসকে সীমাহীন ও স্থায়ীভাবে ফ্রি ধরে নেওয়া হয়নি।

## APK তৈরি (শুধু Android ফোন দিয়ে)
1. GitHub-এ `mmujammel820-ui/MIR-AI-VIDEO-STUDIO` repository খুলুন।
2. `Add file` → `Upload files` চাপুন।
3. ZIP ফাইলটি আগে ফোনে Extract করুন; ZIP-এর ভেতরের সব ফাইল ও `.github` ফোল্ডার repository-র root-এ upload করুন।
4. Commit changes করুন।
5. GitHub repository-তে Actions tab খুলুন। `Build MIR AI VIDEO STUDIO APK` workflow চলবে।
6. Build সফল হলে workflow run-এর নিচে Artifacts থেকে `MIR-AI-VIDEO-STUDIO-debug-apk` ডাউনলোড করে Extract করুন।
7. `app-debug.apk` ইনস্টল করুন। Android অনুমতি চাইলে এই উৎস থেকে install অনুমতি দিন।

## Build configuration
- Android Gradle Plugin 8.7.3
- Gradle 8.9
- JDK 17
- Minimum Android 6.0 (API 23)
- Target Android 15 (API 35)
