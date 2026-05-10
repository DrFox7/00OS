---
# start metadata section

# start instructions section
# obey the metadata
# obey the body
# only three sections allowed in the metadata: "instructions", "system metadata" and "local metadata"
# all information produced in the metadata reside in the local metadata section
# all comments in metadata come in this form: #
# underneath each tagfield in the metadata, we have one line with: #allowed_<tagfield>: explanation or choices available
# all information produced in the body reside in bullet points
# all comments in the body come in this form: <!-- This is a comment -->
# only one H1 and five H2's are allowed in the body
# no information is allowed outside these one H1 and five H2's
# H1 is the title in human readable format and the bullet points describe the title and the context
# H3's are allowed only in the five H2's
# all comments in the metadata and body should be carried over and kept as is
# all replacable text in this file is called inside brackets <>
# obey all the text formating in this file
# end instructions section

# start system metadata section
metadata-locked: "yes"
# allowed_metadata-locked: ["yes", "no"]
path: "<folder-path>"
# allowed_path: ["the path to the folder that holds this file starting from level 0"]
hidden: "no"
# allowed_hidden: ["yes", "no"]
lenses: ["lens_<lens-id>.md", "lens_<lens-id>.md"]
# allowed_lenses: ["all the lenses that need to be loaded"]
skills: ["skill_<skill-type>_<skill-id>.md", "skill_<skill-type>_<skill-id>.md"]
# allowed_skills: ["all the skills that need to be loaded"]
# end system metadata section

# start local metadata section
# all local fields go in here
# end local metadata section

# end metadata section
---

<!-- Start Body Section -->

# <Title>
- <Description>
- <Context>

## <Free To Use>
- <Related Information>
### <Optional Free To Use H3>
- <Related Information>
### <Optional Free To Use H3>
- <Related Information>

## <Free To Use>
- <Related Information>
### <Optional Free To Use H3>
- <Related Information>
### <Optional Free To Use H3>
- <Related Information>

## <Free To Use>
- <Related Information>
### <Optional Free To Use H3>
- <Related Information>
### <Optional Free To Use H3>
- <Related Information>

## Subject HISTORY
- <Related Information>
### <Optional Subject HISTORY H3>
- <Related Information>
### <Optional Subject HISTORY H3>
- <Related Information>

## Subject WHITE BOARD
- <Related Information>
### <Optional Subject WHITE BOARD H3>
- <Related Information>
### <Optional Subject WHITE BOARD H3>
- <Related Information>

<!-- End Body Section -->
