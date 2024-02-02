# Bug HMR of css defect when component is out of root folder

Cannot be reproduces on Stackblitz

Run application and open browser

```
npm install && npm run dev
```

Go to component `ButtonOutOfRoot` and change the background-color from yellow to gray.
In the browser the background color should be changed via HMR.
