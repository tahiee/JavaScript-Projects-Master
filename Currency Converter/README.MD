You need to get your own api key replace it in index.js file on line 28 :

const response = await fetch(`https://v6.exchangerate-api.com/v6/[YOUR_KEY]]/latest/${fromCur.value}`);