---
layout: list
image: /assets/img/blog/hydejack-9.jpg
description: >
  Overview of recent research projects
  with a focus on personal sites that are meant to impress.
hide_description: true
redirect_from:
  - /download/
---

# Recent Projects

## ASAS-SN Eclipsing Binaries

Eclipsing binaries are fundamental tools to determine the physical parameters of stars that are effectively in isolation. By modeling the eclipsing binary light curve and the radial velocities, the masses and radii of stars across the HR diagram can be determined. Almost every photometric survey has detected tens of thousands of eclipsing binaries, and ASAS-SN with more than 150,000 eclipsing binaries classifications. Astronomers interested in smaller subsets of systems, such as extremely eccentric binaries or systems with red giant primaries, can search through these catalogs to identify targets for analysis. In this work we bridged the gap between these two steps by providing model fits for more than 30,000 detached eclipsing binaries using ASAS-SN light curves.

We used PHOEBE, a versatile modeling tool capable of handling all types of binary systems, to optimize the ASAS-SN light curves. We visually inspected all targets to improve model fits and to identify systems that require more complex models. Once all of the binary parameters were determined, we explored the parameter distributions and used Gaia colors and magintudes to place the systems on the color-magnitude diagram. 

All of the binaries are available online at [asas-sn.osu.edu/binaries](https://asas-sn.osu.edu/binaries). The interactive format allows users to search for systems with specific parameters. The individuial light curves and fits are available for each target, and the entire database can be downloaded for further analysis. 

[Paper I ADS Link](https://ui.adsabs.harvard.edu/abs/2022MNRAS.517.2190R/abstract)
[Paper II ADS Link](https://ui.adsabs.harvard.edu/abs/2023MNRAS.520.2386R/abstract)
[Paper III ADS Link](https://ui.adsabs.harvard.edu/abs/2023MNRAS.523.2641R/abstract)

## ASAS-SN Ellipsoidal Variables

By studying black holes we stand to learn more about the underlying distributions of compact objects as well as late-stage evolution of massive stars. Stellar mass black holes are typically studied in interacting X-ray binary systems or during gravitational wave mergers. Interacting and merging systems, however, represent a narrow range of possible binary configurations. In order to better understand black holes, we should search for the largely unstudied population of non-interacting black holes.

Non-interacting stellar mass black holes are typically searched for using radial velocity observations. If we can identify a star with large-amplitude periodic radial velocity variations, we can deduce the mass of the unseen companion. But we could also start the search by looking for ellipsoidal variable stars. Ellipsoidal variables are stars that have been tidally distorted by a companion such that they have a teardrop shape. By modeling ellipsoidal variable light curves we can place some estimates on the mass of the companion. We use ASAS-SN light curves to identify 369 candidates for ellipsoidal variability.

By combining estimates of the photometric primaries mass and radii with the ASAS-SN light curves, we derive minimum companion masses for our ellipsoidal variable candidates. Despite the conservative nature of this estimation, our minimum companion mass offers a useful metric by which to sort ellipsoidal variables in the search for non-interacting compact objects. We are now conducting radial-velocity follow-up of our most promising black hole candidates. 

[ADS Link](https://ui.adsabs.harvard.edu/abs/2021arXiv210502242R/abstract)


## NICER Millisecond Pulsars

Neutron stars are the site of some of the most extreme physics in the universe. By observing millisecond pulsars (MSPs) -- neutron stars rotating hundreds of times per second -- we stand to learn more about high energy emission and degenerate matter. The Neutron Star Interior Composition Explorer (NICER), launched in 2017 and stationed on the International Space Station, observes the X-ray emission from these MSPs. In this work, we used two years of NICER data on three non-thermal millisecond pulsars. 

These three pulsars have been observed by almost every X-ray telescope that has existed. What can we do with NICER to learn more about these objects? We took advantage of NICER's high-precision timing capabilites to perform two analysis techniques: energy dependent pulse profiles and phase-resolved spectroscopy. 

For pulsar PSR B0218+4232 we found that the two peaks in the profile moved closer together in phase at higher energies. While profile evolution is a common phenomenon in radio observations, this is the first time profile evolution has been observed at high energies for this source. For another source, PSR B1937+21, we find that the power law differs between the two profile pulses, a feature not observed in the other two sources. 

The three pulsars included in this analysis have been traditionally grouped together as non-thermal MSPs with narrow peaks. With NICER observations we showed that the subtle differences between their X-ray emission can be described with the current sheet model of pulsar emission.

[ADS Link](https://ui.adsabs.harvard.edu/abs/2020ApJ...892..150R/abstract)

## Variable White Dwarfs with GALEX

The vast majority of stars, including our Sun, will end their lives as white dwarfs. In this work, we complied the largest survey of ultraviolet white dwarf observations to search for variability. We used a system of weighted metrics to comb through the GALEX lightcurves and identify white dwarf pulsators and eclipsing binaries. We show that even with a short observation baseline (<30min) we can identify variability for sources as faint as G=20mag. In total we detect 40 new pulsators, including four DBV pulsators. We also find eight new eciplising systems. 

Since we don't detect any transiting planetary debris we perform an injection/recovery procedure to derive an occurence rate. We find that the 3 sigma maximum occurence rate of WD transiting objects is <= 0.5 %.

[ADS Link](https://ui.adsabs.harvard.edu/abs/2019MNRAS.486.4574R/abstract)

[Astrobites](https://astrobites.org/2018/12/19/galex_wds/)



[blog]: /
[portfolio]: https://hydejack.com/examples/
[resume]: https://hydejack.com/resume/
[download]: https://hydejack.com/download/
[welcome]: https://hydejack.com/
[forms]: https://hydejack.com/forms-by-example/

[features]: #features
[news]: #build-an-audience
[syntax]: syntax-highlighting
[latex]: #beautiful-math
[dark]: https://hydejack.com/blog/hydejack/2018-09-01-introducing-dark-mode/
[search]: https://hydejack.com/#_search-input
[grid]: https://hydejack.com/blog/hydejack/

[lic]: LICENSE.md
[pro]: licenses/PRO.md
[docs]: docs/README.md
[ofln]: docs/advanced.md#enabling-offline-support
[math]: docs/writing.md#adding-math

[kit]: https://github.com/hydecorp/hydejack-starter-kit/archive/v9.0.3.zip
[src]: https://github.com/hydecorp/hydejack
[gem]: https://rubygems.org/gems/jekyll-theme-hydejack
[buy]: https://gum.co/nuOluY
[nfy]: https://app.netlify.com/start/deploy?repository=https://github.com/hydecorp/hydejack-starter-kit
[dtn]: https://www.netlify.com/img/deploy/button.svg

[gpss]: https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fhydejack.com%2Fdocs%2F
[rouge]: http://rouge.jneen.net
[katex]: https://khan.github.io/KaTeX/
[mathjax]: https://www.mathjax.org/
[tinyletter]: https://tinyletter.com/
