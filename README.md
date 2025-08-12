# 📄Portfolio – Youssef Zaafan

## 👤 About Me
I am a passionate Software Testing Engineer with a strong foundation in manual and automated testing.  
Skilled in JAVA, OOP, SystemVerilog, UVM, and functional coverage for hardware verification, as well as using industry-standard tools like Selenium, Postman, and JMeter for software testing.  
I believe in delivering high-quality software by identifying issues early and ensuring robust, maintainable test processes.

---

## 📑 Curriculum Vitae
[📥My CV]([CV/Youssef_Zaafan_SW Testing Engineer.pdf])  


---

## 🛠 Skills & Tools

**Testing Types**  
- Manual Testing, Automation Testing, API Testing, Functional Verification

**Tools**  
- Selenium, Postman, JMeter, Cypress

**Verification**  
- UVM, Functional Coverage, Random Stimulus

**Simulators**  
- Synopsys VCS, Aldec Riviera-PRO

**Bug Tracking**  
- Jira, Trello

**CI/CD**  
- Jenkins, GitHub Actions

**Programming**  
- SystemVerilog, Python, Java

**Databases**  
- MySQL

---

## 📂 Projects

### Manual Testing – Booking.com  
Performed manual functional testing on hotel search and location accuracy.  
Identified an issue with incorrect distance calculation between Tunis village hotels and Fayoum city center.  
[📄 View Bug Report](./Bug_Reports/Bug_report_Booking.com.pdf)

### Manual Testing – Sprints.com  
Performed manual testing on quiz completion and learning flow.  
Identified an issue where the quiz results were not displayed after submission, and the system marked it as complete while unlocking the next module.  
[📄 View Bug Report](./Bug_Reports/Bug_report_Sprints.com.pdf)
### Verification of Sequential Adder  
[🔗 View on GitHub](https://github.com/youssefzaafan/Verification-of-Sequential-Adder)  
Developed full UVM testbench with functional coverage and self-checking scoreboard.

### Verification of Combinational Circuit 4-bit Multiplier  
[🔗 View on GitHub](https://github.com/youssefzaafan/Verification-of-Combinational-Circuit-4-bit-Multiplier)  
Implemented UVM-based verification environment and directed/random tests.

### Verification of UART Protocol  
[🔗 View on GitHub](https://github.com/youssefzaafan/Verification-of-UART-Protocol)  
Created test scenarios for UART TX/RX, checked framing, parity, and timing.

### Verification of I2C Memory  
[🔗 View on GitHub](https://github.com/youssefzaafan/Verification-of-I2C-Memory)  
Verified I2C transactions, ack/nack handling, and memory read/write sequences.


---

## 🪲 Bug Reports

### 1. Quiz Results Not Displayed – Sprints Website
**Summary:** Website crashes after quiz submission, preventing display of quiz results. The system incorrectly marks the quiz as completed and automatically advances the student to the next module without allowing review of the current module’s content.  
**Steps to Reproduce:**  
1. Go to Sprints.com  
2. Search for "Sprints x Microsoft Summer Camp - Software Testing"  
3. Go to quiz for any module  
4. Complete and submit the quiz  
5. Observe missing results and auto-unlock of next module  

**Expected Result:** Display quiz results before marking as complete and unlocking the next module.  
**Actual Result:** Website crashes, results not displayed, next module unlocked.  
**Impact:** Students cannot evaluate performance before moving on.

---

### 2. Incorrect Distance Calculation – Booking Website
**Summary:** Distances between some hotels and the city center are inaccurately displayed, misleading users about the actual travel distance.  
**Example:** “Tunis Camp Fayoum” shown as 35 km from Fayoum city center on Booking.com, but Google Maps shows ~47 km.  
**Steps to Reproduce:**  
1. Go to Booking.com  
2. Search for "Fayoum, Egypt"  
3. Check listings from Tunis village  
4. Compare displayed distance with Google Maps  
**Expected Result:** Accurate distances synced with real travel routes.  
**Actual Result:** Underestimated by 10–15+ km.  
**Impact:** Users may make booking decisions based on incorrect location data.

---

## 📧 Contact
- **Email:** [youssefzafan@gmail.com](mailto:youssefzafan@gmail.com)  
- **LinkedIn:** [linkedin.com/in/youssef-zaafan-211482169](https://www.linkedin.com/in/youssef-zaafan-211482169)  
- **GitHub:** [github.com/youssefzaafan](https://github.com/youssefzaafan)
