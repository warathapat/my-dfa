# Finite State Machine Designer & Simulator

This is a web-based tool for designing, visualizing, and simulating Finite State Machines (FSM) / Finite Automata (FA). It provides an interactive canvas to draw states and transitions, and allows you to test input strings against your machine in real-time.

**Live Demo:** [https://warathapat.github.io/my-dfa/](https://warathapat.github.io/my-dfa/)

<img width="1381" height="948" alt="image" src="https://github.com/user-attachments/assets/fd458a0f-1cdf-48fd-9cec-005145344ff5" />

-----

## ✨ Features

  * **Interactive Canvas:** Visually create and manipulate your FSM.
  * **Create States & Transitions:** Easily add states (double-click) and transitions (Shift + drag).
  * **Self-Loops:** Create transitions that start and end at the same state.
  * **Smart Guides:** Automatically align states for a cleaner diagram.
  * **Curve & Label Adjustment:** Drag the middle of a transition to adjust its curve, and drag its label to any position.
  * **Intuitive Editor:** Click any element to edit its properties (name, start/accept state, transition conditions).
  * **Real-time Simulation:** Input a string and instantly see the result (Accepted/Rejected) with the current state highlighted.
  * **Customization:**
      * Light & Dark Mode.
      * Bilingual UI (English / Thai).
      * Adjustable font size for the diagram.
  * **Export:** Save your FSM diagram as a PNG with a solid or transparent background.

-----

## 🚀 How to Use

### Basic Controls

  * **Create a State:** **Double-click** on an empty area of the canvas.
  * **Create a Transition:** Hold **`Shift`**, then **click and drag** from a start state to an end state.
  * **Move an Object:** **Click and drag** any state or transition label.
  * **Pan the View:** Hold **`Spacebar`** and **drag** the canvas.
  * **Delete an Object:** Select an object and press the **`Delete`** or **`Backspace`** key.

### Editing

1.  **Select an object** by clicking on it. The editor panel will appear on the right.
2.  **To name a state:** Select the state and simply start typing.
3.  **To edit a state:** Use the buttons in the editor panel to set it as the **start state** or toggle its **accept state**.
4.  **To edit a transition:** Use the text box in the editor panel to define its **condition(s)** (e.g., `a`, `b`, `01`).

### Testing the Machine

1.  Define a **start state**.
2.  Type any string into the **"Test String"** input box.
3.  The result will be displayed below the input box, and the final state (if any) will be highlighted in green on the canvas.

-----

## 🛠️ Technologies Used

  * **HTML5**
  * **Tailwind CSS** (via CDN)
  * **Vanilla JavaScript** (ES6+)

-----

## License

This project is licensed under the MIT License. See the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

-----


# เครื่องมือสร้างและจำลอง Finite State Machine

นี่คือเครื่องมือบนเว็บสำหรับออกแบบ สร้าง และจำลองการทำงานของ Finite State Machine (FSM) หรือ Finite Automata (FA) โดยมีพื้นที่ Canvas ให้สามารถวาดสถานะ (State) และเส้นเชื่อม (Transition) และสามารถทดสอบสายอักขระ (String) กับโมเดลที่สร้างขึ้นได้ทันที

**ดูเวอร์ชันเดโม:** [https://warathapat.github.io/my-dfa/](https://warathapat.github.io/my-dfa/)

-----

## ✨ ฟีเจอร์

  * **Interactive Canvas:** สร้างและจัดการ FSM ของคุณได้ด้วยการวาด
  * **สร้างสถานะและเส้นเชื่อม:** เพิ่มสถานะได้ง่ายๆ ด้วยการ **ดับเบิลคลิก** และเพิ่มเส้นเชื่อมด้วยการกด **`Shift` ค้าง + ลาก**
  * **Self-Loops:** สร้างเส้นเชื่อมที่เริ่มต้นและสิ้นสุดที่สถานะเดียวกันได้
  * **Smart Guides:** มีเส้นไกด์ช่วยจัดตำแหน่งของสถานะต่างๆ ให้ตรงกันอัตโนมัติ
  * **ปรับความโค้งและป้ายกำกับ:** ลากตรงกลางเส้นเชื่อมเพื่อปรับความโค้ง และลากข้อความของเส้นเชื่อมเพื่อย้ายตำแหน่ง
  * **Editor ที่ใช้งานง่าย:** คลิกที่ส่วนประกอบใดๆ เพื่อแก้ไขคุณสมบัติ (เช่น ชื่อ, สถานะเริ่มต้น/สถานะยอมรับ, เงื่อนไขของเส้นเชื่อม)
  * **จำลองการทำงานแบบ Real-time:** ป้อน String เพื่อทดสอบและเห็นผลลัพธ์ (Accepted/Rejected) ทันที พร้อมไฮไลท์สถานะปัจจุบัน
  * **การปรับแต่ง:**
      * โหมดสว่าง (Light Mode) และโหมดมืด (Dark Mode)
      * เมนูสองภาษา (อังกฤษ / ไทย)
      * ปรับขนาดตัวอักษรในแผนภาพได้
  * **ส่งออก (Export):** บันทึกแผนภาพ FSM เป็นไฟล์ PNG ได้ทั้งแบบพื้นหลังทึบและโปร่งใส

-----

## 🚀 วิธีการใช้งาน

### การควบคุมพื้นฐาน

  * **สร้างสถานะ (State):** **ดับเบิลคลิก** บนพื้นที่ว่างใน Canvas
  * **สร้างเส้นเชื่อม (Transition):** กด **`Shift` ค้างไว้** แล้ว **คลิกลาก** จากสถานะเริ่มต้นไปยังสถานะปลายทาง
  * **ย้ายวัตถุ:** **คลิกลาก** ที่สถานะ หรือที่ข้อความของเส้นเชื่อม
  * **เลื่อนมุมมอง (Pan):** กด **`Spacebar` ค้างไว้** แล้ว **ลาก** บน Canvas
  * **ลบวัตถุ:** คลิกเลือกวัตถุแล้วกดปุ่ม **`Delete`** หรือ **`Backspace`**

### การแก้ไข

1.  **คลิกเลือก** วัตถุที่ต้องการแก้ไข หน้าต่างแก้ไขจะปรากฏทางด้านขวา
2.  **ตั้งชื่อสถานะ:** คลิกเลือกสถานะที่ต้องการแล้วพิมพ์ชื่อได้เลย
3.  **แก้ไขสถานะ:** ใช้ปุ่มในหน้าต่างแก้ไขเพื่อกำหนดให้เป็น **สถานะเริ่มต้น** หรือสลับการเป็น **สถานะยอมรับ**
4.  **แก้ไขเส้นเชื่อม:** ใช้กล่องข้อความในหน้าต่างแก้ไขเพื่อกำหนด **เงื่อนไข** ของเส้นเชื่อม (เช่น `a`, `b`, `01`)

### การทดสอบ

1.  กำหนด **สถานะเริ่มต้น** ให้เรียบร้อย
2.  พิมพ์สายอักขระ (String) ที่ต้องการทดสอบลงในช่อง **"Test String"**
3.  ผลลัพธ์จะแสดงขึ้นทันที และสถานะสุดท้าย (ถ้ามี) จะถูกไฮไลท์ด้วยสีเขียวบน Canvas
