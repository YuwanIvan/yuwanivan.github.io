# Yufan Chen's Personal Homepage

This is the source code for my personal academic website, hosted at [https://yuwanivan.github.io/](https://yuwanivan.github.io/).

## About

This website is built using [Jekyll](https://jekyllrb.com/) and based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template. It serves as my professional homepage, showcasing my research, teaching, and academic activities.

## Local Development

To run the website locally:

1. Install Ruby and dependencies:

   ```bash
   brew install ruby
   brew install node
   gem install bundler
   ```

2. Install Jekyll dependencies:

   ```bash
   bundle install
   ```

3. Serve the website locally:

   ```bash
   jekyll serve -l -H localhost
   ```

4. Open your browser and navigate to `http://localhost:4000`

## Content Structure

- `_pages/` - Main website pages (About, Research, CV, Teaching, etc.)
- `_config.yml` - Site configuration
- `images/` - Images and photos
- `files/` - PDF files (papers, slides, etc.)
- `_sass/` - Styling files

## License

The template is released under the MIT License. See LICENSE file for details.
