# Regular-Expression
Basic Regex description

# Meta Characters
### [] A set of characters
###  \ Signals a special sequence (can also be used to escape special characters)
###  . Any character (except newline character)
###  ^ Starts with
###  $ Ends with
###  * Zero or more occurrences
###  + One or more occurrences
###  {} Exactly the specified number of occurrences
###  | Either or
###  () Capture and group

### Special Sequences
# \A Returns a match if the specified characters are at the beginning of the string
# \b Returns a match where the specified characters are at the beginning or at the end of a word r"ain\b"
# \B Returns a match where the specified characters are present, but NOT at the beginning (or at the end) of a word

# \d Returns a match where the string contains digits (numbers from 0-9)
# \D Returns a match where the string DOES NOT contain digits
# \s Returns a match where the string contains a white space character
# \S Returns a match where the string DOES NOT contain a white space character
# \w Returns a match where the string contains any word characters (characters from a to Z, digits from 0-9, and the underscore _ character)
# \W Returns a match where the string DOES NOT contain any word characters
# \Z Returns a match if the specified characters are at the end of the string
