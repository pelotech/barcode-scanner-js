# barcode-scanner-js

A very simple pure JS library to allow use of a USB barcode scanner via standard eventing

```javascript
  const barcodeScanner = new BarcodeScanner();
  barcodeScanner.addEventListener('scan', (e) => {
    console.log(e.data);
  }
  ```
