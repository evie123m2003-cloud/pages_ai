# Random Forest

האם מודל Random Forest פותר בעיית קלסיפיקציה, רגרסיה או גם וגם?

גם וגם 

מהו הרעיון המרכזי שעליו מבוסס מודל Random Forest?

הרעיון המרכזי של המודל זה שילוב של כמה עצי החלטה במקום להסתמך על עץ אחד המודל משלב טת התחזיות של כמה עצי החלטה ומגיע לתוצאה יציבה יותר ומדוייקת יותר.

כיצד Random Forest קשור למודל Decision Tree?

מודלRandom Forest הוא אוסף של כמה Decision Tree והתוצאה הסופית במודל Random Forest מתקבלת מכה עצי  Decision Tree. 

מהו Bootstrap Sampling וכיצד הוא משמש ב־Random Forest?

תהליך שבו לוקחים דגימות אקראיות שיש בהם חזרה זה משממש במודל כדי לייצר שונות בדגימות בכל עץ.

מדוע השימוש באקראיות משפר את ביצועי המודל?

אקראיות  מוודא שכל עץ יהיה שונה קצת מאחרים טעויות של עצים שונים לא יהיו זהות  מה שמשפר את הדיוק.

כיצד מתקבלת התחזית הסופית ב־Random Forest לקלסיפיקציה?

על עץ מצביע למחלקה מסויימת התחזית הסופית מתקבלת על ידי הצבעת רוב המחלקה שקיבלה את מספר הקולות הגבוה ביותר נבחרת.

מהו מנגנון ההצבעה (Voting) ב־Random Forest וכיצד הוא פועל?

מנגנון ההצבעה הוא תהליך שכל עץ נותן תחזית משלו.

בבעיות קלאסיפיקציה נבחרת המחלקה עם רוב הקולות ובבעיות רגרסיה נבחר ממוצע התחזיות

כיצד מתקבלת התחזית הסופית ב־Random Forest לרגרסיה?

בבעיות רגרסיה על עץ מחזיר תשובה מספרית והתחזית הסופית מתקבלת על ידי חישוב ממוצע של כל התחזיות שהתקבלו מהעצים. 

אילו Hyperparameters נפוצים קיימים במודל Random Forest?

הHyperparameters הנפוצים הם:

מספר עצי ההחלטה, העומק המקסימלי של כל עץ, מספר המאפיינים שנבדקים בכל פיצול, מספר מינימלי של דוגמאות לפיצול, מספר מינמלי של דוגמאות בעלה.

מהו OOB Error (Out-Of-Bag Error) וכיצד משתמשים בו להערכת ביצועי המודל?

37 אחוז מהדגימות של נבחרו לאימון של  עץ מסוים דגימות אלו משמשות לבדיקה של אותו עץ.

מה היתרון של Random Forest מבחינת יציבות המודל לעומת Decision Tree?

מודל Random Forest  משלב תחזיות של הרבה עצים ונותן תחזיות יציבות ומדוייקות הרבה יותר ממודל Decision Tree שמסתמך על עץ בודד שעלול לעשות טעות לעומת Random Forest שיש כמה עצים זה נותן פחות משקל לטעות.

אילו מדדי ביצוע מתאימים להערכת מודל Random Forest בקלסיפיקציה וברגרסיה?

בבעיות קלסיפקציה 
Accuracy
recall
Precision 
f1(שילוב של המדדים)
בבעיות רגרסיה 
MSE
MAE
R בריבוע

יש לשלוח את הפתרון למייל:
📧 [pythonai200425+supfinal@gmail.com](mailto:pythonai200425+supfinal@gmail.com)
