# Multilingual-Mode

- [Available Languages](#available-languages)
- [Configure Languages](#configure-languages)
- [Translation File Example](#translation-file-example)

## Available Languages

This theme supports the following languages:

- Albanian
- Arabic
- Bengali
- Brazilian Portuguese
- Catalan
- Czech
- German
- English
- Spanish
- Finnish
- French
- Hebrew
- Hindi
- Hungarian
- Indonesian
- Italian
- Japanese
- Korean
- Malay
- Nepali
- Dutch
- Polish
- Romanian
- Russian
- Serbian
- Serbian (Latin)
- Slovak
- Swedish
- Turkish
- Simplified Chinese
- Taiwan Chinese
- Urdu

## Configure languages

Go to [this Hugo documentation page](https://gohugo.io/content-management/multilingual/#configure-languages) to configure one or multiple languages for your website.

## Translation File Example

```toml
[categories]
	one = "category"
	other = "categories"

[tags]
	one = "tag"
	other = "tags"

[series]
	one = "series"
	other = "series"

[authors]
	one = "author"
	other = "authors"

[posts]
	other = "posts"

[reading_time]
	one = "One-minute read"
	other = "{{ .Count }}-minute read"

[page_not_found]
	other = "Page Not Found"

[page_does_not_exist]
	other = "Sorry, this page does not exist."

[head_back]
	other = "You can head back to the <a href=\"{{ . }}\">homepage</a>."

[licensed_under]
	other = "Licensed under"

[powered_by]
	other = "Powered by"

[see_also]
	other = "See also in"

[note]
	other = "note"

[tip]
	other = "tip"

[example]
	other = "example"

[question]
	other = "question"

[info]
	other = "info"

[warning]
	other = "warning"

[error]
	other = "error"

[link_to_heading]
	other = "Link to heading"

[entry_toc]
	other = "Table of Contents"
```
