# aport-builds
Robots for keeping my Alpine packages up to date

When a new version of something I've packaged gets released, there are a few things to do:

- Download the new version
- Build it and run the tests
- Update the version number in `APKBUILD` for the package
- Make sure the package builds correctly
- Open a new MR against the [aports repository](https://gitlab.alpinelinux.org/alpine/aports) to update the package

It's tedious, but it's also very predictable. These GitHub Actions workflows automate the entire process.

I wrote about how it works [here](https://www.acj.sh/2019/10/13/the-robots-are-coming-for-your-maintainership.html).