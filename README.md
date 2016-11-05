# noisylist-hk
Free spam call list for Hong Kong

noisylist-hk is a free spam call list for Hong Kong. Although there is another spam call data provider, HKJunkCall.com, however, using their data is not free. This project aims to be a truelly free replacement of HKJunkCall.com. All data we collected are public, and no one needs to pay for it.

## Contribute
The spam call list is stored in (noisylist-hk-block.txt)[https://github.com/noisylist/noisylist-hk/blob/master/noisylist-hk-block.txt].

If you want to modify the content on the list, please create a pull request. 

### Rules
1. Each rows contains at most one spam call number.
2. If the row contsins `#`, then the characeters from the `#` to the end of the line will be a comment. Caller info can be the comment after the number
3. Rows should be order by number ascendingly

e.g.
```
# This comment continues to the end of line
34000000
24000001 # This comment shows that the number is belonged ABC company
```

## License
The project is released under (GNU General Public License, version 3.0 (GPL-3.0))[https://opensource.org/licenses/GPL-3.0]

## see also
(HKJunkCall.com)[https://hkjunkcall.com]
