# Megacollections:
   - [github.com/cipher387/Dorks-collections-list](https://github.com/cipher387/Dorks-collections-list)
   - [github.com/redduxi/Google-Dorks-Resources](https://github.com/redduxi/Google-Dorks-Resources)

# [Google]( https://www.google.com/advanced_search)

### Lists:
  - #### Short lists:
    - [www.boxpiper.com/posts/top-35-google-dorks-list](https://www.boxpiper.com/posts/top-35-google-dorks-list)
  - #### Big Data:
      - #### General:
         - [hackersonlineclub.com/google-hacking](https://hackersonlineclub.com/google-hacking/)
         - [www.boxpiper.com/posts/google-dork-list](https://www.boxpiper.com/posts/google-dork-list)
         - [github.com/Proviesec/google-dorks](https://github.com/Proviesec/google-dorks)
         - [github.com/aleedhillon/7000-Google-Dork-List](https://github.com/aleedhillon/7000-Google-Dork-List)
         - [github.com/readloud/Google-Hacking-Database-GHDB](https://github.com/readloud/Google-Hacking-Database-GHDB)
         - [github.com/Ishanoshada/GDorks](https://github.com/Ishanoshada/GDorks)
         - [github.com/Machinh/Google-Dorking](https://github.com/Machinh/Google-Dorking)
         - [github.com/BullsEye0/google_dork_list](https://github.com/BullsEye0/google_dork_list)
         - [github.com/opsdisk/pagodo](https://github.com/opsdisk/pagodo/tree/master/dorks)
         - [github.com/thomasdesr/Google-dorks](https://github.com/thomasdesr/Google-dorks)
         - [github.com/arimogi/Google-Dorks](https://github.com/arimogi/Google-Dorks)
         - [github.com/Veradun/My-Dorks](https://github.com/Veradun/My-Dorks)
         - [github.com/0xAbbarhSF/Info-Sec-Dork-List](https://github.com/0xAbbarhSF/Info-Sec-Dork-List)

      - #### SQLi:
         - [gbhackers.com/latest-google-sql-dorks](https://gbhackers.com/latest-google-sql-dorks/)
         - [github.com/JacobRiggs/Google-Dorks-SQLi](https://github.com/JacobRiggs/Google-Dorks-SQLi-)
         - [github.com/rootac355/SQL-injection-dorks-list](https://github.com/rootac355/SQL-injection-dorks-list)
         - [github.com/NoThrowForwardIt/SQLi-Dork-Repository](https://github.com/NoThrowForwardIt/SQLi-Dork-Repository)
         - [github.com/ShivamRai2003/SQL-Injection-Google-Dork-List](https://github.com/ShivamRai2003/SQL-Injection-Google-Dork-List)
         - [github.com/0xZipp0/SQL-injection-dorks-list](https://github.com/0xZipp0/SQL-injection-dorks-list)
         - [github.com/abhishek1924/SQL-Dorks](https://github.com/abhishek1924/SQL-Dorks)
       
      - #### Bug Bounty:
         - [github.com/sushiwushi/bug-bounty-dorks](https://github.com/sushiwushi/bug-bounty-dorks)

### Cheatsheets:
  - [gist.github.com/sundowndev](https://gist.github.com/sundowndev/283efaddbcf896ab405488330d1bbc06)
  - [github.com/chr3st5an/Google-Dorking](https://github.com/chr3st5an/Google-Dorking)
  - [www.tutorialsfreak.com/ethical-hacking-tutorial/google-dorking-cheat-sheet](https://www.tutorialsfreak.com/ethical-hacking-tutorial/google-dorking-cheat-sheet)
  - [ahrefs.com/blog/google-advanced-search-operators](https://ahrefs.com/blog/google-advanced-search-operators/)

### Articles:
  - [securitytrails.com/blog/google-hacking-techniques](https://securitytrails.com/blog/google-hacking-techniques)
  - [moz.com/blog/mastering-google-search-operators-in-67-steps](https://moz.com/blog/mastering-google-search-operators-in-67-steps
)

# [Yahoo](https://search.yahoo.com/web/advanced;_ylt=AwrNPjQzHrxl7fsP.21XNyoA;_ylu=Y29sbwNiZjEEcG9zAzEEdnRpZANRMjIwMjQtU0RfMQRzZWMDc3I-?fr=sfp)

### Articles:
  - [search.mediasova.com/en/yahoo](https://search.mediasova.com/en/yahoo)
  - [en.wikibooks.org/wiki/How_To_Search/Yahoo](https://en.wikibooks.org/wiki/How_To_Search/Yahoo)

# [Yandex](https://yandex.com/support/search/query-language/)
### Articles:
  - [hackware.ru](https://hackware.ru/?p=6045)

# [Baidu](https://www.baidu.com/gaoji/advanced.html)

### Articles:
  - [zhuanlan.zhihu.com](https://zhuanlan.zhihu.com/p/582617911?utm_id=0)

### Cheatsheet based on the official source:  

Operator ""  
According to Google's translation: "Contains the following complete keywords". According to personal limited research it can return results which include only a subset of the specified strings. The spaces between strings can be replaced with anything. The sequence is not always preserved.
Try ~~googling~~ baiding "aaa bbb ccc" or smth similar. The operator might work better for Chinese queries.

Operator |  
Logical OR. Eg (foo | bar).

Operator -  
Used for exclusion. Eg -site:www.somesite.com to exclude from results.

Operator ()  
Used for grouping.

Operator site:  
It has the same purpose as in most other engines. The official page does not include a space between this operator and searched str, though it seems to work fine with space(s). The * seems to produce slightly different results. Subdomains are also returned if no * is provided.  

Operator title:  
It is like intitle in Google. The official page does include a space between operator and the searched title. It also places the title between round brackets. It seems to work fine without space(s) and without braces.  

Operator inurl:  
The official page includes a space between operator and the searched url. It also places the url between round brackets. It seems to work fine without space(s) and without braces.  

Operator filetype:  
Searches for the specified file extensions. Currently supported: pdf, doc, xls, ppt, rtf, all. Others seem to be unreliable. There must be no space between operator and extension.

# [Bing](https://www.bing.com/account/general)
### Articles:
  - [support.microsoft.com/en-us/topic/advanced-search-keywords-ea595928-5d63-4a0b-9c6b-0b769865e78a](https://support.microsoft.com/en-us/topic/advanced-search-keywords-ea595928-5d63-4a0b-9c6b-0b769865e78a)
  - [support.microsoft.com/en-us/topic/advanced-search-options-b92e25f1-0085-4271-bdf9-14aaea720930](https://support.microsoft.com/en-us/topic/advanced-search-options-b92e25f1-0085-4271-bdf9-14aaea720930)
  - [www.bruceclay.com/blog/bing-google-advanced-search-operators](https://www.bruceclay.com/blog/bing-google-advanced-search-operators/)

# [DuckDuckGo](https://duckduckgo.com/duckduckgo-help-pages/results/syntax/)

### Cheatsheet  
Operator filetype:  
The official site states that it supports only these extensions: pdf, doc(x), xls(x), ppt(x), html.  
The personal research has shown that it can also return results for other file types (eg txt, zip).

# Licence
MIT :copyright:
