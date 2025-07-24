# Principles-of-Software-Security-

## 🌱 What I Learned from IFN657 – Principles of Software Security

Taking IFN657 gave me a deep, practical, and technical understanding of how software can be both the source of and the solution to cybersecurity threats. Below are my key learnings from the unit:

---

### 🔍 1. Software Vulnerabilities Are Real and Exploitable
- Explored how minor coding issues like unchecked buffers or format strings can lead to critical vulnerabilities.
- Successfully recreated exploits such as **buffer overflows**, **heap corruption**, and **format string attacks**.

---

### 🛠 2. Applied Security Techniques
- Used tools like **AFL++**, **GDB**, and **custom fuzzing harnesses** to uncover and analyze vulnerabilities.
- Understood the trade-offs between **static vs dynamic analysis** and how each helps in different phases of secure software development.

---

### 💣 3. Real-World Vulnerabilities Aren’t Easy to Find
- Fuzzing popular open-source C/C++ projects often yielded no results — demonstrating the **difficulty and unpredictability** of vulnerability discovery.
- Successfully reproduced **CVE-2023-4863** (heap overflow in `libwebp`) and analyzed its behavior.

---

### ⚖️ 4. Security vs Functionality is Always a Trade-Off
- Learned the importance of balancing usability with strong security practices.
- Real-world examples (e.g., Ariane 5, Boeing 787) showed how minor software bugs can lead to massive failures.

---

### 👩‍💻 5. Language and Design Matter
- C/C++ offer performance but come with high risks due to manual memory management.
- Reinforced the concept that **security must be considered at the design stage**, not added later.

---

### 🧠 6. Mindset Shift: Security Thinking
- Adopted a "red team" mindset — thinking like an attacker to anticipate and close loopholes.
- This shift will be crucial for my future in **cybersecurity and secure software development**.

---

### 🙌 Final Thoughts
This unit was a turning point in my academic journey. I now see software not just as functional code, but as a **potential security surface** that must be tested, hardened, and maintained with vigilance. I feel more prepared to contribute to building secure systems in the real world.

## 📝 Exam Reflection 

The final exam in IFN657 tested not just theoretical knowledge, but my **ability to think like a security analyst** under pressure. It reinforced key concepts from across the semester, such as:

- Identifying real vulnerabilities in C code (e.g. buffer overflows, format string bugs)
- Understanding how and when to stop fuzzing during vulnerability discovery
- Recognizing the differences between similar attacks like **reflected vs persistent XSS**
- Justifying secure coding practices and proposing realistic mitigations

### 🧠 What I Learned:
- **Writing secure code** is not enough — you need to explain *why* something is vulnerable and *how* to fix it.
- **Thinking like an attacker** helps you understand how even small code decisions can be exploited.
- Studying for the exam helped me **solidify my practical knowledge** through applied questions — not just memorization.

This exam experience brought everything together — from raw memory manipulation to web-based threats — and made me more confident in assessing and defending software systems.

---
