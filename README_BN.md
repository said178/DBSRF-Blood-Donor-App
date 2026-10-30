# DBSRF Android — Mobile Cloud Build Project

এই ZIP-এ প্রাথমিক Expo source project এবং আপনার দেওয়া অফিসিয়াল লোগো যুক্ত করা হয়েছে।

**এটি এখনো APK নয়।** সদস্য নিবন্ধন, donor list এবং role panel প্রোটোটাইপ; তথ্য স্থায়ীভাবে অনলাইনে সংরক্ষিত হয় না। OTP SMS, online database, secure login এবং server-side role permissions এখনো যুক্ত করতে হবে।

## Android ফোন দিয়ে APK তৈরির ধাপ
1. ZIP ডাউনলোড করে ফোনে Extract করুন।
2. GitHub-এ নতুন repository তৈরি করে extracted project-এর ফাইল upload করুন।
3. Expo.dev-এ account খুলে GitHub দিয়ে sign in করুন।
4. Expo EAS Build-এ project connect করে Android preview/internal APK build চালান। `eas.json`-এ preview output APK হিসেবে সেট করা।
5. Build সম্পন্ন হলে Expo dashboard থেকে APK download করে install করুন।

Expo account login ও build configuration লাগবে। Play Store-এর জন্য production AAB build ব্যবহার করুন।

## নির্ধারিত নিয়ম
- Admin: শুধু প্রতিষ্ঠাতা ও সভাপতি
- Moderator: নিজ নিজ জেলা/উপজেলা
- সদস্য আবেদন: Moderator যাচাই → Admin চূড়ান্ত অনুমোদন
- Login: মোবাইল নম্বর + OTP (SMS gateway না যুক্ত হওয়া পর্যন্ত বাস্তব OTP পাঠানো যাবে না)
