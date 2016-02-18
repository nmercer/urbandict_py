# urbandict_py
### Urban Dictionary API Python Helper

Just a quick and dirty way to use the Urban Dictionary API in python. Does some basic cleaning. Returns you the full json dump as a dict. Might save someone a few minutes.

### Example
```python
from urbandict import urbandict
urbandict("rare pepe")
```

### Output Example
```
{   
    u'list': [   {   u'author': u'hagueharry',
                     u'current_vote': u'',
                     u'defid': 8343751,
                     u'definition': u'A Pepe that is rare. A collector will always be on the look-out for new rare pepes to add to their collection, which no doubt already contains a lot of rare pepes. While one might be inclined to show off their rare pepes it is adviced to do so with caution, should the rare pepe be shared too much there is a good chance it will devalue in rarity.',
                     u'example': u"person 1: Oh wow that is a rare pepe!\r\nperson 2: Save it, it's all yours my friend. I have plenty of more rare pepes in my collection.",
                     u'permalink': u'http://rare-pepe.urbanup.com/8343751',
                     u'thumbs_down': 15,
                     u'thumbs_up': 81,
                     u'word': u'rare pepe'}],
    u'result_type': u'exact',
    u'sounds': [],
    u'tags': []
}
```
