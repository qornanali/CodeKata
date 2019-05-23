# Supermarket Pricing

Some things in supermarkets have simple prices:

This can of beans costs Rp 7.500.

Other things have more complex prices. For example:

- three for a ten thousand rupiah (so what’s the price if I buy 4, or 5?)

- Rp 10.000/kg (so what does 4 ons cost?)

- Buy two, get one free (so does the third item have a price?)

The exercise is to experiment with various models for representing money and prices
that are flexible enough to deal with these (and other) pricing schemes,
and at the same time are generally usable
(at the checkout, for stock management, order entry, and so on).

Spend time considering issues such as:

- does fractional money exist?

- when (if ever) does rounding take place?

- how do you keep an audit trail of pricing decisions (and do you need to)?

- are costs and prices the same class of thing?

- if a shelf of 100 cans is priced using “buy two, get one free”, how do you value the stock?
