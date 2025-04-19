#🛡️ Nordhold Game – QA & Playtesting Project

Test scenarios and feedback collected during manual testing of the **Nordhold demo**.

---

# 🎯 Overview

- Game Title: Nordhold (Demo)
- Genre: Strategy / Tower Defense
- Platform: PC
- Testing Style: Manual testing
- Language Tested: English UI
- Tester: Kaan YÜZGEÇ
- Test Period: April 2025

---

# 🧪 Testing Methodology

This project uses manual testing combining:

- 🕶️ Black-box testing: Based on visible game behavior without access to internal code.
- 🧭 Exploratory testing: Focused on discovering bugs and issues during free play.
- ✋ Manual testing: All tests executed manually, simulating real player interaction.

> *Note: This test effort does not include white-box or code-level testing.*

---

# 🔍 Test Coverage

- UI and Menu Functionality
- Tower Placement & Enemy Targeting
- Resource Assignment System
- Targeting Priority Settings
- Game Stability and Responsiveness

---

# 🧾 Documentation Structure

| Folder | Description |
|--------|-------------|
| `test-cases/` | Manual test cases (e.g., TC001–TC010) |
| `bug-reports/` | Bug findings and behavior logs |
| `screenshots/` | Visual documentation of bugs and features |
| `reports/` | First impression reports and summaries |

---

# ✅ Sample Test Case

Test Case 8 – Tower Targeting Priority Can Be Set

- Steps:  
  1. Place a tower  
  2. Click the tower and open targeting settings  
  3. Choose a targeting mode (e.g., strongest enemy)

- Expected Result:
  The tower should target enemies based on the selected strategy

- Status: PASS

---

# 📌 Notes

- Testing was conducted entirely on the demo version of Nordhold.
- Workers are assigned numerically; unit production is not available.
- Enemy types (19 in total) can be prioritized per tower using the built-in targeting system.

---

# 📧 Contact

For questions or feedback: [kaanyzgc@gmail.com]
