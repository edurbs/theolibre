# TheoLibre

**TheoLibre** is a source-available desktop application for reading `.jwpub`
publications on Linux. It is written in Java and JavaFX.

TheoLibre is an independent project. It is not affiliated with, sponsored by,
or endorsed by Watch Tower Bible and Tract Society of Pennsylvania,
Watchtower Bible and Tract Society of New York, JW.ORG, or JW Library.
"JW Library" and "JW.ORG" are trademarks of their respective owners, used
here solely to identify the file format TheoLibre reads.

## Status

In development. The application source is being prepared for publication
and will be released in this repository.

## Features

- Open and read `.jwpub` files you already have — no account required
- Library catalog and Home view across all your publications
- Full-text search, inside one publication or across the whole library
- Bible reading with book/chapter navigation
- Study sidebar: scripture citations, footnotes, publication cross-references
- Media gallery with image viewer and video playback
- Dark mode, adjustable font size, reading-position restore, history

## Media and network use

Most media ships inside the `.jwpub` file and is extracted and played
locally. Videos are normally not embedded, so the gallery offers a
**Download** button: one explicit tap downloads exactly one video, directly
from the publisher's CDN to your device. Nothing is ever fetched in the
background, in batch, or through TheoLibre — the project runs no servers
and hosts no content.

## Building

Requires Java 26+ (a JavaFX build). The project builds with Gradle:

```bash
./gradlew build      # build + tests
./gradlew :app:run   # run from source
```

## Legal

- TheoLibre contains no JW Library code and bundles no publications, media,
  or other copyrighted content. You supply your own files and are
  responsible for using them in accordance with applicable copyright and
  the [JW.ORG Terms of Use](https://www.jw.org/en/terms-of-use/) and
  [JW Library Terms of Use](https://www.jw.org/en/terms-of-use-jwlibrary/).
- Support for the `.jwpub` format was implemented independently, from
  observation of the file format. Format support implies no affiliation
  with, endorsement by, or ownership of the format or its content.

## License

The source code is licensed under the **PolyForm Noncommercial License
1.0.0** — free for personal and noncommercial use. See [`LICENSE.md`](LICENSE.md).
Third-party dependencies remain under their own licenses; see [`NOTICE.md`](NOTICE.md).

See also: [`CONTRIBUTING.md`](CONTRIBUTING.md) · [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md)
