মানব ইতিহাসের সবথেকে গুরুত্বপূর্ণ আবিষ্কার গুলির মধ্যে একটি হলো ইন্টারনেট। আমরা প্রায় প্রতিদিনই ইন্টারনেট ব্যবহার করি, এবং ইন্টারনেট ব্যবহার করার সময় আমার প্রায়শই HTTP শর্ট ফর্মটির সাথে সম্মুখীন হয়ে থাকি। কিন্তু এই HTTP আসলে কি অথবা এর ফুল ফর্ম কি তা আমাদের মধ্যে বেশিরভাগ মানুষই জানেনা। তাই আজকে এই আর্টিকেলের মাধ্যমে আমরা HTTP কি, HTTP এর পূর্ণরূপ কি, এটি কিভাবে কাজ করে ও এর সম্পর্কে অন্যান বেসিক তথ্য গুলি জানতে চলেছি।

HTTP-এর ফুল ফর্ম হলো Hypertext Transfer Protocol।

## HTTP এর মানে কি?

এটি একটি নেটওয়ার্ক প্রোটোকল যা প্রধানত ইন্টারনেটে HTML (Hyper-Text Markup Language) ডেটাকে আদান প্রদান করার জন্য ব্যবহার করা হয়। এই প্রোটোকলটিতে বেশকিছু নিয়ম থাকে যার ওপর ভিত্তি করে কোনও ওয়েব ব্রাউজার এবং সার্ভারের মধ্যে তথ্য আদান প্রদান করা হয়।

## HTTP কীভাবে কাজ করে?

HTTP সাধারণত ক্লায়েন্ট এবং সার্ভার কম্পিউটিং মডেলের ওপর ভিত্তি করে রিকোয়েস্ট-রেসপন্স প্রোটোকলের মাধ্যমে তথ্য আদান প্রদান করে। যেখানে ব্যাবহারকারির ওয়েব ব্রাউসার ক্লায়েন্ট হিসাবে ও ওয়েবসাইট হোস্টিং সার্ভার হিসাবে কাজ করে। ওয়েবসাইটের সমস্ত তথ্য এই সার্ভারে আগে থেকেই সঞ্চয় থাকে এবং যখন ক্লায়েন্ট কোনও তথ্যের জন্য সার্ভারকে রিকোয়েস্ট পাঠায় তখন সার্ভার সেই তথ্য গুলোকে ক্লায়েন্ট এর কাছে পাঠিয়ে দেয়।

## HTTP এর ইতিহাস

এই প্রটোকলটি সবার প্রথম ১৯৮৯ সালে পদার্থবিদ্যা ও কম্পিউটার বিজ্ঞানী টিম বার্নার্স লী আবিষ্কার করেন। তবে এর পরেও HTTP-র অনেক সংস্করণ হয়েছিল, যেমন- ১৯৯৭ সালের HTTP/1, ২০১৫ সালের HTTP/2 এবং এর সাকসেসর হিসাবে HTTP/3 এর সংস্করণ করা হয়।

বর্তমানে HTTP এরই একটি সুরক্ষিত রূপ HTTPS (Hypertext Transfer Protocol Secure) কে বেশিরভাগ ওয়েবসাইটে ব্যবহার করা হচ্ছে। এটি HTTP এর মতনি কিন্তু এই প্রটোকল দ্বারা পাঠানো তথ্য গুলি এনক্রিপশনের মাধ্যমে সুরক্ষিত ভাবে ক্লায়েন্ট থেকে সার্ভার ও সার্ভার থেকে ক্লায়েন্ট পৌঁছে যাই।

## http ও https এর মধ্যে পার্থক্য

Hypertext Transfer Protocol Secure (HTTPS) হল HTTP এর সুরক্ষিত Version. আপনার Browser এবং যে Website টি আপনি সংযুক্ত আছেন তার মধ্যে কোন তথ্য পাঠানো হয় সেই প্রোটোকল।
HTTPS এর শেষে 'S' দাঁড়িয়েছে এর মানে হলো SECURE বা 'নিরাপদ'। আপনার Browser এবং ওয়েবসাইটের মধ্যে সমস্ত যোগাযোগ এনক্রিপ্ট করা হয়। এটি SSL (এর পূর্ণরূপ হলো SECURED SOCKET LAYER) ব্যবহার করে যা Browser এবং Server এর মধ্যে একটি Encrypt ফর্মে তথ্য স্থানান্তর করে। এটি ডেটা কে এনক্রিপ্ট করে যাতে ক্লায়েন্ট এবং সার্ভারের মধ্যে কোনও ব্যক্তি ডেটা পড়তে না পারে।

কোনও ওয়েবসাইটের URL এর শুরুতে, আপনি অবশ্যই https: // দেখেছেন, এর অর্থ আপনার ডেটা SSL এর দ্বারা সুরক্ষিত করা হয়েছে। আপনি ক্রোমের ADDRESS বারে URL এর সামনে সবুজ রঙের একটি লক আইকনের সাথে SECURE লেখা দেখতে পাবেন।

কিন্তু HTTP সিকিউর নয় দেখবেন যে ওয়েবসাইট এর ইউআরএল এর শুরুতে এইচটিটিপি লেখা থাকে এর মানে ওই ওয়েবসাইট টি সিকিউর নয় লেখাও থাকবে NOT SECURE আপনি এই ওয়েবসাইট এর মাধ্যমে হ্যাক হতে পারেন।

এর মানে হলো ঐসব Website এ আপনি প্রবেশ করলে হ্যাকার রা আপনার সমস্ত ডাটা পড়তে পারবে।
এইজন্য ফ্রেন্ড যখনি আপনি কোনো ওয়েবসাইট এ ভিসিট করবেন আগে দেখে নেবেন এবং HTTPS তেই ভিসিট করবেন এতে হ্যাক হওয়ার হাত থেকে আপনি বাঁচতে পারবেন।