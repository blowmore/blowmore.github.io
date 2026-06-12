# blowmore.org

Jekyll source for `blowmore.org`.

## Testing locally

### Requirements

Install Jekyll and verify:

```sh
jekyll -v
```

### Build

Build the site into `_site/`:

```sh
jekyll build
```

Stricter build that fails on malformed front matter:

```sh
jekyll build --strict_front_matter
```

### Serve

Run development server:

```sh
jekyll serve
```

Then open:

```text
http://127.0.0.1:4000/
```

If you want browser auto-refresh and the LiveReload port is free, use:

```sh
jekyll serve --livereload
```