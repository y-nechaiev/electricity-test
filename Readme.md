# TEST TASK FOR DEVELOPERS

Please write the implementation for the logic described below. Don't try to rush,
and don't try to polish your solution either. I'd prefer to see a good sane implementation,
just like you would do that if it was a real task for a real project.

# Logic

There is a set of Power Plants and a set of Households. Every Household can be
connected to any number of Power Plants. Power Plant feeds the Household with the
Electricity. The Household has Electricity if it's connected to one or more
Power Plants.

Each Power Plant is alive by default, but can be killed. The Power Plant which
is not Alive will not generate any Electricity.

Household can be connected to Household. The Household which has the Electricity
also passes it to all the connected Households.

The Power Plant can be repaired after killed.


# Our expectations

While I expect that you will treat that just like any other ticket in your
real project, I also wanted to share some of our expectations. These expectations
are relevant in our project on a daily basis anyways.

1. I expect your solution to be so easy to understand that even my grannie will understand it.
2. I expect your abstractions to be solid and clean.
3. I expect your code to be easy to read.
4. I expect your solution to be sane and align with common sense.

# Setup

### install dependencies:

```shell
npm i
```

### Once you are ready to test your solution please run

```shell
npm test
```

# Have fun :-)
