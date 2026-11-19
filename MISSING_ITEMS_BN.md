# NOVA — অনুপস্থিত অংশের অবস্থা

এই ফাইলে বর্তমান Project-এ কী আছে এবং কী এখনো যোগ করা সম্ভব হয়নি তা পরিষ্কারভাবে লেখা হলো।

## যোগ করা হয়েছে
- আগের কথোপকথনে দেওয়া `1000031455.png` রেফারেন্স ছবিটি `app/src/main/res/drawable-nodpi/nova_normal_reference.png` নামে Android resource হিসেবে রাখা হয়েছে।
- Part 4–8-এর মূল ZIP ফাইলগুলো `reference/original_parts_4_to_8/`-এ রাখা আছে।

## এখনো অনুপস্থিত / অসম্পূর্ণ
- Part 1, 2, 3-এর আসল source ZIP বা সম্পূর্ণ code এই Library-তে পাওয়া যায়নি; তাই সেগুলোর আসল implementation হুবহু ফিরিয়ে আনা সম্ভব নয়।
- Normal + SHADOW split dashboard-এর সম্পূর্ণ original artwork/layout source বর্তমান Project-এ নেই। পাওয়া reference PNG-টি রাখা হয়েছে, কিন্তু সেটি একা সম্পূর্ণ split-screen design নয়।
- অনলাইন AI-এর জন্য server/API endpoint ও অনুমোদিত API credential নেই। এগুলো ছাড়া সত্যিকারের online AI conversation চালু করা যাবে না। কোনো secret key APK-তে hard-code করা উচিত নয়।
- Android SDK এবং Gradle build environment এই build container-এ নেই; তাই APK compile/test করা যায়নি।

## বর্তমান কার্যকারিতা
- বাংলা speech recognition ও text-to-speech (ফোনের speech engine সমর্থন করলে)
- স্থানীয় rule-based কিছু উত্তর
- Wi-Fi/Bluetooth/Settings panel খোলা
- Battery percentage দেখানো
- Android-এর screen-capture consent নিয়ে screenshot capture করার চেষ্টা

এটি এখনো পূর্ণাঙ্গ NOVA assistant নয় এবং installable APK হিসেবে verified নয়।
