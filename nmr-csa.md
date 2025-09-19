# Simulated Solid-states spectra

We generated a [data flow](https://chemedata.github.io/solidStateNMRCSA-reader/html/toolsDemo.html) line to show NMR solid-states powder-pattern spectra in Mnova.

In the background, the steps are:

- Create a [CHEMeDATA CSA object](https://chemedata.github.io/solidStateNMRCSA-reader/) (`NMRspinSystemModel_CSA`) from diagonal tensor values.
- Use a [bridge](https://chemedata.github.io/solidStateNMRCSA-reader/) from `NMRspinSystemModel_CSA` to `NMRspectrumObject` objects.
- Export the `NMRspectrumObject` object into Mnova json file into [CHEMeDATA spectrum object](https://chemedata.github.io/solidStateNMRCSA-reader/html/toolsDemo.html) (`NMRspectrumObject`)
# More info

[Main CSA repository](https://chemedata.github.io/solidStateNMRCSA-reader/)
