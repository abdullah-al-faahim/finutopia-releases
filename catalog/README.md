# FinUtopia catalog

The app checks these files once a day. A file with a higher `version` than the one built into the
app replaces it, so new bank ratings, savings rates, banks and insurers reach phones without an
app update. Keep them in step with `assets/catalog` in the app's code.

- `providers.json`: banks, finance companies, wallets, cards and insurers
- `rate_tables.json`: Sanchayapatra rates and tax, bank source tax, bKash terms
- `safety.json`: bank credit ratings (Bangladesh Bank's list) and deposit protection
