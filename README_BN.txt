Glass Pull Calculator — Android Studio project

এই ফোল্ডারটি Android Studio-তে খুলে APK তৈরি করা যাবে। HTML ফাইলটি app/src/main/assets/index.html-এ রাখা আছে।

APK তৈরির ধাপ:
1. কম্পিউটারে Android Studio ইনস্টল করুন।
2. Android Studio > Open নির্বাচন করে এই GlassPullAndroid ফোল্ডারটি খুলুন।
3. Gradle Sync শেষ হওয়া পর্যন্ত অপেক্ষা করুন।
4. Build > Build Bundle(s) / APK(s) > Build APK(s) চাপুন।
5. সফল হলে app/build/outputs/apk/debug/app-debug.apk ফাইলটি পাবেন।
6. APK ফোনে পাঠিয়ে ইনস্টল করুন। প্রয়োজন হলে Android সেটিংসে ওই উৎস থেকে ইনস্টল করার অনুমতি দিন।

নোট:
- এই ZIP-এ Android Studio project source আছে; APK বাইনারি আগে থেকে বিল্ড করা নেই। APK তৈরি করতে Android Studio ও Android SDK-সহ কম্পিউটার লাগবে।
- HTML ফাইলটি অ্যাপের ভিতরে থাকে, তাই ক্যালকুলেটরের মূল পেজ অফলাইনে খোলার জন্য ইন্টারনেট লাগে না।
- localStorage ডেটা অ্যাপের নিজস্ব স্টোরেজে থাকবে। অ্যাপের data clear বা uninstall করলে তা মুছে যেতে পারে; নিয়মিত রিপোর্ট ব্যাকআপ রাখুন।
