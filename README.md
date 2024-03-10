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

### Open a port :

```markdown
sudo ufw allow <port>
```

---

### Run Streamlit file
```markdown
streamlit run app.py --server.fileWatcherType none
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
