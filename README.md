# apko-pluto-with-file-via-apk

Container image, built using [apko](https://github.com/chainguard-dev/apko/),
that contains additional files. As `apko` does not allow adding files directly,
those must be packaged in a `apk` and added during the build process.

## Licensing

The container image contains software packages that are direct or transitive
dependencies. As pluto is the main component, I have taken its [license
Apache-2.0](https://github.com/FairwindsOps/pluto/blob/master/LICENSE) as the
license for this container image.
