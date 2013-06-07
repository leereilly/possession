# Posession

Possessive apostrophes are hard. Especially if they're for singular nouns ending in `s` or `ez`.

```ruby
"Chris".possession("AP", "Chris")
# => "Chris'"

"Chris".possession("Chicago", "Chris")
# => "Chris's"

"Chris".possession("Oxford", "Chris")
# => "Chris's"

"Chris".possession("Gollum", "Chris")
# => "Chrisses's"
```

![](http://i.imgur.com/KrxoMCw.png)
