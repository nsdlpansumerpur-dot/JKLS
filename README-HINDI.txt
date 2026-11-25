J.K. Self Study Hub - GitHub se APK banane ka project

1) GitHub par naya repository banayein: JK-Self-Study-Hub
2) Is ZIP ke andar ki sabhi files/folders repository ke main page par Add file > Upload files se upload karein.
3) Commit changes dabayein. Workflow .github/workflows/build-apk.yml apne aap chalega.
4) Repository me Actions tab kholein.
5) Sabse upar 'Build Android APK' workflow run kholein (green tick aane ka wait karein).
6) Run page ke neeche Artifacts me JK-Self-Study-Hub-debug-apk.zip download karein.
7) ZIP extract karke app-debug.apk phone me bhejein aur install karein.

Note: Ye WebView app aapke diye hue Google Apps Script URL ko kholta hai.
Agar site Google sign-in/third-party cookie ya embedded-browser restrictions lagati hai,
to kuch login flows WebView me kaam na karein. Public deployment / access settings check karein.
APK debug-signed hai; Play Store release ke liye alag signing zaroori hogi.
