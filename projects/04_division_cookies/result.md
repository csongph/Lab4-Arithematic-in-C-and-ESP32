### แบบฝึกหัดที่ 1 เปลี่ยนจำนวนคุกกี้
```c
// หาบรรทัดนี้ในโค้ด:
int total_cookies = 20;    // คุกกี้ทั้งหมด
int friends = 4;           // จำนวนเพื่อน

// ลองเปลี่ยนเป็น:
int total_cookies = 24;    // เพิ่มเป็น 24 ชิ้น
int friends = 6;           // เพิ่มเป็น 6 คน
```

### Result
```c
I (5643) spi_flash: flash io: dio
I (5659) main_task: Started on CPU0
I (5669) main_task: Calling app_main()
I (5669) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (5669) COOKIES_MATH: ================================
I (5669) COOKIES_MATH: 📖 โจทย์:
I (5669) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (5669) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (5669) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (5669) COOKIES_MATH:
I (8669) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (8669) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (8669) COOKIES_MATH:    = 24 ÷ 6
I (8669) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (8669) COOKIES_MATH: 
I (8669) COOKIES_MATH: ✅ คำตอบ:
I (8669) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (8669) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (8669) COOKIES_MATH: 
I (8669) COOKIES_MATH: 🎨 ภาพประกอบการแบ่ง:
I (8669) COOKIES_MATH:    คุกกี้ทั้งหมด: 🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪 (24 ชิ้น)
I (8669) COOKIES_MATH:
I (8669) COOKIES_MATH:    เพื่อนคนที่ 1: 
I (8669) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (8669) COOKIES_MATH:    เพื่อนคนที่ 2: 
I (8669) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (8669) COOKIES_MATH:    เพื่อนคนที่ 3: 
I (8669) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (8669) COOKIES_MATH:    เพื่อนคนที่ 4: 
I (8669) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (8669) COOKIES_MATH:    เพื่อนคนที่ 5: 
I (8669) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (8669) COOKIES_MATH:    เพื่อนคนที่ 6: 
I (8669) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (8669) COOKIES_MATH: 
I (8669) COOKIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (8669) COOKIES_MATH:    คุกกี้ 15 ชิ้น แบ่งให้ 3 คน
I (8669) COOKIES_MATH:    = 15 ÷ 3 = 5 ชิ้นต่อคน, เหลือ 0 ชิ้น
I (8669) COOKIES_MATH: 
I (8669) COOKIES_MATH:    คุกกี้ 13 ชิ้น แบ่งให้ 4 คน
I (8669) COOKIES_MATH:    = 13 ÷ 4 = 3 ชิ้นต่อคน, เหลือ 1 ชิ้น
I (8669) COOKIES_MATH:    (หารไม่ลงตัว)
I (8669) COOKIES_MATH: 
I (8669) COOKIES_MATH: ⚠️  กรณีพิเศษ - หารด้วยศูนย์:
I (8669) COOKIES_MATH:    ถ้าไม่มีเพื่อนมาแบ่ง (หารด้วย 0)
I (8669) COOKIES_MATH:    ไม่สามารถคำนวณได้ในทางคณิตศาสตร์
I (8669) COOKIES_MATH:    ในชีวิตจริง: คุกกี้จะเหลือทั้งหมด
I (8669) COOKIES_MATH:
I (8669) COOKIES_MATH: 🔄 ความสัมพันธ์กับการคูณ:
I (8669) COOKIES_MATH:    การหาร: 24 ÷ 6 = 4
I (8669) COOKIES_MATH:    การคูณ: 4 × 6 = 24
I (8669) COOKIES_MATH:    การหารและการคูณเป็นการดำเนินการตรงข้ามกัน
I (8669) COOKIES_MATH: 
I (8669) COOKIES_MATH: 📊 สรุปการดำเนินการทั้งหมด:
I (8669) COOKIES_MATH:    การบวก (+): เพิ่มจำนวน
I (8669) COOKIES_MATH:    การลบ (-): ลดจำนวน
I (8669) COOKIES_MATH:    การคูณ (×): บวกซ้ำๆ หลายชุด
I (8669) COOKIES_MATH:    การหาร (÷): แบ่งออกเป็นกลุ่มเท่าๆ กัน
I (8669) COOKIES_MATH: 
I (8669) COOKIES_MATH: 🎓 แนวคิดขั้นสูง:
I (8669) COOKIES_MATH:    1. การหารจะได้ผลหาร (quotient) และเศษ (remainder)
I (8669) COOKIES_MATH:    2. ในภาษา C:
I (8669) COOKIES_MATH:       ผลหาร = a / b
I (8669) COOKIES_MATH:       เศษ = a % b
I (8669) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์เป็นสิ่งสำคัญ
I (8669) COOKIES_MATH:    4. การหารด้วย 1 จะได้ตัวเลขเดิม
I (8669) COOKIES_MATH:    5. การหารตัวเลขด้วยตัวมันเองจะได้ 1
I (8669) COOKIES_MATH:
I (8669) COOKIES_MATH: 📚 สิ่งที่เรียนรู้:
I (8669) COOKIES_MATH:    1. การหารเลข (Division): a ÷ b = c
I (8669) COOKIES_MATH:    2. การใช้ Modulo operator (%) หาเศษ
I (8669) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์
I (8669) COOKIES_MATH:    4. ความแตกต่างระหว่างหารลงตัวและไม่ลงตัว
I (8669) COOKIES_MATH:    5. ความสัมพันธ์ระหว่างการหารและการคูณ
I (8669) COOKIES_MATH:    6. การจัดการกรณีพิเศษ (Error Handling)
I (8669) COOKIES_MATH:
I (8669) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (8669) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (10669) main_task: Returned from app_main()
```

### แบบฝึกหัดที่ 2 เพิ่มการตรวจสอบหารลงตัว
```c
int cookies_per_person = total_cookies / friends;
int remaining_cookies = total_cookies % friends;

if (remaining_cookies == 0) {
    ESP_LOGI(TAG, "✅ หารลงตัว! ทุกคนได้เท่ากัน");
} else {
    ESP_LOGI(TAG, "⚠️ หารไม่ลงตัว! เหลือ %d ชิ้น", remaining_cookies);
}
```

### Result
```c
I (5913) spi_flash: flash io: dio
I (5932) main_task: Started on CPU0
I (5942) main_task: Calling app_main()
I (5942) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (5942) COOKIES_MATH: ================================
I (5942) COOKIES_MATH: 📖 โจทย์:
I (5942) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (5942) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (5942) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (5942) COOKIES_MATH: 
I (8942) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (8942) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (8942) COOKIES_MATH:    = 24 ÷ 6
I (8942) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (8942) COOKIES_MATH: 
I (8942) COOKIES_MATH: ✅ หารลงตัว! ทุกคนได้เท่ากัน
I (8942) COOKIES_MATH: ✅ คำตอบ:
I (8942) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (8942) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (8942) COOKIES_MATH: 
I (8942) COOKIES_MATH: 📚 สิ่งที่เรียนรู้:
I (8942) COOKIES_MATH:    1. การหารเลข (Division): a ÷ b = c
I (8942) COOKIES_MATH:    2. การใช้ Modulo operator (%) หาเศษ
I (8942) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์
I (8942) COOKIES_MATH:    4. ความแตกต่างระหว่างหารลงตัวและไม่ลงตัว
I (8942) COOKIES_MATH:    5. การจัดการกรณีพิเศษ (Error Handling)
I (8942) COOKIES_MATH: 
I (8942) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (8942) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (10942) main_task: Returned from app_main()
```

### แบบฝึกหัดที่ 3 หาจำนวนเพื่อนที่เหมาะสม
```c
int cookies = 30;
ESP_LOGI(TAG, "🔍 คุกกี้ %d ชิ้น หารลงตัวกับ:", cookies);

for (int people = 1; people <= 10; people++) {
    if (cookies % people == 0) {
        ESP_LOGI(TAG, "   ✅ %d คน → คนละ %d ชิ้น", 
                 people, cookies / people);
    }
}
```

### Result
```c
I (6101) spi_flash: flash io: dio
I (6121) main_task: Started on CPU0
I (6131) main_task: Calling app_main()
I (6131) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (6131) COOKIES_MATH: ================================
I (6131) COOKIES_MATH: 📖 โจทย์:
I (6131) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (6131) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (6131) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (6131) COOKIES_MATH: 
I (9131) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (9131) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (9131) COOKIES_MATH:    = 24 ÷ 6
I (9131) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (9131) COOKIES_MATH: 
I (9131) COOKIES_MATH: ✅ หารลงตัว! ทุกคนได้เท่ากัน
I (9131) COOKIES_MATH: ✅ คำตอบ:
I (9131) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (9131) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (9131) COOKIES_MATH:
I (9131) COOKIES_MATH: 🔍 คุกกี้ 30 ชิ้น หารลงตัวกับ:
I (9131) COOKIES_MATH:    ✅ 1 คน → คนละ 30 ชิ้น
I (9131) COOKIES_MATH:    ✅ 2 คน → คนละ 15 ชิ้น
I (9131) COOKIES_MATH:    ✅ 3 คน → คนละ 10 ชิ้น
I (9131) COOKIES_MATH:    ✅ 5 คน → คนละ 6 ชิ้น
I (9131) COOKIES_MATH:    ✅ 6 คน → คนละ 5 ชิ้น
I (9131) COOKIES_MATH:    ✅ 10 คน → คนละ 3 ชิ้น
I (9131) COOKIES_MATH:
I (9131) COOKIES_MATH: 📚 สิ่งที่เรียนรู้:
I (9131) COOKIES_MATH:    1. การหารเลข (Division): a ÷ b = c
I (9131) COOKIES_MATH:    2. การใช้ Modulo operator (%) หาเศษ
I (9131) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์
I (9131) COOKIES_MATH:    4. ความแตกต่างระหว่างหารลงตัวและไม่ลงตัว
I (9131) COOKIES_MATH:    5. การจัดการกรณีพิเศษ (Error Handling)
I (9131) COOKIES_MATH:
I (9131) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (9131) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (11131) main_task: Returned from app_main()
```
