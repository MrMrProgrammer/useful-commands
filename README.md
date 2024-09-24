### Failure to display warnings

```python
import warnings
warnings.filterwarnings("ignore")
```

#### Show warnings :
```python
warnings.filterwarnings("default")
```

---

###  Update Jupyter Output
```python
from IPython.display import clear_output, display

for i in range(10):
    clear_output(wait=True)
    display(f"Current value: {i}")
```

---
### Using `fireducks` instead of `pandas` to increase speed

```bash
pip install fireducks
```

```python
import fireducks.pandas as pd
```

---

### Convert HTML to PDF

```python
from weasyprint import HTML
HTML('https://google.com').write_pdf(f'google.pdf')
```

---

### Show history of latest command in terminal

```markdown
history | grep httpd : filter history by "httpd"
```

---

### Kill a port in ubuntu

```markdown
sudo kill -9 $(sudo lsof -t -i:8000)
```

---

### Installation using pip without description and with description

#### without description:
```markdown
pip install -q <something>
```

#### with description:
```markdown
pip install -v <something>
```

---

### Changing the Phpmyadmin Theme

- step 1 : Download theme from [here](https://www.phpmyadmin.net/themes/)
- step 2 : Place the desired theme in the ```/theme/‍‍‍``` docker folder
  ```markdown
  docker cp <theme_folder_name> <phpmyadmin_container_name>:/var/www/html/themes/
  ```

---

### Inserting numbers into text in Python:

1) F-String :
   ```python
   age = 23
   print(f"I'm {age} years old")
   ```
2) Format String :
   ```python
   age = 23
   print("I'm {} years old".format(age))
   ```
3) String Formatting With %d
   ```python
   age = 23
   print("I'm %d years old" % (age))
   ```

---

### Open a port

```markdown
sudo ufw allow <port>
```

---

### Change Jupyter Notebook Theam
```markdown
https://saturncloud.io/blog/jupyter-notebook-dark-mode-a-step-by-step-guide/
```

---

### Give access to files and folders

chmod [مجوزها] [فایل یا پوشه]

```markdown
chmod -R 777 'FOLDER NAME'
```

در اینجا، [مجوزها] می‌تواند به چندین شکل مختلف باشد، از جمله:

- حالت عددی (مثل ۷۵۵)
- حالت نمادی (مثل u+rwx)
- حالت مختصر (مثل u+x)

مجوزهای مهم در این دستور به شرح زیر است:

- نمایانگر صاحب فایل (کاربر) u
- نمایانگر گروه فایل g
- نمایانگر دیگران o
- نمایانگر تمام افراد (صاحب، گروه و دیگران) a
و همچنین:

- +برای افزودن مجوز
- - برای حذف مجوز
- = برای تنظیم مجوز به صورت دقیق
 

---
