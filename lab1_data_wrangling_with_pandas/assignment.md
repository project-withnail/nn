За допомогою Pandas надати відповідь на питання на базі датасету adult.data.csv.

Пріоритет середовища виконання Colab.


Унікальні значення ознак:
• age: continuous.

• workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov,
Without-pay, Never-worked.

• fnlwgt: continuous.

• education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc,
9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.

• education-num: continuous.

• marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed,
Married-spouse-absent, Married-AF-spouse.

• occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-
specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-
moving, Priv-house-serv, Protective-serv, Armed-Forces.

• relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.

• race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.

• sex: Female, Male.

• capital-gain: continuous.

• capital-loss: continuous.

• hours-per-week: continuous.

• native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany,
Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras,
Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-
Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua,
Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-
Netherlands.

• salary: >50K,<=50K


1. Скільки чоловіків і жінок (ознака sex) представлено в цьому наборі даних?

2. Який середній вік (ознака age) жінок?

3. Яка частка громадян Німеччини (ознака native-country)?

4. Які середні значення і середньоквадратичні відхилення віку тих, хто отримує
більше 50K в рік (ознака salary) і тих, хто отримує менше 50K в рік?

5. Чи правда, що люди, які отримують більше 50k, мають як мінімум вищу
освіту? (Ознака education - Bachelors, Prof-school, Assoc-acdm, Assoc-voc, Masters
або Doctorate)

6. Виведіть статистику віку для кожної раси (ознака race) і кожної статі.
Використовуйте groupby і describe. Знайдіть таким чином максимальний вік
чоловіків раси Amer-Indian-Eskimo.

7. Серед кого більша частка заробляючих багато (> 50K): серед одружених або
неодружених чоловіків (ознака marital-status)? Одруженими вважаємо тих, у кого
marital-status починається з Married (Married-civ-spouse, Married-spouse-absent
або Married-AF-spouse), інших вважаємо холостими.

8. Яка максимальна кількість годин людина працює в тиждень (ознака hours-per-
week)? Скільки людей працюють таку кількість годин і який серед них відсоток
заробляють багато?

9. Порахуйте середній час роботи (hours-per-week) тих, хто заробляє мало і багато
(salary) для кожної країни (native-country).

## deadline is 13_10_20
