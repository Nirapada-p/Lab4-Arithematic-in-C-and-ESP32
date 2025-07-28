### 📝 แบบฝึกหัดที่ 1: เปลี่ยนจำนวนไข่
```c
// หาบรรทัดนี้ในโค้ด:
int eggs_already_have = 4;    // ไข่ไก่ที่แม่มีอยู่แล้ว
int eggs_new_today = 2;       // ไข่ไก่ที่ไก่ออกวันนี้

// ลองเปลี่ยนเป็น:
int eggs_already_have = 8;    // เพิ่มเป็น 8 ฟอง
int eggs_new_today = 3;       // เพิ่มเป็น 3 ฟอง
```
``` c
I (17531) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (17531) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (17531) EGGS_MATH:    = 4 + 2
I (17531) EGGS_MATH:    = 6 ฟอง
I (17531) EGGS_MATH: 
I (17531) EGGS_MATH: ✅ คำตอบ:
I (17531) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 6 ฟอง
I (17531) EGGS_MATH: 
I (17531) EGGS_MATH: 🎨 ภาพประกอบ:
I (17531) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚 (4 ฟอง)
I (17531) EGGS_MATH:    ไข่ใหม่: 🥚🥚 (2 ฟอง)
I (17531) EGGS_MATH:    รวม:    🥚🥚🥚🥚🥚🥚 (6 ฟอง)
I (17531) EGGS_MATH: 
I (17531) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (17531) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (17531) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (17531) EGGS_MATH: 
I (17531) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (17531) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (17541) EGGS_MATH: 
I (17541) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (17541) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (17541) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (17541) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (17541) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (17541) EGGS_MATH:
I (17541) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (17541) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (19541) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 2: เพิ่มไข่เป็ด
เพิ่มโค้ดนี้หลังบรรทัด `int total_eggs;`:
```c
int duck_eggs = 3;            // ไข่เป็ดที่แม่มี
int total_all_eggs;           // ไข่ทั้งหมด (ไก่ + เป็ด)
```
```c
I (17417) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (17417) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (17417) EGGS_MATH:    = 8 + 3
I (17417) EGGS_MATH:    = 11 ฟอง
I (17417) EGGS_MATH: 
I (17417) EGGS_MATH: ✅ คำตอบ:
I (17417) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 11 ฟอง
I (17417) EGGS_MATH: 
I (17417) EGGS_MATH: 🎨 ภาพประกอบ:
I (17417) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚 (8 ฟอง)
I (17417) EGGS_MATH:    ไข่ใหม่: 🥚🥚 (3 ฟอง)
I (17417) EGGS_MATH:    รวม:    🥚🥚🥚🥚🥚🥚 (11 ฟอง)
I (17417) EGGS_MATH:
I (17417) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (17417) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (17417) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (17417) EGGS_MATH:
I (17417) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (17417) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (17417) EGGS_MATH:
I (17417) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (17427) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (17427) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (17427) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (17427) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (17427) EGGS_MATH:
I (17427) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (17427) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (19427) main_task: Returned from app_main()
```

แล้วเพิ่มการคำนวณหลังบรรทัด total_eggs = eggs_already_have + eggs_new_today;:
```c
I (14922) spi_flash: detected chip: winbond
I (14945) spi_flash: flash io: dio
I (14975) main_task: Started on CPU0
I (14995) main_task: Calling app_main()
I (15005) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (15005) EGGS_MATH: =====================================
I (15005) EGGS_MATH: 📖 โจทย์:
I (15005) EGGS_MATH:    แม่มีไข่ไก่อยู่แล้ว: 8 ฟอง
I (15005) EGGS_MATH:    เมื่อเช้าไก่ออกไข่เพิ่ม: 3 ฟอง
I (15005) EGGS_MATH:    ❓ วันนี้แม่มีไข่ไก่รวมกี่ฟอง?
I (15005) EGGS_MATH: 
I (18005) EGGS_MATH: 🦆 และแม่มีไข่เป็ด: 3 ฟอง
I (18005) EGGS_MATH: 🥚 ไข่ทั้งหมด (ไก่+เป็ด): 14 ฟอง
I (18005) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (18005) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (18005) EGGS_MATH:    = 8 + 3
I (18005) EGGS_MATH:    = 11 ฟอง
I (18005) EGGS_MATH: 
I (18005) EGGS_MATH: ✅ คำตอบ:
I (18005) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 11 ฟอง
I (18005) EGGS_MATH:
I (18005) EGGS_MATH: 🎨 ภาพประกอบ:
I (18005) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚 (8 ฟอง)
I (18005) EGGS_MATH:    ไข่ใหม่: 🥚🥚 (3 ฟอง)
I (18005) EGGS_MATH:    รวม:    🥚🥚🥚🥚🥚🥚 (11 ฟอง)
I (18005) EGGS_MATH:
I (18005) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (18005) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (18005) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (18015) EGGS_MATH: 
I (18015) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (18015) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (18015) EGGS_MATH:
I (18015) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (18015) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (18015) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (18015) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (18015) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (18015) EGGS_MATH:
I (18015) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (18015) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (20015) main_task: Returned from app_main()
```
