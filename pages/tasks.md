---
layout: page-fullwidth
title: "Tasks"
permalink: "/tasks/"
---

INCEpTION comes with project templates for common annotation tasks. When you first log in, the
project creation dialog offers these templates. You can bring it up again with the
**Create new project** button on the start page.

<div class="feature-grid">

  <div class="feature">
    <img src="{{ site.url }}/images/tasks/entity-annotation.svg" alt="">
    <div>
      <h3>Identify and classify named entities</h3>
      <p><strong>Template: Entity annotation.</strong> Includes example documents and annotations, plus recommenders that suggest entities as you work. A good place to start if you are new to INCEpTION.</p>
    </div>
  </div>

  <div class="feature">
    <img src="{{ site.url }}/images/tasks/entity-linking.svg" alt="">
    <div>
      <h3>Link mentions to Wikidata</h3>
      <p><strong>Template: Entity linking (Wikidata).</strong> Annotate named entities and link them to their entries in Wikidata.</p>
    </div>
  </div>

  <div class="feature">
    <img src="{{ site.url }}/images/tasks/document-classification.svg" alt="">
    <div>
      <h3>Classify documents</h3>
      <p><strong>Template: Document classification.</strong> Assign labels to whole documents. Define your labels in the project settings before you start.</p>
    </div>
  </div>

  <div class="feature">
    <img src="{{ site.url }}/images/tasks/sentence-classification.svg" alt="">
    <div>
      <h3>Classify sentences</h3>
      <p><strong>Template: Sentence classification.</strong> Assign labels at the sentence level and define new labels as you go along.</p>
    </div>
  </div>

  <div class="feature">
    <img src="{{ site.url }}/images/tasks/basic.svg" alt="">
    <div>
      <h3>Annotate spans and connect them</h3>
      <p><strong>Template: Basic annotation (span/relation).</strong> Create annotations on words and connect them using relations.</p>
    </div>
  </div>

  <div class="feature">
    <img src="{{ site.url }}/images/tasks/universal-dependencies.svg" alt="">
    <div>
      <h3>Follow the Universal Dependencies guidelines</h3>
      <p><strong>Template: Universal Dependencies.</strong> Part-of-speech tags, dependency parsing, morphological features, lemmas and surface forms, with import and export in the CoNLL-U format.</p>
    </div>
  </div>

  <div class="feature">
    <img src="{{ site.url }}/images/tasks/phi.svg" alt="">
    <div>
      <h3>Annotate personal health information</h3>
      <p><strong>Template: PHI annotation.</strong> Mark anything that can identify a patient or individual in medical documentation. Includes example documents derived from the <a href="https://zenodo.org/records/11502329">GraSCCo_PHI dataset</a>, provided under the <a href="https://creativecommons.org/licenses/by/4.0/legalcode">CC BY 4.0</a> license.</p>
    </div>
  </div>

  <div class="feature">
    <img src="{{ site.url }}/images/tasks/classic.svg" alt="">
    <div>
      <h3>Do classic linguistic annotation</h3>
      <p><strong>Template: Classic linguistic project.</strong> Comes pre-configured for many linguistic annotation tasks. This is closest to the classic WebAnno project setup.</p>
    </div>
  </div>

  <div class="feature">
    <img src="{{ site.url }}/images/tasks/blank.svg" alt="">
    <div>
      <h3>Define your own annotation scheme</h3>
      <p><strong>Template: Blank project (no layers).</strong> Starts without any pre-defined layers. You define the layers you need in the project settings.</p>
    </div>
  </div>

</div>

To see how others set up their projects, have a look at the [stories]({{ site.url }}/use-cases/).
To work with INCEpTION from your own code, see [tools and integrations]({{ site.url }}/tools/).
