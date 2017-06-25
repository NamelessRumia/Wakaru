This readme file is for borrowing themes and using it on different software.

## Importing to Wakaba
If you plan on borrowing these themes for Wakaba, the "futaba_style.pl" file
needs the following changes in order for the CSS to function properly.

Find "<style type="text/css">" and remove:
  .reply blockquote, blockquote :last-child { margin-bottom: 0em }
  
Then, between "<style type="text/css">" and "<style>", insert:
  .code { font-family: monospace; }
  .spoiler { background: #000000; color: #000000; }
  .spoiler:hover { color: #FFFFFF; }
  .theader, .passvalid { margin: 2px 0 0 0; padding: 2px; }
  .logo { padding-top: 6px; }
