# GitHub Pages & wordpress.com
- Fetch wordpress.com blog posts and meta data to GitHub Pages site
- Uses WP post categories to populate site sections
  - category: header -> content for header
  - category: footer -> content for footer
  - category: postitem -> render wp posts as grid
- Uses WP post tags to populate navigation
  - tags: art -> filter and show posts with tag "art"

## Development
- Open index.html with Live Server plugin (VS Code) 
- TESTMODE variable in index.html
  - true -> use mock data files from json/ folder
  - false -> fetch actual data from wordpress.com blog
