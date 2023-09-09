# Credit Card Validator

## Installation
Run this command for installation:

```
 npm i bank-credit-card-validation
```
## Usage
After installation is completed, import the component you want to use the package
```
 import isCreditCard from 'bank-credit-card-validation';
```

The package includes a function called "isCreditCard", developed according to the Luhn algorithm, and returns "valid" or "invalid" depending on the number sent.

```
 isCreditCard("5196081888500645") => return "valid"
```

If you want to know more about Luhn Algorithm, [click here](https://www.geeksforgeeks.org/luhn-algorithm/)
