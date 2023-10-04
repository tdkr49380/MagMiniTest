# Notejam Markdown

---
# Class Diagram
---

```Mermaid
classDiagram
    class User
    User : ID
    User : Email
    User : Password
    User : Authenticate ()
```

---
---

```Mermaid
classDiagram
    class Note
    Note : +String owner
    Note : +Bigdecimal balance
    Note : +deposit(amount)
    Note : +withdrawal(amount)

