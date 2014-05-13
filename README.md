# About

The classic XIAG test task given to job applicants, implemened in Clojure and ClojureScript

# Problem statement

1. Site-visitor (V) enters any original URL to the Input field, like http://anydomain/any/path/etc;
2. V clicks submit button;
3. Page makes AJAX-request;
4. Short URL appears in Span element, like http://yourdomain/abCdE (don't use any external APIs as goo.gl etc.);
5. V can copy short URL and repeat process with another link

Short URL should redirect to the original link in any browser from any place and keep actuality forever, doesn't matter how many times application has been used after that.

# Status

NOT READY
