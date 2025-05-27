# 🚀 Command Bus & Query Bus

## 🧠 What is Command Bus and Query Bus?

The **Command Bus** pattern separates *what should happen* (the **Command**) from *who handles it* (the **Handler**). It helps to organize code by encapsulating actions into distinct command objects.

The **Query Bus** is responsible for *fetching data* without changing the application state, separating reads from writes.

---

## ✅ Advantages

- 🎯 **Separation of concerns** (Single Responsibility Principle)  
- 🧪 **Improved testability**, since each handler can be tested in isolation  
- ⚙️ Supports **CQRS** (Command Query Responsibility Segregation) and event-driven architectures  
- 🧹 Enables **clean orchestration** and prevents "spaghetti service" classes  

---

## ⚠️ Disadvantages

- 🧩 Adds **some complexity** which might be overkill for small projects  
- 📝 Requires **boilerplate code** for registering handlers and commands  
- ⚠️ Risk of **overusing commands**, leading to fragmentation and unnecessary complexity  

---

## 💡 Why use Command & Query Bus?

This pattern shines in **large-scale, complex systems** where scalability, maintainability, and clear separation of responsibilities are critical. It helps keep your backend code clean, modular, and easier to evolve.

---

## 📌 Example (Kotlin) IN REPO!
