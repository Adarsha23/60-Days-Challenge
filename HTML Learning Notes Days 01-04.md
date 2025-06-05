# HTML Learning Notes

---

## Day 01 – Intro to HTML

### 1. **Header Basics**
- `&lt;header&gt;` is used to define the top section of a webpage or a specific section.
- It usually includes logos, titles, navigation, etc.
- You can have **multiple `&lt;header&gt;` tags** on a page (like one for whole site and others inside `&lt;section&gt;` or `&lt;article&gt;`).
- Helps structure the page and improve accessibility (screen readers love it).
- It’s **semantic**, meaning it has *meaning* not just *style*.
- **Different from `&lt;head&gt;`** (which is invisible metadata like `&lt;title&gt;`, `&lt;meta&gt;`, etc.).
- Inside a `&lt;header&gt;` you can use tags like `&lt;h1&gt;–&lt;h6&gt;`, `&lt;nav&gt;`, images, search bars, etc.
- `&lt;header&gt;` has **no default style**, you have to use CSS.

---

### 2. **Text Basics**
- `&lt;em&gt;` = emphasis (usually italic).
- `&lt;strong&gt;` = bold and important.
- `&lt;hr&gt;` = horizontal line (divider).
- `&lt;br&gt;` = line break (like pressing enter).
- **HTML Entity** = for special characters like `&amp;`, `&lt;`, `&gt;`, etc.  
  - Example: `&amp;copy;`, `&amp;amp;`, `&amp;lt;`, etc.
- `&lt;abbr title="World Health Organization"&gt;WHO&lt;/abbr&gt;` = shows hover text “World Health Organization”.
- `&lt;address&gt;` = shows contact info or physical address (usually italic by default).

---

### 3. **Lists**
- 3 Types:
  - **Ordered List (`&lt;ol&gt;`)** – items with numbers.
  - **Unordered List (`&lt;ul&gt;`)** – items with bullets.
  - **Description List (`&lt;dl&gt;`)** – term + description pair.
- Use `&lt;li&gt;` for list items inside `&lt;ul&gt;` or `&lt;ol&gt;`.
- For `&lt;dl&gt;`, use:
  ```html
  &lt;dl&gt;
    &lt;dt&gt;HTML&lt;/dt&gt;
    &lt;dd&gt;HyperText Markup Language&lt;/dd&gt;
  &lt;/dl&gt;
  ```

---

## Day 02 – Quotations, Links, and Images

### 1. **HTML Quotations**
- `&lt;blockquote&gt;` – long quote from a source (usually indented).
- `&lt;q&gt;` – short inline quote (adds quotes around it).

---

### 2. **HTML Links**
- `&lt;a href="url"&gt;Link&lt;/a&gt;` creates a hyperlink.
- `href` = where the link goes.
- By default, opens in the same tab. Use `target="_blank"` for new tab.
- Absolute URL = full link (`https://google.com`).
- Relative URL = internal link (`../Day04/Day04.html`).
- You can **link images** using `&lt;a&gt;&lt;img src="https://media.tenor.com/9SQNOsNr3OwAAAAM/jujutsukaisen-anime.gif"&gt;&lt;/a&gt;`.
- Use `mailto:` to create email links.
- `title` adds hover text.
- Use `id` to bookmark a section and link with `href="#sectionID"`.

---

### 3. **HTML Images**
- `&lt;img src="path" alt="desc"&gt;` is how you embed an image.
- `src` = image path, `alt` = text shown if image doesn’t load.
- Can be used with GIFs too.
- You can **make the image a link** by wrapping in `&lt;a&gt;`.
- Use `float` in CSS to make text wrap around the image.
- Background image for elements via CSS like:
  ```css
  body {
    background-image: url('https://media.tenor.com/9SQNOsNr3OwAAAAM/jujutsukaisen-anime.gif');
  }
  ```

---

## Day 03 – Tables and Multimedia

### 1. **HTML Tables**
- Structure:
  ```html
  &lt;table&gt;
    &lt;tr&gt;
      &lt;th&gt;Heading&lt;/th&gt;
      &lt;td&gt;Data&lt;/td&gt;
    &lt;/tr&gt;
  &lt;/table&gt;
  ```
- `&lt;tr&gt;` = table row  
- `&lt;th&gt;` = table header (bold + centered)  
- `&lt;td&gt;` = table data (normal cell)  
- Can nest multiple rows  
- Use `colspan`, `rowspan` to merge cells

---

### 2. **Audio**
```html
&lt;audio controls&gt;
  &lt;source src="audio.mp3" type="audio/mpeg"&gt;
  Your browser does not support the audio element.
&lt;/audio&gt;
```

### 3. **Video**
```html
&lt;video width="320" height="240" controls&gt;
  &lt;source src="movie.mp4" type="video/mp4"&gt;
  Your browser does not support the video tag.
&lt;/video&gt;
```

---

## Day 04 – Forms and Input

### 1. **Form Basics**
- `&lt;form action="backend.php" method="POST"&gt;` ... `&lt;/form&gt;`
- `action` = where form data is sent  
- `method` = `GET` (URL visible) or `POST` (hidden)

### 2. **Inputs**
```html
&lt;input type="text" name="username"&gt;
&lt;input type="password" name="pass"&gt;
&lt;input type="checkbox" name="terms"&gt;
&lt;input type="radio" name="gender" value="male"&gt; Male
&lt;input type="submit" value="Login"&gt;
```

### 3. **Dropdowns and Textarea**
```html
&lt;select name="cars"&gt;
  &lt;option value="volvo"&gt;Volvo&lt;/option&gt;
  &lt;option value="bmw"&gt;BMW&lt;/option&gt;
&lt;/select&gt;

&lt;textarea name="comments" rows="4" cols="50"&gt;&lt;/textarea&gt;
```
