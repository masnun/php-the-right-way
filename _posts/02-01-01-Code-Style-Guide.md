---
title: কোড স্টাইল গাইড
isChild: false
---

# কোড স্টাইল গাইড


পিএইচপি কমিউনিটিটা বেশ বড়, বৈচিত্র্যপূর্ন - অসংখ্যা লাইব্রেরী, ফ্রেমওয়ার্ক এবং কম্পোনেন্ট এর সমাহার দেখা যায় এই কমিউনিটিতে । স্বাভাবিকভাবেই ডেভেলপাররা এগুলো থেকে বেশ প্রয়োজনমত কম্পোনেন্টগুলো বেছে নিয়ে তাদের প্রজেক্টে ব্যবহার করেন । ঠিক একারণেই সব পিএইচপি কোড একটি কমন কোড স্টাইল অনুসরণ করে লেখা প্রয়োজন যাতে ডেভেলপারদের জন্য বিভিন্ন লাইব্রেরী এক করা সহজ হয়। 

এই উদ্দেশ্যে [The Framework Interop Group][fig] কতগুলো স্টাইল প্রস্তাব এবং অনুমোদন করেছে, যেমন-  [PSR-0][psr0], [PSR-1][psr1] এবং [PSR-2][psr2]. এই কোড স্টাইল ইতোমধ্যে  Drupal, Zend, Symfony, CakePHP, phpBB, AWS SDK, FuelPHP, Lithium সহ অনেক প্রজেক্ট অনুসরণ করা শুরু করেছে । আপনিও আপনার প্রজেক্টে এগুলো অনুসরণ করা শুরু করতে পারেন ।

তবে সাধারণত এমনভাবে কোড লেখা উচিৎ যাতে কোড একটি নির্দিষ্ট স্ট্যান্ডার্ড অনুসরণ করে । হতে পারে তা PSR গুলোর সমন্বয় অথবা কোন পরিচিত স্ট্যান্ডার্ড যেমন PEAR বা Zend । আমাদের মূল লক্ষ্য থাকবে যাতে অন্য ডেভেলপাররা আমাদের কোড সহজে পড়তে পারে এবং আমাদের কোড নিয়ে কাজ করতে পারে । এই স্ট্যান্ডার্ডগুলো অনুসরণ করা হলে কোন এ্যাপ্লিকেশন যদি অনেক থার্ড পার্টি কম্পোনেন্টও ব্যবহার করে তারপরও কনসিস্টেন্সী থাকবে । 

নিচের লিংক গুলো থেকে স্ট্যান্ডার্ডগুলো সম্পর্কে আরো জানতে পারবেন - 

* [PSR-0][psr0]
* [PSR-1][psr1]
* [PSR-2][psr2]
* [PEAR][pear-cs]
* [Zend][zend-cs]

আপনি চাইলে [PHP_CodeSniffer][phpcs] ব্যবহার করে এইসব স্ট্যান্ডার্ডের সাথে আপনার লেখা কোড তুলনা করতে পারেন । এই টুলটি কোড স্টাইলের নানা অসঙ্গতি তুলে ধরবে । কোন কোন টেক্সট এডিটর বা আইডিএ তে এর জন্য প্লাগিনও পাবেন যেমন - [Sublime Text 2 PHP CS][st-cs] । 

এছাড়া Fabien Potencier এর [PHP Coding Standards Fixer][phpcsfixer] ব্যবহার করে অটোমেটিক্যালি সিনট্যাক্স ঠিক করে নিতে পারেন । এতে আপনার সময় বাচবে । 

কোড লেখার জন্য ইংরেজীটাই প্রাধান্য দেওয়া উচিৎ, বিশেষ করে বিভিন্ন সিম্বল ডেফিনিশনের বেলায় । কমেন্ট টা প্রজেক্ট অনুযায়ী অন্য ভাষায় করা যেতে পারে তবে সেক্ষেত্রে যারা পরবর্তীতে এই প্রজেক্টে কাজ করবে তাদের সম্ভাব্য ভাষা জ্ঞান মাথায় রাখা জরুরী । 

[fig]: http://www.php-fig.org/
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[psr1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[psr3]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-3-logger-interface.md
[pear-cs]: http://pear.php.net/manual/en/standards.php
[zend-cs]: http://framework.zend.com/wiki/display/ZFDEV2/Coding+Standards
[phpcs]: http://pear.php.net/package/PHP_CodeSniffer/
[st-cs]: https://github.com/benmatselby/sublime-phpcs
[phpcsfixer]: http://cs.sensiolabs.org/
