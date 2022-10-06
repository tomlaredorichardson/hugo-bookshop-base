# Hugo Gallery Starter

A basic hugo page with Bookshop functionality and a gallery page.

## Getting Started

In your local development environment, run:

```
npx @bookshop/browser
```

## Creating a new bookshop component

To create a new bookshop component

```
npx @bookshop/init --component <name>
```

## Troubleshooting

If encountering this error:

```
ERROR 2022/04/18 21:14:00 render of "taxonomy" failed: "/Users/yourname/yourrepo/layouts/_default/baseof.html:8:31": execute of template failed: template: _default/list.html:8:31: executing "_default/list.html" at <partial "bookshop_scss" .>: error calling partial: partial "bookshop_scss" not found
```

Try run

```
hugo mod clean
```

in your local Hugo/Bookshop repo. The command deletes the project’s existing Hugo Modules cache.
