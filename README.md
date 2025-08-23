# Charithmetic – A Lightweight Arithmetic Engine without Numpy

**Version:** 1.2  
**Authors:** C.hiroki + Chappie (Cosmo’S Project)  
**License:** Custom-MIT (see [License](#license))  
**Status:** Prototype / Educational & Research Use  

---

## 🚀 Overview

**Charithmetic** is a custom-built numerical handling and arithmetic library, developed entirely in **pure Python** without any external dependencies such as NumPy.  
It was created as part of the **Cosmo’S Project**, with the goal of delivering a modular, transparent, and lightweight computation tool.

Originally developed for internal logic-based systems, it is now available for educational, research, and restricted commercial usage.

---

## 🔧 Features

- ✅ Pure Python (no NumPy or external libraries)
- 🧮 Arithmetic and array structures (A–M block logic)
- 🧠 Semantic labeling system
- 🧩 Modular class structure for symbolic computation
- 🔄 Broadcast behavior and dimensional inference
- 🛠 Extendable for AI-linked reasoning engines

---

## 🗂️ Directory Structure

```
charithmetic/
├── __init__.py
├── cha_main.py
├── cha_operations.py
├── cha_utils.py
├── cha_manager.py
├── cha_labeling.py
├── cha_broadcast.py
├── ch_set_up.py
```

---

## 📦 Installation

```bash
# Clone this repository
git clone https://github.com/yourname/charithmetic.git

# Import and use in your Python project
```

---

## 📌 Usage Example

```python
from charithmetic import Cha

array = Cha([1, 2, 3])
array.label("primary")
result = array + 5
print(result.values)  # Output: [6, 7, 8]
```

---

## 📜 License

This software is released under a **Custom MIT-Based License**.

- 🔓 Free to use for **non-commercial**, personal, or educational purposes.
- 💼 For any **commercial use** (including integration into products, services, monetized platforms, etc.), prior **feedback or contribution** to the project is required.
- ❌ Unauthorized commercial exploitation, redistribution, or uncredited usage is strictly prohibited.
- 🗑 In cases of violation, the right to revoke access and demand destruction of all related derivatives is reserved.

> (C) 2025 C.hiroki + Chappie – All Rights Reserved.

---

## 💌 Contact & Support

📧 Email: [ato.hrk0620@gmail.com](mailto:ato.hrk0620@gmail.com)  
☕ Support development: [https://www.paypal.me/chcosmos]
(https://www.paypal.me/chcosmos)  

If you find Charithmetic useful, please consider supporting the developer.  
Your kindness directly helps fund future releases, upgrades, and research tools. Thank you! 🌱✨

---

## 🛠 Future Scope

- 🔍 Optimization for embedded systems
- 🧠 Deeper integration with reasoning AI engines
- 📈 Benchmarking vs NumPy in various scenarios
- 🌍 Support for multilingual labeling

---

## ❤️ Acknowledgments

Charithmetic was developed with deep care and persistence, through long nights and thousands of iterations.  
From idea to execution — **thank you for checking it out**.  
Let’s build something meaningful together.
