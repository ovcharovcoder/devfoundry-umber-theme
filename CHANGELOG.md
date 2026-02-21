# Changelog
All notable changes to the DevFoundry Umber VS Code extension will be documented in this file. The format is based on Keep a Changelog, and this project adheres to Semantic Versioning.


## [1.0.0] - 2025-12-20
### Added

* Initial release of DevFoundry Umber — a warm dark theme featuring amber accents and earthy tones for comfortable extended coding sessions.
* Comprehensive syntax highlighting optimized for JavaScript/TypeScript, React (JSX/TSX), HTML, CSS/SCSS/SASS, Python, PHP, Java, C/C++, Ruby, JSON, YAML, Markdown, and other popular languages.
* Harmonious UI styling across editor, sidebar, activity bar, tabs, status bar, and terminal.
* Accessibility-compliant contrast ratios and subtle translucent selections.
* Built-in support for error/warning indicators and Git decorations.

## [1.0.1 - 1.0.2] - 2026-02-08
### Improved

* Refined overall color consistency to more closely match Chrome DevTools visual language.
* Improved selection visibility while preserving warm amber DevTools-inspired aesthetics.
* Enhanced line highlight behavior for better cursor tracking during long coding sessions.
* Tuned widget backgrounds (hover, suggest, editor widgets) for more cohesive UI layering.
* Improved scrollbar colors for better visibility without breaking dark UI balance.
* Refined comment, variable, and function contrast for improved readability across multiple languages.

### Fixed
* Replaced deprecated indent guide color keys with modern VS Code-compatible keys.
* Fixed minor inconsistencies between active and inactive selection states.
* Corrected subtle contrast issues in find match highlighting.

### Added
* Extended UI coverage for hover widgets, suggestion widgets, and editor widgets.
* Improved tab and focus visual feedback.
* Better visual harmony between editor surface and surrounding VS Code UI panels.

## [1.0.4] - 2026-02-09
### Enhanced
* Complete color palette refinement for optimal eye comfort and reduced visual fatigue during extended coding sessions.
* Extended language support covering modern web development stack: Vue.js, Tailwind CSS, GraphQL, Docker Compose, and API development.
* Improved syntax highlighting granularity with specialized tokenization for TypeScript decorators, React Hooks, and Vue.js directives.
* Enhanced UI component styling including notifications, sticky scroll, marker navigation, and diff editor visual improvements.
* Advanced bracket pair guidance with multi-level coloring for better code navigation in complex nested structures.
* Optimized terminal color scheme with full ANSI color support matching the theme's visual language.

###  Fixed
* Resolved JSON color inconsistency – restored distinct color differentiation between keys and values for better data structure visualization.
* Corrected tab highlight colors – unified active tab border to maintain theme's amber-based visual identity.
* Adjusted editor selection transparency – fine-tuned opacity levels for more comfortable text highlighting.
* Fixed validation errors by replacing deprecated editorLink.foreground with correct textLink.foreground property.
* Removed unsupported token background – resolved VS Code compatibility warnings in Markdown code block definitions.

### Added
* Comprehensive notifications system – fully styled notification panels, toasts, and icons with theme-consistent colors.
* Advanced Git integration – specialized highlighting for commit messages, diff headers, and merge conflicts.
* Testing framework support – dedicated syntax highlighting for test cases, assertions, and testing utilities.
* Shell/Terminal command highlighting – improved readability for command-line operations and arguments.
* HTTP/API development enhancements – specialized colors for HTTP methods, status codes, and API documentation.
* Code navigation improvements – added editor link colors, marker navigation backgrounds, and sticky scroll support.

### Technical
* Maintained Chrome DevTools inspiration while enhancing visual comfort and reducing eye strain.
* Preserved semantic token coloring consistency across all supported programming languages.
* Optimized transparency values throughout the theme for better UI layer separation.
* Expanded documentation coverage with proper changelog formatting and version tracking.
  
## [1.0.5] - 2026-02-10

### Added
* Extended semantic token coverage for parameters, readonly parameters, self parameters, and default library symbols.
* Inlay hints styling for improved readability of inline type and parameter hints.
* Extended JSON key highlighting support for object literal structures.
* Inline diff syntax coloring for inserted and removed text in code comparisons.
* Notebook UI token support for consistent styling inside notebook editors.

### Improved
* Enhanced visual consistency between semantic tokens and TextMate scopes.
* Better support for modern TypeScript / JavaScript language features.
* Improved color mapping for built-in library functions and methods.
* More consistent diff and merge visual feedback across editor UI.

### Fixed
* Reduced potential scope conflicts in extended token coverage areas.

## [1.0.6] - 2026-02-21

### Fixed
This version has refined the color system, improving contrast, strengthening visual hierarchy, and adding depth to the interface. The theme has become more balanced, focused, and noticeably more premium in everyday use.

