# Contribution Guidelines
Please ensure your pull request adheres to the following guidelines:

* Please search previous suggestions before making a new one, as yours may be a duplicate.
* Enter a meaningful pull request description.
* Please make an individual commit for each suggestion in a pull request.
* Use the following format for an extension. The name is bold and is not a link. The description stays on that line. Each link is its own nested bullet, indented with two spaces so GitHub renders it as a sub-list:

  ```
  * **Extension Name** - Short description.
    * Website: [example.com](https://example.com)
    * Chrome Web Store: [Chrome Web Store](https://chromewebstore.google.com/detail/EXTENSION_ID)
  ```

  * An entry with only one link gets a single nested bullet.
  * A GitHub repository can stand in as the Website when that is the extension's home and it has no separate website. Keep any extra link the entry already has (for example Source or Firefox Add-ons) as its own labeled nested bullet.
  * Only add a URL you have opened or requested successfully. A website should respond successfully, and a Chrome Web Store URL should be a live listing (not an "item not available" page). If you cannot find the missing link, keep the existing one.
* New categories, or improvements to the existing categorisation, are always welcome.
* Keep descriptions short and simple.
* End all descriptions with a full stop/period.
* Check your spelling and grammar.
* Make sure your text editor is set to remove trailing whitespace.

Thank you for your suggestions!

## Pull request format

Every pull request must include all of these sections:

1. Screenshots: required for UI changes and visual fixes. Otherwise write `Not applicable: <reason>`.
2. Recordings: required for interaction changes, animations, and flows. Otherwise write `Not applicable: <reason>`.
3. What changed: a description in very simple language.
4. Before / After: what the function or behavior was before, and what it is now.
5. Alignment: why this task was chosen and prioritized over other work.

Keep any other required sections, such as Changelog (when this repo's changelog tooling reads `## Changelog`) and Testing.

Use `.github/pull_request_template.md` when opening a pull request. Do not merge a pull request that is missing any of these sections.

