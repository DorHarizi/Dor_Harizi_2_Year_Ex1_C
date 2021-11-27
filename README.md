##NumClass dictionary
---

עליכם לכתוב ספריה שחושפת למשתמש מספר פונקציות לסיווג מספרים. הפונקציות יוגדרו בקובץ
עבור שאילתה בוליאנית: int כאשר מחזירים NumClass.h
0 is false
1 is true
על הקובץ להכיל את החתימות:
/* will return if a number is Armstrong number
An Armstrong number is an n-digit number that is equal to the sum of the nth powers of its digits.
For Example: 407 = 43 + 03 + 73 = 64 + 0 + 343 = 407
*/
int isArmstrong(int)
/* will return if a number is a palindrome */
int isPalindrome(int)
/* will return if a number is prime*/
int isPrime(int)
/*Strong number is a special number whose sum of the factorial of digits is equal to the original
number. For Example: 145 is strong number
1! + 4! + 5! = 145
*/
int isStrong(int)
את מימושי הפונקציות יש לכתוב 3 קבצים שונים.
isPrime, isStrong שיכיל את מימושי הפונקציות basicClassification.c 1.קובץ ראשון
אשר ימומשו isArmstrong, isPalindrome שיכיל את מימושי פונקציות advancedClassificationLoop.c .2
בעזרת לולאות
אשר isArmstrong, isPalindrome שיכיל את מימושי פונקציות advancedClassificationRecursion.c .3
ימומשו בעזרת רקורסיה

---

##Main
---

עליכם לכתוב תוכנית שתקבל מהמשתמש 2 מספרים שלמים חיובים עליכם להדפיס למסך 4 שורות אשר
יכילו את כל המספרים הראשונים, מספרי ארמסטרונג, מספרים חזקים והפלנדרומים אשר בין שני המספרים
שהתקבלו )כולל המספרים עצמם(.
אין להדפיס כל פלט נוסף פרט למה שהתבקשת. עליכם להיות תואמים לחלוטין לדוגמאות הקלט והפלט
שתקבלו.

---

##Makefile
---

עם הפקודות הבאות: makefile עליכם להגיש קובץ בשם
שתכיל את מימושי כל libclassloops.a על הקומפיילר ליצור את הספרייה הסטאטית make loops *
)basic הפונקציות שלכם עם המימוש בעזרת הלולאות )כולל ה
שתכיל את מימושי כל libclassrec.a על הקומפיילר ליצור את הספרייה הסטאטית make recursives *
)basic הפונקציות שלכם עם המימוש בעזרת רקורסיה )כולל ה
שתכיל את מימושי כל libclassrec.so על הקומפיילר ליצור את הספרייה דינאמית make recursived *
)basic הפונקציות שלכם עם המימוש בעזרת רקורסיה )כולל ה
שתכיל את מימושי כל libclassloops.so על הקומפיילר ליצור את הספרייה דינאמית make loopd *
)basic הפונקציות שלכם עם המימוש בעזרת לולאות )כולל ה
כשהיא מלונקג'ת mains על הקומפיילר ליצור את התוכנית הראשית שלכם בשם make mains *
לספרייה הסטאטית הרקורסיבי ת. אם הספרייה כבר הייתה קיימת אין לקמפל אותה שוב.
כשהיא maindloop על הקומפיילר ליצור את התוכנית הראשית שלכם בשם make maindloop *
מלונקג'ת לספרייה הדינאמית עם הלולאות.
כשהיא maindrec על הקומפיילר ליצור את התוכנית הראשית שלכם בשם make maindrec *
מלונקג'ת לספרייה הדינאמית עם הרקורסיו ת.
יקמפל את כל הספריות והתוכניות שלכם. אם משהו כבר קיים אין לקמפל אותו שוב. make all *
עצמו. makefile וה .h .c .txt ינקה את התיקיה מכל הקבצים המקומפלים וישאיר רק קבצי make clean 







