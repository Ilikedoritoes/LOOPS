#define _CRT_SECRURE_NO_WARNINGS
#include <stdlib.h>
#include <stdio.h>

void main()
{
//                                          לולאות
// לולאת 4 היא לולאה שמפעילה קטע קוד מסויים אשר נמצא בתוך בלוק 0 פעמים או יותר כול עוד תנאי הלולאה מחזיר אמת
// נשתמש בלולאת 4 כדי לחסוך שיכפול של קטעי קוד 
//        עדכון            תנאי          אתחול
// (האתחול: מתבצע פעם ראשונה בלבד)
    int index;
    for (index = 0; index < 100; index++)
   {
        printf("OR IS COOL!!!!!!!\n");
