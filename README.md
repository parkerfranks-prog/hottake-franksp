# Hot Take

One screen. One opinion. Yours.

A Hot Take is deliberately small: one headline, one argument, one thing you
think that other people might not. It is not the big project — that is Top 6,
and it comes later. This is where you make the mistakes first, on a page small
enough that a mistake is cheap.

Pick something you actually believe. A page arguing nothing looks fine no matter
what you do to it, which means you learn nothing from it.

## What is already done, and what is not

**Wired for you:** the doctype, the meta tags, Tailwind, daisyUI, and a
stylesheet of your own that loads last so it wins ties. You install nothing.

**Not done:** the page. You build it in class, together, in four stages. That is
the point — this starter is nearly empty on purpose.

## Start here

1. Open `index.html` with **Live Server**. Not by double-clicking — see Unit 4
   for why `file://` is not a website.
2. You should see an unstyled heading and one line of text. That is correct.
   It means the wiring works and the design has not started.
3. Change `data-theme="nord"` on the `<html>` tag to something else. Five
   seconds, and it is the fastest way to find the mood you want. Try
   `synthwave`, `forest`, `cupcake`, `dracula`, `retro`, `autumn`, `lofi`,
   `night`.
4. Commit as you go. Push at least once a session — a commit is local until you
   push it, and **pushed is submitted**.

## The four stages

Each one is marked with a comment in `index.html`, in order.

| Stage | What you add | Objective |
|---|---|---|
| One | A container: a width ceiling, centred, with padding | `WD3.1.A`, `WD3.1.B` |
| Two | Container → row → columns. Three reasons as daisyUI cards | `WD3.2.A`, `WD3.4.A` |
| Three | One column on a phone, three from `md:` up | `WD3.3.A`, `WD3.3.B` |
| Four | One media query, written by hand, in `styles.css` | `WD3.3.C` |

Stage three **edits** stage two rather than adding to it. That is normal and it
is worth noticing: making something responsive is usually a change to what you
already wrote, not a second copy of it for phones.

## Check your own work before you hand it in

Tick it yourself first — auditing a page against a written spec is a graded
skill in its own right (`WD3.B`), and it is much better to find these than to
have them found.

### Structure

- [ ] Every section is the element it should be — `header`, `main`, `footer` —
      not a `div` wearing a class.
- [ ] The headings outline the page. Read `h1`, `h2` alone, in order: does it
      make sense? No levels skipped.
- [ ] Exactly one `h1`, and it is the take itself.
- [ ] The three reasons are **parallel**: same shape, same kind of content,
      similar length.

### Layout

- [ ] A container caps the width. Text does not run edge to edge on a laptop.
- [ ] One column at 380px, three from `md:` up. Check all three widths —
      narrow your browser window until it is phone-shaped.
- [ ] Nothing scrolls sideways at 380px.
- [ ] The column split you chose serves your content, and you can say why.
      "It looked better" is a starting point, not an answer.

### Design

- [ ] The theme is not `nord`, or you can say why `nord` was genuinely right.
- [ ] Your palette is recorded as a comment block at the top of `styles.css`,
      with a mood sentence and a job for each colour.
- [ ] Two type faces at most: one for headings, one for body.
- [ ] Body text against its background is at least **4.5:1**. Check it — do not
      guess.

### Content and credit

- [ ] The take is yours. Search the file for `Gym class` — if it is still
      there, you have not started.
- [ ] Every piece of placeholder text is gone. Search for `______` too.
- [ ] Every image has `alt` text that says what the image is FOR. Decorative
      images take an empty `alt=""`.
- [ ] Every image has its creator, source and licence recorded in the footer.
      If you cannot write that line, you are not allowed to use it.
- [ ] If you used AI to generate any part of this, say so and say which part.
      That is the professional norm and it costs you nothing.

### Handing in

- [ ] It works from a fresh clone — no absolute paths to your own disk.
- [ ] Your commit messages say what changed and why.
- [ ] It is **pushed**.

## Credits

The component classes here are [daisyUI](https://daisyui.com/) by Pouya
Saadeghi, MIT licensed, on top of [Tailwind CSS](https://tailwindcss.com/),
also MIT. Both are loaded from a CDN by the three tags in `index.html`.

Nothing in this starter is stock photography or borrowed copy, so there is
nothing else to credit — yet. That changes the moment you add an image, and the
footer is where the credit goes.
