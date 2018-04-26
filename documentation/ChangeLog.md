# Local Legislation (Change Log)

History:

- [Version 1.0](#v10)

## v1.0 

> Apr 10, 2018

### What's Changed

- Changed title format.
- Users can now see all text in one page.
- Added 'FootNotes' section in text body.
- Added 'Metadata' section in text body.
- Removed empty 'Incipit' and 'Explicit' sections, excluding those that say "None".
- :star2: "Time Series" feature now working.
- :star2: Multiple "sort by" options added.
- Added and re-ordered facets and search options.
- Renamed 'head' facet to 'header'

- Currently used facets:
    'record_id',
    'create_date',
    'origPlace',
    'diocese',
    'province',
    'country',
    'classification',  
    'language'

- Currently used search options:
    'record_id',
    'title',  
    'origPlace',
    'country',
    'diocese',
    'province',
    'language',
    'year',
    'head'

### General Notes:

- :star2: You can choose multiple facet options (e.g See results from province "Reims" or "Trier".)
    - To do so, go to `Show Search Options` > `Province` and type in `Reims OR Trier`
    - It also supports `Reims NOT Trier`
- :star2: You can filter results by specifying start and end years. 
    - To do that, go to `Show Search Options` > `Year` and type in `1250-1300` for example.
- Version 1.0 uses 493 source files.
- Version 1.0 uses a new version of parser (`master parser`) which is more comprehensive and user-friendly.

### To-do:

- Populate all metadata fields in XML file. (v1.0 only contains the metadata fields used by PhiloLogic.)
- Implement Orthographic systematization.
