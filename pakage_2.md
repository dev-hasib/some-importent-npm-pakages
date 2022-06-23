গুরুত্বপূর্ণ কিছু NPM প্যাকেজ পরিচিতি পর্ব ২ :
React front-end Design & Development এর জন্য কিছু গুরুত্বপূর্ণ "npm" প্যাকেজ যা আপনার দৈনন্দিন কাজে যথেষ্ট সহায়ক ভূমিকা রাখবে। উক্ত প্যাকেজগুলো বহুল ব্যবহৃত হচ্ছে এবং আপনার কাজ সহজতর করার জন্য এইগুলো খুবই দারুণ ভূমিকা রাখবে।
### 1) Html-react-parser
---- যখন আমরা ব্লগ লিখি তখন আমাদের backend অথবা admin প্যানেল থেকে সেগুলো পোস্ট করতে হয়। তবে হা যখন আমরা পোস্টগুলো করি সেগুলো নরমাল টেক্সট হিসেবে ডাটাবেজে store হয়ে যায়, কিন্তু আমরা যদি এই প্লাগইনটি ব্যবহার করি তাহলে সম্পূর্ণ HTML স্ট্রাকচার হয়ে ডাটাবেজে store হয়ে যাবে। অর্থাৎ এই প্লাগিন এর মাধ্যমে আমরা সম্পূর্ণ html কে পাঠিয়ে দিতে পারি।
উদাহরণস্বরূপ :``` parse'<h1>single</h1> ```;
অর্থাৎ আমরা এখানে আউটপুট পাবো ঠিক এরকম ``` <h1>single</h1>```, আরেকটি সম্পূর্ণরূপে ডাটাবেজে স্টোর হয়ে যাবে।
> [ https://www.npmjs.com/package/html-react-parser](https://www.npmjs.com/package/html-react-parser)

### 2) Axios 
---- HTTP client রিসিভ করার জন্য জনপ্রিয় একটি প্লাগিন হচ্ছে এটি। সাধারণত client site এ আমাদেরকে API নিয়ে কাজ করতে হয়। ডাটা লোড করার জন্য API ব্যবহার করা বাধ্যতামূলক। তবে শুরুর ক্ষেত্রে আমরা fetch() ব্যবহার করে থাকি। তবে সবচেয়ে মজার বিষয় হল এই প্লাগইনটি এতটাই সহজ যে আপনি খুব দ্রুত ভাবে API লোড করতে পারবেন।
উদাহরণস্বরূপ :

- axios.request(config)
- axios.get(url[, config])
- axios.delete(url[, config])
- axios.head(url[, config])
- axios.options(url[, config])
- axios.post(url[, data[, config]])
- axios.put(url[, data[, config]])
- axios.patch(url[, data[, config]])

> [https://www.npmjs.com/package/axios]( https://www.npmjs.com/package/axios)


### 3) React-share
---- বিভিন্ন ব্লগ পোস্টে আমরা নিচের দিকে বা উপরের দিকে দেখতে পারি কিছু সোশ্যাল নেটওয়ার্কে শেয়ার এর ব্যবস্থা থাকে। আমরা চাইলে ঠিক ঐরকম ব্যবস্থা গ্রহণ করতে পারি এই প্লাগিন এর মাধ্যমে। এ প্লাগিনটির কাজ হচ্ছে সোশ্যাল নেটওয়ার্কের সাথে কানেক্ট করা অর্থাৎ সোশ্যাল নেটওয়ার্কে আপনি আপনার পোস্টটি শেয়ার করতে চাইলে এই প্লাগিন এর মাধ্যমে করতে পারবেন।
উদাহরণস্বরূপ :
> https://amitjs.com/single-blog/61fc22bc97f9ad3882822bc2 
 এই ওয়েবসাইট এর ব্লগ পোস্টে শেয়ার আইকনগুলো লোড করা হয়েছে অর্থাৎ এখান থেকে সেই ব্লগ পোষ্ট টি সোশ্যাল নেটওয়ার্কে শেয়ার করা যাবে
> https://www.npmjs.com/package/react-share

### 4) Export-from-json 
---- এটি সাধারণত json ফাইলকে এক্সপোর্ট করার কাজে ব্যবহার করা হয়। Export to plain text, css, html, json, csv, xls, xml files from JSON. আপনাদের যদি প্রয়োজন হয় যে JSON ফাইল থেকে plain text, css, html, json, csv, xls, xml files এ এক্সপোর্ট করতে হবে তাহলে এটি ব্যবহার করতে পারেন।
> https://www.npmjs.com/package/export-from-json

### 5) EmailJS 

---- সাধারণত contact লিস্টে আমরা তথ্য আদান প্রদান করে থাকি। যোগাযোগ ব্যবস্থা সর্বপ্রথম শুরু হয় এ কন্টাক্ট লিস্ট থেকে আর আপনি এই প্লাগিন এর মাধ্যমে যোগাযোগ ব্যবস্থা খুব সহজতর করতে পারেন অর্থাৎ এই প্লাগিন এর দ্বারা আপনি ইমেইলের মাধ্যমে উক্ত কন্টাক লিস্টে ফাইলগুলো খুব সহজেই পেতে পারেন।
> https://www.emailjs.com/docs/examples/reactjs/
###  6) Progressbar
---- ওয়েবসাইট ডিজাইনের ক্ষেত্রে আমরা বেশির ভাগই দেখে থাকি Progressbar, Progressbar হলো কিছু সাংকেতিক design যা দ্বারা বোঝা যায় যে একটি বিষয়ের উপর সে কতটুকু জ্ঞান অর্জন করেছে বা একটি কোম্পানির যাবতীয় তথ্য। নিজেরে প্লাগিনগুলো ব্যবহার করে আপনারা আপনাদের মনের মত করে ডিজাইন তৈরি করতে পারবেন।
> - https://www.npmjs.com/package/react-circular-progressbar
> - https://www.npmjs.com/package/@ramonak/react-progress-bar
> - https://www.npmjs.com/package/react-customizable-progressbar
> - https://www.github.com/kimmobrunfeldt/progressbar.js
> - https://www.npmjs.com/package/react-progressbar-fancy
> - https://kimmobrunfeldt.github.io/progressbar.js/

###  7) Rich editor

---- The Rich Text Editor is a tool that allows you to add or edit content, images, links, and other components on the page without having to know any code. It displays the content and any formatting as it would display in the browser. Html-react-parser সাথে এই প্লাগিন গুলো ভাই ভাই সম্পর্ক।
> - https://ckeditor.com/.../latest/guide/dev_react_v2.html
> - https://www.npmjs.com/package/quill
😎 React-tabs ---- এটি ছাড়া আমি একদম চলতে পারি না। আমার তৈরি করা প্রতিটি ওয়েবসাইটে এই প্লাগিনটি ব্যবহার করতে হয়েছে। এক কথায় বলতে গেলে অসাধারণ। এমন কি আমি মেনু / Navbar তৈরি করেছে এই প্লাগিনটি সাহায্যে। তবে অন্যান্য ফ্রেমওয়ার্ক এ এই ধরনের ডিজাইন রয়েছে যেমন, বুটস্ট্র্যাপ ট্যাব তবে আমি সবচেয়ে উপরে রাখবো এই React-tabs প্লাগিন কে।
উদাহরণস্বরূপ : 
> http://met-cifo.amitjs.com/service-details (আমার তৈরি করা এই ওয়েবসাইটে ডিজাইন টি দেখলে বুঝতে পারবেন)।
 > https://www.npmjs.com/package/react-tabs
###  9) Scroll Effect
--- CSS ডিজাইনের জন্য এই প্লাগইনগুলো যথেষ্ট উপকারী। আপনি যখন আপনার ওয়েবসাইটটি scroll করবেন তখন বেশ কিছু পরিবর্তন এই প্লাগিন গুলোর সাহায্যে করে নিতে পারবেন।
 > - https://www.npmjs.com/package/react-scroll-parallax
> - https://www.npmjs.com/package/react-custom-scroll 
> (ব্রাউজারের ডান পাশে যে scroll bar ডিজাইন টি দেখতে পাওয়া যায় সেটি পরিবর্তন করার জন্য এই প্লাগইনটি ব্যবহার করা যেতে পারে)।
> - https://www.npmjs.com/package/react-infinite-scroller
> -  https://www.npmjs.com/package/react-custom-scrollbars

### 10) React Date Picker 
---- নাম শুনেই বুঝতে পারছেন একটি কাজ কি হতে পারে। A simple and reusable Datepicker component for React. ওয়েবসাইটে অনেক সময় আমাদের date count করার প্রয়োজন হতে পারে। আপনি এই প্লাগিন এর সাহায্যে সহজেই টাইম তুলে নিতে পারেন। খুবই জনপ্রিয় প্লাগিন যা বহুল ব্যবহৃত হচ্ছে।
> - https://www.npmjs.com/package/react-datepicker
> - https://www.npmjs.com/package/react-datetime
> - https://www.npmjs.com/package/react-date-range
### 11) React-select
  ---- এটি খুবই অ্যাডভান্স একটি টপিক। সাধারণত html select নামে একটি tag রয়েছে। যা কিনা সিলেক্ট করার কাজে ব্যবহার করা হয়। তবে w3school এই ওয়েবসাইটে (https://www.w3schools.com/tags/tag_option.asp ) যেটি রয়েছে সেটি খুবই নরমাল কিন্তু আপনি যদি advance কিছু ফিচার পেতে চান তাহলে এই npm React-select প্যাকেজটি বিকল্প কিছু নেই। তবে একটু জটিল, যদি আপনি তাদের ডকুমেন্টেশন ভালো করে পড়েন তবে সহজে এটি ব্যবহার করতে পারবেন। গত 2 দিন আগে আমি অনেকটা ঝামেলায় পড়ে গিয়েছিলাম এই প্যাকেজটি ব্যবহার করে, তবে আমি হাল ছাড়িনি প্রায় 14 ঘণ্টা ব্যয় করার পর সমস্যার সমাধান আমি বের করেছিলাম। ওই যে বললাম ডকুমেন্টেশন ভালো করে পড়তে হবে আমি সময় নিয়ে ডকুমেন্টেশন লাইন বাই লাইন পড়ে তারপর সে কোডগুলো কে যথাযথ মর্যাদায় নিয়ে এসেছে।
> https://www.npmjs.com/package/react-select
### 12) React-accessible-accordion
 ---- Accordion নাম শুনে আপনারা বুঝে গেছেন এটির কাজ কি। কোন একটা লেখা বা আইকনে ক্লিক করলাম আর অমনি নিচের দিকে একটি সেকশন বেরিয়ে কিছু তথ্য দিয়ে দিল, আবার সেই আইকনে ক্লিক করলাম সেটি ক্লোজ হয়ে গেল। হা এর নাম হলো Accordion. আপনারা চাইলে বুটস্ট্রাপ অথবা অন্যান্য ফ্রেমওয়ার্ক যেগুলো রয়েছে সেগুলো থেকেও ব্যবহার করতে পারবেন তবে আমার কাছে এই প্লাগইনটি খুব দারুণ লেগেছে আমি বেশ কিছু ওয়েবসাইটেও এটি ব্যবহার করেছি খুব সুন্দর কাস্টমাইজ করা যায় নিজের মত করে।
> - https://www.npmjs.com/package/react-accessible-accordion (I personally use it)
> - https://www.npmjs.com/package/react-collapsible
> - https://www.npmjs.com/package/rc-collapse
### 13) React Visibility Sensor
----- খুবই অ্যাডভান্স একটি টপিক। তবে বুঝতে পারলে খুব সহজ। বিগত দুই মাস আগে আমি চারটি react টেমপ্লেট ক্রয় করি Themeforest থেকে শুধুমাত্র গবেষণার কাজে। এবং আমার দেখা সবচেয়ে আকর্ষণীয় প্যাকেজ হল এটি। এটির কাজ হচ্ছে Sensor component for React that notifies you when it goes in or out of the window viewport. অর্থাৎ আপনার সম্পূর্ণ ওয়েব পেজটি লোড হওয়ার পর যতক্ষণ না পর্যন্ত আপনি একটি নির্দিষ্ট সেকশনে গিয়ে না দাঁড়াবেন ততক্ষণ পর্যন্ত কাজটি আপনার জন্য অপেক্ষা করবে। ধরুন আপনি আপনার ওয়েবসাইটে কাউন্টার নামক একটি সেকশন তৈরি করলেন এবং সেখানে যখন ডাটা অথবা ওয়েবসাইট রিলোড হয় তখন এক থেকে একশ গণনা করা হয়। কিন্তু আপনি একটা জিনিস খেয়াল করে দেখবেন যদি আপনার কাউন্টার সেকশনটি একদম footer এ থাকে তখন আপনি footer এ যেতে যেতে দেখবেন কাউন্টার 100 পূর্ণ হয়ে গেছে। এই যে কাউন্টার গণনা 100 হচ্ছে সেটি আর আপনি চোখে দেখলেন না। আর তাই এই React Visibility Sensor প্লাগিনটির কাজটি হচ্ছে যতক্ষণ না পর্যন্ত আপনি সেই সেকশনে না যাচ্ছেন ততক্ষণ পর্যন্ত কাউন্টার গণনা করা হবে না। যেইমাত্র আপনি সেই সেকশনে অথবা আপনার মনিটরের ওই সেকশনটি দেখা গেল তখন ঐ কাউন্টার টি গণনা শুরু করবে। অর্থাৎ মাউসের scroll ঘুরিয়ে আপনি কাউন্টার সেকশনে গেলেন ঠিক তখনই এক থেকে একশ কাউন্ট করা শুরু করে দিবে।
উদাহরণস্বরূপ: 
> - http://met-cifo.amitjs.com/about-us
> - https://www.npmjs.com/package/react-visibility-sensor
### 14) React Hook Form 
---- খুবই জনপ্রিয় একটি প্লাগিন হল React Hook Form (Performant, flexible and extensible forms with easy-to-use validation)। যখন আমরা Form নিয়ে কাজ করি তখন আমাদেরকে বেশকিছু বাধ্যবাধকতা তৈরি করে দিতে হয়, আর তাই এই প্লাগিনটি আপনাকে যথেষ্ট পরিমান সাহায্য করবে সে কাজটি করার জন্য। একদম সহজ গঠন এবং প্রচুর জনপ্রিয়তা রয়েছে এই প্লাগিনটি। এটি react web & react native উভয়ের সাথে কাজ করতে পারে।
>  https://react-hook-form.com/
### 15) React-helmet 
---- ডায়নামিক ভাবে মেটাডাটা সেট করার জন্য এই প্লাগইনটি খুবই জনপ্রিয় আমি প্রতিটি ওয়েবসাইটে এ প্লাগিনটি ব্যবহার করে থাকি।
উদাহরণস্বরূপ: http://met-cifo.amitjs.com/ ( আপনি এই ওয়েবসাইটে প্রতিটি পেইজ এর favicon এ hover করলে দেখতে পাবেন প্রতিটি পেইজে মেটাডাটা আলাদাভাবে দেখা যাচ্ছে। এই কাজটি করেছি আমি প্লাগইনটি দিয়ে।
> https://www.npmjs.com/package/react-helmet
### 16) React-image-magnify 
----- যখন আমরা ই-কমার্স ওয়েবসাইট ভিজিট করি এবং প্রোডাক্ট এর উপর যখন মাউস hover করি তখন উক্ত প্রোডাক্টটি অনেক বড় করে দেখাই অর্থাৎ zoom হয়ে যায়। এই ধরনের কাজ গুলো আপনি React-image-magnify প্লাগিন দ্বারা করতে পারবেন। তবে সেটআপ টা একটু জটিল তাই ডকুমেন্টেশন ভালো করে পড়ে নিবেন।
> https://www.npmjs.com/package/react-image-magnify
### 17) React-modal 
----- একটি আইকনে ক্লিক করলেন আর একটি পপ আপ বক্স দেখা গেল। অর্থাৎ পপ-আপ মডেল তৈরি করার কাজে এই প্লাগিনটি ব্যবহার করা যেতে পারে।
> https://www.npmjs.com/package/react-modal

 ### 18) Countdown
 ----- কাউন্টডাউন অর্থাৎ গণনা কাজে ব্যবহার করা হয়। ওয়েবসাইটে আমরা সচরাচর দেখি যে কাউন্টার নামক কিছু তথ্য বেশিরভাগ ই দেখা যায় একটি কোম্পানিতে কতজন কাজ করছে বা একটি কোম্পানির লোক সংখ্যা কতজন অথবা কতটি প্রোজেক্ট কমপ্লিট করেছে এই ধরনের তথ্যগুলো একটি ডিজাইনের মাধ্যমে উপস্থাপন করা হয়। ধরুন আপনি একটি প্রোজেক্ট কমপ্লিট করেছেন এখন আপনার ডিজাইনটি হবে 1 থেকে 100 পর্যন্ত গণনা করে দেখানো । আপনি এই কাজটি এই নিচে প্লাগইনগুলো দ্বারা করতে পারবেন।
> -  https://www.npmjs.com/package/react-countdown
> - ttps://www.npmjs.com/package/use-react-countdown
> - https://www.npmjs.com/package/react-countdown-circle-timer
### 19) Table
---- টেবিল যা খুবই দরকারি একটি tag. যখন আমাদের হাতে প্রচুর ডাটা থাকে তখন সেই ডাটাগুলোকে দেখানোর জন্য টেবিলের সাহায্য নিতে হয়। আপনারা চাইলে w3schools এ নরমাল টেবিল ফরম্যাট তৈরি ও ব্যবহার করতে পারেন। আবার যদি চান যে অ্যাডভান্স লেভেলের কিছু তাহলে এই প্লাগিনটি ব্যবহার করতে পারেন আমি ব্যক্তিগতভাবে এই প্লাগিন গুলো ব্যবহার করি।
> - https://www.npmjs.com/package/react-table
> - https://www.npmjs.com/package/rc-table
### 20) React Rating 
---- আমাদেরকে অনেক সময় ফিডব্যাক সেকশন তৈরীর ক্ষেত্রে রেটিং ব্যবহার করতে হয়। আপনারা এই নিচের প্লাগিনগুলোর সাহায্যে রেটিং খুব সুন্দর ভাবে তৈরি করতে পারেন। এই প্লাগিন গুলো ব্যবহার করে নিজস্ব কাস্টমাইজেশনের মাধ্যমে ডিজাইন গুলোকে আরো সুন্দর করে সাজিয়ে নিতে পারবেন।
> - https://www.npmjs.com/package/react-rating
> - https://www.npmjs.com/package/react-simple-star-rating
> - https://www.npmjs.com/package/react-rating-stars-component
> - https://www.npmjs.com/package/react-star-ratings
### 21) Typewriter Effect 
---- বিভিন্ন ওয়েবসাইটে দেখা যায় যে কিছু টেক্স নেচে নেচে আসছে আবার কেমন যেন উধাও হয়ে যাচ্ছে। হা এ গুলোকে বলে Typewriter Effect. নিচে দেওয়া এই প্লাগিন গুলো ব্যবহার করে সহজেই টেক্সট ইফেক্ট তৈরী করে নিতে পারবেন।
> - https://www.npmjs.com/package/typewriter-effect
> - https://www.npmjs.com/package/react-simple-typewriter
'''' সবাই ভালো থাকুন আপনার ভবিষ্যৎ সুন্দর হোক """

## Stack Learner - Programming Community

