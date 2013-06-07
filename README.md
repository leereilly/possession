# Posession

Possessive apostrophes are hard. Especially if their for singular nouns ending in s.

```ruby
Posession::Parser::AP "Chris"
# => "Chris'"

Posession::Parser::Chicago "Chris"
# => "Chris's"

Posession::Parser::Oxford "Chris"
# => "Chris's"

Posession::Parser::Gollum "Chris"
# => "Chrisses's"
```
