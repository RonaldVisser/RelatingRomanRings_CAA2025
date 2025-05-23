
# Relating Roman Rings: an open and reproducible approach to understanding provenance patterns of wood using networks

[![DOI](https://zenodo.org/badge/974772798.svg)](https://doi.org/10.5281/zenodo.15342407)

Author: Ronald Visser

Presentation presented at the CAA 2025 in Athens
(<https://2025.caaconference.org/>)

## Abstract

Wood was, is and will be on of the most important resources. While wood
is one of the most sustainable and strongest building materials, wood is
also prone to decay and therefore often lacking in archaeological
contexts. In the Roman period many objects and structures were made of
wood, such as roads, bridges, ships, buildings, chairs, boxes and
buckets. However, these are only found in very dry or very wet
conditions. The lower Rhine area is such an environment, with high
ground water levels and a high sedimentation rate, resulting in
excellent preservation conditions for organic materials, such as wood.
Over the past decades, wood has been excavated and part of this has been
subjected to dendrochronological and dendroarchaeological research. This
resulted in a large dataset of tree-ring material. While the find
location is often known, the provenance of the trees, i.e. the growth
region, is often unknown and has to be reconstructed. Determining the
provenance of wood based on dendrochronological research is termed
dendroprovenance. This is often based on matching tree-ring patterns
with existing regional and/or site chronologies using various software
packages. This process does not always comply with the aims of Open
Science, since not all software is open, sometimes resulting in
workflows that are not fully reproducible. This paper will address the
following central research question: How to determine the provenance of
wood using dendroarchaeology in a reproducible and open method?

Before being able to address the question in detail the data needs to be
described, explaining the life history of the data set, what temporal
and spatial patterns are present in the dataset. These patterns define
the suitability of the data for further analyses and this will be
discussed in the presentation.

Dendroprovenance is an important field of research aiming to determine
the provenance of wood. A new method has been developed using network
analyses to assess the provenance (Visser and Vorst 2022; Visser 2021).
Dendroprovenance is based on the statistical relations between tree-ring
series or chronologies and a strong statistical relation between series
assumes similar growth patterns and therefore a similar provenance. As
argued elsewhere (Visser 2021), methods such as clustering are not
suitable for this, due to the varying temporal and spatial distribution
of the sometimes sparse data. The use of a network for studying the
relations between a tree-rings series for determining the provenance
solves many issues and makes the method also more transparent. Networks
are created by using the pair-wise similarity of tree-ring patterns to
build the edges, while the nodes represent the find location or the wood
sample(s). The neighbours of a node in the network reflects the
similarity of the growth patterns and therefore the trees probably grew
in the same region. However, since wood could have been moved and
transported in the past, various factors need to be taken in to
consideration when interpreting the patterns, such as context, spatial
location, growth patterns (Visser 2021, 244). These networks have led to
new insights in the Roman wood economy and has also shown that wood was
only transported over long distances in specific projects, such as the
road along the Roman *limes* or to construct Roman barges (Visser and
Vorst 2022). Local wood procurement was the rule, and long-distance
transport remained the exception (Visser 2025).

The analyses and method were published as open as possible and all data
and source code was made available upon request, but to advance the
openness and reproducibility, a package for R was developed (Visser
2024). This package is reviewed and published with rOpenSci:
<https://docs.ropensci.org/dendroNetwork/>. Building a package ensured
that the methodology became more generally applicable. At the same time,
lessons were learned, especially how to share a method in a reproducible
and universal way
(<https://ropensci.org/blog/2024/06/06/from-scripts-to-package/>).

This presentation will deal with the issues in the dataset and how
network analyses using open software resulted in a reproducible workflow
leading to new insights into the wood economy in the Roman period. It
will also address some of the challenges of making research completely
open by sharing scripts and a package, and how network science is an
essential aspect thereof.

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-visser2021" class="csl-entry">

Visser, Ronald M. 2021. “Dendrochronological Provenance Patterns.
Network Analysis of Tree-Ring Material Reveals Spatial and Economic
Relations of Roman Timber in the Continental North-Western Provinces.”
*Journal of Computer Applications in Archaeology* 4 (1): 230–53.
<https://doi.org/10.5334/jcaa.79>.

</div>

<div id="ref-visser2024" class="csl-entry">

———. 2024. *dendroNetwork: A r-Package to Create Dendrochronological
Networks*. Zenodo. <https://doi.org/10.5281/zenodo.10636310>.

</div>

<div id="ref-visser2025" class="csl-entry">

———. 2025. “Relating Roman Rings. An Interdisciplinary Study Using
Archaeology, Data Science and Tree Rings to Understand Timber Provision
in the German Provinces of the Roman Empire.” PhD thesis, Amsterdam.
<https://doi.org/10.5463/thesis.1062>.

</div>

<div id="ref-visser2022" class="csl-entry">

Visser, Ronald M., and Yardeni Vorst. 2022. “Connecting Ships: Using
Dendrochronological Network Analysis to Determine the Wood Provenance of
Roman-Period River Barges Found in the Lower Rhine Region and Visualise
Wood Use Patterns.” *International Journal of Wood Culture* 3 (1-3):
123–51. <https://doi.org/10.1163/27723194-bja10014>.

</div>

</div>
