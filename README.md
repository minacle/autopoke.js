# autopoke.js
## How to use
1. Access [pokes](https://www.facebook.com/pokes).
2.  
    - If you're using Firefox, evaluate

      ``` javascript
      (function(a){setInterval(function(){if(a.length>0)a.pop().click();else for(var b=document.body.querySelectorAll("div[id^=poke_live_item]"),c=0,d;c<b.length;c++)(d=b[c].querySelector('[ajaxify^="/pokes/inline/"][class*=selected]'))&&a.push(d)},2e3)})([])
      ```
      in Web Console.
    - Else, copy

      ``` javascript
      javascript:(function(a){setInterval(function(){if(a.length>0)a.pop().click();else for(var b=document.body.querySelectorAll("div[id^=poke_live_item]"),c=0,d;c<b.length;c++)(d=b[c].querySelector('[ajaxify^="/pokes/inline/"][class*=selected]'))&&a.push(d)},2e3)})([])
      ```
      and paste it on address bar then press enter key. *(Some browser remove leading `javascript:`. If it removed, type it yourself.)*
3. ...
4. PROFIT!
