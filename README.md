# PerseusR-DualQualityFilter
Perseus plugin in R for dual matrix quality filtering.

## Main usage
This tool was made specifically for filtering SILAC data on the Ratio counts and the Ratio variability,
allowing a borderline scenario where low counts are tolerated if the variability is low enough.

## Relevant parameters
-value1 is the minimum ratio count

-value2 is the maximum variability

## How-to
Copy the file to a destination on your computer and use it from Perseus through the button External > R.

Example for changing the parameters to higher stringency using the additional arguments box:

-value1 3 -value2 20
