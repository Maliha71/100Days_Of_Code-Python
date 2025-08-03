# Day 1 – Environment Set Up and Basic Functions

### ⚙️ Python Environment Setup in VS Code

---

#### 🧪 Step 1: Create a New Conda Environment  
Open **Anaconda Prompt** and run:

```bash
conda create -n angela100 python=3.10
conda activate angela100
```

---

#### 📦 Step 2: Install Basic Package (Optional but Helpful)  
This allows your environment to work with notebooks like Jupyter or VS Code interactive.

```bash
pip install ipykernel
```

---

#### 🖥️ Step 3: Open VS Code and Set Your Folder  
1. Open **VS Code**  
2. Go to **File > Open Folder**  
3. Select this folder on your system:  
   `E:\Learn Python\1 Angela_Wu_100Days_Code\Day 1`

---

#### 🐍 Step 4: Select Python Interpreter in VS Code  
1. Click the Python version in the **bottom-left** corner of VS Code  
2. Or press `Ctrl + Shift + P`, then select `Python: Select Interpreter`  
3. Choose: `Python 3.10 (angela100)` or the environment name you used

---

#### 📝 Step 5: Create and Run Your First Script  
1. Inside your folder, create a file named `main.py`  
2. Paste your solution code into it  
3. Run it by:  
   - Clicking the **Run ▶️** button  
   - Or right-clicking → **Run Python File in Terminal**

✅ Your environment is now ready, and your first script is running!

---

### 🧠 Challenge  
Write a Python program that uses `print()` statements to output a 5-step recipe.  
The output **must exactly match** the example format including punctuation and spacing.

---

### ✅ Example Output

```
1. Mix 500g of Flour, 10g Yeast and 300ml Water in a bowl.
2. Knead the dough for 10 minutes.
3. Add 3g of Salt.
4. Leave to rise for 2 hours.
5. Bake at 200 degrees C for 30 minutes.
```

---

### 🔍 How I Thought About It

1. First, I carefully read and observed what the problem is asking  
2. It's asking to **print some text** → So I need to use the `print()` function  
3. The recipe is all **strings** → So each line must be wrapped in quotes `" "`  
4. Each step goes in a separate `print()` line  
5. I matched punctuation, capitalization, and spacing **exactly**

---

### 💡 What I Learned

- How to use the `print()` function  
- Why exact formatting matters (punctuation, spaces, line breaks)  
- Careful reading of instructions is key to solving simple problems

---

### 💻 My Code

```python
print("1. Mix 500g of Flour, 10g Yeast and 300ml Water in a bowl.")
print("2. Knead the dough for 10 minutes.")
print("3. Add 3g of Salt.")
print("4. Leave to rise for 2 hours.")
print("5. Bake at 200 degrees C for 30 minutes.")
```

----


