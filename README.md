## Exchange Rate

Select countries to get the exchange rate for a specific amount

## Project Specifications

- Display UI with 2 select lists for countries and 2 inputs for amounts
- Fetch exchange rates from API (https://api.exchangerate-api.com)
- Display the values for both countries
- Update values on amount change
- Swap country rates

## 架構

- index.html都是放HTML，也就是所謂的靜態檔案，沒有任何邏輯
- script.js 裡面有抓匯率API(API來源就是https://api.exchangerate-api.com)的程式碼，幣值換算的邏輯也藏在裡面
- style.css 裡面放美化HTML的CODE
- 當使用者按下任何按鍵都會觸發script.js裡面的calculate函數(透過document.getElementById(XXX)來將HTML和資料去做雙向綁定)
