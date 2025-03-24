### Files:
- !important: Define IDE settings to insert a final newline (insert a final new line at the end of the file when saving it).
- All file and folder names must start from lower cased letter (inclede app.ts/x).

### Folders:
```
.
├── src
│ ├── api
│ ├── entities # biusiness logic
│ ├── pages # SPA pages
│ ├── ui # UI components
│ ├── utils # parser, sanitize, throttle, etc.
│ ├── shared # Shared components
│ ├── widgets # Complex components
```

Using [Feature-Sliced Design](https://feature-sliced.design/docs/get-started/overview) methodology.

No imports from utils, ui, shared.
Shared folder in this project it is external package.
