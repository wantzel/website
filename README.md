# wantzel.com

The website for [Wantzel](https://github.com/wantzel/wantzel), served by GitHub Pages
straight from this repository. A push to `main` is the deployment; there is no build step
and no hosting to maintain.

## What belongs here

The sixty-second version: what problem Wantzel solves, what is different about it, twenty
lines of code, how to install it, what you can run straight away. Everything longer lives
in the compiler repository and is linked, not copied.

**The language reference is not mirrored here.** The original wins, and a copy drifts.

## Layout

| file | what it is |
|---|---|
| `index.html` | the page; hand-written, no generator |
| `CNAME` | the custom domain, read by GitHub Pages |

## Working on it

Open `index.html` in a browser — there is nothing to compile. The page is one file with
its styles inline, it carries no JavaScript and no external requests, and it works in
light and dark.

## License

MIT, the same as the compiler.
