# Silent Auction 🏆  

A simple Python program that simulates a **silent auction**, where multiple participants can place bids anonymously. At the end, the program announces the winner with the highest bid.  

This project was built as part of the **100 Days of Code: Python Bootcamp** to practice working with dictionaries, functions, loops, and modular code.  

---

## Features ✨
- Collects names and bid amounts from multiple participants  
- Stores bids securely in a dictionary  
- Clears the screen (simulated with line breaks) to keep bids hidden between turns  
- Determines the highest bidder and announces the winner  

---

## Files 📂
- `main.py` → The main program file  
- `art.py` → Contains ASCII art for the logo, displayed when the program starts  

---

## How It Works ⚙️
1. Each participant enters their name and bid amount.  
2. The program asks if there are other bidders.  
   - If **yes**, the screen clears and the next bidder enters their details.  
   - If **no**, the program ends and the highest bidder is announced.  

---

## Example Run 💻
```bash
Welcome to the Silent Auction!
What is your name: Alice
What is your bid? RM 150
Are there any other bidders? Type 'yes' or 'no'.
yes

What is your name: Bob
What is your bid? RM 200
Are there any other bidders? Type 'yes' or 'no'.
no

The winner is Bob with the bid of RM200.
