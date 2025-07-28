📝 แบบฝึกหัดที่ 1: เปลี่ยนจำนวนคุกกี้
```c
I (17127) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (17127) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (17127) COOKIES_MATH:    = 24 ÷ 6
I (17127) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (17127) COOKIES_MATH: 
I (17127) COOKIES_MATH: ✅ คำตอบ:
I (17127) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (17127) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (17127) COOKIES_MATH: 
I (17127) COOKIES_MATH: 🎨 ภาพประกอบการแบ่ง:
I (17127) COOKIES_MATH:    คุกกี้ทั้งหมด: 🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪 (24 ชิ้น)
I (17127) COOKIES_MATH: 
I (17127) COOKIES_MATH:    เพื่อนคนที่ 1: 
I (17137) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17137) COOKIES_MATH:    เพื่อนคนที่ 2: 
I (17137) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17137) COOKIES_MATH:    เพื่อนคนที่ 3: 
I (17137) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17137) COOKIES_MATH:    เพื่อนคนที่ 4: 
I (17137) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17137) COOKIES_MATH:    เพื่อนคนที่ 5: 
I (17137) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17137) COOKIES_MATH:    เพื่อนคนที่ 6: 
I (17137) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17137) COOKIES_MATH: 
I (17137) COOKIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (17137) COOKIES_MATH:    คุกกี้ 15 ชิ้น แบ่งให้ 3 คน
I (17147) COOKIES_MATH:    = 15 ÷ 3 = 5 ชิ้นต่อคน, เหลือ 0 ชิ้น
I (17147) COOKIES_MATH: 
I (17147) COOKIES_MATH:    คุกกี้ 13 ชิ้น แบ่งให้ 4 คน
I (17147) COOKIES_MATH:    = 13 ÷ 4 = 3 ชิ้นต่อคน, เหลือ 1 ชิ้น
I (17147) COOKIES_MATH:    (หารไม่ลงตัว)
I (17147) COOKIES_MATH: 
I (17147) COOKIES_MATH: ⚠️  กรณีพิเศษ - หารด้วยศูนย์:
I (17147) COOKIES_MATH:    ถ้าไม่มีเพื่อนมาแบ่ง (หารด้วย 0)
I (17147) COOKIES_MATH:    ไม่สามารถคำนวณได้ในทางคณิตศาสตร์
I (17147) COOKIES_MATH:    ในชีวิตจริง: คุกกี้จะเหลือทั้งหมด
I (17157) COOKIES_MATH: 
I (17157) COOKIES_MATH: 🔄 ความสัมพันธ์กับการคูณ:
I (17157) COOKIES_MATH:    การหาร: 24 ÷ 6 = 4
I (17157) COOKIES_MATH:    การคูณ: 4 × 6 = 24
I (17157) COOKIES_MATH:    การหารและการคูณเป็นการดำเนินการตรงข้ามกัน
```
📝 แบบฝึกหัดที่ 2: เพิ่มการตรวจสอบหารลงตัว
เพิ่มการตรวจสอบว่าหารลงตัวไหม:
```c
I (14863) spi_flash: detected chip: winbond
I (14885) spi_flash: flash io: dio
I (14926) main_task: Started on CPU0
I (14946) main_task: Calling app_main()
I (14946) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (14946) COOKIES_MATH: ================================
I (14946) COOKIES_MATH: 📖 โจทย์:
I (14946) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (14946) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (14946) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (14946) COOKIES_MATH: 
I (17946) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (17946) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (17946) COOKIES_MATH:    = 24 ÷ 6
I (17946) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (17946) COOKIES_MATH: 
I (17946) COOKIES_MATH: ✅ คำตอบ:
I (17946) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (17946) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (17946) COOKIES_MATH: 
I (17946) COOKIES_MATH: 🎨 ภาพประกอบการแบ่ง:
I (17946) COOKIES_MATH:    คุกกี้ทั้งหมด: 🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪 (24 ชิ้น)
I (17946) COOKIES_MATH: 
I (17946) COOKIES_MATH:    เพื่อนคนที่ 1: 
I (17946) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17946) COOKIES_MATH:    เพื่อนคนที่ 2: 
I (17946) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17946) COOKIES_MATH:    เพื่อนคนที่ 3: 
I (17946) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17946) COOKIES_MATH:    เพื่อนคนที่ 4: 
I (17946) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17946) COOKIES_MATH:    เพื่อนคนที่ 5: 
I (17946) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17946) COOKIES_MATH:    เพื่อนคนที่ 6: 
I (17946) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (17946) COOKIES_MATH: 
I (17956) COOKIES_MATH: ✅ หารลงตัว! ทุกคนได้เท่ากัน
```
