# ⏳ Advanced Countdown Timer

A simple yet powerful **Countdown Timer** web app built with **HTML, CSS, and Vanilla JavaScript** — using `setTimeout` and `setInterval` concepts.

---

## 🚀 Features

- **⏱️ Custom Time Input** 
- **▶️ Start / ⏸️ Pause / ⏹️ Stop / 🔁 Reset**
- **📊 Live Progress Bar**
- **🔊 Sound Alert** 
- **🔔 Alert Notification** — "Timer Finished!" popup

---

## 🛠️ Built With

| **Technology** | **Purpose** |
|---|---|
| **HTML5** | Structure |
| **CSS3** | Styling & Layout |
| **JavaScript (ES6)** | Timer Logic |

---

## 📁 Project Structure

```
mini_project_setTimeout_and_setInterval/
│
└── index.html   
```

---

## ⚙️ How It Works

### **1. setInterval — Timer Engine** per**1 second**

```javascript
timer = setInterval(() => {
    document.getElementById("count").innerHTML = count;
    count--;
    if (count < 0) {
        clearInterval(timer);
    }
}, 1000);
```

### **2. clearInterval — Pause & Stop**
`clearInterval(timer)

### **3. Progress Bar Logic**
```javascript
let progressWidth = (count / originalTime) * 100;
progressBar.style.width = progressWidth + "%";
```

---

## 🎮 Button Functions

| **Button** | **Function** | 
|---|---|---|
| **▶ Start** | `startTimer()` 
| **⏸ Pause** | `pauseTimer()` 
| **⏹ Stop** | `stopTimer()` | 
| **🔁 Reset** | `resetTimer()` 

---

## 📸 Preview

```
┌─────────────────────────────────┐
│    Advanced Countdown Timer ⏳  │
│                                 │
│    [  Enter seconds  ]          │
│                                 │
│           15                    │
│                                 │
│  [████████████░░░░░░]           │
│                                 │
│  [Start] [Pause] [Stop] [Reset] │
└─────────────────────────────────┘
```

---

## 🧠 Concepts Covered

- **`setInterval()`** — Repeated execution every N milliseconds
- **`clearInterval()`** — Stop a running interval
- **DOM Manipulation** — `getElementById`, `innerHTML`, `style.width`
- **Conditional Logic** — Timer end detection
- **Audio API** — `new Audio().play()sound play

---

## 📌 How To Run

**১।** `index.html` 
**২।** Input box- seconds 
**৩।** **Start** button press
**৪।** Enjoy! 🎉


---

## 👨‍💻 Author

**Your Name**
- GitHub:https://github.com/uzzal6090

---

## 📄 License

This project is open source and available
