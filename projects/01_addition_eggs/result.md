แบบฝึกหัดที่ 1: เปลี่ยนจำนวนไข่
```c
// หาบรรทัดนี้ในโค้ด:
int eggs_already_have = 4;    // ไข่ไก่ที่แม่มีอยู่แล้ว
int eggs_new_today = 2;       // ไข่ไก่ที่ไก่ออกวันนี้

// ลองเปลี่ยนเป็น:
int eggs_already_have = 8;    // เพิ่มเป็น 8 ฟอง
int eggs_new_today = 3;       // เพิ่มเป็น 3 ฟอง
```

```c
I (7498) main_task: Started on CPU0
I (7508) main_task: Calling app_main()
I (7508) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (7508) EGGS_MATH: =====================================
I (7508) EGGS_MATH: 📖 โจทย์:
I (7508) EGGS_MATH:    แม่มีไข่ไก่อยู่แล้ว: 4 ฟอง
I (7508) EGGS_MATH:    เมื่อเช้าไก่ออกไข่เพิ่ม: 2 ฟอง
I (7508) EGGS_MATH:    ❓ วันนี้แม่มีไข่ไก่รวมกี่ฟอง?
I (7508) EGGS_MATH: 
I (10508) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (10508) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (10508) EGGS_MATH:    = 4 + 2
I (10508) EGGS_MATH:    = 6 ฟอง
I (10508) EGGS_MATH: 
I (10508) EGGS_MATH: ✅ คำตอบ:
I (10508) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 6 ฟอง
I (10508) EGGS_MATH:
I (10508) EGGS_MATH: 🎨 ภาพประกอบ:
I (10508) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚 (4 ฟอง)
I (10508) EGGS_MATH:    ไข่ใหม่: 🥚🥚 (2 ฟอง)
I (10508) EGGS_MATH:    รวม:    🥚🥚🥚🥚🥚🥚 (6 ฟอง)
I (10508) EGGS_MATH: 
I (10508) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (10508) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (10508) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (10508) EGGS_MATH: 
I (10508) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (10508) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (10508) EGGS_MATH:
I (10508) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (10508) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (10508) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (10508) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (10508) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (10508) EGGS_MATH: 
I (10508) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (10518) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (12518) main_task: Returned from app_main()
```

แบบฝึกหัดที่ 2: เพิ่มไข่เป็ด
```c
int duck_eggs = 3;            // ไข่เป็ดที่แม่มี
int total_all_eggs;           // ไข่ทั้งหมด (ไก่ + เป็ด)
```
แล้วเพิ่มการคำนวณหลังบรรทัด total_eggs = eggs_already_have + eggs_new_today;:
```c
total_all_eggs = total_eggs + duck_eggs;

// แสดงผลไข่เป็ด
ESP_LOGI(TAG, "🦆 และแม่มีไข่เป็ด: %d ฟอง", duck_eggs);
ESP_LOGI(TAG, "🥚 ไข่ทั้งหมด (ไก่+เป็ด): %d ฟอง", total_all_eggs);
```
```c
I (7528) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (7528) EGGS_MATH: =====================================
I (7528) EGGS_MATH: 📖 โจทย์:
I (7528) EGGS_MATH:    แม่มีไข่ไก่อยู่แล้ว: 4 ฟอง
I (7528) EGGS_MATH:    เมื่อเช้าไก่ออกไข่เพิ่ม: 2 ฟอง
I (7528) EGGS_MATH:    ❓ วันนี้แม่มีไข่ไก่รวมกี่ฟอง?
I (7528) EGGS_MATH:
I (10528) EGGS_MATH: 🦆 และแม่มีไข่เป็ด: 3 ฟอง
I (10528) EGGS_MATH: 🥚 ไข่ทั้งหมด (ไก่+เป็ด): 9 ฟอง
I (10528) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (10528) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (10528) EGGS_MATH:    = 4 + 2
I (10528) EGGS_MATH:    = 6 ฟอง
I (10528) EGGS_MATH: 
I (10528) EGGS_MATH: ✅ คำตอบ:
I (10528) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 6 ฟอง
I (10528) EGGS_MATH: 
I (10528) EGGS_MATH: 🎨 ภาพประกอบ:
I (10528) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚 (4 ฟอง)
I (10528) EGGS_MATH:    ไข่ใหม่: 🥚🥚 (2 ฟอง)
I (10528) EGGS_MATH:    รวม:    🥚🥚🥚🥚🥚🥚 (6 ฟอง)
I (10528) EGGS_MATH: 
I (10528) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (10528) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (10528) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (10528) EGGS_MATH:
I (10528) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (10528) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (10528) EGGS_MATH:
I (10528) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (10528) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (10528) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (10528) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (10528) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (10528) EGGS_MATH: 
I (10528) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (10528) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (12528) main_task: Returned from app_main()
```

แบบฝึกหัดที่ 3: สร้างโจทย์ของตัวเอง
📚 หนังสือบนชั้น

```c
I (8416) EGGS_MATH: 📚 เริ่มต้นโปรแกรมนับหนังสือบนชั้นวาง 📚
I (8416) EGGS_MATH: =====================================
I (8416) EGGS_MATH: 📖 โจทย์:
I (8416) EGGS_MATH:    หนังสือที่มีอยู่แล้ว: 4 เล่ม
I (8416) EGGS_MATH:    หนังสือที่รับเพิ่มเข้ามาวันนี้: 2 เล่ม
I (8416) EGGS_MATH:    ❓ วันนี้มีหนังสือทั้งหมดกี่เล่ม?
I (8416) EGGS_MATH: 
I (11416) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (11416) EGGS_MATH:    หนังสือที่มีอยู่แล้ว + หนังสือที่เพิ่มเข้ามาวันนี้
I (11416) EGGS_MATH:    = 4 + 2
I (11416) EGGS_MATH:    = 6 เล่ม
I (11416) EGGS_MATH: 
I (11416) EGGS_MATH: ✅ คำตอบ:
I (11416) EGGS_MATH:    วันนี้มีหนังสือทั้งหมด 6 เล่ม
I (11416) EGGS_MATH: 
I (11416) EGGS_MATH: 🎨 ภาพประกอบ:
I (11416) EGGS_MATH:    หนังสือที่มี: 📚📚📚📚 (4 เล่ม)
I (11416) EGGS_MATH:    หนังสือใหม่: 📚📚 (2 เล่ม)
I (11416) EGGS_MATH:    รวม:    📚📚📚📚📚📚 (6 เล่ม)
I (11416) EGGS_MATH:
I (11416) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (11416) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (11416) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (11416) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (11416) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (11426) EGGS_MATH:
I (11426) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (11426) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (13426) main_task: Returned from app_main()
```
