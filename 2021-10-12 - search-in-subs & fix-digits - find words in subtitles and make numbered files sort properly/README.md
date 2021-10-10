# search-in-subs & fix-digits - find words in subtitles and make numbered files sort properly
 
[![Linguistic Mind - search-in-subs & fix-digits - find words in subtitles and make numbered files sort properly](https://img.youtube.com/vi/6Q2avEWiQB8/0.jpg)](https://www.youtube.com/watch?v=6Q2avEWiQB8)
 
Recorded on 2021-09-29.1<br>
Released on 2021-10-12
 
## Description
 
I talk about two command line tools that I wrote. One of them allows you to quickly find text in srt subtitles, and the other one adds leading zeros to numbered files, so that they always sort correctly.
 
## Chapters
 
[0:00](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=0m0s "Intro") Intro<br>
[1:29](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=1m29s "Installation") Installation<br>
[5:39](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=5m39s "search-in-subs") search-in-subs<br>
[7:06](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=7m6s "Installing dependencies; notes on running on different operating systems") Installing dependencies; notes on running on different operating systems<br>
[10:53](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=10m53s "search-in-subs, continued") search-in-subs, continued<br>
[13:00](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=13m0s "Basic usage") Basic usage<br>
[14:27](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=14m27s "--verbose, --inverse") --verbose, --inverse<br>
[17:11](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=17m11s "How search-in-subs treats whitespace (--strict-search)") How search-in-subs treats whitespace (--strict-search)<br>
[19:21](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=19m21s "Statistics in search-in-subs (--stats)") Statistics in search-in-subs (--stats)<br>
[24:05](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=24m5s "Use cases for search-in-subs; other options") Use cases for search-in-subs; other options<br>
[28:19](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=28m19s "fix-digits") fix-digits<br>
[31:40](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=31m40s "How to change defaults by setting aliases") How to change defaults by setting aliases<br>
[34:04](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=34m4s "fix-digits, continued") fix-digits, continued<br>
[36:15](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=36m15s "Setting regexes for --head and --tail (to tell fix-digits where the numbers are)") Setting regexes for --head and --tail (to tell fix-digits where the numbers are)<br>
[41:17](https://www.youtube.com/watch?v=6Q2avEWiQB8&t=41m17s "Outro") Outro
 
## Links
 
Main repo: https://github.com/linguisticmind/lmutils
 
search-in-subs: https://github.com/linguisticmind/lmutils/blob/master/search-in-subs<br>
fix-digits: https://github.com/linguisticmind/lmutils/blob/master/fix-digits
 
macOS package management (MacPorts, Homebrew): https://www.youtube.com/watch?v=vC6ykcyTzLg<br>
Setting PATH tutorial (Corey Schafer): https://www.youtube.com/watch?v=PUIE7CPANfo&t=8m44s<br>
Regular expressions tutorial (Corey Schafer) (also see notes below): https://www.youtube.com/watch?v=sa-TUpSx1JA 
 
## Notes
 
The linked regular expressions tutorial talks about a slightly different kind of regular expressions. These command line tools use a regex flavor called POSIX Extended Regular Expressions. It doesn't have character classes like `\s`, `\d`, it uses `[[:space:]]`, `[[:digit:]]` instead. (You can find a full list here: https://en.wikibooks.org/wiki/Regular_Expressions/POSIX-Extended_Regular_Expressions#Character_classes) It also doesn't have lookahead `(?=text)` and lookbehind `(?<=text)`. These are all the differences that I can think of. You can find more information about different regex flavors on this page: https://en.wikipedia.org/wiki/Regular_expression#POSIX_basic_and_extended
 
## Support Linguistic Mind
 
Patreon: https://patreon.com/linguisticmind<br>
Ko-fi: https://ko-fi.com/linguisticmind
