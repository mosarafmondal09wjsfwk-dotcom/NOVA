NOVA Native Android project — Phase 3 starter

এটি Android Studio-তে খোলার জন্য source project, APK নয়।

Build করার ধাপ:
1. কম্পিউটারে Android Studio ইনস্টল করো।
2. Android Studio > Open > এই ZIP extract করা NOVA_Android_Studio_Project ফোল্ডার নির্বাচন করো।
3. Gradle Sync শেষ হতে দাও; SDK Platform 35 ও Android Gradle Plugin-এর জন্য ইন্টারনেট লাগতে পারে।
4. Build > Build Bundle(s) / APK(s) > Build APK(s)।
5. APK তৈরি হলে Android Studio-র notification থেকে locate করো।

এই ধাপে:
- Android native WebView shell আছে।
- আগের Phase 2 UI ও দুইটি Avatar asset যুক্ত।
- App offline assets থেকে interface দেখাতে পারে।

এখনো বাস্তব AI service/backend নেই; ফোনের সব অ্যাপ নিয়ন্ত্রণ, lock-screen wake word, speaker identity verification, WhatsApp integration, boot auto-start, default launcher mode, native screenshot capture, advanced emotions নেই।
এই প্রজেক্ট এখানে compile করে পরীক্ষা করা হয়নি কারণ এই build পরিবেশে Android SDK/Gradle নেই। Android Studio-তে sync/build ও বাস্তব ফোনে পরীক্ষা আবশ্যক।
