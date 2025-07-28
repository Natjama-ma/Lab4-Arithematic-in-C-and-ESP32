แบบฝึกหัดที่ 1: เปลี่ยนจำนวนคุกกี้
```c
// หาบรรทัดนี้ในโค้ด:
int total_cookies = 20;    // คุกกี้ทั้งหมด
int friends = 4;           // จำนวนเพื่อน

// ลองเปลี่ยนเป็น:
int total_cookies = 24;    // เพิ่มเป็น 24 ชิ้น
int friends = 6;           // เพิ่มเป็น 6 คน
```
```c
I (11184) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (11184) COOKIES_MATH: ================================
I (11184) COOKIES_MATH: 📖 โจทย์:
I (11184) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (11184) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (11184) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (11184) COOKIES_MATH:
I (11184) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (11184) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (11184) COOKIES_MATH:    = 24 ÷ 6
I (11184) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (11184) COOKIES_MATH: 
I (11184) COOKIES_MATH: ✅ คำตอบ:
I (11184) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (11184) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (11184) COOKIES_MATH: 
I (11184) COOKIES_MATH: 🎨 ภาพประกอบการแบ่ง:
I (11184) COOKIES_MATH:    คุกกี้ทั้งหมด: 🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪 (24 ชิ้น)
I (11184) COOKIES_MATH:
I (11184) COOKIES_MATH:    เพื่อนคนที่ 1: 
I (11184) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (11184) COOKIES_MATH:    เพื่อนคนที่ 2: 
I (11184) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (11184) COOKIES_MATH:    เพื่อนคนที่ 3: 
I (11184) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (11184) COOKIES_MATH:    เพื่อนคนที่ 4: 
I (11184) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (11194) COOKIES_MATH:    เพื่อนคนที่ 5: 
I (11194) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (11194) COOKIES_MATH:    เพื่อนคนที่ 6: 
I (11194) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (11194) COOKIES_MATH:
I (11194) COOKIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (11194) COOKIES_MATH:    คุกกี้ 15 ชิ้น แบ่งให้ 3 คน
I (11194) COOKIES_MATH:    = 15 ÷ 3 = 5 ชิ้นต่อคน, เหลือ 0 ชิ้น
I (11194) COOKIES_MATH: 
I (11194) COOKIES_MATH:    คุกกี้ 13 ชิ้น แบ่งให้ 4 คน
I (11194) COOKIES_MATH:    = 13 ÷ 4 = 3 ชิ้นต่อคน, เหลือ 1 ชิ้น
I (11194) COOKIES_MATH:    (หารไม่ลงตัว)
I (11194) COOKIES_MATH: 
I (11194) COOKIES_MATH: ⚠️  กรณีพิเศษ - หารด้วยศูนย์:
I (11194) COOKIES_MATH:    ถ้าไม่มีเพื่อนมาแบ่ง (หารด้วย 0)
I (11194) COOKIES_MATH:    ไม่สามารถคำนวณได้ในทางคณิตศาสตร์
I (11194) COOKIES_MATH:    ในชีวิตจริง: คุกกี้จะเหลือทั้งหมด
I (11194) COOKIES_MATH: 
I (11194) COOKIES_MATH: 🔄 ความสัมพันธ์กับการคูณ:
I (11194) COOKIES_MATH:    การหาร: 24 ÷ 6 = 4
I (11194) COOKIES_MATH:    การคูณ: 4 × 6 = 24
I (11194) COOKIES_MATH:    การหารและการคูณเป็นการดำเนินการตรงข้ามกัน
I (11194) COOKIES_MATH: 
I (11194) COOKIES_MATH: 📊 สรุปการดำเนินการทั้งหมด:
I (11194) COOKIES_MATH:    การบวก (+): เพิ่มจำนวน
I (11194) COOKIES_MATH:    การลบ (-): ลดจำนวน
I (11194) COOKIES_MATH:    การคูณ (×): บวกซ้ำๆ หลายชุด
I (11194) COOKIES_MATH:    การหาร (÷): แบ่งออกเป็นกลุ่มเท่าๆ กัน
I (11194) COOKIES_MATH:
I (11194) COOKIES_MATH: 🎓 แนวคิดขั้นสูง:
I (11194) COOKIES_MATH:    1. การหารจะได้ผลหาร (quotient) และเศษ (remainder)
I (11194) COOKIES_MATH:    2. ในภาษา C:
I (11194) COOKIES_MATH:       ผลหาร = a / b
I (11194) COOKIES_MATH:       เศษ = a % b
I (11194) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์เป็นสิ่งสำคัญ
I (11194) COOKIES_MATH:    4. การหารด้วย 1 จะได้ตัวเลขเดิม
I (11204) COOKIES_MATH:    5. การหารตัวเลขด้วยตัวมันเองจะได้ 1
I (11204) COOKIES_MATH: 
I (11204) COOKIES_MATH: 📚 สิ่งที่เรียนรู้:
I (11204) COOKIES_MATH:    1. การหารเลข (Division): a ÷ b = c
I (11204) COOKIES_MATH:    2. การใช้ Modulo operator (%) หาเศษ
I (11204) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์
I (11204) COOKIES_MATH:    4. ความแตกต่างระหว่างหารลงตัวและไม่ลงตัว
I (11204) COOKIES_MATH:    5. ความสัมพันธ์ระหว่างการหารและการคูณ
I (11204) COOKIES_MATH:    6. การจัดการกรณีพิเศษ (Error Handling)
I (11204) COOKIES_MATH: 
I (11204) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (11204) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (13204) main_task: Returned from app_main()
```
แบบฝึกหัดที่ 2: เพิ่มการตรวจสอบหารลงตัว
เพิ่มการตรวจสอบว่าหารลงตัวไหม:
```c
int cookies_per_person = total_cookies / friends;
int remaining_cookies = total_cookies % friends;

if (remaining_cookies == 0) {
    ESP_LOGI(TAG, "✅ หารลงตัว! ทุกคนได้เท่ากัน");
} else {
    ESP_LOGI(TAG, "⚠️ หารไม่ลงตัว! เหลือ %d ชิ้น", remaining_cookies);
}
```
```c
I (24725) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (24725) COOKIES_MATH: ================================
I (24725) COOKIES_MATH: 📖 โจทย์:
I (24725) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (24725) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (24725) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (24725) COOKIES_MATH:
I (24725) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (24725) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (24725) COOKIES_MATH:    = 24 ÷ 6
I (24725) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (24725) COOKIES_MATH: 
I (24725) COOKIES_MATH: ✅ หารลงตัว! ทุกคนได้เท่ากัน
I (24725) COOKIES_MATH: 
I (24725) COOKIES_MATH: ✅ คำตอบ:
I (24725) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (24725) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (24725) COOKIES_MATH: 
I (24725) COOKIES_MATH:    คุกกี้ 15 ชิ้น แบ่งให้ 3 คน
I (24735) COOKIES_MATH:    = 15 ÷ 3 = 5 ชิ้นต่อคน, เหลือ 0 ชิ้น
I (24735) COOKIES_MATH: 
I (24735) COOKIES_MATH:    คุกกี้ 13 ชิ้น แบ่งให้ 4 คน
I (24735) COOKIES_MATH:    = 13 ÷ 4 = 3 ชิ้นต่อคน, เหลือ 1 ชิ้น
I (24735) COOKIES_MATH:    (หารไม่ลงตัว)
I (24735) COOKIES_MATH:
I (24735) COOKIES_MATH: ⚠️  กรณีพิเศษ - หารด้วยศูนย์:
I (24735) COOKIES_MATH:    ถ้าไม่มีเพื่อนมาแบ่ง (หารด้วย 0)
I (24735) COOKIES_MATH:    ไม่สามารถคำนวณได้ในทางคณิตศาสตร์
I (24735) COOKIES_MATH:    ในชีวิตจริง: คุกกี้จะเหลือทั้งหมด
I (24735) COOKIES_MATH: 
I (24735) COOKIES_MATH: 🔄 ความสัมพันธ์กับการคูณ:
I (24735) COOKIES_MATH:    การหาร: 24 ÷ 6 = 4
I (24735) COOKIES_MATH:    การคูณ: 4 × 6 = 24
I (24735) COOKIES_MATH:    การหารและการคูณเป็นการดำเนินการตรงข้ามกัน
I (24735) COOKIES_MATH: 
I (24735) COOKIES_MATH: 📊 สรุปการดำเนินการทั้งหมด:
I (24735) COOKIES_MATH:    การบวก (+): เพิ่มจำนวน
I (24735) COOKIES_MATH:    การลบ (-): ลดจำนวน
I (24735) COOKIES_MATH:    การคูณ (×): บวกซ้ำๆ หลายชุด
I (24735) COOKIES_MATH:    การหาร (÷): แบ่งออกเป็นกลุ่มเท่าๆ กัน
I (24735) COOKIES_MATH: 
I (24735) COOKIES_MATH: 🎓 แนวคิดขั้นสูง:
I (24735) COOKIES_MATH:    1. การหารจะได้ผลหาร (quotient) และเศษ (remainder)
I (24735) COOKIES_MATH:    2. ในภาษา C:
I (24735) COOKIES_MATH:       ผลหาร = a / b
I (24735) COOKIES_MATH:       เศษ = a % b
I (24735) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์เป็นสิ่งสำคัญ
I (24735) COOKIES_MATH:    4. การหารด้วย 1 จะได้ตัวเลขเดิม
I (24735) COOKIES_MATH:    5. การหารตัวเลขด้วยตัวมันเองจะได้ 1
I (24735) COOKIES_MATH: 
I (24735) COOKIES_MATH: 📚 สิ่งที่เรียนรู้:
I (24735) COOKIES_MATH:    1. การหารเลข (Division): a ÷ b = c
I (24735) COOKIES_MATH:    2. การใช้ Modulo operator (%) หาเศษ
I (24745) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์
I (24745) COOKIES_MATH:    4. ความแตกต่างระหว่างหารลงตัวและไม่ลงตัว
I (24745) COOKIES_MATH:    5. ความสัมพันธ์ระหว่างการหารและการคูณ
I (24745) COOKIES_MATH:    6. การจัดการกรณีพิเศษ (Error Handling)
I (24745) COOKIES_MATH: 
I (24745) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (24745) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (26745) main_task: Returned from app_main()
```
แบบฝึกหัดที่ 3: หาจำนวนเพื่อนที่เหมาะสม
ลองหาว่าคุกกี้ 30 ชิ้น จะแจกให้กี่คนได้หารลงตัว:
```c
I (9882) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (9882) CANDIES_MATH: ====================================
I (9882) CANDIES_MATH: 📖 โจทย์:
I (9882) CANDIES_MATH:    มีถุงลูกอมทั้งหมด: 9 ถุง
I (9882) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (9882) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (9882) CANDIES_MATH:
I (9882) CANDIES_MATH: 🧮 รายละเอียดถุงลูกอมแยกรสชาติ:
I (9882) CANDIES_MATH:    🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (9882) CANDIES_MATH:    🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (9882) CANDIES_MATH:    🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (9882) CANDIES_MATH: 
I (9882) CANDIES_MATH: ✅ คำตอบ:
I (9882) CANDIES_MATH:    มีลูกอมทั้งหมด 72 เม็ด
I (9882) CANDIES_MATH: 
I (9882) CANDIES_MATH: 👥 แจกให้เพื่อน 12 คน:
I (9882) CANDIES_MATH:    คนละ 6 เม็ด
I (9882) CANDIES_MATH:    ✅ หารลงตัว! ทุกคนได้เท่ากัน ไม่มีลูกอมเหลือ
I (9882) CANDIES_MATH:
I (9882) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (9882) main_task: Returned from app_main()
```

