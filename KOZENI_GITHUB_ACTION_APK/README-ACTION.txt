KOZENI - GitHub Actions APK Builder

Upload ketiga file/folder ini ke ROOT repo Kozeni:
- package.json
- capacitor.config.json
- .github/workflows/build-apk.yml

Setelah di-commit:
1. Buka tab Actions di GitHub.
2. Pilih "Build Kozeni APK".
3. Klik "Run workflow".
4. Tunggu job selesai sampai hijau.
5. Buka hasil workflow.
6. Di bagian Artifacts, download "Kozeni-APK".
7. Extract ZIP artifact, lalu install app-debug.apk di Android.

Package ID:
com.kozeni.finance

APK ini membungkus file HTML Kozeni langsung di dalam aplikasi, jadi tidak bergantung pada Netlify.
