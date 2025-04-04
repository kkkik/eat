<div align="center" style="background-color: #f2f2f2; padding: 30px; border-radius: 12px;">

  <img src="https://via.placeholder.com/300x100?text=EAT" alt="EAT Logo" />

  <h1>🍽️ EAT — Execute Analyze Transform</h1>

  <p><i>Smart & safe Python code execution</i></p>

  <a href="https://badge.fury.io/py/eat">
    <img src="https://badge.fury.io/py/eat.svg" alt="PyPI version" />
  </a>

</div>

---

## ⚡ Quick Example

```python
from eat import digest, scan

code = "print('Hello from EAT')"

if not scan(code):
    digest(code)
```

---

🧠 Features

🔥 burn(code) — Obfuscate code

📊 chew(code) — Analyze code structure

🛡️ scan(code) — Detect malicious patterns

⚙️ digest(code) — Execute safely

♻️ full(code) — Prevent duplicate execution

🧠 throwup() — Get last result



---

📦** Install**
```bash
pip install eat
```

---

<p align="center">
  Built with love by <strong>kkkik</strong>
</p>
