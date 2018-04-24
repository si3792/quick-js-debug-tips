# Quick tips for debugging JS

---

## Who am I?
### { name: 'Simo',  <!-- .element: class="fragment" -->
###   company: 'Leanplum',  <!-- .element: class="fragment" -->
###   position: 'FE developer' }  <!-- .element: class="fragment" -->

---

## What is this talk about?

* Lesser-known ways to debug JS applications <!-- .element: class="fragment" -->
* Focus on Chrome DevTools <!-- .element: class="fragment" -->
* NOT a complete guide to DevTools <!-- .element: class="fragment" -->

---

## Good ol' breakpoint

* Automatic  <!-- .element: class="fragment" -->
* Conditional  <!-- .element: class="fragment" -->
* Pause on exception  <!-- .element: class="fragment" -->

---

## Bookmarklets


```
  javascript:(function(){
  var s=document.createElement('script');
  s.setAttribute('src','https://code.jquery.com/jquery.js');
  document.getElementsByTagName('body')[0].appendChild(s);})();
```
  <!-- .element: class="fragment" -->

---
## Raygun

![raygun](https://raw.githubusercontent.com/si3792/quick-js-debug-tips/master/raygun.png)

---

## Magic with $

* no, this is not JQuery again <!-- .element: class="fragment" -->
* $0 and $1 <!-- .element: class="fragment" -->

---

## Local Overrides

* Fancy new feature in Chrome 65 <!-- .element: class="fragment" -->

* Make changes and persist them across page reloads <!-- .element: class="fragment" -->

---

![Not enough dev tools?](https://raw.githubusercontent.com/si3792/quick-js-debug-tips/master/inception.jpg)

#### Debug DevTools using DevTools.. and so on <!-- .element: class="fragment" -->

---

Thank you for your time!