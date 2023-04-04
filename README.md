
# URL Notepad
URL Notepad is a simple browser notepad written in plain html, css, and
js in a single html file.

URL Notepad was designed to be able to run by copy pasting it into the
address bar of the browser of your choosing (less than 2000 characters!)

## Usage

### With `url.html`

Simply copy and paste the contents of `url.html` into your address bar.

### With `expanded.html`

Download a copy and load it into you browser (drag and drop, copy file path ...)

### Bookmarking
- Issue in Opera where bookmarking will change link to a
`sync-thumbnails.operacdn` link, which breaks the CSP. Save `expanded.html`
and bookmark its path to solve this.

## Notes

### Differences in `url.html`
- Changed `<DOCTYPE! html>` to `data:text/html,` to enable url html
- Changed all `#` to `%23` to allow them to render in the url
- Changed four space tab to `"%20%20%20%20"` to allow render in url
- Removed unnecessary whitespace