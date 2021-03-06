# Changelog

## v1.2.0
- B-Lists can now be used with `<ul>` and `<li>`

## v1.1.3
- added a minified version of B-Lists (thanks Freeformatter for making me use their CSS minifier)
- added a text-color class (also with 15 color schemes)
- added effects for all links in section.b-lists

## v1.1.2

- changed the `padding-right` in all list items from 200px to 250px
- changed the width of the left border in all list items from 2px to 2.5px
- removed the `transition-timing-function` in box-shadow because `ease` is the default option

## v1.1.1

- added support for older Mozilla Firefox and Google Chrome versions for the `transition` property
- added a line-height property to all headings in `section.b-lists`
- made a media query for the border between each list so that the border would not overlap on mobile
- adjusted `box-shadow` sizes by 2px
- adjusted `padding` in `.row`
- adjusted `padding-right` in all list items so that the hoverable area would be bigger
- changed `transition-duration` of `box-shadow` from 0.25s to 0.2s
- changed `transition-timing-function` of `box-shadow` from `ease-in-out` to `ease`
- removed `margin-top` for each table row
- removed `font-size` in item.lg because it will make everything have a 24px font-size

## v1.1.0

- changed `border-left` to `box-shadow` for better consistency (making `b-lists.css` work properly on IE10 and above only)
- fixed some bugs

## v1.1.0-beta

- added a [demo page](http://rawgit.com/1nonlyxtian/b-lists/master/test.html).
- added hoverable border effects in the list items (beta testing; was inspired by Edmodo groups list)
- fixed some bugs

## v1.0.0

- initial release
