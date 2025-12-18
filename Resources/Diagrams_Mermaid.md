# 📊 Diagrams as Code (Mermaid.js)

Did you know you can make charts in GitHub just by writing text? No images required!
Copy these blocks into your Markdown files.

### 🔀 Flowchart
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
