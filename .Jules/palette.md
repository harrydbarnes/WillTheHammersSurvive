## 2025-02-12 - Non-Semantic Interactive Elements
**Learning:** Several core interactive features (scroll-to-top, minimize table) were implemented as non-semantic `div`/`span` elements, relying solely on CSS for appearance and JS for behavior. This made them inaccessible to keyboard and screen reader users.
**Action:** Replace `div`/`span` with semantic `<button>` elements, ensuring default browser styles are reset appropriately, and manage `aria-label` state dynamically via JS.
