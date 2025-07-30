### แบบฝึกหัดที่ 1 เปลี่ยนจำนวนถุงลูกอม
```c
// หาบรรทัดนี้ในโค้ด:
int candy_bags = 5;         // จำนวนถุง
int candies_per_bag = 6;    // ลูกอมต่อถุง

// ลองเปลี่ยนเป็น:
int candy_bags = 7;         // เพิ่มเป็น 7 ถุง
int candies_per_bag = 8;    // ลูกอมถุงละ 8 เม็ด
```

### Result
```c
I (5841) main_task: Started on CPU0
I (5851) main_task: Calling app_main()
I (5851) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (5851) CANDIES_MATH: ====================================
I (5851) CANDIES_MATH: 📖 โจทย์:
I (5851) CANDIES_MATH:    มีถุงลูกอม: 5 ถุง
I (5851) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (5851) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (5851) CANDIES_MATH:
I (8851) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (8851) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (8851) CANDIES_MATH:    = 5 × 8
I (8851) CANDIES_MATH:    = 40 เม็ด
I (8851) CANDIES_MATH: 
I (8851) CANDIES_MATH: ✅ คำตอบ:
I (8851) CANDIES_MATH:    มีลูกอมทั้งหมด 40 เม็ด
I (8851) CANDIES_MATH: 
I (8851) CANDIES_MATH: 🎨 ภาพประกอบ:
I (8851) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (8851) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (8851) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (8851) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (8851) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (8851) CANDIES_MATH:    รวม:     40 เม็ด
I (8851) CANDIES_MATH:
I (8851) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (8851) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (8851) CANDIES_MATH:    การบวกซ้ำๆ: 
I (8851) CANDIES_MATH:                   8
I (8851) CANDIES_MATH:                 + 8
I (8851) CANDIES_MATH:                 + 8
I (8851) CANDIES_MATH:                 + 8
I (8851) CANDIES_MATH:                 + 8 = 40
I (8851) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (8851) CANDIES_MATH: 
I (8851) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (8851) CANDIES_MATH:    1 × 8 = 8
I (9151) CANDIES_MATH:    2 × 8 = 16
I (9451) CANDIES_MATH:    3 × 8 = 24
I (9751) CANDIES_MATH:    4 × 8 = 32
I (10051) CANDIES_MATH:    5 × 8 = 40
I (10351) CANDIES_MATH:    6 × 8 = 48
I (10651) CANDIES_MATH:    7 × 8 = 56
I (10951) CANDIES_MATH:    8 × 8 = 64
I (11251) CANDIES_MATH:    9 × 8 = 72
I (11551) CANDIES_MATH:    10 × 8 = 80
I (11851) CANDIES_MATH: 
I (11851) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (11851) CANDIES_MATH:    ถ้ามีถุงลูกอม 4 ถุง ถุงละ 8 เม็ด
I (11851) CANDIES_MATH:    จะได้ลูกอม 4 × 8 = 32 เม็ด
I (11851) CANDIES_MATH:
I (11851) CANDIES_MATH:    ถ้ามีถุงลูกอม 6 ถุง ถุงละ 4 เม็ด
I (11851) CANDIES_MATH:    จะได้ลูกอม 6 × 4 = 24 เม็ด
I (11851) CANDIES_MATH: 
I (11851) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (11851) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (11851) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (11851) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (11851) CANDIES_MATH:
I (11851) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (11851) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (11851) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (11851) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (11851) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (11851) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (11851) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (11851) CANDIES_MATH: 
I (11851) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (11851) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (11851) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (11851) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (11851) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (11851) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (11851) CANDIES_MATH: 
I (11851) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (11851) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (13851) main_task: Returned from app_main()
```

### แบบฝึกหัดที่ 2 เพิ่มลูกอมหลายรส
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
### Result
```c
I (5834) spi_flash: detected chip: winbond
I (5844) spi_flash: flash io: dio
I (5857) main_task: Started on CPU0
I (5867) main_task: Calling app_main()
I (5867) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (5867) CANDIES_MATH: ====================================
I (5867) CANDIES_MATH: 📖 โจทย์:
I (5867) CANDIES_MATH:    มีลูกอมทั้งหมด 9 ถุง
I (5867) CANDIES_MATH:    ถุงละ 8 เม็ด
I (5867) CANDIES_MATH:    ❓ รวมเป็นลูกอมทั้งหมดกี่เม็ด?
I (5867) CANDIES_MATH: 
I (8867) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (8867) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (8867) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (8867) CANDIES_MATH:
I (8867) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (8867) CANDIES_MATH:    รวมถุงทั้งหมด: 3 + 2 + 4 = 9 ถุง
I (8867) CANDIES_MATH:    ลูกอมทั้งหมด = 9 × 8 = 72 เม็ด
I (8867) CANDIES_MATH:
I (8867) CANDIES_MATH: ✅ คำตอบ:
I (8867) CANDIES_MATH:    มีลูกอมทั้งหมด 72 เม็ด
I (8867) CANDIES_MATH:
I (8867) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (8867) CANDIES_MATH:    1 × 8 = 8
I (9067) CANDIES_MATH:    2 × 8 = 16
I (9267) CANDIES_MATH:    3 × 8 = 24
I (9467) CANDIES_MATH:    4 × 8 = 32
I (9667) CANDIES_MATH:    5 × 8 = 40
I (9867) CANDIES_MATH:    6 × 8 = 48
I (10067) CANDIES_MATH:    7 × 8 = 56
I (10267) CANDIES_MATH:    8 × 8 = 64
I (10467) CANDIES_MATH:    9 × 8 = 72
I (10667) CANDIES_MATH:    10 × 8 = 80
I (10867) CANDIES_MATH: 
I (10867) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (10867) CANDIES_MATH:    1. การคูณเลข (Multiplication)
I (10867) CANDIES_MATH:    2. การรวมรสชาติลูกอม (Addition + Multiplication)
I (10867) CANDIES_MATH:    3. การใช้ตัวแปรและแสดงผลด้วย ESP_LOGI
I (10867) CANDIES_MATH: 
I (10867) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (10867) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (12867) main_task: Returned from app_main()
```

### แบบฝึกหัดที่ 3 สร้างตารางสูตรคูณ
```c
ESP_LOGI(TAG, "📊 ตารางสูตรคูณของ %d:", candies_per_bag);
for (int i = 1; i <= 10; i++) {
    ESP_LOGI(TAG, "   %d x %d = %d", i, candies_per_bag, i * candies_per_bag);
}
```

### Result
```c
I (5842) spi_flash: detected chip: winbond
I (5852) spi_flash: flash io: dio
I (5868) main_task: Started on CPU0
I (5878) main_task: Calling app_main()
I (5878) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (5878) CANDIES_MATH: ====================================
I (5878) CANDIES_MATH: 📖 โจทย์:
I (5878) CANDIES_MATH:    มีลูกอมทั้งหมด 9 ถุง
I (5878) CANDIES_MATH:    ถุงละ 8 เม็ด
I (5878) CANDIES_MATH:    ❓ รวมเป็นลูกอมทั้งหมดกี่เม็ด?
I (5878) CANDIES_MATH:
I (8878) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (8878) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (8878) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (8878) CANDIES_MATH: 
I (8878) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (8878) CANDIES_MATH:    รวมถุงทั้งหมด: 3 + 2 + 4 = 9 ถุง
I (8878) CANDIES_MATH:    ลูกอมทั้งหมด = 9 × 8 = 72 เม็ด
I (8878) CANDIES_MATH: 
I (8878) CANDIES_MATH: ✅ คำตอบ:
I (8878) CANDIES_MATH:    มีลูกอมทั้งหมด 72 เม็ด
I (8878) CANDIES_MATH: 
I (8878) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (8878) CANDIES_MATH:    1 x 8 = 8
I (8878) CANDIES_MATH:    2 x 8 = 16
I (8878) CANDIES_MATH:    3 x 8 = 24
I (8878) CANDIES_MATH:    4 x 8 = 32
I (8878) CANDIES_MATH:    5 x 8 = 40
I (8878) CANDIES_MATH:    6 x 8 = 48
I (8878) CANDIES_MATH:    7 x 8 = 56
I (8878) CANDIES_MATH:    8 x 8 = 64
I (8878) CANDIES_MATH:    9 x 8 = 72
I (8878) CANDIES_MATH:    10 x 8 = 80
I (8878) CANDIES_MATH: 
I (8878) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (8878) CANDIES_MATH:    1. การคูณเลข (Multiplication)
I (8878) CANDIES_MATH:    2. การรวมรสชาติลูกอม (Addition + Multiplication)
I (8878) CANDIES_MATH:    3. การใช้ตัวแปรและแสดงผลด้วย ESP_LOGI
I (8878) CANDIES_MATH: 
I (8878) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (8878) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (10878) main_task: Returned from app_main()
```

### แบบฝึกหัดที่ 4 แจกลูกอมให้เพื่อน
```c
int friends = 12;           // จำนวนเพื่อน
int candies_per_friend = total_candies / friends;  // ลูกอมต่อคน
int remaining_candies = total_candies % friends;   // ลูกอมที่เหลือ

ESP_LOGI(TAG, "👥 แจกให้เพื่อน %d คน:", friends);
ESP_LOGI(TAG, "   คนละ %d เม็ด", candies_per_friend);
ESP_LOGI(TAG, "   เหลือ %d เม็ด", remaining_candies);
```

### Result
```c
I (5807) spi_flash: flash io: dio
I (5824) main_task: Started on CPU0
I (5834) main_task: Calling app_main()
I (5834) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (5834) CANDIES_MATH: ====================================
I (5834) CANDIES_MATH: 📖 โจทย์:
I (5834) CANDIES_MATH:    มีลูกอมทั้งหมด 9 ถุง
I (5834) CANDIES_MATH:    ถุงละ 8 เม็ด
I (5834) CANDIES_MATH:    ❓ รวมเป็นลูกอมทั้งหมดกี่เม็ด?
I (5834) CANDIES_MATH: 
I (8834) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (8834) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (8834) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (8834) CANDIES_MATH:
I (8834) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (8834) CANDIES_MATH:    รวมถุงทั้งหมด: 3 + 2 + 4 = 9 ถุง
I (8834) CANDIES_MATH:    ลูกอมทั้งหมด = 9 × 8 = 72 เม็ด
I (8834) CANDIES_MATH:
I (8834) CANDIES_MATH: ✅ คำตอบ:
I (8834) CANDIES_MATH:    มีลูกอมทั้งหมด 72 เม็ด
I (8834) CANDIES_MATH: 
I (8834) CANDIES_MATH: 👥 แจกให้เพื่อน 12 คน:
I (8834) CANDIES_MATH:    คนละ 6 เม็ด
I (8834) CANDIES_MATH:    เหลือ 0 เม็ด
I (8834) CANDIES_MATH: 
I (8834) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (8834) CANDIES_MATH:    1 x 8 = 8
I (8834) CANDIES_MATH:    2 x 8 = 16
I (8834) CANDIES_MATH:    3 x 8 = 24
I (8834) CANDIES_MATH:    4 x 8 = 32
I (8834) CANDIES_MATH:    5 x 8 = 40
I (8834) CANDIES_MATH:    6 x 8 = 48
I (8834) CANDIES_MATH:    7 x 8 = 56
I (8834) CANDIES_MATH:    8 x 8 = 64
I (8834) CANDIES_MATH:    9 x 8 = 72
I (8834) CANDIES_MATH:    10 x 8 = 80
I (8834) CANDIES_MATH:
I (8834) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (8834) CANDIES_MATH:    1. การคูณเลข (Multiplication)
I (8834) CANDIES_MATH:    2. การรวมรสชาติลูกอม (Addition + Multiplication)
I (8834) CANDIES_MATH:    3. การแจกลูกอมให้เพื่อนโดยหารและหาค่าเศษ
I (8834) CANDIES_MATH:    4. การใช้ตัวแปรและแสดงผลด้วย ESP_LOGI
I (8834) CANDIES_MATH:
I (8834) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (8834) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (10834) main_task: Returned from app_main()
```
