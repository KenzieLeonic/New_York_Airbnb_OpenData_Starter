# New_York_Airbnb_OpenData_Starter

Sources = https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

## Data Dictionary (data detail EN to TH)
number of columns | columns name
0. id : id เป็นตัวแปรประเภท ตัวเลข
1. name : ชื่อบ้านเช้า เป็นตัวแปรประเภท string
2. host_id : หลายเลขเจ้าของบ้าน ตัวแปรประเภท string
3. host_name : ชื่อเจ้าของบ้าน เป็นตัวแปรประเภท string
4. neighbourhood_group : เขตการปกครองท้องถิ่นใน New York เป็นตัวแปรประเภท string 
- Manhattan = แมนแฮตตัน
- Brooklyn = บรุกลิน
- Queens = ควีน
- Bronx = บร็องซ์ 
- Staten Island = เกาะสแตเทน  

5. neighbourhood : พื้นที่ใกล้กับที่พัก เป็นตัวแปรประเภท string 
6. latitude : พิกัดละติจูด เป็นตัวแปรประเภททศนิยม
7. longitude : พิกัดลองจิจูด เป็นตัวแปรประเภททศนิยม
8. room_type : ประเภทห้องพัก เป็นตัวแปรประเภท string
- Entire home/apt = บ้านหรืออพาร์ตเมนต์  
- Private room = ห้องส่วนตัว
- Shared room = ห้องแชร์ 
9. price : ราคาที่พัก เป็นตัวแปรประเภท float 
10. minimum_nights: คืนที่นอนค้างน้อยที่สุด เป็นตัวแปรประเภทตัวเลข
11. number_of_reviews : จำนวนคนที่มารีวิว เป็นตัวแปรประเภทตัวเลข
12. last_review : วันที่ลูกค้าเขียนรีวิวล่าสุด เป็นตัวแปรประเภทวันที่ 
13. reviews_per_month: จำนวนคนที่มารีวิวต่อเดือน เป็นตัวแปรประเภททศนิยม
14. calculated_host_listings_count : จำนวนรายการต่อเจ้าของบ้าน เป็นตัวแปรประเภทตัวเลข 
15. availability_365 : จำนวนวันที่ทำการเปิดจองที่พัก เป็นตัวแปรประเภทตัวเลข
