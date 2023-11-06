# HighParking
האתר שלנו עוסק בניהול רשתות חניון
טבלאות:
טבלת סטטוס - תכונות
רגיל
וי.אי.פי
פרימיום

טבלת לקוחות:
ת.ז.
שם
כתובת מייל
מספר טלפון
קוד אישי (אופציונלי)
מספר אשראי
מספר ביט
סטטוס
נקודות

טבלת תעריף:(ENUM)

טבלת קבלה:
מספר קבלה(אוטומטי)
ת.ז.
סוג משתמש
זמן כניסה 
זמן יציאה
סה"כ זמן
תאריך
סוג תשלום
סך לתשלום

status:
POST https://highparking.com/status/{string}
GET https://highparking.com/status
PUT	https://highparking.com/status/{string}
DELETE https://highparking.com/status/{string}

customer:
POST https://highparking.com/customer/{id}
GET https://highparking.com/customer
GET https://highparking.com/customer/{id}
PUT	https://highparking.com/customer/{id}
DELETE https://highparking.com/customer/{id}

rate:
POST https://highparking.com/customer/{key}
GET https://highparking.com/customer
GET https://highparking.com/customer/{key}
PUT	https://highparking.com/customer/{key}
DELETE https://highparking.com/customer/{key}

Invoicing:

POST https://highparking.com/customer/{id}
GET https://highparking.com/customer
GET https://highparking.com/customer/{id}
PUT	https://highparking.com/customer/{id}
DELETE https://highparking.com/customer/{id}





