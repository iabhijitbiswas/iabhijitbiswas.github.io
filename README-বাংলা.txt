অভিজিৎ বিশ্বাস — দুই ফোল্ডারের ওয়েবসাইট

ফাইল:
index.html = হোমপেজ
assets/abhijit-cover.png = আপনার পাঠানো ছবি (প্রোফাইল ও হালকা ব্যাকগ্রাউন্ড)
photos/marriage.html = বিবাহের স্লাইডশো
photos/others.html = অন্যান্য ছবির স্লাইডশো

GitHub-এ আপনার iabhijitbiswas.github.io repository-তে:
1) পুরোনো index.html-এর বদলে এই index.html আপলোড/replace করুন।
2) assets ফোল্ডারসহ abhijit-cover.png আপলোড করুন।
3) photos ফোল্ডারের marriage.html ও others.html আপলোড করুন।
একই নাম ও ফোল্ডার-পথ বজায় রাখুন।

Drive-এর ছবি যোগ:
1) Google Drive-এ ছবির Share > General access > Anyone with the link > Viewer করুন।
2) লিংক https://drive.google.com/file/d/FILE_ID/view হলে FILE_ID অংশটি কপি করুন।
3) photos/marriage.html-এ বিবাহের ID এবং photos/others.html-এ অন্যান্য ছবির ID PHOTO_IDS তালিকায় বসান।
4) GitHub-এ Commit changes করুন।

উদাহরণ:
const PHOTO_IDS = ["ABC123xyz", "DEF456uvw"];

হোম: https://iabhijitbiswas.github.io/
বিবাহ: https://iabhijitbiswas.github.io/photos/marriage.html
অন্যান্য: https://iabhijitbiswas.github.io/photos/others.html

সতর্কতা: Anyone with the link করলে লিংক জানা যে কেউ ছবিগুলো দেখতে পারে। QR Code গোপনীয়তা বা পাসওয়ার্ড সুরক্ষা নয়। Drive-এ অনেক ছবি হলে লোডিং সীমাবদ্ধতা হতে পারে; আগে ২-৩টি ছবি দিয়ে পরীক্ষা করুন।
