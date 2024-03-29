# Document source

## [WCAG (Quick Reference)](https://github.com/w3c/wai-wcag-quickref/tree/gh-pages/_data)

- wcag20-long-en.yaml is a YAML coversion of the [JSON WCAG 2.0 file](https://github.com/w3c/wai-wcag-quickref/blob/gh-pages/_data/wcag2.json)
- wcag21-long-en.yaml is a YAML coversion of the [JSON WCAG 2.1 file](https://github.com/w3c/wai-wcag-quickref/blob/gh-pages/_data/wcag21.json)
- Straight import of tags-sc.yml renamed as tags-sc.yaml for consistency

## [WCAG-EM Report Tool](https://github.com/w3c/WCAG-EM-Report-Tool)

- wcag21-short-en.yaml is a YAML coversion of the [JSON WCAG 2.1 file](https://github.com/w3c/wcag-em-report-tool/blob/master/app/wcag2spec/wcag2-en.json)

## [Mapping of WCAG 2.0 to US Functional Performance Criteria (FPC)](https://www.section508.gov/content/mapping-wcag-to-fpc)

- mapping-wcag-to-fpc.csv is a CSV file from the HTML table with an alt_id added for engagement with WCAG references
- mapping-wcag-to-fpc.yaml ia YAML file from the CSV above

## [Mapping of US Trusted Tester ID's, WCAG SC & FPC ID's](https://github.com/Section508Coordinators/ACRT/blob/master/Resources/TT5-ID-FPC_Mapping_07-15-20.xlsx)

- TT5-ID-FPC_Mapping_07-15-20.csv a CSF file exported from the original Excel file published by the [Section508Coordinators](https://github.com/Section508Coordinators)

## [Purple Hats axeTypes and WCAG Links](https://github.com/GovTechSG/purple-hats/tree/master/constants)

- axeTypes.yaml is a conversion of axeTypes.json from [Purple Hats](https://github.com/GovTechSG/purple-hats)
- wcagLinks.yaml is a conversion of wcagLinks.json from [Purple Hats](https://github.com/GovTechSG/purple-hats)

Also see: [axe rule description](https://github.com/dequelabs/axe-core/blob/develop/doc/rule-descriptions.md)

## NN/g's Usability Heuristics based on [Aligning Jakob Nielsen's 10 Usability Heuristics with the WCAG 2.1](https://rightbadcode.com/aligning-jakob-nielsens-10-usability-heuristics-with-the-wcag-21) and [Usability and Accessibility](https://blog.orium.com/usability-and-accessibility-213c3185314f)
- NNg-usability-heuristics-wcag.csv

## Comparison of axeTypes & Functional Performance Criteria (FPC)

- axeType2FPC.yaml - Needed an easier way to compare and reference disability types

### Section 508 FPC Disability Types

- WV - Without Vision
- LV - Limited Vision
- WPC - Without Perception of Color
- WH - Without Hearing
- LH - Limited Hearing
- WS - Without Speech
- LM - Limited Manipulation
- LRS - Limited Reach and Strength
- LLCLA - Limited Language, Cognitive, and Learning Abilities

## [EN 301 549 v3.2.1 - Table B.2 Requirements in clauses 5 to 13 supporting accessibility need](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Expressed in Functional Performance Statements (FPS)

- EN301549-to-FPS.csv
- EN301549-to-FPS.yaml

### EN 301 549 disability types

- **4.2.1. Usage without vision:** Where ICT provides visual modes of operation, some users need ICT to provide at least one mode of operation that does not require vision.
- **4.2.2. Usage with limited vision:** Where ICT provides visual modes of operation, some users will need the ICT to provide features that enable users to make better use of their limited vision.
- **4.2.3. Usage without perception of colour:** Where ICT provides visual modes of operation, some users will need the ICT to provide a visual mode of operation that does not require user perception of colour.
- **4.2.4. Usage without hearing:** Where ICT provides auditory modes of operation, some users need ICT to provide at least one mode of operation that does not require hearing.
- **4.2.5. Usage with limited hearing:** Where ICT provides auditory modes of operation, some users will need the ICT to provide enhanced audio features.
- **4.2.6. Usage without vocal capability:** Where ICT requires vocal input from users, some users will need the ICT to provide at least one mode of operation that does not require them to generate vocal output.
- **4.2.7. Usage with limited manipulation or strength:** Where ICT requires manual actions, some users will need the ICT to provide features that enable users to make use of the ICT through alternative actions not requiring manipulation or hand strength.
- **4.2.8. Usage with limited reach:** Where ICT products are free-standing or installed, the operational elements will need to be within reach of all users.
- **4.2.9. Minimize photosensitive seizure triggers:** Where ICT provides visual modes of operation, some users need ICT to provide at least one mode of operation that minimizes the potential for triggering photosensitive seizures.
- **4.2.10. Usage with limited cognition:** Some users will need the ICT to provide features that make it simpler and easier to use.
- **4.2.11. Privacy:** Where ICT provides features that are provided for accessibility, some users will need their privacy to be maintained when using those ICT features that are provided for accessibility.

## How many people have a disability? 

From [UK Department for Education - Design Manual](https://design.education.gov.uk/learn/how-many-users) and their [GitHub Repository](https://github.com/DFE-Digital/design/blob/main/app/data/stats.json).
- UK-How-many-people.json
- UK-How-many-people.csv

## Also See
- [thisiswcag.com](https://thisiswcag.com)'s GitHub site was taken down but they did have a JSON file with a clean breakdown of critieria [this is a fork of the data file](https://github.com/rjabdurrahman/thisiswcag-beta/blob/main/data/json.js) for WCAG 2.1. 
- [Tenon: WCAG 2.1 as JSON](https://github.com/tenon-io/wcag-as-json)
- [a11y-data-keywords](https://github.com/7mary4/a11y-data-keywords) a compiled list of keywords to use when data-mining customer feedback to get the voice of your customers with a disability.
- Since much of this is axe based, worth pointing out [Deque's tables of axe rules](https://dequeuniversity.com/rules/axe/html), which in tern links to the [W3C's ACT Rules](https://act-rules.github.io/rules/).
- [Accessible Community's Usable](https://accessiblecommunity.github.io/useable/) project also on [GitHub](https://github.com/accessiblecommunity/useable)
