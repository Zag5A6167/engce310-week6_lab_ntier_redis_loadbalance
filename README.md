# engce310-week6_lab_ntier_redis_loadbalance
ผมใช้ popOS 

เเลปนี้ ทำเว็บให้ เร็วขึ้นด้วย Redis และ อึดขึ้น ด้วย Nginx Load Balance

ผลทดลอง 


รัน docker ผลท่ได้
<img width="1909" height="1078" alt="image" src="https://github.com/user-attachments/assets/c8bff48d-15f2-46e2-beff-36b720c92617" />



<img width="1905" height="548" alt="image" src="https://github.com/user-attachments/assets/ecfb3833-b839-4ef1-a6bf-09bc8fa236f0" />

เปิด localhost ผลที่ได้
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/9d5a9d3d-31a7-4f53-9ec8-6710c9daa1a4" />

ทดสอบ Load Balancing
<img width="1914" height="485" alt="image" src="https://github.com/user-attachments/assets/7d06dae1-d630-494a-9da4-0dd1ca8adbba" />

 ทดสอบ Redis Caching
<img width="1919" height="1036" alt="image" src="https://github.com/user-attachments/assets/3fab2232-6f0f-44c3-8555-8a16c774a7d3" /><img width="1502" height="811" alt="image" src="https://github.com/user-attachments/assets/83f25729-8d80-495b-969e-faa3068038c6" />


ทดสอบ Cache Invalidation
<img width="1915" height="843" alt="image" src="https://github.com/user-attachments/assets/c83491ae-3ca9-4a28-bbfa-77378fca84e0" />
<img width="1917" height="843" alt="image" src="https://github.com/user-attachments/assets/7434c5e0-ba0d-417a-a175-b3a387180496" />

Load Testing (Simple)
<img width="1919" height="483" alt="image" src="https://github.com/user-attachments/assets/b9b0cc76-5725-4d90-a1b4-836eca9c5e5d" />

 ดู Redis Keys
<img width="1916" height="1012" alt="image" src="https://github.com/user-attachments/assets/78fc1ff3-c727-4f3c-9081-710743584ce7" />


ยิง health check
<img width="1919" height="1012" alt="image" src="https://github.com/user-attachments/assets/95ba8f3d-b96b-424a-8ccc-41559854906f" />

ปิด API app 1 ตัว ทดสอบซ้ำ (ให้ลองหลายครั้ง/หลายรอบ)

<img width="1919" height="1008" alt="image" src="https://github.com/user-attachments/assets/68d417a7-a14a-4ffe-b98e-46c806692200" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4d6b59e7-a959-47c2-b771-e2281d825742" />



