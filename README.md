# 💚 GRAYBYTE BYTE SNIPER 💚


__GRAYBYTE BYTE SNIPER is a web-based tool for extracting, processing, and manipulating URLs or text input. Built with HTML, CSS, and JavaScript, it features a cyberpunk interface with a particle background, glitch animations, and a responsive design. Ideal for security researchers, data center admins, or text manipulation enthusiasts, it extracts URLs, removes duplicates, transforms text, and more.__

## 🔥 Features
- **Extract URLs from raw text with deduplication**
- **Manipulate text (uppercase, lowercase, title case, shuffle, etc.)**
- **Add custom prefixes/suffixes to lines**
- **Filter lines based on keywords or character counts**
- **Copy results to clipboard**
- **Responsive design with neon animations and particle canvas**



## Button Functions and Examples

**URL-X (Extract URLs) Description:** Extracts all URLs from input text, removes duplicates (case-insensitive), and applies optional prefixes/suffixes from Before and After fields. Example:
Input: Visit https://example.com and http://test.com Also check https://EXAMPLE.com/path and test.com
Before: https://
After: /admin
Output: https://example.com/admin https://test.com/admin
Summary: Total URLs Found: 4, Duplicates Removed: 2, Unique URLs: 2

**N-DUP (Remove Duplicates) Description** : Removes duplicate lines from input text (case-sensitive) and applies optional prefixes/suffixes. Example:
Input: apple banana apple orange
Before: [
After: ]
Output: [apple] [banana] [orange]
Summary: Total lines: 4, Unique lines: 3

**RM / DUP (Remove Slash and Deduplicate) Description**: Extracts URLs, removes everything after the first slash (keeping only the domain), removes duplicates (case-insensitive), and applies prefixes/suffixes. Example:
Input: https://example.com/path/to/page http://example.com/other https://test.com
Before: www.
After: .org
Output: www.example.com.org www.test.com.org
Summary: Total URLs Found: 3, Duplicates Removed: 1, Unique Domains: 2
RM-CON (Remove Containing) Description: Removes lines containing the keyword specified in the Keyword field and applies prefixes/suffixes to remaining lines. Example:
Input: https://example.com/wp-content https://test.com https://example.com/admin
Keyword: /wp-content
Before:
After:
Output: https://test.com https://example.com/admin
Summary: Total lines: 3, Lines removed: 1, Remaining lines: 2

**RM-NON (Remove Non-Containing) Description**: Keeps only lines containing the keyword specified in the Keyword field and applies prefixes/suffixes. Example:
Input: https://example.com/wp-content https://test.com https://example.com/admin
Keyword: /wp-content
Before:
After:
Output: https://example.com/wp-content
Summary: Total lines: 3, Lines removed: 2, Remaining lines: 1

**RMN-NUM (Remove N Characters) Description**: Removes the first N characters from each line, where N is specified in the Number field, and applies prefixes/suffixes. Example:
Input: https://example.com https://test.com
Number: 8
Before:
After:
Output: example.com test.com
Summary: Processed lines: 2

**UPPE (Uppercase) Description**: Converts all lines to uppercase and applies prefixes/suffixes. Example:
Input: apple Banana ORANGE
Before:
After:
Output: APPLE BANANA ORANGE
Summary: Processed lines: 3

**LOWE (Lowercase) Description**: Converts all lines to lowercase and applies prefixes/suffixes. Example:
Input: APPLE Banana ORANGE
Before:
After:
Output: apple banana orange
Summary: Processed lines: 3

**CAPE (Capitalize) Description**: Converts all lines to title case (first letter of each word capitalized) and applies prefixes/suffixes. Example:
Input: apple pie banana split orange juice
Before:
After:
Output: Apple Pie Banana Split Orange Juice
Summary: Processed lines: 3

**Shuffle Description**: Randomly shuffles all lines and applies prefixes/suffixes. Example:
Input: line1 line2 line3
Before:
After:
Output (order varies): line3 line1 line2
Summary: Total Lines Processed: 3

**Copy Results Description**: Copies the content of the Processed Output textarea to the clipboard. Example:
Output Textarea: https://example.com https://test.com
Action: Click Copy Results
Result: Text is copied to clipboard, notification says “Results copied!” (or “Nothing to copy!” if empty)
Additional Features

**Text To Add Before/After**: Add custom strings before or after each line (e.g., https:// before, /admin after).
**Keyword Field**: Used by RM-CON and RM-NON to filter lines based on a keyword (e.g., /wp-content).
**Number Field**: Used by RMN-NUM to specify how many characters to remove from the start of each line.
**Summary**: Displays stats like total lines, duplicates removed, or remaining lines after processing.
**Notifications**: Green for success (e.g., “Extraction complete!”), red for errors (e.g., “Input is empty!”).


# 👨🏻‍💻 FOR MORE INFORMATION AND SUPPORT 👨🏻‍💻

[TELEGRAM](https://t.me/rex_cc) | 
[FACEBOOK](https://www.facebook.com/graybyt3) | 
[X](https://x.com/gray_byte) | 
[INSTAGRAM](https://www.instagram.com/gray_byte)
