# Gamma-Spectrum-Database

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/OpenGammaProject/Gamma-Spectrum-Database?style=flat-square) ![GitHub](https://img.shields.io/github/license/OpenGammaProject/Gamma-Spectrum-Database?style=flat-square) ![Website](https://img.shields.io/website?url=https%3A%2F%2Fgammadb.nuclearphoenix.xyz&style=flat-square) ![GitHub deployments](https://img.shields.io/github/deployments/OpenGammaProject/Gamma-Spectrum-Database/github-pages?label=GitHub%20%20Pages&style=flat-square)

Open and comprehensive database of (common) gamma-ray emitting radioisotopes for gamma-spectroscopy built with Jekyll and [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/).

All the spectrum files that are embedded into the site can be found in [/assets/spectra/](/assets/spectra/). Entirely new pages must also be added to the navigation bar ([_data/](_data/))!

The corresponding Jekyll pages for all the isotopes can be found in [/collections/_spectrum/](/collections/_spectrum/).

Blog posts for updates and the kind are in [/collections/_posts/](/collections/_posts/) and static pages are in [/collections/_pages/](/collections/_pages/).

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J61GLR3G)

## Contributing

Everybody is welcome to participate and submit spectra or fix mistakes, etc.

There are multiple ways to do so, here's a rough guideline:

- Issue: Enhancements, Bugs, Mistakes in the text, all kinds of other issues (duh), adding a new spectrum
- Pull Request: Fixes with the code, typos, adding a new spectrum directly with all the files
- Discussion: General discussions about the database, radiation, gamma spectroscopy, simple questions, etc.

If you're not sure where to post your request, just choose any of the above and we'll figure it out ;)

**A small guide to add a new spectrum to the database can be found in this [post](https://gammadb.nuclearphoenix.xyz/jekyll/update/ready-for-action/#contributing)!**

## Copyright

This repository, the code and all the spectra are licensed under GPLv3, therefore you are allowed to do basically anything with it as long as it does not violate the license. This, however, does **not** apply to any of the favicons and logos, basically all the branding -- so please **do not** reuse them for your own purposes. Thanks!

Note to self: Build and deploy locally using `bundle exec jekyll serve --force_polling --livereload`
