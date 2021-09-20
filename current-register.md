###### [Software Development Priorities](README.md)

# Current Register
###### Last updated: Sep 20, 2021

This page provides a listing of features grouped by priority. High priority features may be described in greater detail than in the [Issues tab](https://github.com/SFU-Archives/software-development-priorities/issues).
- [In progress](#in-progress)
- [High priority](#high-priority)
- [Medium priority](#medium-priority)
- [Low priority](#low-priority)

## In progress
### [Digital object metadata display: retroactive implementation](https://github.com/SFU-Archives/software-development-priorities/issues/43)
The Archives sponsored an improved display of digital object metadata in AtoM in the [2019-20 development contract](/development-contracts/2019-20.md). This makes a clear distinction between the metadata for the original file, the preservation copy, and the various access copies in AtoM (thumbnail, reference, master).

This new representation will now apply to all digital objects uploaded to AtoM but it does not apply retroactively to existing content. The current project creates a script to retroactively apply to existing AtoM digital objects by getting the data from the Archivematica AIP / METS file (where the AtoM digital object was sent via Archivematica).

## High priority
### [Archivematica error handling](https://github.com/SFU-Archives/software-development-priorities/issues/7)
Support better error handling. There are two main use cases we have in mind:

(i) The Archives has several processing configs that are fully automated, i.e. archivist starts ingest, all decision points are automated, process completes. Later the archivist confirms completion by expanding microservices to make sure no errors occurred. It would preferable if Archivematica produced a report at the end that showed any errors. (anything else that could / should go into the report? e.g. option implemented at each decision point?)

(i) During ingest if file format identification fails with the preferred tool, Archivematica should try another. Could be an admin setting to state the order of preference.

### [AtoM home page image carousel](https://github.com/SFU-Archives/software-development-priorities/issues/38)
Support a rotating set of images for the AtoM home page and provide an admin interface to allow easy upload / deletion.

### [AtoM theme: SFU branding](https://github.com/SFU-Archives/software-development-priorities/issues/47)
SFU Archives' website runs on the university's Abode Experience Manager platform and follows SFU branding style guidelines. This project would create a customized theme for SFU AtoM that would implement a similar look and feel, aligning it with the rest of the Archives' website. Adobe XD and the css files for the website are available to work from.

### [Subject terms: multiple thesauri](https://github.com/SFU-Archives/software-development-priorities/issues/32)
It is possible to set up multiple subject taxonomies in AtoM (e.g. BC Thesaurus top terms, taxonomies specific to Archives or Special Collections). But the interface for applying terms just gives a flat list of all terms from all taxonomies. This project would create an interface to support faceted filtering so that the user can view / select terms from a specific taxonomy.

## Medium priority
### AtoM
- [Access points: use other forms of name](https://github.com/SFU-Archives/software-development-priorities/issues/35)
- [Accessions module](https://github.com/SFU-Archives/software-development-priorities/issues/21)
- [AtoM collections / exhibits](https://github.com/SFU-Archives/software-development-priorities/issues/39)
- [AtoM csv utility](https://github.com/SFU-Archives/software-development-priorities/issues/26)
- [AtoM export: filter access points by taxonomy](https://github.com/SFU-Archives/software-development-priorities/issues/33)
- [AtoM search enhancements](https://github.com/SFU-Archives/software-development-priorities/issues/20)
- [Rights management](https://github.com/SFU-Archives/software-development-priorities/issues/18)

### Archivematica
- [AIP repository manager](https://github.com/SFU-Archives/software-development-priorities/issues/11)
- [Disk images](https://github.com/SFU-Archives/software-development-priorities/issues/4)

### Archivematica–AtoM
- [DIP management](https://github.com/SFU-Archives/software-development-priorities/issues/12)
- [Email](https://github.com/SFU-Archives/software-development-priorities/issues/13)
- [Object metadata extraction](https://github.com/SFU-Archives/software-development-priorities/issues/14)
- [Semi-active digital transfers environment](https://github.com/SFU-Archives/software-development-priorities/issues/16)
- [Web archiving](https://github.com/SFU-Archives/software-development-priorities/issues/15)

### ePADD
- [ePADD import: formatting](https://github.com/SFU-Archives/software-development-priorities/issues/45)
- [ePADD mbox](https://github.com/SFU-Archives/software-development-priorities/issues/46)
- [ePADD timestamps](https://github.com/SFU-Archives/software-development-priorities/issues/44)

## Low priority
### Archivematica
- [Bulk extractor enhancements](https://github.com/SFU-Archives/software-development-priorities/issues/3)
- [Format Policy Registry (FPR)](https://github.com/SFU-Archives/software-development-priorities/issues/5)
- [Links AIPs to fonds / collections](https://github.com/SFU-Archives/software-development-priorities/issues/1)
- [Submission documentation](https://github.com/SFU-Archives/software-development-priorities/issues/6)
- [Transfer analysis and validation tools](https://github.com/SFU-Archives/software-development-priorities/issues/2)

### AtoM
- [AtoM related materials note](https://github.com/SFU-Archives/software-development-priorities/issues/40)
- [AtoM SQL interface / support](https://github.com/SFU-Archives/software-development-priorities/issues/30)
- [Authority records: duplicates](https://github.com/SFU-Archives/software-development-priorities/issues/34)
- [Authority records: links to URIs](https://github.com/SFU-Archives/software-development-priorities/issues/36)
- [Collections as data](https://github.com/SFU-Archives/software-development-priorities/issues/22)
- [Physical locations module](https://github.com/SFU-Archives/software-development-priorities/issues/19)
- [Selective de-indexing of digital objects](https://github.com/SFU-Archives/software-development-priorities/issues/27)
- [User contributed content](https://github.com/SFU-Archives/software-development-priorities/issues/24)
