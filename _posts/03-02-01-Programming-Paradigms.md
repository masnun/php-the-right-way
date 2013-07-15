---
isChild: true
---

## প্রোগ্রামিং প্যারাডাইম 

#### প্যারাডাইম কি? 

প্যারাডাইম হলো কোন কিছু করার মৌলিক পদ্ধতি । সাধারণত কোন কিছু আমরা যে ভিন্ন ভিন্ন উপায়ে করে থাকি সেগুলোই হলো ঐ কাজের জন্য প্যারাডাইম ।  প্রোগ্রামিং এর বেলায়ও এরকম ৪টি প্রধান প্যারাডাইম আছে - 
* imperative
* declarative
* functional
* objec oriented

প্রোগ্রামিং প্যারাডাইম সম্পর্কে আরো বিস্তারিত জানতে ঘুরে আসুন উইকিপিডিয়ায় - [Programming Paradigm][pdg]

#### পিএইচপি এবং প্রোগ্রামিং প্যারাডাইম 
 
পিএইচপি একটি ফ্লেক্সিবল, ডাইনামিক ল্যাঙ্গুয়েজ যেটা একাধিক প্রোগ্রামিং টেকনিক সাপোর্ট করে । গত কয়েক বছরে পিএইচপিতে এসেছে নাটকীয় পরিবর্তন । তার মধ্যে উল্লেখযোগ্য -

* ২০০৪ সালে PHP 5.0 তে একটি সলিড অবজেক্ট ওরিয়েন্টেড মডেল যোগ করা হয় 
* ২০০৯ এ এসে এ্যানোনিমস ফাংশন, নেইমস্পেইস যোগ হয় PHP 5.3 এ
* ২০১২ তে PHP 5.4 এ আমরা পাই ট্রেইটস
* ২০১৩ এ জেনারেটর নিয়ে আসে PHP 5.5



### অবজেক্ট ওরিয়েন্টেড প্রোগ্রামিং

পিএইপিতে পাবেন অবজেক্ট ওরিয়েন্টেড প্রোগ্রামিং এর জন্য প্রয়োজনীয় ফিচারগুলোর একটি পূর্নাঙ্গ সেট । যার মধ্যে আছে - 
* ক্লাস
* এ্যাবস্ট্র্যাক্ট ক্লাস
* ইন্টারফেইস
* ইনহেরিট্যান্স
* কন্স্ট্রাক্টরস
* ক্লোনিং
* এক্সেপশন, ইত্যাদি ।

নিচের লিংক দুটো থেকে পিএইচপির অবজেক্ট ওরিয়েন্টেড ফিচারগুলো সম্পর্কে আরো বিস্তারিত জানতে পারবেন - 

* [Object-oriented PHP][oop]
* [Traits][traits]

### Functional Programming

PHP supports first-class function, meaning that a function can be assigned to a variable. Both user defined and built-in 
functions can be referenced by a variable and invoked dynamically. Functions can be passed as arguments to other
functions (feature called Higher-order functions) and function can return other functions.

Recursion, a feature that allows a function to call itself is supported by the language, but most of the PHP code focus
on iteration.

New anonymous functions (with support for closures) are present since PHP 5.3 (2009).

PHP 5.4 added the ability to bind closures to an object's scope and also improved support for callables such that they
can be used interchangeably with anonymous functions in almost all cases.

* Continue reading on [Functional Programming in PHP](/pages/Functional-Programming.html)
* [Read about Anonymous Functions][anonymous-functions]
* [Read about the Closure class][closure-class]
* [More details in the Closures RFC][closures-rfc]
* [Read about Callables][callables]
* [Read about dynamically invoking functions with `call_user_func_array`][call-user-func-array]

### Meta Programming

PHP supports various forms of meta programming through mechanisms like the Reflection API and Magic Methods. There are
many Magic Methods available like `__get()`, `__set()`, `__clone()`, `__toString()`, `__invoke()`, etc. that allow
developers to hook into class behavior. Ruby developers often say that PHP is lacking `method_missing`, but it is
available as `__call()` and `__callStatic()`.

* [Read about Magic Methods][magic-methods]
* [Read about Reflection][reflection]

[namespaces]: http://php.net/manual/en/language.namespaces.php
[overloading]: http://php.net/manual/en/language.oop5.overloading.php
[oop]: http://www.php.net/manual/en/language.oop5.php
[anonymous-functions]: http://www.php.net/manual/en/functions.anonymous.php
[closure-class]: http://php.net/manual/en/class.closure.php
[callables]: http://php.net/manual/en/language.types.callable.php
[magic-methods]: http://php.net/manual/en/language.oop5.magic.php
[reflection]: http://www.php.net/manual/en/intro.reflection.php
[traits]: http://www.php.net/traits
[call-user-func-array]: http://php.net/manual/en/function.call-user-func-array.php
[closures-rfc]: https://wiki.php.net/rfc/closures
[pdg]: https://en.wikipedia.org/wiki/Programming_paradigm
