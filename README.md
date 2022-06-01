A simple static website that provides an alternative interface to the official [TDK](https://sozluk.gov.tr/) Turkish dictionary.

I've written this for use with dictionary programs that expect templated URL patterns like GoldenDict,
as the TDK website no longer provides that.

## Notes about usage with GoldenDict

The current builds of [GoldenDict](https://github.com/goldendict/goldendict) as of June 2022 are too ancient to support relatively modern JavaScript. I had a go at using Babel to transpile the website to something that can be understood by GoldenDict, but had no success so far.
The [xiaoyifang/goldendict](https://github.com/xiaoyifang/goldendict) fork uses WebEngine and can display the site fine though.
If you need to use the official build nevertheless,
I converted the dictionary data to a DICT file that can be used with it; see [tdk2dict](https://github.com/abdnh/tdk2dict/).

## Related

Also see my other projects related to Turkish:
- https://github.com/abdnh/tdk
- https://github.com/abdnh/anki-trdict

## TODO

- Use custom html elements to show response data: https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements
- show sound buttons
- show compound nouns and expressions
- a more fancy interface maybe
