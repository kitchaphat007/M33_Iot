# 📝 Project Specification: 10th Grade Admission Portfolio Website

## 1. Project Overview
**Project Name:** Personal Portfolio Website for High School Admission (M.4)
**Target Audience:** High School Admission Committees, Teachers, and Interviewers.
**Objective:** To design and develop a responsive single-page portfolio website that showcases the student's academic excellence in Mathematics, Science, and English, utilizing the 5W1H framework to present a well-rounded and compelling narrative.

---

## 2. Architecture & Technology Stack
*   **HTML:** HTML5 (Semantic Structure)
*   **CSS Framework:** Tailwind CSS (via CDN for rapid prototyping)
*   **Typography:** Google Fonts (`'Prompt'` or `'Kanit'`) for clean, readable Thai and English text.
*   **Icons:** FontAwesome (via CDN)
*   **Interactivity:** Vanilla JavaScript (for smooth scrolling and basic mobile menu toggle)

---

## 3. Design System & UI/UX Guidelines
### 3.1. Color Palette (Student-Friendly & Professional)
*   **Primary Background:** `#F8FAFC` (Slate 50)
*   **Primary Text:** `#0F172A` (Slate 900)
*   **Brand/Header Color:** `#1E3A8A` (Blue 900) - Navy Blue
*   **Accent/Highlight Color:** `#38BDF8` (Sky 400) or `#F59E0B` (Amber 500)

### 3.2. Typography
*   **Headings (H1, H2, H3):** Google Font `Prompt` (Bold/Semi-bold).
*   **Body Text:** Google Font `Prompt` (Regular/Light).
*   **Line-height:** `1.6` for optimal readability.

### 3.3. Responsive Layout
*   **Mobile First:** Ensure all sections are legible on small screens (iPhone/Android).
*   **Tablet/Desktop:** Utilize CSS Grid and Flexbox to create multi-column layouts.

---

## 4. Page Structure & Exact Content Mapping (5W1H)

*Note for AI Developer: Please use the exact Thai text provided in the quotation marks below for each section.*

### Section 1: Navigation Bar (Sticky Top)
*   **Component:** Fixed Header (`position: sticky`, `top: 0`, `z-index: 50`).
*   **Links:** 
    *   หน้าแรก (Home)
    *   ประวัติ (About)
    *   ทักษะ (Skills)
    *   ผลงาน (Portfolio)
    *   เป้าหมาย (Motivation)
    *   ติดต่อ (Contact)

### Section 2: Hero Section (Who)
*   **Layout:** Split layout (Desktop) / Stacked (Mobile) with a placeholder for a profile image.
*   **Headline (H1):** "สวัสดีครับ ผมชื่อ กิจพัฒน์ บัวแย้ม"
*   **Sub-headline (H2):** "นักเรียนชั้น ม.3 ผู้หลงใหลในตัวเลข วิทยาศาสตร์ และภาษาอังกฤษ"
*   **Call to Action Button:** "ดูผลงานของฉัน" (Clicking this scrolls to the Portfolio section)

### Section 3: About Me & Education (Where & When)
*   **Title:** "ประวัติส่วนตัวและการศึกษา"
*   **Body Text:** "ผมเป็นนักเรียนจากโรงเรียนวิทยาศาสตร์จุฬาภรณราชวิทยาลัย ที่มีความมุ่งมั่นในการพัฒนาตนเองอย่างต่อเนื่อง โดยเฉพาะในสายวิชาคณิตศาสตร์และวิทยาศาสตร์ รวมถึงการใช้ภาษาอังกฤษในการค้นคว้าข้อมูลและสื่อสาร"
*   **Vertical Timeline Element:**
    *   "ม.1 - เริ่มต้นค้นคว้าในวิชาคณิตศาสตร์และวิทยาศาสตร์"
    *   "ม.2 - พัฒนาโครงงานวิชาการระดับโรงเรียน"
    *   "ม.3 - แข่งขันและทำโครงงานวิทยาศาสตร์"

### Section 4: Skills & Superpowers (How)
*   **Title:** "ทักษะและความถนัด"
*   **Progress Bars / Circular Indicators:**
    *   "Mathematics (คณิตศาสตร์) - 90%"
    *   "Science (วิทยาศาสตร์) - 85%"
    *   "English (ภาษาอังกฤษ) - 95%"
*   **Additional Text:** "นอกจากทักษะด้านวิชาการแล้ว ยังมีทักษะด้านการแก้ปัญหา (Problem Solving) และการทำงานเป็นทีม (Teamwork)"

### Section 5: Portfolio & Achievements (What)
*   **Title:** "ผลงานเด่นที่ภาคภูมิใจ"
*   **Layout:** Grid of cards (use image placeholders for each card).
    *   **Card 1:** 
        *   Title: "รางวัล/โครงงานวิทยาศาสตร์"
        *   Description: "คำอธิบาย: การทำโครงงานเกี่ยวกับ การพัฒนาเครื่องมือสำหรับติดตามค่าธาตุอาหารหลักที่พืชต้องการในแปลงเพาะปลูกพืช"
    *   **Card 2:** 
        *   Title: "กิจกรรมค่าย/ภาษาอังกฤษ"
        *   Description: "คำอธิบาย: เข้าร่วมกิจกรรมทดสอบทักษะภาษาอังกฤษ ASMO2567"

### Section 6: Motivation (Why)
*   **Title:** "เป้าหมายและแรงบันดาลใจ"
*   **Body Text:** "ทำไมผมถึงอยากเข้าศึกษาต่อในระดับชั้น ม.4 ที่นี่? เพราะผมเชื่อว่าศักยภาพด้านวิทย์-คณิต-อังกฤษ ของผม จะสามารถต่อยอดและพัฒนาได้อย่างก้าวกระโดดภายใต้สภาพแวดล้อมและหลักสูตรของโรงเรียนแห่งนี้ ผมมีความฝันที่จะนำความรู้ไปประยุกต์ใช้ในสายอาชีพ จิตแพทย์ ในอนาคต"

### Section 7: Footer & Contact (How to reach me)
*   **Title:** "ช่องทางการติดต่อ"
*   **Content:**
    *   Email Icon: kitchaphat.bua@pccpl.ac.th
    *   Phone Icon: 0855265354
    *   Copyright text: "© 2026 กิจพัฒน์ บัวแย้ม. All Rights Reserved."

---

## 5. Development Guide
1.  **Initialization:** Read this `spec.md` to understand the full context.
2.  **HTML Generation:** Generate the `index.html` file using Tailwind CSS and integrate the exact Thai content outlined in Section 4.
3.  **Styling:** Ensure the design is clean, the scrolling is smooth, and the layout works perfectly on both mobile and desktop screens. Code must be well-commented.