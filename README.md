# DAX-Functions

- **Sum (جمع)**
Meaning: Sum ka matlab hai "total" ya "addition". Ye function numbers ko add karke unka total nikalta hai.

Example:
Agar aapke pass yeh numbers hain: 5, 10, 15
Toh SUM = 5 + 10 + 15 = 30

Practical Use:
Aap iska istemal monthly expenses calculate karne ke liye kar sakte hain. Masalan:

     January expense: 5000
     February expense: 7000
     March expense: 6000
     SUM = 5000 + 7000 + 6000 = 18000

- **Average (اوسط)**
Meaning: Average ka matlab hai "mean". Ye function numbers ka average nikalta hai. Isko nikalne ke liye sum ko count se divide karte hain.

Formula:
Average = Sum / Count
Example:

    Numbers: 4, 8, 12
    SUM = 4 + 8 + 12 = 24
    COUNT = 3
    AVERAGE = 24 / 3 = 8

Practical Use:
Aap iska istemal students ki marks calculate karne ke liye kar sakte hain. Masalan:

    Student ne 3 tests diye hain: 70, 80, 90
    AVERAGE = (70 + 80 + 90) / 3 = 80

- **Max (زیادہ سے زیادہ)**

Meaning: Max ka matlab hai sabse bada number find karna.

Example:

    Numbers: 10, 25, 5, 40
    MAX = 40

Practical Use:
Aap iska istemal sales data mein sabse zyada sale find karne ke liye kar sakte hain. Masalan:

    Sales data: 5000, 7000, 6000
    MAX = 7000

- **Min (کم سے کم)**
Meaning: Min ka matlab hai sabse chota number find karna.

Example:

    Numbers: 10, 25, 5, 40
    MIN = 5

Practical Use:

Aap iska istemal temperature data mein sabse kam temperature find karne ke liye kar sakte hain. Masalan:

    Temperature data: 30°C, 25°C, 35°C
    MIN = 25°C

- **Divide (تقسیم)**
Meaning: Divide ka matlab hai ek number ko doosre number se divide karna.

Formula:
Result = Number1 / Number2

Example:

    Number1 = 10, Number2 = 2
    DIVIDE = 10 / 2 = 5

Practical Use:

Aap iska istemal budget distribution karne ke liye kar sakte hain. Masalan:

    Total Budget: 10000, Members: 5
    DIVIDE = 10000 / 5 = 2000 per member

- **Count (گنتی)**
Meaning: Count ka matlab hai kitne numbers ya items hain.

Example:

    Numbers: 5, 10, 15, 20
    COUNT = 4

Practical Use:
Aap iska istemal students ki total count nikalne ke liye kar sakte hain. Masalan:
Class mein students: Ali, Ahmed, Sara, Zain
COUNT = 4

- **CountA (غیر خالی خانوں کی گنتی)**
  
Meaning: CountA ka matlab hai non-empty cells (khali na hone wale cells) ki count karna.

Example:

    Data: Ali, , Sara, Zain
    COUNTA = 3 (kyunki ek cell khali hai)

Practical Use:

Aap iska istemal attendance sheet mein present students ki count nikalne ke liye kar sakte hain. Masalan:

    Attendance: Present, Absent, Present, Present
    COUNTA = 3 (kyunki sirf 3 students present hain)

- **CountRows (قطاروں کی گنتی)**

Meaning: CountRows ka matlab hai table ya dataset mein kitni rows hain.

Example:

    Table:
    Ali
    20
    Ahmed
    22
    Sara
    21
    COUNTROWS = 3

Practical Use:

Aap iska istemal database mein total records ki count nikalne ke liye kar sakte hain. Masalan:

    Customer Records: 100 customers
    COUNTROWS = 100

- **DistinctCount (منحصربفروں کی گنتی)**

Meaning: DistinctCount ka matlab hai unique values ki count karna.

Example:

    Data: Apple, Banana, Apple, Orange
    DISTINCTCOUNT = 3 (kyunki sirf 3 unique fruits hain: Apple, Banana, Orange)

Practical Use:

Aap iska istemal product categories ki unique count nikalne ke liye kar sakte hain. Masalan:

    Products: Laptop, Phone, Laptop, Tablet
    DISTINCTCOUNT = 3 (kyunki sirf 3 unique categories hain: Laptop, Phone, Tablet)

Final Recap:

    Sum : Total addition (جمع)
    Average : Mean of numbers (اوسط)
    Max : Largest number (زیادہ سے زیادہ)
    Min : Smallest number (کم سے کم)
Divide : Division of numbers (تقسیم)
Count : Total numbers/items (گنتی)
CountA : Non-empty cells (غیر خالی خانوں کی گنتی)
CountRows : Total rows in a table (قطاروں کی گنتی)
DistinctCount : Unique values (منحصربفروں کی گنتی)
