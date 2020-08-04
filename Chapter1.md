# บทที่ 1 introduction
## ทำไมต้อง Data Mining ถึงมีความสำคัญ
### ในปัจจุบันข้อมูลมีขนาดใหญ่ขึ้นเรื่อยๆ จาก terabytes ที่เริ่มจะไม่พอ จึงต้องไปสู่ petabytes 
## *สิ่งที่ทำให้ Data มากขึ้น*
### 1. Automated data collection(อุปกรณ์ที่ใช้เก็บข้อมูลอัตโนมัติ) เช่น เซ็นเซอร์ 
### 2. Databas systems 
### 3. Web
### 4. computerized society 
### จากพฤติกรรมการเข้าใช้งานในเว็บต่างๆ การเล่นเฟซบุ๊ค อัพรูปภาพ ก็จะถูกเก็บไว้ ทำให้ทำให้ข้อมูลมีมากขึ้น จนต้องหาวิธีนำมาใช้ หนึ่งในนั้น คือ Data Minning 
## *Data Mining คืออะไร*
### Data Mining คือ การทำเหมืองข้อมูล สิ่งที่เราต้องการจากการทำเหมืองข้อมูล คือ องค์ความรู้ โดยที่เรามีข้อมูลแต่ยังไม่รู้ว่ามีอะไรซ้อนอยู่จึงต้องทำการสกัดข้อมูล สามารถเรียกชื่ออื่นๆได้ เช่น
#### Knowledge discovery คือ การค้นพบความรู้ใหม่
#### Knowledge extraction คือ การสกัดความรู้ 
## *Knowledge Discovery(KDD) Process*
### 1. Databases = การเก็บข้อมูลไม่ให้หายไป เก็บให้เร็วและไม่ซ้ำซ้อน
### 2. Data Cleaning = การทำความสะอาดข้อมูล โดยการหาข้อมูลที่มันผิดพลาด เช่น การใส่ข้อมูลผิดช่อง 
### 3. Data Integration = การรวมข้อมูลจากหลายๆแหล่งเข้าด้วยกัน
### 4. Data Warehouse = คลังข้อมูล การเก็บข้อมูลเพื่อจุดมุ่งหมายหนึ่ง สามารถเลือกดูข้อมูลในมุมต่างๆได้ หลังจากนั้นจึงไป Data Minning 
## *Data Mining in Business สำหรับใช้ในองค์กร*
### > Data Sources ทุกข้อมูลจะเก็บลงใน Database
### > Data Preprocessing การจัดการข้อมูล = cleaning / Integration รวมข้อมูลจากหลายแหล่งเข้าด้วยกัน โดยข้อมูลที่จะรวมมาจากหลายๆ Database ,รวมเสร็จแล้วค่อยนำไปเก็บใน > Data Warehouses 
### > Data Exploration = การดึงข้อมูลมาดูในมุมต่างๆ = Data Warehouses 
### > Data Mining = การสกัดความรู้ออกจากข้อมูล
### > Data Presentation นำข้อมูลที่ได้แล้วไปนำเสนอหรือคิดต่อว่าจะนำไปใช้ประโยชน์อะไรต่อ
### > Decision Making การตัดสินใจว่าจะเอาข้อมูลไปใช้ทำอะไร
## *On What Kinds of Data ข้อมูลที่สามารถเอาไปทำ Data Mining ได้*
### ● Data streams and sensor data ข้อมูลมันไหลเรื่อยๆ มาจาก sensor เช่น เครื่องวัดอุณหภูมิ
### ● Time series เช่น ข้อมูลของตลาดหุ้น
### ● Structure data, graphs, social networks and information networks กราฟ ข้อมูลต่างๆที่เราใช้ในพื้นที่ของ social
### ● Spatial data and spatiotemporal data ข้อมูลชั่วขณะเชิงพื้นที่ 
### ● Multimedia database เช่น Youtube ที่มีวิดีโอและคอมเมนท์ มีไลฟ์ มีจำนวนคนดู
### ● Text databases
### ● The World-Wide Web
## *สิ่งที่สกัดได้จากข้อมูล*
### 1. Generalization
### 2. Pattern Discovery มองรูปแบบในข้อมูลให้ออก เช่น มองว่าลูกค้าต้องการอะไรเหมือนกันมากๆ
### 3. Classification ดูข้อมูลแล้วแบ่งกลุ่มให้กับข้อมูล ; การจัดหมวดหมู่ ทำนายจากข้อมูลที่มี
### 4. Cluster Analysis แบ่งกลุ่มจากข้อมูลที่เราไม่รู้ชื่อกลุ่ม
### 5. Outlier Analysis ข้อมูลที่หลุดจากกลุ่ม เช่น การกรอกข้อมูลผิด
### 6. Time and Ordering: Sequential Pattern, Trend and Evolution Analysis ทำนายข้อมูลโดยดูจากเชิงเวลาเป็นต้น
### 7. Structure and Network Analysis
## *Evaluation of Knowledge ประเมินข้อมูลว่าถูกผิดมากน้อยแค่ไหน*
