# My GitHub Pages Site

This is my personal website using the Jekyll Leap Day theme.

## Structure

- **_config.yml**: Configuration file for the site.
- **index.md**: The homepage of the site.
- **publications.md**: The projects page.

## Adding New Tabs

To add new tabs to the navigation:
1. Create a new markdown file in the root directory.
2. Update the `_config.yml` file to include the new page in the navigation.

Example `_config.yml` update:
```yaml
nav:
  - title: "Home"
    url: "/"
  - title: "About"
    url: "/about"
  - title: "Projects"
    url: "/projects"
  - title: "New Tab"
    url: "/new-tab"
