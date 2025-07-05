What is OMOD?

OMOD by SquirrelRidge.org is an urgent
intervention for linguistics and NLPAI.

Orthographic Mapping Ondemand Dataset is
what the acronym OMOD stands for. Goal:
Provide accurate, Unicode/Glottocode-linked
glyph-to-phoneme systems across languoids
to account for dialectic variety, enabling
text-to-speech and endangered language
rescue work through open data systems.

Repo structure:

/omod/schema/
-------------
Defines structure and contents for omod
on a per-languoid basis. Minimum file is
femtomod, a machine-readable barebones
IPA-glyph mapping reference. Human-legible
omod-languoids, omod-orthosets, and
omod-orthogons provide additional detail.
omod-credits enables verifiable sourcing
and appropriate community attribution.

/omod/data/
-----------
Folders "omod-abcd9876" append omod to
an existing Glottocode. Contents range
from femtomod alone to all 5 schematypes.
