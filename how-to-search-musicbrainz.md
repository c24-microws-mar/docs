# How to search the [MusicBrainz](http://musicbrainz.org/) metadata service

## Query for releases

    GET http://musicbrainz.org/ws/2/release?query={searchTerm}&limit=100&fmt=json

This will (hopefully) get you a list of Album releases for the provided search term.

## Search Covers

    GET http://coverartarchive.org/release/{releaseId}

This will get you URLs for CD Covers. Use the release ID from MusicBrainz.
