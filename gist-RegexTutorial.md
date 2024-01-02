# Regex Tutorial (Module 17)

This document introduces a regex pattern crafted for the validation and extraction of email addresses from text. The regex meticulously analyzes email structures, covering the local part, '@' symbol, and domain part. Components are explained to provide clarity on their role in the pattern. This guide aims to enhance understanding and proficiency in employing regular expressions for email validation in diverse applications.
## Summary

I will be describing a regex pattern that matches email addresses. The regex aims to validate and extract email addresses from a given text. It will cover the basic structure of email addresses, including the local part, the '@' symbol, and the domain part. Here is the code snippet for the regex:

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

# Regular Expressions 

##  Anchors
- **Description:** Anchors are like bookends, dictating where your search begins or concludes within the vast pages of text.
- **Example:** Using `^abc` is akin to saying, "I want 'abc,' but it must grace the very commencement of this textual tome."

##  Quantifiers
- **Description:** Quantifiers act as orchestrators, deciding the rhythm and flow of characters, determining how many dance steps a pattern takes.
- **Examples:** With `a*`, it's like commanding, "Seek out 'a,' whether it's absent or in abundance." `b+` directs, "Discover 'b,' but at least once; don't be satisfied with solitary occurrences."

##  OR Operator
- **Description:** The OR operator is the curator of options, offering you a choice, much like deciding between two distinct art pieces.
- **Example:** In `dog|cat`, it's as if you're asking, "Shall I uncover a 'dog' or revel in the presence of a 'cat' within this creative masterpiece?"

##  Character Classes
- **Description:** Character classes are the selectors in a grand wardrobe, enabling you to attire your pattern with any garment of your choosing.
- **Examples:** `[aeiou]` is akin to decreeing, "Any vowel will suffice," while `[0-9]` proclaims, "Let any digit find its place in the pattern."

## Flags
- **Description:** Flags are the conductors guiding the symphony of pattern matching, dictating whether the melody should heed the distinctions of case.
- **Example:** In `/pattern/i`, it's like commanding, "Seek 'pattern' regardless of the case – be it uppercase, lowercase, or a blend."

##  Grouping and Capturing
- **Description:** Grouping is the act of enclosing patterns in parentheses, akin to framing a masterpiece, and capturing is immortalizing that framed beauty.
- **Examples:** `(ab)+` is like instructing, "Reveal one or more occurrences of the duo 'ab,' and savor the entire spectacle." `(\d{3})-\d{2}-\d{4}` captures a sequence akin to preserving a vintage photograph.

##  Bracket Expressions
- **Description:** Bracket expressions are the bespoke categories, akin to custom-made containers, allowing you to pick characters like selecting ingredients from a gourmet pantry.
- **Examples:** `[A-Za-z]` is akin to declaring, "Embrace any letter, be it regal uppercase or humble lowercase," and `[0-9a-f]` is like commanding, "Conjure the essence of any hexadecimal digit within this spellbinding pattern."

##  Greedy and Lazy Match
- **Description:** Greedy matching is the insatiable explorer, consuming as much territory as possible, while lazy matching is the contemplative wanderer, taking just what is necessary.
- **Examples:** `x*` voraciously engulfs zero or more 'x,' whereas `y*?` is the discerning collector, acquiring only the minimum necessary 'y' occurrences.

##  Boundaries
- **Description:** Boundaries are akin to hallowed thresholds, ensuring your pattern's presence within the sanctified confines of words.
- **Examples:** `\bword\b` declares, "Seek the entirety of the lexicon's entry labeled 'word,'" while `\Bword\B` commands, "Discern 'word,' but only when it stands in solitude, not entwined with neighboring letters."

##  Back-references
- **Description:** Back-references are the echoes of the past, resonating patterns from earlier passages, creating a harmonious symphony of repetition.
- **Example:** `(\w+) \1` orchestrates a poetic recurrence, like witnessing the refrain of a familiar melody, ensuring the duplicity of a word, such as 'hello hello' or '123 123.'

##  Look-ahead and Look-behind
- **Description:** Look-ahead and look-behind are the clairvoyant seers, peering into the future and reflecting on the past before bestowing the gift of recognition upon a pattern.
- **Examples:** `foo(?=bar)` foresees, "Locate 'foo,' but only if it anticipates the imminent arrival of 'bar.'" `(?<=\$)\d+` reflects, "Discern digits, but only if they gracefully follow the heraldry of a dollar sign."


## Author
Mohamed Amin - GitHub link
https://github.com/Mohamedamin141/RegexTutorial
