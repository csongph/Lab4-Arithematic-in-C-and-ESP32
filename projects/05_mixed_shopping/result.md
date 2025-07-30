### โจทย์ท้าทาย
ลองเปลี่ยนโจทย์:
1.เพิ่มสินค้าชอบที่คุณชอบ
2.เปลี่ยนส่วนลดเป็นเปอร์เซ็นต์ (10%)
3.เพิ่มภาษี VAT 7%

### Result
```c
I (6598) spi_flash: flash io: dio
I (6616) main_task: Started on CPU0
I (6626) main_task: Calling app_main()
I (6626) SHOPPING_MATH: 🛒 เริ่มต้นโปรแกรมซื้อของที่ตลาด (เวอร์ชันใหม่) 🛒
I (6626) SHOPPING_MATH: ==============================================
I (6626) SHOPPING_MATH: 📖 โจทย์:
I (6626) SHOPPING_MATH:    - แอปเปิ้ล: 5 หน่วย หน่วยละ 15 บาท
I (6636) SHOPPING_MATH:    - กล้วย: 10 หน่วย หน่วยละ 8 บาท
I (6636) SHOPPING_MATH:    - ชานมไข่มุก: 2 หน่วย หน่วยละ 40 บาท
I (6636) SHOPPING_MATH:    - ส่วนลด: 10%
I (6636) SHOPPING_MATH:    - VAT: 7%
I (6636) SHOPPING_MATH:    - แบ่งจ่าย: 3 คน
I (6636) SHOPPING_MATH:
I (9636) SHOPPING_MATH: 🧮 คำนวณราคารวม: 235.00 บาท
I (9636) SHOPPING_MATH: 💸 หลังหักส่วนลด 10%: 211.50 บาท
I (9646) SHOPPING_MATH: 💰 ภาษี VAT 7%: 14.81 บาท
I (9646) SHOPPING_MATH: 🧾 ยอดสุทธิรวม VAT: 226.30 บาท
I (9646) SHOPPING_MATH: 👥 แบ่งจ่าย 3 คน: คนละ 75.43 บาท
I (9646) SHOPPING_MATH:
I (9646) SHOPPING_MATH: 🧾 ใบเสร็จรับเงิน:
I (9646) SHOPPING_MATH:    =====================================
I (9646) SHOPPING_MATH:    แอปเปิ้ล: 5 × 15 = 75 บาท
I (9646) SHOPPING_MATH:    กล้วย: 10 × 8 = 80 บาท
I (9646) SHOPPING_MATH:    ชานมไข่มุก: 2 × 40 = 80 บาท
I (9646) SHOPPING_MATH:    -------------------------------------
I (9646) SHOPPING_MATH:    ยอดรวม:              235.00 บาท
I (9646) SHOPPING_MATH:    ส่วนลด 10%:          -23.50 บาท
I (9646) SHOPPING_MATH:    VAT 7%:               +14.81 บาท
I (9646) SHOPPING_MATH:    ยอดสุทธิ:            226.30 บาท
I (9646) SHOPPING_MATH:    แบ่ง 3 คน:           75.43 บาท/คน
I (9646) SHOPPING_MATH:    =====================================
I (9646) SHOPPING_MATH:    ขอบคุณที่ใช้บริการ 😊
I (11646) main_task: Returned from app_main()
```
