# Mestrelab .json 

Starting from the version 14.1 of Mnova, spectra, peak-lists and signal assignment can be **exported** and **imported** in the json format.

## User interface

Use "Save as" and select the relevant (*.json) entries from the pull-down menu. Drop json files directly into the main Mnova application window to import files.
 
## Mnova scripting

<div class="code-box">
<pre><code>
serialization.save("c:/santonin.mol", "mol"); // for JSmol
serialization.save("c:/santonin_molecule.json", "JSON Molecule (*.json)") // for the J-graph
serialization.save("c:/santonin_spectrum.json", "JSON NMR (*.json)") // for the spectrum
</code></pre>

Related page

Demonstration of [using Mnova json files](./mnova-reader.md).