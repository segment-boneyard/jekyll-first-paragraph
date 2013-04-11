# jekyll-first-paragraph

  A Jekyll plugin that adds the `first_paragraph` Liquid filter, which returns the first paragraph of an HTML string. Useful for creating excerpts for a post.

## Usage
  
  It requires the `'nokogiri'` gem, so:
  
```ruby
gem install nokogiri
```

  And then in your Liquid-parsed file:

```liquid
{{ post.content | first_paragraph }}
```

## License

  MIT
