CGI (Common Gateway Interface)
==========
web伺服器所處理的內容都是靜態的  
若要動態處理，必須要有後端程式語言  
後端程式語言可以用很多種編寫，如php，java，python  
網頁伺服器不可能讀懂所有語言，所以不能直接處理後端語言  
於是有了 __CGI__ 協定，CGI程式是根據CGI協定  
具有標準輸入、輸出和環境變量，cgi程式會啟動zend虛擬機以載入php腳本。

* CGI可以用任何語言編寫，一般是 Perl 和 C 語言

FastCGI
==========
也是一種協議，cgi優化版，具有較佳的性能


php-fpm
==========
php-fpm(php-Fastcgi Process Manager) 是對FastCGI協議的具體實現  
PHP-FPM 就是 PHP 版本的 FastCGI 協議的具體實作，目的為實現 web server 與 PHP 腳本之間的溝通。


參考:  
https://www.itread01.com/p/120252.html  
https://yuchitung.github.io/2020/07/06/cgi-fastcgi-and-phpfpm/
