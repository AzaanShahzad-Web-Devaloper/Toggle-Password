# 🔐 Password Toggle

A simple and interactive **Password Show/Hide Toggle** built with **HTML, CSS, and JavaScript**.

This project allows users to toggle the visibility of their password by clicking the eye icon. When the password is hidden, the input uses the `password` type. When the eye icon is clicked, the input changes to the `text` type and the password becomes visible.

## ✨ Features

* 🔒 Password input field
* 👁️ Show password functionality
* 🙈 Hide password functionality
* 🔄 Dynamic eye icon switching
* ⚡ Simple JavaScript interaction
* 📱 Clean and responsive design

## 🛠️ Technologies Used

* **HTML5** — Page structure
* **CSS3** — Styling and layout
* **JavaScript** — Password visibility toggle functionality

## 📁 Project Structure

```text
project-folder/
│
├── index.html
├── style.css
├── eye-open.png
└── eye-close.png
```

## ⚙️ How It Works

The password input initially uses:

```html
<input type="password" placeholder="Password" id="password">
```

When the user clicks the eye icon, JavaScript checks the current input type.

```javascript
if (password.type === "password") {
    password.type = "text";
    eyeicon.src = "/eye-open.png";
} else {
    password.type = "password";
    eyeicon.src = "/eye-close.png";
}
```

### Password Hidden

* Input type: `password`
* Password characters are hidden.
* Closed eye icon is displayed.

### Password Visible

* Input type: `text`
* Password characters become visible.
* Open eye icon is displayed.

## 🖼️ Required Images

Make sure these image files are included in your project:

```text
eye-open.png
eye-close.png
```

* `eye-open.png` — Displayed when the password is visible.
* `eye-close.png` — Displayed when the password is hidden.

## 🚀 How to Run

1. Clone or download this repository.
2. Make sure `style.css`, `eye-open.png`, and `eye-close.png` are included.
3. Open `index.html` in your web browser.
4. Enter a password.
5. Click the eye icon to show or hide the password.

## 📂 Main Files

### `index.html`

Contains:

* Password input field
* Eye icon
* JavaScript toggle functionality

### `style.css`

Contains the styling and layout for the password input box and eye icon.

## 📄 License

This project is available for **learning, personal, and educational purposes**.

---

⭐ If you like this project, consider giving the repository a star!
