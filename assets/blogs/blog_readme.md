Asset area for blogging

each blog uses a folder structure to keep posts organized by category and ID. Use the format:

  [L/W][xxxx]

Where:
- `L` indicates a Life post
- `W` indicates a Work post
- `xxxx` is a four-digit identifier

Inside each blog folder include:

- `blog_id.txt` — short summary or metadata for the post
- `blog_id.html` — the actual blog post page
- `assets/blog_id_xxx.png` — optional featured image or related illustration

Use `blog-template.html` at the repository root as the starting point for new posts. Create a new folder under `assets/blogs/`, then duplicate and edit the template to make a fresh article page.
