Web Automation KASIR AJA
Create Web Automation untuk KasirAja menggunakan WebDriver.io & Cucumber.

Tech stack
WebDriver.io
Cucumber
HTML Nice Reports
Install library
install seluruh library yang dibutuhkan :

  npm install
How to run ?
npm run wdio
Run "All Feature and Test Case" dengan comand :

npm run wdio
Run "only specific feature" dengan comand :

npm run wdio-login
npm run wdio-register
Run "only specific scenario" dengan comand :

npm run wdio-negative
*Untuk detail script lainnya dapat dilihat pada file package.json

Reporting
Reports secara menyeluruh akan tersimpan pada direktori ./reports/html/html-reports

Di dalam direktori tersebut terdapat :

File HTML report untuk masing-masing feature.
Satu file HTML Master Report yang merupakan gabungan dari seluruh feature.
Setiap kali ditemukan hasil failed saat menjalankan sebuah Test Case, akan otomatis tercapture dan disimpan pada direktori ./reports/screenshot/ dengan nama file berdasarkan timestamp.

Berikut spesifik direktorinya :

  html-reports  : "/reports/html/html-reports" --> open file.html pada browser
  screenshot    : "/reports/screenshot/"
