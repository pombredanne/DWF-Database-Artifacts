# DWF Database Artifacts

The DWF Database artifacts contains additional information about vulnerabilities. Specifically there is a JSON file with machine/human readable data, and then one or more associated artifacts (e.g. a security report/advisory, copy of a bug report, reproducer, etc.).

## DWF Database Artifacts format

Database artifacts should be left in their original state if possible (e.g. raw copy of a web page, PDF, etc.). Artifacts may be optionally tar'ed and/or compressed (e.g. a web page with images may be stored as a compressed tarball).

## Dangerous artifacts

Due to the nature of the data being stored some of it may be potentially dangerous (e.g. weaponized exploit code embedded in an HTML file or image file). In this case the item should be compressed using "zip" with a password set, the password MUST be set to "infected" (this is a relatively standard practice across the AV industry).

## A note on the DWF Project data and the Apache License

It is the intent of the DWF Project that the data contained within the DWF-Database and the DWF-Database-Artifacts repositories be widely used (in licensing terms "redistributed") by vendors, security practitioners and any interested party. However we would ask that you abide by the terms of the Apache License which primarily require a copy of the license to be provided (so e.g. "Our database may contain content redistributed from the DWF Project under the Apache License, click here for a copy") and any altered data (e.g. a "Description" of a vulnerability) to be labeled as altered (e.g. "This description has been altered from the original provided by the DWF").