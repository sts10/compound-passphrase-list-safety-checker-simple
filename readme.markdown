# Compound Passphrase List Safety Checker (Simple Version)

This command line tool checks whether a given passphrase word list (such as a diceware word list) has any words that can be combined to make another word on the list. It's written in Rust, which I am new to, so please use this with caution.

This code has moved to [the `simple` branch of this project](https://github.com/sts10/compound-passphrase-list-safety-checker/tree/simple). Note that there is a separate, later version of this project that's called [csafe](https://github.com/sts10/csafe). 

**Disclosure**: I am not a professional programmer, researcher, or statistician, and frankly I'm pretty fuzzy on some of this math. This code/theory/explanation could be very wrong (but hopefully not harmful?). If you think it could be wrong or harmful, please leave an issue! 

