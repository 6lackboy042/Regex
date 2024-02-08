Explanation of the Regex Pattern:

The regex pattern consists of a series of alternatives (separated by |) to match different credit card formats.
Each alternative represents a specific credit card issuer's format:
Visa: Starts with 4, followed by 12 or 15 digits.
Mastercard: Starts with 51 to 55, followed by 14 digits.
Dollar Account: Starts with 34 or 37, followed by 15 digits.
Verve: Starts with 6011 or 65, followed by 16 digits.
BTC: Starts with 300 to 305, 36, or 38, followed by 14 digits.
The pattern is wrapped in a non-capturing group (?: ... ) and anchored with ^ (start of string) and $ (end of string) to ensure that the entire input matches one of the specified formats.