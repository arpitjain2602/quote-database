# Quote Database for Chrome Extension

This repository hosts a collection of quotes categorized by topics such as **"Tech"**, **"Product Management"**, and **"AI"**, along with a **"Random"** category for general wisdom. This data powers a Chrome extension that provides daily inspiration.

## Data Structure

The quotes are stored in `quotes.json` as an array of JSON objects. Each object represents a single quote and follows this structure:

{
  "quote": "The actual quote text goes here.",
  "author": "Name of the author",
  "categories": ["Category One", "Category Two"]
}

- quote (string): The text of the quote.
- author (string): The person or entity attributed to the quote.
- categories (array of strings): A list of categories that the quote belongs to.

### Accepted Categories

- Tech
- Product Management
- AI
- Random

A quote can belong to multiple categories. Please use the exact category names.

---

## How to Contribute

We welcome contributions of new quotes to expand our database!

### Steps to Contribute

1. Fork this repository.
2. Clone your forked repository to your local machine.
3. Create a new branch for your contributions:
   git checkout -b add-new-quotes
4. Edit quotes.json:
   - Open the file.
   - Add your new quote(s) to the array, ensuring they follow the specified JSON structure.
   - ✅ Make sure your JSON remains valid after your edits (use an online JSON validator if unsure).
5. Commit your changes with a clear message:
   git commit -m "Add new tech and AI quotes"
6. Push your branch to your fork:
   git push origin add-new-quotes
7. Create a Pull Request from your fork to the main repository.

---

Your pull request will be reviewed, and if it meets the guidelines, it will be merged.

Thank you for helping us grow this collection!
