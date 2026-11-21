# musicbox-updates
Software updates for Music Box players. Boxes check here daily for signed releases. Nothing about a box or its owner is sent.

Software updates for Music Box speakers and Pads. Boxes download
`releases/latest/download/manifest.json`, check its signature, and install the zip it names.
Each `releases/<version>/` folder holds a signed release; pushing one publishes it as the
latest GitHub release (`.github/workflows/publish.yml`). No keys or owner data live here.
