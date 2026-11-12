# PayMe Safari iframe test

Compare PayMe’s hosted checkout in a Safari iframe and in a new tab using the same sale.

1. Download `index.html` and run `python3 -m http.server 4173 --bind 127.0.0.1` from its folder.
2. Open [localhost:4173](http://localhost:4173) in Safari, enter your PayMe seller ID, and generate a sale.
3. Try Google Pay in the iframe, then use **Open same sale in a new tab** to compare. Completing checkout can charge ₪5.
