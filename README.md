# LDES in LDP specification

Writing to a time-based fragmented Linked Data Event Stream that is stored on a Linked Data Platform.

## Build the spec

Install [bikeshed](https://tabatkins.github.io/bikeshed/#installing) and then run `bikeshed watch ldesinldp.bs`

## Specification

The specification is available at [https://woutslabbinck.github.io/LDESinLDP/](https://woutslabbinck.github.io/LDESinLDP/)

## Libraries

The [VersionAwareLDESinLDP](https://www.npmjs.com/package/@treecg/versionawareldesinldp) package provides support for both the [**LDES in LDP**](https://woutslabbinck.github.io/LDESinLDP/#ldesinldp) as the [**Versioned LDES in LDP**](https://woutslabbinck.github.io/LDESinLDP/#VLIL) protocol.


## Applications

* [metadata announcements](https://tree.linkeddatafragments.org/announcements/) builds upon the LDES in LDP protocol to build a time-based LDES of metadata announcements of DCAT-APs.
* [Solid Event Sourcing](https://github.com/woutslabbinck/SolidEventSourcing) is a repository that builds a versioned LDES in LDP from a gpx file.
Your location data is transformed to RDF and each point is represented as a version in the LDES.
The created LDES thus is an Event Source of your location data.

## Contributions

Through pull requests
