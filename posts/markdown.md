# 📘 HƯỚNG DẪN MARKDOWN (FULL)

## 🧠 1. Markdown là gì

Markdown là một ngôn ngữ markup nhẹ giúp định dạng văn bản nhanh chóng, thường dùng cho:

* README GitHub
* tài liệu kỹ thuật
* ghi chú
* blog

---

## ✍️ 2. Cú pháp cơ bản

### 🔹 2.1 Heading (Tiêu đề)

```md
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

---

### 🔹 2.2 Định dạng chữ

```md
**bold**
*italic*
~~strike~~
`inline code`
```

Ví dụ:

* **bold**
* *italic*
* ~~strike~~
* `code`

---

### 🔹 2.3 Danh sách (List)

#### Unordered List

```md
- Item 1
- Item 2
  - Sub item
```

#### Ordered List

```md
1. Item 1
2. Item 2
```

---

### 🔹 2.4 Link

```md
[Google](https://google.com)
```

---

### 🔹 2.5 Image

```md
![alt text](image.png)
```

---

### 🔹 2.6 Blockquote

```md
> Đây là trích dẫn
```

---

### 🔹 2.7 Code block

<pre>
```java
System.out.println("Hello World");
```
</pre>

---

## 📊 3. Table (Bảng)

```md
| Name | Age |
|------|-----|
| Hung | 20  |
| An   | 22  |
```

---

## 🧩 4. Nâng cao

### 🔹 Checklist

```md
- [x] Done
- [ ] Todo
```

---

### 🔹 Horizontal line

```md
---
```

---

### 🔹 Escape ký tự

```md
\* không bị in nghiêng *
```

---

### 🔹 HTML trong Markdown

```md
<b>bold</b>
<br>
<i>italic</i>
```

---

## ⚡ 5. GitHub Markdown (GFM)

### 🔹 Syntax Highlight

<pre>
```python
print("Hello")
```
</pre>

---

### 🔹 Emoji

```md
:smile:
🔥 🚀 🎯
```

---

### 🔹 Mention

```md
@username
```

---

## 📁 6. Template README chuẩn

````md
# 🚀 Project Name

## 📌 Giới thiệu
Mô tả ngắn gọn về project

## ⚙️ Cài đặt
```bash
npm install
````

## ▶️ Chạy project

```bash
npm start
```

## 📂 Cấu trúc thư mục

* src/
* docs/
* public/

## 🧠 Công nghệ sử dụng

* Java
* Spring Boot
* MySQL

## 📸 Demo

![demo](demo.png)

## 🤝 Đóng góp

Pull request are welcome!

## 👤 Author

Nguyễn Khánh Hưng

````

---

## 💡 7. Best Practice

- Dùng heading rõ ràng (#, ##, ###)
- Luôn highlight code
- Viết ngắn gọn, dễ đọc
- Dùng emoji hợp lý

---

## 🔥 8. Tips xịn

### 🔹 Tạo mục lục
```md
## Table of Contents
- [Intro](#giới-thiệu)
- [Install](#cài-đặt)
````

---

### 🔹 Anchor link

```md
[Go to Install](#cài-đặt)
```

---

### 🔹 Xuống dòng

```md
Dòng 1  
Dòng 2
```

---

### 🔹 Nested list

```md
- A
  - B
    - C
```

---

## 🎯 9. Khi nào nên dùng Markdown

| Trường hợp      | Dùng |
| --------------- | ---- |
| GitHub README   | ✅    |
| Docs API        | ✅    |
| Ghi chú         | ✅    |
| Web UI phức tạp | ❌    |

---

## 🚀 10. Cheat Sheet nhanh

| Mục        | Cú pháp       |   |
| ---------- | ------------- | - |
| Heading    | `#`           |   |
| Bold       | `**text**`    |   |
| Italic     | `*text*`      |   |
| Code       | `` `code` ``  |   |
| List       | `-`           |   |
| Link       | `[text](url)` |   |
| Image      | `![alt](url)` |   |
| Table      | `             | ` |
| Code block | ```           |   |

---

## 🏁 Kết luận

👉 Chỉ cần nhớ:

* `#` tiêu đề
* `-` danh sách
* ` ` code
* `[]()` link
* `|` bảng

Là bạn dùng Markdown ngon rồi 🚀
