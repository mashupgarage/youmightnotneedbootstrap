# you-might-not-need-bootstrap

> Substitutes for things you usually will do with Bootstrap

## Tooltips

Consider [hint.css](https://kushagragour.in/lab/hint/). It's a pure HTML/CSS solution:

```html
<a
  href='...'
  class='submit-button hint--bottom'
  aria-label='Please check your entries before submitting!'>
  Submit
</a>
```

## jQuery

Consider not using jQuery. Here's how you can do it with DOM:

- http://youmightnotneedjquery.com/
- https://github.com/rstacruz/cheatsheets/pull/145

## Sticky headers

Consider [headroom.js](http://wicky.nillia.ms/headroom.js/) to make sticky headers.

![headroom](https://user-images.githubusercontent.com/74385/35092295-e697c4da-fc79-11e7-9d64-691980884a5e.gif)

## Parallax

Consider [rellax](http://yarn.pm/rellax).

- https://github.com/dixonandmoe/rellax
- https://dixonandmoe.com/rellax/

## Datepicker

Consider:

- ~~[Pikaday](https://dbushell.com/Pikaday/)~~
- ~~[rome](https://github.com/bevacqua/rome)~~
- [flatpickr](https://flatpickr.js.org/)

## Grids

Consider:

- [Jeet](http://jeet.gs/) lets you build grids with Sass
- [Pure.css](https://purecss.io/grids/) has grids. No Sass support though
- ...consider writing your own classes as needed. Grids are easy to do with Flexbox!

## Ajax

Use `window.fetch` instead of jQuery's `$.get` or `$.ajax`.

- http://devhints.io/js-fetch

## Toast notifications

Consider:

- https://yarn.pm/react-toastify

## Moment.js

Moment.js is huge, bloated, and not very friendly to functional approaches. Consider instead:

- https://date-fns.org/

## Icons

Consider:

- http://yarn.pm/ionicons-inline

## Modal

Consider:

- [tingle](https://robinparisi.github.io/tingle/)
- [reach-dialog](https://ui.reach.tech/dialog) _(React)_

## React components

To use React components in your non-React site, consider:

- [remount](https://github.com/rstacruz/remount)
