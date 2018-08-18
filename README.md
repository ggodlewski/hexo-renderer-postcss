# hexo-renderer-postcss
A Hexo plugin for rendering PostCSS

I'm not sure how to make this work with all the various PostCSS plugins without requiring them as dependencies. If you have an idea, let me know. If you want a dependency added, pull request :)

Sample usage:

Add following to your _config.yml
```
postcss:
  plugins:
    postcss-cssnext:
      browsers:
      - 'last 2 versions'
      - '> 5%'
    cssnano:
```
