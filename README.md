# Clickable Mentions

*A fork of [paul999/mention](https://github.com/paul999/mention) with common-sense improvements -_-*

For reasons unfathomable, basic features like creating a link to a mentioned user's profile are not implemented upstream.

For reasons *beyond* unfathomable, I am supporting this even though I don't care about phpBB.

Yeah, yeah – you're welcome.

## Installation

Copy these files to `phpBB3/ext/paul999/mention`. Be sure to use the correct version of the extension for your version of phpBB.

### phpBB 3.2

Use v1 of this extension:
```bash
git clone -b v1 https://github.com/ftc2/phpbb-clickable-mentions.git /path/to/phpBB3/ext/paul999/mention
```

### phpBB 3.3

Use v2 of this extension:
```bash
git clone -b v2 https://github.com/ftc2/phpbb-clickable-mentions.git /path/to/phpBB3/ext/paul999/mention
```

## Upgrading

```bash
cd /path/to/phpBB3/ext/paul999/mention
git pull
```

If you upgrade from phpBB 3.2 -> 3.3, I believe switching from v1 to v2 of the extension should "just work".

```bash
cd /path/to/phpBB3/ext/paul999/mention
git pull
git switch v2
```

## License

[GPLv2](license.txt)
