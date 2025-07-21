# GitHub Pages & wordpress.com
- Fetch wordpress.com blog posts and meta data to GitHub Pages site
- Uses WP post categories to populate site sections
  - category: header -> content for header
  - category: footer -> content for footer
  - category: postitem -> render wp posts as grid
- Uses WP post tags to populate navigation
  - tags: art -> filter and show posts with tag "art"

## Development
- Set TESTMODE true to use local JSON files
- Open index.html with Live Server plugin (VS Code) 

## Settings
Configure variables in index.html
- TESTMODE
  - true -> Use mock data files from json/ folder
  - false -> Fetch actual data from wordpress.com blog
- EXPANDCARD
  - true -> Clicking "Read more" expands card to show all text in blog post
  - false -> Clicking "Read more" opens single blog post view
