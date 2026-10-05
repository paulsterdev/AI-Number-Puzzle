The missing number is **51**.

The grid is just the numbers **1–100** written 9 per row (11 rows × 9 = 99 slots, i.e. one number omitted). In the row that should run `46 … 54`, it actually reads:

`46 47 48 49 50` **`52`** `53 54 55`

So it jumps straight from **50 to 52**, skipping **51**. Everything after that is shifted by one within the rows, which is why that row ends at `55` yet the final row still reaches `100`.