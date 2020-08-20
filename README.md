# Індекс діяльності ОДА v0.5 (2 квартал 2020 року): 

* [Таблиця з параметрами](https://docs.google.com/spreadsheets/d/1ceBKHWzE51ogxC5EFibUah67H05VMdyqYlmkYtJtAa0/edit?usp=sharing)
* [Дані](https://drive.google.com/drive/folders/139xreTx0BqZTgCuHNOB6lPPRPbiHQ5Eu?usp=sharing)
* [Презентація](https://docs.google.com/presentation/d/16wWl2MA3tKkT_bKvJs1O8M92CU05CELNeD51UVup1bU/edit?usp=sharing)

*ви можете самостійно відтворити розрахунки за допомогою скриптів у цьому репозиторії:
для правильної роботи скриптів необхідно завантажити репозиторій та дані у сусідніх теках на жорсткому диску*

## Перелік параметрів індексу

### P1: Соціально-економічний розвиток
* **p1_01:** сума коштів актуальних (діючих) проєктів міжнародної допомоги, бенефіціаром яких є ОДА, у розрахунку на душу населення (коефіцієнт важливості при розрахунку параметру верхнього рівня 1)*
* **p1_02:** сума коштів, залучених за новими проєктами міжнародної допомоги, бенефіціаром яких є ОДА, що почали діяти з початку року до кінця звітного періоду (коефіцієнт важливості 0,5)
* **p1_03:** рівень використання коштів державного фонду регіонального розвитку (коефіцієнт важливості 0,5)
* **p1_04:** частка коштів, затверджених КМУ на виконання конкретних проєктів ДФРР, відносно загальної суми виділених на область коштів (коефіцієнт важливості 1)
#### Джерела даних:
**p1_01-p1_02:** Секретаріат Кабінету міністрів України\
**p1_03-p1_04:** Міністерство розвитку громад та територій

### P2: Бюджет та фінанси
* **p2_01:** рівень надходжень податку на доходи фізичних осіб на одну особу наявного населення станом на 1 січня попереднього року (коефіцієнт важливості при розрахунку параметру верхнього рівня 0,4)
* **p2_02:** рівень виконання доходів загального фонду зведеного бюджету області, мм. Києва та Севастополя (без міжбюджетних трансфертів) (коефіцієнт важливості 0,4)
* **p2_04:** обсяг капітальних видатків зведеного бюджету області, мм. Києва та Севастополя (коефіцієнт важливості 0,4)
* **p2_05:** рівень надходження плати за землю (земельного податку та орендної плати) до зведеного бюджету області, мм. Києва та Севастополя (коефіцієнт важливості 0,4)
* **p2_06:** частка вартості закупівль, проведених за процедурою відкритих торгів відносно загальної вартості закупівель, проведених обласними, Київською та Севастопольською міськими держадміністраціями, їх структурними підрозділами та підприємствами, установами, організаціями, які належать до сфери їх управління (коефіцієнт важливості 1)
* **p2_07:** недоотримано державних фінансових ресурсів за результатами аудиту (грн) (коефіцієнт важливості 0,25)
* **p2_08:** рівень незаконних витрат державних ресурсів за результатами аудиту (грн) (коефіцієнт важливості 0,25)
* **p2_09:** рівень нецільових витрат державних ресурсів за результатами аудиту (грн) (коефіцієнт важливості 0,25)
* **p2_10:** недостача державних ресурсів за результатами аудиту (грн) (коефіцієнт важливості 0,25)
#### Джерела даних:
**p2_01-p2_05:** ДП “Відкриті публічні фінанси” (https://openbudget.gov.ua/)
**p2_06:** ДП “Прозорро” (biProZorro)
**p2_07-p2_10:** Державна аудиторська служба

### P3: Управління майном, приватизація, сприяння розвитку підприємництва та здійснення державної регуляторної політики
* **p3_01:** оголошена вартість майна, що реалізується в рамках малої приватизації у регіоні протягом звітного періоду  (коефіцієнт важливості при розрахунку параметру верхнього рівня 1)
* **p3_02:**  дохід від малої приватизації у регіоні протягом звітного періоду (коефіцієнт важливості 1)
#### Джерела даних:
**p3_01-p3_02:** ДП “Прозорро” (biProZorro Sale)

### P4: Містобудування, ЖКГ, побутове, торговельне обслуговування, транспорт і зв’язок
* **p4_02:** наявність генеральних планів у містах та селищах міського типу (при розрахунку параметру верхнього рівня 1)
* **p4_03:** наявність генеральних планів у селах (коефіцієнт важливості 1)
* **p4_05:** протяжність автомобільних доріг загального користування місцевого значення, на яких проведено капітальний ремонт, реконструкцію, відносно загальної довжини доріг (коефіцієнт важливості 1)
* **p4_06:** рівень використання коштів дорожнього фонду, передбачених для будівництва, реконструкції, ремонту та утримання автомобільних доріг загального користування місцевого значення, вулиць і доріг комунальної власності у населених пунктах (вага 1)
* **p4_07:** середній рівень будівельної готовності об'єктів Великого будівництва (за касовими видатками) (вага 1)
* **p4_08:** середній рівень освоєння коштів, виділених на об'єкти Великого будівництва з усіх джерел (вага 1)
#### Джерела даних:
**p4_01:** Міністерство енергетики та захисту довкілля
**p4_02, p4_03, p4_05:** Обласні державні адміністрації
**p4_06:** Дані КМУ, зібрані з ОДА за Постановою від 24 січня 2020 р. № 35
**p4_07-p4_08:** Міністерство розвитку громад та територій

### P5: Використання та охорона земель, природних ресурсів і охорона довкілля
* **p5_01:** обсяги незаконних вирубок лісів відносно загальної площі лісових насаджень (коефіцієнт важливості при розрахунку параметру верхнього рівня 1)
* **p5_02:** частка земель лісового фонду, на які оформлені правовстановлюючі документи (коефіцієнт важливості 1)
* **p5_03:** площа об'єктів природно-заповідного фонду області відносно загальної площі області (коефіцієнт важливості 1)
* **p5_07:** частка площі заповідної території із затвердженими проектами землеустрою від площі заповідної території (коефіцієнт важливості 1)
#### Джерела даних:
**p5_01-p5_02, p5_07:** Обласні державні адміністрації
**p5_03:** Міністерство енергетики та захисту довкілля

### P6: Наука, освіта, охорона здоров’я, культура, фізкультура і спорт, материнство і дитинство, сім’я та молодь
* **p6_01:** кількість укладених декларацій про вибір лікаря, який надає первинну медичну допомогу (коефіцієнт важливості при розрахунку параметру верхнього рівня 0,5)
* **p6_02:** рівень охоплення щепленнями відповідно до річного календаря профілактичних щеплень в Україні (коефіцієнт важливості 0,5)
* **p6_03:** частка лікувально-профілактичних закладів, що мають статус некомерційних комунальних підприємств (коеф. важливості 1)
* **p6_04:** частка лікувально-профілактичних закладів, підключених до системи e-health (коефіцієнт важливості 1)
* **p6_05:** середній розмір класу у сільських закладах загальної середньої освіти (ЗЗСО) (коефіцієнт важливості 1)
* **p6_06:** частка ЗЗСО, у яких навчається менше 100 учнів, за винятком ЗЗСО І та ІІІ ступеня (коефіцієнт важливості 1)
* **p6_07:** кількість учнів, що навчаються індивідуально не за станом здоров’я (коефіцієнт важливості 1)
* **p6_08:** частка ЗЗСО ІІ та/або ІІІ ступеня, у яких бракує профільних вчителів з двох чи більше предметів (української мови та літератури, історії, фізики, математики, основ інформатики, хімії, географії, біології) (коефіцієнт важливості 1)
* **p6_09:** кількість дітей віком від трьох до п’яти років, охоплених дошкільною освітою (коефіцієнт важливості 1)
#### Джерела даних:
**p6_01, p6_02, p6_09:** Дані КМУ, зібрані з ОДА за Постановою від 24 січня 2020 р. № 35
**p6_03-p6_04:** Національна служба здоров’я України
**p6_05-p6_08:** ДНУ “Інститут освітньої аналітики”

### P7: Соціальне забезпечення та соціальний захист населення
* **p7_01:** кількість виданих одиниць технічних та інших засобів реабілітації у розрахунку на одну особу з інвалідністю (коефіцієнт важливості при розрахунку параметру верхнього рівня 1)
* **p7_02:** частка дітей, що перебуває на обліку в інклюзивно-ресурсних центрах (коефіцієнт важливості 1)
* **p7_03:** частка дітей-сиріт та дітей, позбавлених батьківського піклування, яких влаштували до сімейних форм виховання (коефіцієнт важливості 0,5)
* **p7_06:** частка дітей, що здобуває освіту в інклюзивних групах ЗДО та інклюзивних класах ЗЗСО (коефіцієнт важливості 0,5)
* **p7_07:** кількість місць у закладах (відділеннях) соціального захисту для бездомних громадян (коефіцієнт важливості 0,5)
#### Джерела даних:
**p7_01:** Фонд соціального захисту інвалідів
**p7_02, p7_06:** Обласні державні адміністрації
**p7_03, p7_07:** Міністерство соціальної політики

### P8: Зайнятість населення, праця та заробітна плата
* **p8_03:** кількість нещасних випадків на виробництві (коефіцієнт важливості при розрахунку параметру верхнього рівня 1)
* **p8_04:** частка неформально зайнятого населення (коефіцієнт важливості 1)
* **p8_05:** прострочена кредиторська заборгованість з виплати заробітної плати (з нарахуваннями) працівникам бюджетних установ, які утримуються за рахунок коштів місцевих бюджеті (коефіцієнт важливості 1)
#### Джерела даних:
**p8_03-p8_04:** Міністерство розвитку економіки, торгівлі та сільського господарства
**p8_05:** Дані КМУ, зібрані з ОДА за Постановою від 24 січня 2020 р. № 35
