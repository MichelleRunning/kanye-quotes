# Kanye Quotes Application

An interactive desktop application built with Python and Tkinter that fetches random Kanye West quotes from a public API.

The app displays a quote on a styled canvas background and allows users to generate a new quote at the click of a button.

---

## Features

- Fetches real-time quotes from the Kanye REST API  
- Clean graphical user interface built with Tkinter  
- Styled canvas layout with background image  
- One-click quote refresh  
- Simple and lightweight design  

---

## Application Preview

![App Preview](preview-kanye-quotes.jpg)

---

## Technology Used

- **Python 3** – Core programming language  
- **Tkinter** – Graphical user interface (GUI)  
- **Requests** – API calls to retrieve quotes  
- **Kanye REST API** – https://api.kanye.rest  

---

## How It Works

1. The application window is created using Tkinter.
2. A canvas displays a background image and placeholder text.
3. When the user clicks the Kanye button:
   - A GET request is sent to the Kanye REST API.
   - The JSON response is parsed.
   - The quote text is extracted.
   - The canvas text is updated dynamically with the new quote.
4. The app remains open until the user closes the window.

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/MichelleRunning/kanye-quotes.git
```

2. Install dependencies
```bash
pip install requests
```
- Tkinter comes pre-installed with most Python distributions. 

3. Run the application
```bash
python main.py
```
