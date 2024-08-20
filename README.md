# metashrew-ord

Implementation of [https://github.com/ordinals/ord](https://github.com/ordinals/ord) using BST structures for sat ranges.

For Bellschain, we simply hardcode a block reward of 5000e8 units of currency and treat coinbase output value less than this amount as unspent and directed to 0xdead outpoint.

This is acceptable to implement [https://github.com/sandshrewmetaprotocols/metashrew-bel20](https://github.com/sandshrewmetaprotocols/metashrew-bel20).

## Author

Sandshrew Inc

## License

MIT
