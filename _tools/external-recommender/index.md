---
title: External Recommender for INCEpTION
third_party: true
kind: Tool
subheadline: "Run your own recommenders using Python"
permalink: /tools/external-recommender/
---

{% assign stable = site.data.releases | where: "status", "stable" | first %}

External recommenders are web services that provide annotation suggestions to INCEpTION. They let you
integrate custom classifiers or pre-trained models.

The [inception-external-recommender][1] repository provides **ariadne**, a Python library for running
and implementing external recommenders. It also comes with ready-to-use recommenders, for example
based on [spaCy](https://spacy.io/).

To get started, see the [tutorial][2]. Installation instructions are in the repository.

## Connecting a recommender to your project

1. Start the recommender service. Its [README][1] has an example that serves spaCy named entity and
   part-of-speech recommenders at URLs such as `http://localhost:5000/spacy_ner`.
2. In INCEpTION, open the project settings, choose **Recommenders** and click **Create**.
3. Choose the layer and feature, select the external recommender as the tool, enter the URL of the
   service and save.
4. Open a document on the annotation page. The suggestions appear after your next annotation action.

## Further reading

* [External recommenders in the User Guide][3], including HTTPS connections
* [External recommender API in the Developer Guide][4], for implementing your own service in any
  language

[1]: https://github.com/inception-project/inception-external-recommender
[2]: https://github.com/inception-project/inception-external-recommender/blob/main/Tutorial.ipynb
[3]: {{ site.url }}/releases/{{ stable.version }}/docs/user-guide.html#_external_recommender
[4]: {{ site.url }}/releases/{{ stable.version }}/docs/developer-guide.html#_external_recommender_api_overview
