A simple static website that provides an alternative interface to the official [TDK](https://sozluk.gov.tr/) Turkish dictionary.

I've written this for use with dictionary programs that expect templated URL patterns like ~~GoldenDict~~ [1],
as the TDK website no longer provides that.

## Related

Also see my other projects related to Turkish:
- https://github.com/abdnh/tdk
- https://github.com/abdnh/anki-trdict

## TODO

- Use custom html elements to show response data: https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements
- show sound buttons
- show compound nouns and expressions
- a more fancy interface maybe

## Notes

[1]: GoldenDict is too ancient to support relatively modern JavaScript. I had a go at using Babel to transpile the website
to something that can be understood by GoldenDict, but I had no success so far. I ended up converting the dictionary data to the DICT format and using it with GoldenDict; see [tdk2dict](https://github.com/abdnh/tdk2dict/).
