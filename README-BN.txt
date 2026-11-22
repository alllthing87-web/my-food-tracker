MY FOOD TRACKER – INSTALLABLE PWA

এটি একটি PWA (Progressive Web App)। HTTPS-এ publish করলে Android Chrome থেকে Install করা যাবে।

সহজ উপায়: GitHub Pages
1. GitHub-এ একটি account খুলে New repository তৈরি করো (যেমন my-food-tracker)।
2. এই ZIP extract করে সব ফাইল ও icons folder repository-তে upload করো। index.html যেন repository-র root-এ থাকে।
3. Repository Settings > Pages > Build and deployment থেকে Deploy from a branch বেছে নাও।
4. Branch হিসেবে main এবং folder হিসেবে /(root) নির্বাচন করে Save করো।
5. GitHub যে https://...github.io/... website address দেবে, Android Chrome-এ সেটি খোলো।
6. Chrome-এর menu (⋮) > Install app অথবা Add to Home screen চাপো।

নোট:
- PWA-টি offline-এও খোলার জন্য service worker দেওয়া আছে।
- মিলের রেকর্ড ওই ফোনের ওই browser-এ local save হয়; cloud sync নেই।
- Browser data মুছে গেলে রেকর্ড হারাতে পারে; CSV download করে backup রেখো।
- এটি Android-এ Home Screen app হিসেবে install হবে; APK ফাইল নয়।
