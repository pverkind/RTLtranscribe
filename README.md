# RTLtranscribe
Transcription tool for manuscripts in RTL languages

This tool is being developed for the IslamAtlas project.

The tool will facilitate line-by-line transcription of manuscripts written in Arabic (and other RTL languages). 

In the background is a picture of the page to be transcribed, segmented into lines by the Kraken tool (https://github.com/mittagessen/kraken)

There are two text input fields: one for BetaCode (https://github.com/maximromanov/ArabicBetacode), one for Arabic; both fields are connected, and the content of one is converted into the other at the press of the space bar (or by leaving the field). Using BetaCode should make it easier to introduce annotation tags (TEI, or OpenITI mARkdown).

In addition, there is another text field with the text from a digitized edition / a previously transcribed manuscript. The relevant section can be selected and copied into the input fields in order to speed up transcription. 

When a line is finished, both versions of the transcribed line (and, if necessary, derived versions) are written to a database, and a new line is selected. 

Currently, only the 

