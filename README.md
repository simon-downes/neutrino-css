# Neutrino CSS

## What

My own CSS framework largely based on the excellent [Pico CSS](https://github.com/picocss/pico).

## Why

Of all the lightweight CSS frameworks Pico is my favourite, but there's a few
things I didn't like and a few things it didn't have that I wanted.

Also I get to stretch my CSS muscles a little bit...

## How

- Clone the repo
- Make sure you have [Sass](https://sass-lang.com/) installed
- Run `build.sh`

## Key Changes

A none-exhaustive list of changes away from Pico:
- The following variables and associated conditionals have been removed
  and the functionality explicitly either included or excluded:
  - `$enable-grid` - included
  - `$enable-transitions` - included
  - `$enable-important` - included
  - `$enable-viewport` - included
  - `$enable-class-container` - included
  - `$enable-viewport` - included
  - `$enable-semantic-container` - excluded
  - `$enable-responsive-typography` - excluded

## Browser Support

Who knows ¯\\_(ツ)_/¯ - it works well enough for me... 🤣

# License

Licensed under the [MIT License](LICENSE.md).
