# Mô tả tập dữ liệu titanic
![Titanic](https://cafefcdn.com/203337114487263232/2023/7/3/dt6rd9-168794189980444550528-1688002071245-1688002071386463675400-16883921272271781744944-1688427759024-1688427759243994796231.jpg)

| Variable  | Definition                  | Key                                 |
|-----------|-----------------------------|-------------------------------------|
| survival  | Survival                    | 0 = No, 1 = Yes                     |
| pclass    | Ticket class                | 1 = 1st, 2 = 2nd, 3 = 3rd           |
| sex       | Sex                         |                                     |
| Age       | Age in years                |                                     |
| sibsp     | # of siblings / spouses     |                                     |
| parch     | # of parents / children     |                                     |
| ticket    | Ticket number               |                                     |
| fare      | Passenger fare              |                                     |
| cabin     | Cabin number                |                                     |
| embarked  | Port of Embarkation         | C = Cherbourg, Q = Queenstown, S = Southampton |

* sibsp : 
The dataset defines family relations in this way...

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)

* parch :
The dataset defines family relations in this way...

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children travelled only with a nanny, therefore parch=0 for them.

### Mục đích của tập dữ liệu

* Dự đoán xem có bao nhiêu người sống sót trên con tàu Titanic
