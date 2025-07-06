# 🧱 Rush00 — 42 Piscine Project

This is a small C project from the **42 Piscine**.

The goal is to print rectangles using characters like `o`, `-`, `|`, and spaces.  
You give the size (width and height), and the program draws a shape.

---

## ✅ Files in the project

This project has only **3 files**, as required:

- `main.c` – starts the program
- `ft_putchar.c` – prints a character (using `write`)
- `rush.c` – has the code to draw the shape

---

## 🛠 How to compile

Open your terminal and run:

```bash
cc -Wall -Wextra -Werror main.c rush.c ft_putchar.c -o rush00
./rush00
```
⸻

🧪 Example output

If you call rush00(5, 3);, you will see:
```bash
o---o
|   |
o---o
```

⸻

🧠 You can change the size

In main.c, change:

rush00(5, 3);

to any size you want. For example:
```bash
rush00(1, 1);
rush00(4, 4);
rush00(1, 5);
rush00(5, 1);
```
⸻

📌 Rules from 42
	•	✅ Use write, not printf or puts
	•	✅ Use while, not for
	•	✅ Code should follow the Norminette

⸻

👩‍💻 Author

Made by Olga
Student at 42 Piscine 🇫🇷
GitHub: Liasique

⸻
