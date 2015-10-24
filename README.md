# Block Disposable and free email addresses
This service allows you to block disposable and free email addresses

Usage:
```
echo DisposableEmailChecker::checkEmail("10minutemail.com");
```

Output:

A risk rating (integer)
>0 is the lowest risk
>1 are trusted free email providers
>>=2 are disposable email addresses and high risk providers
