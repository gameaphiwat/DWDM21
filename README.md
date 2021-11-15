# **DWDM21**
# **Data Warehouse &amp; Data Mining 2021**

**นายอภิวัฒน์ เหลี่ยมสิงขร 623020545-4**

## **Group Name : I Love อ.ต้น**

1.**ช่วงชัย จันทร์มณี**       **รหัส 623020519-5**

2.**ชยากร** **จันทร์ลุน**        **รหัส 623020517-9**

3.**นวลแพร** **พนาวัฒนวงค์**   **รหัส 623020525-0**

4.**อภิวัฒน์** **เหลี่ยมสิงขร**      **รหัส 623020545-4**

5.**กิตติคุณ** **เกียรติศักดิ์ศิริ**   **รหัส 623020760-0**


# สารบัญเนื้อหา

* บทที่1 [Introduction](https://github.com/gameaphiwat/DWDM21/blob/main/HW%201.pdf)
  * Data Warehouse คืออะไร
  * Data Mining คืออะไร
  * ทำไมต้องทำ Data Mining
  * ตัวอย่างข้อมูล
  * การเรียกชื่ออื่น ๆ
  * ลักษณะภาพรวม
  * ขั้นตอนการทำข้อมูล
  * หัวข้อที่จะเรียน

* บทที่ 2 [Getting to Know Your Data](https://github.com/gameaphiwat/DWDM21/blob/main/HW%202.1.pdf)
  * ลักษณะภาพว่าแต่ละมิติแตกต่างกันอย่างไร
  * ลักษณะข้อมูล EX ข้อมูลเป้นกราฟ , วิดีโอ
  * ชนิดของข้อมูล
  * คุณสมบัติที่สำคัญ
  * ชนิดของ Attribute
  * การนำค่าสถิติเข้ามาเกี่ยวข้อง

* บทที่ 3 [Data Preprocessing](https://github.com/gameaphiwat/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%203.pdf)
  * Data Cleaning คืออะไร 
  * Data Integration คืออะไร 
  * Data Reduction and Tranformation คืออะไร 
  * Dimensionality Reduction คืออะไร

* บทที่ 4 [Data Warehousing and On-line Anaalytical Processing](https://github.com/gameaphiwat/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%204.pdf)
  * Data Warehousing คืออะไร
  * OLTP & OLAP
  * ทำไมถึงต้องแยก Data Warehousing
  * โมเดล ทั้ง 3 แบบของ Data Warehousing
  * Meta Data
  * การสร้างแบบจำลองแนวคิดของ Data Warehousing ว่ามีแบบไหนบ้าง แต่ละแบบเป็นอย่างไร
  * ลักษณะข้อมูลในหลายมิติเป็นอย่างไร
  * การใช้ data warehouse ทั้งหมด 3 ประเภท

* บทที่ 5 [Data Cube Technology](https://github.com/gameaphiwat/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%885.pdf)
  * ความหมาย
  * Besic Concepts
  * Efficient Pattern Mining Methods

* บทที่ 6 [Mining Frequent Patterns, Association and Correlations:Basic Concepts and Methods](https://github.com/gameaphiwat/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%886.pdf)
  * Basic Concepts
  * Patterns หมายถึงอะไร ทำไมมันถึงสำคัญ
  * ตัวอย่าง K-Itemsets
  * การหาค่าต่าง ๆ ของ K-Itemsets
  * The Apriori Algorihm
  * ตัวอย่าง The Apriori Algorihm

* บทที่ 7 [Advanced Frequent Pattern Minning](https://github.com/gameaphiwat/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%207.pdf)

* บทที่ 8 [Classification:Basic Concepts](https://github.com/gameaphiwat/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%208.pdf)
  * ลักษณะการสร้างโมเดลแบบมีผู้สอน
  * ลักษณะการสร้างโมเดลแบบไม่มีผู้สอน
  * การทำนายปัญหา ระหว่าง Classification กับ การใช้ ทำนายตัวเลข
  * การสร้างโมเดลแบบจำลอง
  * Decision Tree ต้นไม้ตัดสินใจ
  * หลักการสร้างตาราง
  * ตัวอย่างในการหาค่าต่าง ๆ
  * Gini Index
  * การหาค่า Gini
  * Naive Bayes Classfier
  * Linear Regreesion


# ภาคปฏิบัติ (Google Colab)

* บทที่ 2 [Data101(Chapter2)](https://github.com/gameaphiwat/DWDM21/blob/main/Data101_(Chapter2).ipynb)
  * ไฟล์ .csv (cav คือ comma separated values) เป็นไฟล์หลักที่เราได้ใช้เรียนกันในวิชานี้
  * Basic Python
  * Casting int () float () str ()
  * Data Structure
  * วิธีสร้าง list ว่าง
  * เติมค่าลงไปใน list ใช้ (.append)
  * การชี้ค่าใน list (indexing)
  * list slicing การตัดลิสต์
  * จุดเริ่มต้น:จุดสุดท้าย :step
  * list + list
  * format string
  * Loop
  * Nested loop ลูบซ้อนลูบ
  * Condition (if statement)
  * Quiz 1 หา max
  * การบ้านที่ 3 หาเกรด
  * Function
  * ลักณะตัวอย่าง (ไม่มี input)
  * ลักษณะตัวอย่างที่ (ไม่มี output)
  * ลักษณะตัวอย่าง (ไม่มี input และ output)
  * ลักษณะของ input (พารามิเตอร์)

* บทที่ 2 [Data102_(Chapter2)](https://github.com/gameaphiwat/DWDM21/blob/main/Data102_(Chapter2).ipynb)
  * Nan = not a Number (ช่องว่าง)
  * คำสั่ง .head() .tail()
  * Box plot
  * Time Series Plot

* บทที่ 3 [Data_Preprocessing_(Chapter_3)](https://github.com/gameaphiwat/DWDM21/blob/main/Data_Preprocessing_(Chapter3).ipynb)
  * Meta Data (Data ที่ใช้อธิบาย Data)
  * ชี้ข้อมูลในตาราง
  * ชี้แบบ .iloc[] (มองข้อมูลแบบ matrix)
  * Missing Values
  * Handling Misiing Value 1 (ลบค่า missing ออกไป)
  * Quiz 3 ให้หาว่าการทำ dropna() ทำให้ข้อมูลหายไปกี่ %
  * Handling Misiing Value 1.5 (ลบค่า missing เฉพาะในคอลัมม์ที่เราสนใจออกไป)
  * Quiz 3.1 ให้หาว่าการทำ dropna() แบบเลือก drop เฉพาะคอลลัมม์ที่เราสนใจ (age) ทำให้ข้อมูลหายไปกี่ %
  * Handling Misiing Value 2 (แทนค่าด้วย class ใหม่ (unknown))
  * Handling Misiing Value 3 (แทนค่าด้วย class ใหม่ (ค่าที่เหมาะสม)
  * Handling Misiing Value 4 (แทนค่าด้วย ค่ากลาง)
  * Handling Misiing Value 5 (แทนค่าด้วย ค่ากลางของ sample ใน class เดียวกัน)
  * Select data by values [PD] คำสั่งแพนด้า
  * ขั้นตอนสร้าง list ของ boolen
  * สร้าง list ของ boolen
  * Quiz 4 + การบ้าน
  * ต่อตารางแนวแกน Y [PD]
  * การเรียงข้อมูล [PD]
  * Outlier
  * Quiz 5
  * Quiz กลุ่ม
  * การรวมตาราง (ต่อตารางในแนวแกน x) Data Integration
  * รวม 2 ตาราง (.merge())
  * เอาเฉพาะคอลลัมม์ที่เราต้องการมาแปะ (.map())
  * Project กลุ่ม
  * Group by (pandas)
  * การบ้าน + Quiz
  * save ตารางเอาไปใช้ที่อื่น
  * การสร้างตาราง

* บทที่ 6 [Chapter_6_Association_Rules](https://github.com/gameaphiwat/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
  * ลบ records ที่ถูก cancel ออกไป
  * การบ้านครั้งที่ 13 วาดกราฟสรุปจำนวน items และ ยอดขายของแต่ละประเทศ
  * เตรียม Data สำหรับ (Fequence Pattern) Association Rules
  * Apriori
  * (Quiz 7)

* บทที่ 7 [Chapter7_Classification_(Decision_Tree)](https://github.com/gameaphiwat/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
  * Load Data
  * train (ฝึกสอนตัวแบบ)
  * plot tree
  * Evaluation
  * Random
  * Advanced Tree
  * TEST
  * Start here
  * Train - Test
  * Train - Validation
  * การบ้านครั้งที่ 16

* บทที่ 7 [Chap7_Classification_(KNN_NN))](https://github.com/gameaphiwat/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
  * Load data
  * Split Data
  * Train Model
  * knn1
  * knn2
  * knn3
  * Retrain & Evaluate
  * Neural Network
  * Train - Test
  * ANN 2
  * ANN 3

* บทที่ 7 [Chapter_7_Classification_(Evaluation))](https://github.com/gameaphiwat/DWDM21/blob/main/Chapter_7_Classification_(Evaluation).ipynb)
  * Load data
  * แบ่ง data
  * สร้าง model ทำนาย
  * Train - Test
  * Evalution

* บทที่ 8 [Chap_8_Clustering)](https://github.com/gameaphiwat/DWDM21/blob/main/Chap8Clustering.ipynb)
  * K-means
  * Clustering
  * Example application (Color Quantization)

* [Data_Visualization)](https://github.com/gameaphiwat/DWDM21/blob/main/Data_Visualization.ipynb)
  * Visuliazation
  * Scatter plot
  * Plot
  * ควิซกลุ่ม
  * Bar chart
  * Stacked Barchart
  * Histrogram

* [Distance_Numpy)](https://github.com/gameaphiwat/DWDM21/blob/main/Distance_Numpy.ipynb)
  * Numpy Array
  * สร้าง numpy array
  * สร้าง matrix เริ่มต้น (zeros,ones)
  * สร้าง matrix random ค่าเเบบมั่ว ๆ
  * matrix transpose
  * Indexing & Slicing
  * Useful Function
  * วนลูปเอง
  * Summation
  * Quiz กลุ่ม
  * Distance Matrix
  * Euclidean Distance (L2-norm)
  * คำนวณระยะห่าง dist(P1,P2)
  * คำนวณระยะห่าง dist(P2,P4)
  * Distance function
  * Quiz 6
  * การบ้านครั้งที่ 11
  * Distance of Binary Value

* **สอบมิดเทอม** [Mini_Exam](https://github.com/gameaphiwat/DWDM21/blob/main/Mini_Exam.ipynb)

* **FinalProject** [FinalProject](https://github.com/gameaphiwat/DWDM21/blob/main/FinalProject.ipynb)

