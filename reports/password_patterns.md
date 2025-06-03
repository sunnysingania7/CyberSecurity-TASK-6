# Password Pattern Observations 

During testing, I identified a variety of password structures to evaluate their strength: 

* **Lowercase Only**    : 
    sunshine, holidaytime, elephantwalk
* **Upper + Lowercase** : 
    Sunshine, HolidayTime, ElephantWalk
* **Alphanumeric**      : 
    Sunshine123, BookLover2025, Eagle7Time
* **Symbols Included**  : 
    S@feHome#2025, M0v!eBuff$, Tr@v3l!ng
* **Passphrases**       : 
    "sunshine on mountains", "books are life", "I love coffee at 8am!"

**Findings** : 

* Passphrases and long passwords consistenly scored better. 
* Short passwords, even with complexity, often had poor strength. 
* Adding symbols improved resistance, but length was more critical.