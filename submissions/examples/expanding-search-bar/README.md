# 🔍 Pure CSS Expanding Search Bar

A lightweight search bar that smoothly expands from a compact circular
search icon into a full input field when focused.

The animation is built entirely with HTML and CSS and requires no
JavaScript.

## Features

- Pure CSS implementation
- No JavaScript
- Smooth expanding animation
- Focus-triggered interaction
- Responsive design
- Semantic search form
- Accessible label
- Keyboard accessible
- Visible focus state
- Search icon built with inline SVG
- Reduced-motion support
- No external dependencies

## Usage

Add the following structure:

```html
<form class="search-container" role="search">
  <label class="search-label" for="site-search">
    Search
  </label>

  <input
    class="search-input"
    id="site-search"
    name="q"
    type="search"
    placeholder="Search..."
  >

  <button
    class="search-button"
    type="submit"
    aria-label="Submit search"
  >
    <svg
      class="search-icon"
      viewBox="0 0 24 24"
      aria-hidden="true"
    >
      <circle
        cx="10.8"
        cy="10.8"
        r="6.8"
      ></circle>

      <path d="m16 16 5 5"></path>
    </svg>
  </button>
</form>