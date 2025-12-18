# 📊 Diagrams as Code (Mermaid.js)

Did you know you can make charts in GitHub just by writing text? No images required!
Copy these blocks into your Markdown files.

### 🔀 Flowchart


```mermaid
graph TD;
    A[User Starts] --> B{Has Account?};
    B -- Yes --> C[Login];
    B -- No --> D[Register];
    C --> E[Dashboard];
    D --> E;
```

### ⏱️ Gantt Chart (Timeline)

```mermaid
gantt
    title Project Timeline
    dateFormat  YYYY-MM-DD
    section Design
    Wireframe      :a1, 2023-01-01, 5d
    Prototyping    :after a1, 5d
    section Dev
    Backend        :2023-01-10, 10d
    Frontend       :2023-01-15, 10d
```

### 💾 Database Schema (ER Diagram)

```mermaid
erDiagram
    USER ||--o{ ORDER : places
    USER {
        string name
        string email
    }
    ORDER {
        int id
        string details
    }
```
Many More Differnet Are Available Here :- https://github.com/mermaid-js/mermaid
In **Readme** You will Find All the Diagram You Want
