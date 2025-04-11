<div dir="rtl">

# النظام الثماني في الكمبيوتر

## سؤال ١

- ![Homework](/resources/_8_octal/questions/FirstQuestions.png)

- تلميح:
  ![Convert from Octal to Decimal Example](/resources/_8_octal/hints/ConvertFromOctalToDecimalExample.png)

## الحل

</div>

1. 100
    - 1
        - 1 * 8^2
            - 1 * 64
                - 64
    - 0
        - 0 * 8^1
            - 0 * 8
                - 0
    - 0
        - 0 * 8^0
            - 0 * 1
                - 0
    - 64 + 0 + 0
        - 64

2. 512
    - 5
        - 5 * 8^2
            - 5 * 64
                - 320
    - 1
        - 1 * 8^1
            - 1 * 8
                - 8
    - 2
        - 2 * 8^0
            - 2 * 1
                - 2
    - 320 + 8 + 2
        - 330

---

<div dir="rtl">

## سؤال ٢

- ![Homework](/resources/_8_octal/questions/SecondQuestions.png)

- تلميح:
  ![Convert from Decimal to Octal Example](/resources/_8_octal/hints/ConvertFromDecimalToOctalExample.png)

## الحل

</div>

- 64

| Decimal System / 8 | Result | Integer | Fraction | Remainder | Octal System Digit |
|:------------------:|:------:|:-------:|:--------:|:---------:|:------------------:|
|       64 / 8       |   8    |    8    |    0     |   8 * 0   |         0          |
|       8 / 8        |   1    |    1    |    0     |   8 * 0   |         0          |
|       1 / 8        | 0.125  |    0    |  0.125   | 8 * 0.125 |         1          |

= 100

- 330

| Decimal System / 8 | Result | Integer | Fraction | Remainder | Octal System Digit |
|:------------------:|:------:|:-------:|:--------:|:---------:|:------------------:|
|      330 / 8       | 41.25  |   41    |   0.25   | 8 * 0.25  |         2          |
|       41 / 8       | 5.125  |    5    |  0.125   | 8 * 0.125 |         1          |
|       5 / 8        | 0.625  |    0    |  0.625   | 8 * 0.625 |         5          |

= 512

---

<div dir="rtl">

## سؤال ٣

- ![Homework](/resources/_8_octal/questions/ThirdQuestions.png)

- تلميح:
  ![Convert from Octal to Binary Example](/resources/_8_octal/hints/ConvertFromOctalToBinaryExample.png)

## الحل

</div>

1. 100
    - 1
        - 001
    - 0
        - 000
    - 0
        - 000
    - = `001` `000` `000`
        - = `0100` `0000`
2. 512
    - 5
        - 101
    - 1
        - 001
    - 2
        - 010
    - = `101` `001` `010`
        - = `0001` `0100` `1010`

---

<div dir="rtl">

## سؤال ٤

- ![Homework](/resources/_8_octal/questions/FourthQuestions.png)

- تلميح:
  ![Convert from Octal to Binary Example](/resources/_8_octal/hints/ConvertFromBinaryToOctalExample.png)

## الحل

</div>

1. `001` `000` `000`
    - 001
        - 1
    - 000
        - 0
    - 000
        - 0
    - = 100
2. `101` `001` `010`
    - 101
        - 5
    - 001
        - 1
    - 010
        - 2
    - = 512