# My Jekyll Blog

This is a simple Jekyll blog site that can be hosted on GitHub Pages. Below are the details for setting up and using the project.

## Project Structure

The project has the following structure:

```
my-jekyll-blog
├── _config.yml          # Configuration settings for the Jekyll site
├── _includes            # Contains reusable HTML snippets
│   ├── footer.html      # Footer section of the site
│   └── header.html      # Header section of the site
├── _layouts             # Layout templates for the site
│   ├── default.html     # Default layout for the site
│   └── post.html        # Layout for individual blog posts
├── _posts               # Directory for blog posts
│   └── 2024-01-01-welcome-to-jekyll.md # Sample blog post
├── assets               # Directory for assets like CSS and JS
│   ├── css
│   │   └── main.scss    # Main stylesheet (Sass)
│   └── js
│       └── script.js    # JavaScript file for interactivity
├── pages                # Additional pages for the site
│   └── about.md         # About page
├── Gemfile              # Ruby gems required for the project
├── .gitignore           # Files and directories to ignore in Git
└── README.md            # Documentation for the project
```

## Setup Instructions

1. **Install Ruby and Bundler**: Ensure you have Ruby installed on your machine. You can check this by running `ruby -v` in your terminal. If you don't have Ruby, you can install it from [ruby-lang.org](https://www.ruby-lang.org/en/downloads/). After installing Ruby, install Bundler by running:
   ```
   gem install bundler
   ```

2. **Install Jekyll**: You can install Jekyll by running:
   ```
   gem install jekyll
   ```

3. **Install Dependencies**: Navigate to the project directory and run:
   ```
   bundle install
   ```

4. **Run the Jekyll Server**: Start the Jekyll server with:
   ```
   bundle exec jekyll serve
   ```
   Your site will be available at `http://localhost:4000`.

## Usage

- You can add new blog posts in the `_posts` directory. Make sure to follow the naming convention `YYYY-MM-DD-title.md`.
- Modify the `_config.yml` file to change site settings like title and description.
- Customize the styles in `assets/css/main.scss` and add any JavaScript functionality in `assets/js/script.js`.

## Deployment

To deploy your Jekyll site on GitHub Pages, push your code to a GitHub repository and enable GitHub Pages in the repository settings. Make sure to set the source to the `main` branch or the `gh-pages` branch, depending on your setup.

Happy blogging!