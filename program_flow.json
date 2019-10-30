{
  "proto":
    {
      "uri": "$uri",
      "fn" : "?fn",
      "title" : "$ebucore:title | ebucore:mainTitle",
      "description": "$ebucore:description",
      "episodeNumber" : "$ebucore:episodeNumber",
      "tags": "$ebucore:hasKeyword",
      "genre": "$ebucore:hasGenre",
      "languages" : "$ebucore:hasLanguage",
      "workingTitle" : "$ebucore:workingTitle",
      "theme" : "$ebucore:hasTheme",
      "producer":"$ebucore:hasProducer",
      "programmeTitle" : "$ebucore:hasEpisode / ebucore:title",
      "firstPublicationChannel" : "$ebucore:hasPublicationHistory / ebucore:hasPublicationEvent / ebucore:isReleasedBy / ebucore:publicationChannelName",
      "firstPublicationTime" : "$ebucore:hasPublicationHistory / ebucore:hasPublicationEvent / ebucore:hasPublicationStartDateTime"
    },
  "$where": ["$uri ebucore:filename ?fn"],
  "$prefixes": {
      "ebucore": "http://www.ebu.ch/metadata/ontologies/ebucore/ebucore#"
  }
}