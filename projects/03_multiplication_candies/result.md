แบบฝึกหัดที่ 1: เปลี่ยนจำนวนถุงลูกอม
```c
// หาบรรทัดนี้ในโค้ด:
int candy_bags = 5;         // จำนวนถุง
int candies_per_bag = 6;    // ลูกอมต่อถุง

// ลองเปลี่ยนเป็น:
int candy_bags = 7;         // เพิ่มเป็น 7 ถุง
int candies_per_bag = 8;    // ลูกอมถุงละ 8 เม็ด
```
```c
I (11052) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (11052) CANDIES_MATH: ====================================
I (11052) CANDIES_MATH: 📖 โจทย์:
I (11052) CANDIES_MATH:    มีถุงลูกอม: 7 ถุง
I (11052) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (11052) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (11052) CANDIES_MATH: 
I (11052) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (11052) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (11052) CANDIES_MATH:    = 7 × 8
I (11052) CANDIES_MATH:    = 56 เม็ด
I (11052) CANDIES_MATH: 
I (11052) CANDIES_MATH: ✅ คำตอบ:
I (11052) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (11052) CANDIES_MATH: 
I (11052) CANDIES_MATH: 🎨 ภาพประกอบ:
I (11052) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (11052) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (11052) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (11052) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (11052) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (11052) CANDIES_MATH:    รวม:     56 เม็ด
I (11052) CANDIES_MATH: 
I (11052) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (11052) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (11052) CANDIES_MATH:    การบวกซ้ำๆ:
I (11052) CANDIES_MATH:                   8
I (11052) CANDIES_MATH:                 + 8
I (11052) CANDIES_MATH:                 + 8
I (11052) CANDIES_MATH:                 + 8
I (11052) CANDIES_MATH:                 + 8
I (11052) CANDIES_MATH:                 + 8
I (11052) CANDIES_MATH:                 + 8 = 56
I (11052) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (11052) CANDIES_MATH: 
I (11052) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (11052) CANDIES_MATH:    1 × 8 = 8
I (11352) CANDIES_MATH:    2 × 8 = 16
I (11652) CANDIES_MATH:    3 × 8 = 24
I (11952) CANDIES_MATH:    4 × 8 = 32
I (12252) CANDIES_MATH:    5 × 8 = 40
I (12552) CANDIES_MATH:    6 × 8 = 48
I (12852) CANDIES_MATH:    7 × 8 = 56
I (13152) CANDIES_MATH:    8 × 8 = 64
I (13452) CANDIES_MATH:    9 × 8 = 72
I (13752) CANDIES_MATH:    10 × 8 = 80
I (14052) CANDIES_MATH: 
I (14052) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (14052) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (14052) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (14052) CANDIES_MATH: 
I (14052) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (14052) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (14052) CANDIES_MATH:
I (14052) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (14052) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (14052) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (14052) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (14052) CANDIES_MATH: 
I (14052) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (14052) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (14052) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (14052) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (14052) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (14052) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (14052) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (14052) CANDIES_MATH: 
I (14052) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (14062) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (14062) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (14062) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (14062) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (14062) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (14062) CANDIES_MATH:
I (14062) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (14062) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (16062) main_task: Returned from app_main()
```
แบบฝึกหัดที่ 2: เพิ่มลูกอมหลายรส
```c
int strawberry_bags = 3;    // ถุงรสสตรอเบอร์รี่
int orange_bags = 2;        // ถุงรสส้ม
int grape_bags = 4;         // ถุงรสองุ่น

int total_bags = strawberry_bags + orange_bags + grape_bags;
int total_candies = total_bags * candies_per_bag;

ESP_LOGI(TAG, "🍓 สตรอเบอร์รี่: %d ถุง = %d เม็ด", 
         strawberry_bags, strawberry_bags * candies_per_bag);
ESP_LOGI(TAG, "🍊 รสส้ม: %d ถุง = %d เม็ด", 
         orange_bags, orange_bags * candies_per_bag);
ESP_LOGI(TAG, "🍇 รสองุ่น: %d ถุง = %d เม็ด", 
         grape_bags, grape_bags * candies_per_bag);
```
```c
I (12453) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (12453) CANDIES_MATH: ====================================
I (12453) CANDIES_MATH: 📖 โจทย์:
I (12453) CANDIES_MATH:    มีถุงลูกอมทั้งหมด: 9 ถุง
I (12453) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (12453) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (12453) CANDIES_MATH:
I (12453) CANDIES_MATH: 🧮 รายละเอียดถุงลูกอมแยกรสชาติ:
I (12453) CANDIES_MATH:    🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (12453) CANDIES_MATH:    🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (12453) CANDIES_MATH:    🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (12453) CANDIES_MATH:
I (12453) CANDIES_MATH: ✅ คำตอบ:
I (12453) CANDIES_MATH:    มีลูกอมทั้งหมด 72 เม็ด
I (12453) CANDIES_MATH: 
I (12453) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (12453) main_task: Returned from app_main()
```
แบบฝึกหัดที่ 3: สร้างตารางสูตรคูณ
เพิ่มการแสดงตารางสูตรคูณ:
```c
ESP_LOGI(TAG, "📊 ตารางสูตรคูณของ %d:", candies_per_bag);
for (int i = 1; i <= 10; i++) {
    ESP_LOGI(TAG, "   %d x %d = %d", i, candies_per_bag, i * candies_per_bag);
}
```
```c
I (12684) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (12684) CANDIES_MATH: ====================================
I (12684) CANDIES_MATH: 📖 โจทย์:
I (12684) CANDIES_MATH:    มีถุงลูกอมทั้งหมด: 9 ถุง
I (12684) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (12684) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (12684) CANDIES_MATH: 
I (12684) CANDIES_MATH: 🧮 รายละเอียดถุงลูกอมแยกรสชาติ:
I (12684) CANDIES_MATH:    🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (12684) CANDIES_MATH:    🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (12684) CANDIES_MATH:    🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (12684) CANDIES_MATH:
I (12684) CANDIES_MATH: ✅ คำตอบ:
I (12684) CANDIES_MATH:    มีลูกอมทั้งหมด 72 เม็ด
I (12684) CANDIES_MATH:
I (12684) CANDIES_MATH: 🔄 เปรียบเทียบการคูณกับการบวกซ้ำๆ:
I (12694) CANDIES_MATH:    การคูณ: 9 × 8 = 72
I (12694) CANDIES_MATH:    การบวกซ้ำๆ:
I (12694) CANDIES_MATH:       8
I (12694) CANDIES_MATH:     + 8
I (12694) CANDIES_MATH:     + 8
I (12694) CANDIES_MATH:     + 8
I (12694) CANDIES_MATH:     + 8
I (12694) CANDIES_MATH:     + 8
I (12694) CANDIES_MATH:     + 8
I (12694) CANDIES_MATH:     + 8
I (12694) CANDIES_MATH:     + 8 = 72
I (12694) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (12694) CANDIES_MATH: 
I (12694) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (12694) CANDIES_MATH:    1 × 8 = 8
I (12894) CANDIES_MATH:    2 × 8 = 16
I (13094) CANDIES_MATH:    3 × 8 = 24
I (13294) CANDIES_MATH:    4 × 8 = 32
I (13494) CANDIES_MATH:    5 × 8 = 40
I (13694) CANDIES_MATH:    6 × 8 = 48
I (13894) CANDIES_MATH:    7 × 8 = 56
I (14094) CANDIES_MATH:    8 × 8 = 64
I (14294) CANDIES_MATH:    9 × 8 = 72
I (14494) CANDIES_MATH:    10 × 8 = 80
I (14694) CANDIES_MATH: 
I (14694) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (14694) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (14694) CANDIES_MATH:       9 × 8 = 8 × 9 = 72
I (14694) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (14694) CANDIES_MATH:       9 × 0 = 0 (ไม่มีถุงลูกอม)
I (14694) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (14694) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (14694) CANDIES_MATH: 
I (14694) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (14694) CANDIES_MATH:    - การคูณเลข (Multiplication): a × b = c
I (14694) CANDIES_MATH:    - การใช้ for loop สำหรับการทำซ้ำ
I (14694) CANDIES_MATH:    - ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (14694) CANDIES_MATH:    - คุณสมบัติพิเศษของการคูณ
I (14694) CANDIES_MATH:    - การแสดงผลแบบตาราง
I (14694) CANDIES_MATH: 
I (14694) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (14694) main_task: Returned from app_main()
```
แบบฝึกหัดที่ 4: แจกลูกอมให้เพื่อน
คำนวณการแจกลูกอม:
```c
int friends = 12;           // จำนวนเพื่อน
int candies_per_friend = total_candies / friends;  // ลูกอมต่อคน
int remaining_candies = total_candies % friends;   // ลูกอมที่เหลือ

ESP_LOGI(TAG, "👥 แจกให้เพื่อน %d คน:", friends);
ESP_LOGI(TAG, "   คนละ %d เม็ด", candies_per_friend);
ESP_LOGI(TAG, "   เหลือ %d เม็ด", remaining_candies);
```
```c
I (11863) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (11863) CANDIES_MATH: ====================================
I (11863) CANDIES_MATH: 📖 โจทย์:
I (11863) CANDIES_MATH:    มีถุงลูกอมทั้งหมด: 9 ถุง
I (11863) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (11863) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (11863) CANDIES_MATH: 
I (11863) CANDIES_MATH: 🧮 รายละเอียดถุงลูกอมแยกรสชาติ:
I (11863) CANDIES_MATH:    🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (11863) CANDIES_MATH:    🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (11863) CANDIES_MATH:    🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (11863) CANDIES_MATH: 
I (11863) CANDIES_MATH: ✅ คำตอบ:
I (11863) CANDIES_MATH:    มีลูกอมทั้งหมด 72 เม็ด
I (11863) CANDIES_MATH: 
I (11863) CANDIES_MATH: 👥 แจกให้เพื่อน 12 คน:
I (11863) CANDIES_MATH:    คนละ 6 เม็ด
I (11863) CANDIES_MATH:    เหลือ 0 เม็ด
I (11863) CANDIES_MATH: 
I (11863) CANDIES_MATH: 🔄 เปรียบเทียบการคูณกับการบวกซ้ำๆ:
I (11863) CANDIES_MATH:    การคูณ: 9 × 8 = 72
I (11863) CANDIES_MATH:    การบวกซ้ำๆ:
I (11863) CANDIES_MATH:       8
I (11863) CANDIES_MATH:     + 8
I (11863) CANDIES_MATH:     + 8
I (11863) CANDIES_MATH:     + 8
I (11863) CANDIES_MATH:     + 8
I (11863) CANDIES_MATH:     + 8
I (11873) CANDIES_MATH:     + 8
I (11873) CANDIES_MATH:     + 8
I (11873) CANDIES_MATH:     + 8 = 72
I (11873) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (11873) CANDIES_MATH: 
I (11873) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (11873) CANDIES_MATH:    1 × 8 = 8
I (12073) CANDIES_MATH:    2 × 8 = 16
I (12273) CANDIES_MATH:    3 × 8 = 24
I (12473) CANDIES_MATH:    4 × 8 = 32
I (12673) CANDIES_MATH:    5 × 8 = 40
I (12873) CANDIES_MATH:    6 × 8 = 48
I (13073) CANDIES_MATH:    7 × 8 = 56
I (13273) CANDIES_MATH:    8 × 8 = 64
I (13473) CANDIES_MATH:    9 × 8 = 72
I (13673) CANDIES_MATH:    10 × 8 = 80
I (13873) CANDIES_MATH: 
I (13873) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (13873) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (13873) CANDIES_MATH:       9 × 8 = 8 × 9 = 72
I (13873) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (13873) CANDIES_MATH:       9 × 0 = 0 (ไม่มีถุงลูกอม)
I (13873) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (13873) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (13873) CANDIES_MATH:
I (13873) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (13873) CANDIES_MATH:    - การคูณเลข (Multiplication): a × b = c
I (13873) CANDIES_MATH:    - การใช้ for loop สำหรับการทำซ้ำ
I (13873) CANDIES_MATH:    - ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (13873) CANDIES_MATH:    - คุณสมบัติพิเศษของการคูณ
I (13873) CANDIES_MATH:    - การแสดงผลแบบตาราง
I (13873) CANDIES_MATH: 
I (13873) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (13873) main_task: Returned from app_main()
```
