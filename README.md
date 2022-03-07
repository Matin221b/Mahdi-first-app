سلام مهدی محمدی هستم کلاس 108

توضیح درمورد نحوه ساخت این پروژه:دراولین مرحله: برنامه‌ی به نام (نودجی اس) را نصب کردیم

در دومین مرحله:برنامه ی به نام (گیت) را نصب کردیم 

در سومین مرحله:وارد برنامه ی (گیت بش) شدیم و شروع به کد زدن کردیم ترتیب کدهایی که زدیم این شکلی هست

1.```npm -v```

2.```npm install -g @vue/cli```

3.```npm install npm@latest -g```

4.```npm install --global yarn```

5.```yarn --version```

6.```node --version```


این دستور هم صفحه ی گیت بش را تمیز میکنه

7.```clear```

این کد هم میره به پوشه یوزرز در درایو سی

8.```cd ~```

برای اطمینان این 3 تا کد ها را هم زدیم تا از ورژن ها مطمئن بشیم.

9.1.```node -v```2.```yarn -v```3.```npm -v```

10.```Set-ExecutionPolicy -ExecutionPolicy Undefined -Scope LocalMachine```

الان به ساخت پوشه ها رسیدیم

11.```cd ~```


12.```mkdir projects```


13.```cd projects```

14.```mkdir talash && cd talash```



این کد برای لیست کردن محتویات پوشه است

15.```ls```

16.```yarn create vite first-app --template vue```

17.```cd first-app```

18.```yarn```

19.```yarn dev```


بعد از انجام این کار ها این آدرس را به ما میده http://localhost:3000/

بعد از ورود به این آدرس پروژه ساخته می شه و ران میشه

2-توضیح کلی درمورد این برنامه و محتوای پوشه‌یfirst-app:

محتوای پوشه ی first-app:

1_.vscode

2_dist

3_node_modules

4_public

5_src

6_.gitignore

7_index.html

8_package.json

9_README.md

10_vite.config.js

11_yarn.lock

توضیحات درمورد پروژه:یکی از قسمت های مهم این پروژه index.html است که ما کد هایمان را برای ساخت سایت آنجا میزنیم

این پروژه قسمت های مختلفی داره مثل بخش HelloWorld که در پوشه ی src\components است

و میتوانیم داخلش سایز رنگ و فونت نوشتمون را تغییر دهیم