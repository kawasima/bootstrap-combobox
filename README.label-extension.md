Bootstrap combobox (label extension)
====================================

This extension enable to display the label and search the option tag's text,when the label attribute was set in the option tag.

## Example

Define the option as follow.

    <select class="combobox">
      <option label="Tokyo" value="01">Tokyo Tokio</option>
      <option label="Kanagawa" value="02">Kanagawa Yokohama</option>
      <option label="Chiba" value="03">Chiba Shimousa</option>
    </select>

If you type "Tokio" as belows, "Tokyo" was shown as candidates.

    [Tokio ▼]
    |Tokyo   |


