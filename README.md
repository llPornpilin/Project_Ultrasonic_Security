# Ultrasonic Security

ชื่อโครงงาน: Ultrasonic Security<br>
ชนิดโครงงาน: Micro-controller<br>

<b>ที่มาและความสำคัญ</b><br /> <br>
  เนื่องจากปัจจุบันปัญหาเกี่ยวกับการลักขโมยของยังคงมีอัตราการเกิดค่อนข้างสูงโดยเฉพาะยามวิกาลที่มีการรักษาความปลอดภัยต่ำ ทางกลุ่มเล็งเห็นถึงปัญหานี้จึงได้จัดทำโครงงาน Ultrasonic Security ขึ้น เพื่อที่จะเพิ่มประสิทธิภาพของระบบรักษาความปลอดภัยภายในบ้าน
  
<b>จุดประสงค์</b><br>
  1. เพื่อศึกษาและประดิษฐ์อุปกรณ์ iot ที่สามารถเพิ่มความปลอดภัยในการดูแลบ้านและทรัพย์สินภายในบ้าน
  
<b>ประโยชน์</b><br>
  1. ลำโพงส่งเสียงเตือนเมื่อมีคนมาเข้าใกล้บริเวณที่ติดตั้ง Ultrasonic Security
  2. ลดความกังวลของผู้อยู่อาศัย
  3. ลดค่าใช้จ่ายในการติดตั้งอุปกรณ์ราคาแพงเพื่อรักษาความปลอดภัย

<b>อุปกรณ์</b><br>
1. ESP 32 simulator <br>
<img src = "https://user-images.githubusercontent.com/88420671/166657183-22f6d4ba-c7f2-4973-ae8a-bf035c975bc5.png" width = "200px"><br>
2. LED <br>
<img src = "https://user-images.githubusercontent.com/88420671/166657335-da558e56-70c3-4f53-bf02-67b39a9bf3a5.png" width = "200px"><br>
3. Resistor 220 โอห์ม 2 อัน<br>
<img src = "https://user-images.githubusercontent.com/101054221/167414625-871ac7e3-0a92-44bf-8e95-57145c0e22b7.png" width = "200px"><br>
4. HC-SR04 Ultrasonic Distance Sensor <br>
<img src = "https://user-images.githubusercontent.com/88420671/166657383-98dbf3ad-286e-4024-9c63-781665dd4e9d.png" width = "200px"><br>
5. Buzzer <br>
<img src = "https://user-images.githubusercontent.com/88420671/166657399-70d8aad2-9327-456c-8fae-c5e1e2358426.png" width = "200px"><br>
6. Slide switch <br>
<img src = "https://user-images.githubusercontent.com/88420671/166657478-f4151467-0850-471a-a4c9-4a401f309b1f.png" width = "200px"><br>

  <b>หลักการทำงานของ Ultrasonic Sensor</b><br /> <br>
  เซนเซอร์วัดระยะทางด้วย Ultrasonic ใช้หลักการส่งคลื่นเสียงความถี่ต่ำ Ultrasonic ออกไป เมื่อคลื่นเสียงกระทบกับวัตถุจะมีการสะท้อนกลับมา เซนเซอร์จะจับเวลาที่ส่งคลื่นเสียงออกไปจนถึงเวลาที่คลื่นเสียงสะท้อนกลับมา เมื่อนำมาคำนวณกับเวลาที่เสียงเดินทางในอากาศก็จะได้เป็นระยะทางออกมา
  
  <b>หลักการทำงานของ Ultrasonic Security</b><br /> <br>
  เมื่อติดตั้งอุปกรณ์ ultrasonic security ไว้บริเวณที่ต้องการเช่นหน้าประตูบ้านแล้ว หากในเวลากลางคืนต้องการใช้งานอุปกรณ์ก็ทำการเปิดสวิตช์เพื่อให้เซนเซอร์ทำงาน เมื่อมีคนเข้าใกล้บริเวณที่ติดตั้งอุปกรณ์ไว้ในระยะ 50 เซนติเมตร จะมีการส่งสัญญาณผ่านระบบ internet ไปสั่งการให้ลำโพงและหลอดไฟ led ทำงาน เพื่อแจ้งเตือนให้คนภายในบ้านได้รับรู้ และหากไม่ต้องการใช้งานสามารถทำการปิดสวิตช์ได้
 <br /> <br>
 
<a href = "https://youtu.be/7cu831H9Jzg">Presentation</a><br>
<a href = "https://wokwi.com/projects/330350510226801235">Wokwi Ultrasonic</a><br>
<a href = "https://wokwi.com/projects/330897401225151060">Wokwi Led and Buzzer</a><br>
  
<b>สมาชิกกลุ่ม</b>
  1. นางสาว กุลธิดา         จำปา          64070008<br>
  2. นางสาว ปัณณพร        จึงเปี่ยมสุข      64070183<br>
  3. นางสาว พรไพลิน        วงศ์ศรีตรัง      64070196<br>
  


