Google Montserrat bold text is rendered way differently on Safari compared to FF or Chrome.
The issue is resolved by explicitely imporing both regular and bold font weights from Google Fonts.

Before: `index.html`
After: `index-fixed.html`

Before CSS:
```
@import url('https://fonts.googleapis.com/css?family=Montserrat');
```

After CSS:
```
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,600');
```