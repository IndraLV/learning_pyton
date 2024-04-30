# capitalize(): Returns a copy of the string with the first character capitalized and the rest lowercased.
s = "hello"
result = s.capitalize()  # Returns "Hello"

# upper(): Returns a copy of the string with all characters converted to uppercase.
s = "hello"
result = s.upper()  # Returns "HELLO"

# lower(): Returns a copy of the string with all characters converted to lowercase.
s = "HELLO"
result = s.lower()  # Returns "hello"

# strip(): Returns a copy of the string with leading and trailing whitespace removed.
s = "  hello  "
result = s.strip()  # Returns "hello"

# split(sep=None, maxsplit=-1): Splits the string into a list of substrings separated by the specified separator sep. If sep is not provided, whitespace is used as the default separator. The maxsplit parameter limits the number of splits.
s = "hello world"
result = s.split()  # Returns ['hello', 'world']

# join(iterable): Concatenates the elements of an iterable (such as a list) with the string as a separator.
words = ["hello", "world"]
result = " ".join(words)  # Returns "hello world"

# find(substring): Returns the lowest index in the string where the substring is found. Returns -1 if the substring is not found.
s = "hello world"
index = s.find("world")  # Returns 6

# replace(old, new): Returns a copy of the string with all occurrences of the old substring replaced by the new substring.
s = "hello world"
result = s.replace("world", "universe")  # Returns "hello universe"

# These are just a few examples of the many methods available for working with strings in Python.
