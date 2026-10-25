# Jira Wiki Markup Live Preview

**Live site: https://soniji-tanishque33.github.io/jira-wiki-markup-preview/**

Write Jira wiki markup on the left and see how it will look in Jira on the right, updating as you type.

It is a single HTML file. There is no server, no sign-up and no tracking. Everything runs in your browser and **nothing you type is uploaded anywhere**.

## What it does

- **Live preview** of Jira wiki markup, written to match the HTML that Jira Server / Data Center produces.
- **Formatting supported:** headings, bold / italic / underline / strikethrough / monospace / superscript / subscript / citation, colours, nested lists (`*`, `#`, `-`), tables, links, anchors, images, block quotes, `{quote}`, `{panel}`, `{noformat}`, `{code}`, horizontal rules, escapes and emoticons.
- **Code highlighting** for `{code:lang}` blocks: Java, JavaScript, JSON, XML/HTML, SQL, Python, Bash, YAML and CSS.
- **Toolbar** that inserts the markup for you, plus shortcuts: Ctrl+B, Ctrl+I, Ctrl+K.
- **Copy** button for the raw text, and auto-save in your browser so a refresh does not lose your work.
- **Synced scrolling**, a draggable divider, and an optional "Wrap code" switch.
- **Sample** button that loads text covering every syntax.

## Good to know

- It targets the classic **wiki markup** (Jira Server / Data Center, and Cloud with the legacy editor). It does not cover the newer Jira Cloud editor.
- Things that cannot be reproduced outside Jira show as placeholders: attachments, attached images and `[~user]` mentions.
- Issue keys such as `ABC-123` are only linked if their project key is listed in the **Issue keys** box. This matches Jira, which only links keys that exist. Set **URL** to your own Jira address to make those links point there.
- It is a preview, not Jira itself. Small differences can exist, so check important text in Jira's own preview.

## Run it locally

Download `index.html` and open it in any browser. It works offline.

## Contributing

Bug reports and pull requests are welcome. If a piece of markup renders differently from real Jira, open an issue with the markup and what Jira shows. Please do not paste confidential text into issues.

## License

[MIT](LICENSE)
