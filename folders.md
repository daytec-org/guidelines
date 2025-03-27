### Files:
- !important: Define IDE settings to insert a final newline (insert a final new line at the end of the file when saving it).
- All file and folder names must start from lower cased letter (inclede app.ts/x).

### Imports:
- All import must be absolute. Relative imports allowed only for the nested components.
- Imports from the upper layer are restricted (component can not import widget or page, for example).

### Folders:
```
.
├── src
│ ├── api
│ ├── entities # biusiness logic
│ ├── pages # SPA pages (or src/app if using SSR router)
│ ├── ui # UI components (or src/components)
│ ├── utils # parser, sanitize, throttle, etc.
│ ├── shared # Shared components
│ ├── widgets # Complex components
```

Using [Feature-Sliced Design](https://feature-sliced.github.io/documentation/) methodology.

