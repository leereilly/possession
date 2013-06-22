# Posession

Possessive apostrophes are hard. Especially if they're for singular nouns ending in `s` or `ez`.

```ruby
"Chris".possessive(:ap)
# => "Chris'"

"Chris".possessive(:chicago)
# => "Chris's"

"Chris".possessive(:oxford)
# => "Chris's"

"Chris".possessive(:gollum)
# => "Chrisses's"

"Chris".possessive(:connery)
# => "Chrisish"
```

![](http://i.imgur.com/KrxoMCw.png)

## Resources

* [Apostrophe-S vs. Apostrophe: Forming Possessives of Words Ending in S](http://www.apvschicago.com/2011/06/apostrophe-s-vs-apostrophe-forming.html)
* [Oxford Apostrophe](http://oxforddictionaries.com/words/apostrophe)
