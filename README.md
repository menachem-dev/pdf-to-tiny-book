# pdf-to-tiny-book
I wrote the instructions in Hebrew. If you'r not jewish: good luck with google-translate...

dvirgim@gmail.com

לטובת הציבור שמתי פה את התוכנה היעילה הנ"ל. השימוש אמור להיות די אינטואיבטיבי.
כמו כן הוספתי את הקוד (בפייתון), למי שחפץ לעשות בו שינויים ולשחק עם זה (אצלו במחשב. לא פה).

הסבר:

הורדת התוכנה:
יש להוריד את קובץ הexe. המחשב לפעמים חושד שזה וירוס, אז תאשרו למחשב שימוש בתוכנה.

כיצד ספר בנוי:
ספר מורכב מחוברות. כל חוברת מודבקת או נתפרת לחוברת אחרת.
בתוכנה יש אפשרות לבקש תפירה (sew) או הדבקה (lazy).

השימוש בתוכנה וההדפסה:
לתוכנה מכניסים קובץ pdf, לאחר שערכתם אותו עם גודל הכתב הרצוי וכו. כדאי להוסיף לקובץ עמוד ריק בהתחלה ובסוף.
אם תבחרו בהדבקה (lazy) התוכנה תוסיף עמוד ריק בתחילת ובסוף כל חוברת.
דוגמה: אם יש לכם 150 עמודים, ובחרתם 32 עמודים בכל חוברת, יצאו לכם 5 חוברות שבכל חוברת עמוד ראשון ואחרון ריק (כדי שתוכלו להדביק את החוברות אחת לשניה).
התוכנה מוציאה קובץ בשם "reay to print". יש לראות שהקובץ כראוי, ואז להדפיס דו"צ - אם הקובף עם דפים גבוהים וצרים, יש להדפיס "flip on the long side", אם דפים רחבים ונמוכים אז "flip on the short side". (כמו כן התוכנה מיצרת תקיית trash, אותה ניתן למחוק בתום התהליך).
בתוכנה החדשה שכאן (סיומת ++) הוספתי אפשרות להדפיס חוברת ארוכה. המטרה היא שתכניסו במספר החוברת את מספר העמודים בספר, והתוכנה תסדר זאת כך שלאחר ההדפסה, לוקחים את ערימות הדפים שיצאו לאחר החיתוך בגיליוטינה, עורמים אחת על השניה ומקפלים. זה חוסך זמן, לא צריך לסדר את החוברת דף דף... 

יצירת הספר בהדבקה (תפירה רעיון דומה):
לאחר ההדפסה, חותכים את הדפים בגיליוטינה. אם הגדרתם 4 עמודים בכל צד של הדף, אז צריך לחתוך רק ל2. וכן על זה הדרך.
אוספים לפי הסדר ומקפלים. אם הגדרתם 32 עמודים בחוברת, אז צריך לקחת שמונה דפים קטנים ולקפל לחוברות.
כל חוברת להדק באמצע, כדי שהדפים לא יפלו.
לחבר יחד את כל החוברות עם דבק (שימו לב לסדר!)
להכין כריכה. קרטון פיצה, קרטון חזק יותר או סתם נייר יפה. תלוי כמה חזק תרצו שהספר יהיה וכמה אתם יצירתיים.


בהצלחה, ניתן לפנות אלי בשאלות במייל או פנים אל פנים או במספר למי שיש...). לא בשעת הסדרים (אם זה פנים אל פנים).
דביר ג'מדני.

נ"ב למביני עניין:
הקוד לא מדפיס הודעת שגיאה אם פישלתם בנתונים. אז שימו לב.
אם יש לאחר הפעלת התוכנה חלק מהדפים נחתכים בקצוות, זה כנראה כי לקחתם pdf סרוק מhebrewbooks או משהו כזה. הפתרון הוא לשנות בקוד את השורות הללו:
xPrime = 842 # 792
yPrime = 595 # 612
(הן מופיעות פעמיים בקובץ המשני, בסדר הפוך. צריך לשנות את היחס - נניח להכפיל את x בקצת כדי שיגדל הגובה, או משהו כזה. תלוי מקרה).


I have put this neat and useful program here, it's use should be rather intuitive.

Explanation: 
 
Downloading:

Downloading and running the .exe file usually works. Sometimes windows may think its a virus, in that case you just tell windows to trust it.

How a book is built:
A book is build is by binding multiple booklets, each one glued or sewn to another.
The program has options for sewing and gluing (lazy).

Using the program and printing: 
The input to the program is a .pdf file.
If you choose to go with gluing the program will add an extra blank page an the beginning and the end of every booklet.
Example: if you have a book of 150 pages, and choose 32 pages per booklet, you will end up with 5 booklets each having a blank page at the beginning and the end (in ordar to glue them to each other).
The program outputs a file called “reay to print”. Make sure it is formatted properly and then print double sided – if the file has tall and thin pages, print with “flip on long side”, if the pages are short and wide print with “flip on short side”. Along with the print file the program will also output a trash folder that can be deleted at the end of the process.

Putting the book together with glue (sewing is a similar idea):
after printing cut the pages precisely. If you have defined 4 pages on every printed paper you will only need to cut paper in 2. And so on.  Collecte the pages in order and fold them. If you have 32 pages in a booklet then you should have 8 papers to fold at a time. Staple the booklet so that it doesn't fall apart. Glue all the booklets together (beware of the order).
Make a cover out of cardboard of sorts.
And there yo have it.

