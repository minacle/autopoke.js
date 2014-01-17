# autopoke.js
## How to use
1. Access [pokes](https://www.facebook.com/pokes).
2. Write `javascript:setInterval(function(){var _=document.body.querySelectorAll('#poke_live_new [ajaxify*="/pokes/inline/"]'),a=0;for(;a<_.length;a++)_[a].click()},2000)` on address bar.
If you're using Firefox, evaluate 'setInterval(function(){var _=document.body.querySelectorAll('#poke_live_new [ajaxify*="/pokes/inline/"]'),a=0;for(;a<_.length;a++)_[a].click()},2000)' in Web Console.
3. Fire!
