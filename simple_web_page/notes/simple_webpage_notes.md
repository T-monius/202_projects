## Walkthrough Project: A Simple Web Page

### Understanding
- Use boilerpoint code
- Can probably accomplish most styling with semantic HTML
  + Don't necessarily use a CSS reset
  + Using a reset would simply require a bit more styling specificity in the CSS file
- `body`
  + Starts out with a `<section>`
  + Followed by an `<h1>` header
  + 3 `p` elements nested in section
    * Couple of inline styles in the first `p` element
    * `a` attribute linking to the 'Launch School' website
    * Second two paragraphs are a lighter color
      - Change `color` with CSS class
    * Underline the last paragraph
      - Use an `id` tag on this paragraph
      - Select it in the `.css` file to style
- CSS
  + 'Heading' is orange
  + Strongly styled words are blue and underlined
  + Italicized word is red
  + The paragraph font is slightly larger than before.

### Task
- In this walkthrough project, we'll learn the basic mechanics of constructing a new web page using HTML alone. The final result will look like this:
  + Snapshot with styling and text description
  + Saved in `Pictures/ls_html_css` directory

### Implementation
- Create a project directory
- Create a file `index.html`
- Create `assets` directory with child `stylesheets`
  + Create `main.css` in the child
  + Link this file to the `index.html` file in the project root directory
- Follow the 'Understanding' and implement the appropriate elements in `index.html`
- Implement CSS styles in the `.css` file
