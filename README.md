# ⏱️ FocusCGL: The Anti-Distraction Prep Engine
> **Re-engineering competitive exam preparation for the distracted generation.**

FocusCGL is a premium, high-aesthetics, single-page web application engineered specifically for SSC CGL aspirants who struggle with severe distractibility. 

Instead of fighting executive dysfunction with unsustainable willpower, **FocusCGL leverages cognitive psychology and dopamine engineering** to turn dry syllabus tracking and speed preparation into a high-octane, gamified dashboard.

---

## 🚀 Live Demo & Hosting
The application is hosted 100% serverless and client-side:
👉 **[Open Live FocusCGL App](https://btwary.github.io/focus-CGL/)**

---

## 🧠 The Psychology Under the Hood
FocusCGL distills the core methodologies of elite performance and habits science into direct CGL preparation strategies:

| Author / Book | Core Insight | FocusCGL Application |
| :--- | :--- | :--- |
| **James Clear** (*Atomic Habits*) | The 2-Minute Rule | **PYQ Incrementor:** Solve at least 1 question to break the starting friction. |
| **Nir Eyal** (*Indistractable*) | Delayed Gratification | **Mind-Locker Scratchpad:** Intrusive thoughts are logged, blurred, and frozen until the study session ends. |
| **David Goggins** (*Can't Hurt Me*) | The Cookie Jar | **The Triumph Jar:** Reach in to consume a random hard victory from your past when you want to quit. |
| **Eckhart Tolle** (*The Power of Now*) | Anchored Attention | **Concentric Timer Rings:** Keeping focus strictly on the current immediate task. |

---

## ⚡ Core Upgraded Features

### 1. ⏱️ 15-Minute Sectional Sprint Timer (Background-Safe)
Aligned to the latest CGL speed-stakes constraints. Featuring **absolute timestamp-delta tracking**, the countdown clock remains 100% accurate even if your browser throttles or puts the tab to sleep while you are solving a mock test on another website.

### 📝 2. The Active Scratchpad (Thought Dump)
Enforces focus by capturing intrusive thoughts instantly. 
*   **Active Sprint:** The list is **blurred and locked** down—you can dump thoughts, but you cannot review them until the work is done.
*   **Post-Sprint:** The list unlocks, letting you review, check off, or delete items.

### 🍪 3. Goggins-Style Cookie Jar
An interactive motivational modal. Add custom victories to your visual ledger, and press the **"Reach into Cookie Jar"** button when you hit a mental wall to retrieve a random victory alongside a high-intensity Goggins quote.

### 🌳 4. Nested CGL Syllabus Accordions with Progress Sync
A highly thorough nested hierarchy: **4 Subjects ➔ ~40 Major Topics ➔ ~150 Core CGL Subtopics** (including *Disinterested/Dishonest Shopkeeper, Relative Speed, Tense Shifts*).
*   **Accordion Drawers:** View exact subtopics with clickable checkboxes.
*   **Real-time Progress Bars:** Child checks dynamically calculate and animate the parent topic's completion percentage (e.g., `3/5 (60%)`).
*   **Global Search Mode:** Instantly scan the entire syllabus. Finding a subtopic automatically bypasses tab limits, expands the matching accordion, and highlights it.

---

## 🔒 100% Client-Side Privacy
FocusCGL requires **no logins, no databases, and no cloud server connections**. 

All your custom streaks, captured distractions, triumphs lists, and syllabus checklist records are stored **exclusively in your browser's own memory (LocalStorage)**. Your data is 100% private to your specific physical device.

---

## 💻 Running Locally
Since FocusCGL is built with pure, high-performance vanilla web technologies, you can run it instantly without compiling any code:
1. Clone this repository:
   ```bash
   git clone https://github.com/BTwary/focus-CGL.git
