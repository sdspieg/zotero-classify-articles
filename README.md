zotero-classify-articles
========================

Zotero plugin to tag journal articles with discipline classification of journal in which article is published

## Description

This plugin searches for journal article items in a user's Zotero library. Each of these items should have a publication title, i.e. the journal in which the item was published. This title is matched against the plugin's list of publication titles. If a match is found, the item is tagged with the publication's discipline.

### Example

For instance, suppose the article *The European Security Strategy: Multilateral Security with Teeth?* is present in the user's Zotero library. This article was published in *Defense & Security Analysis* 21:3 (2005). This publication, according our plugin's database, belongs to the *Social Sciences* discipline, and the *Defense* subdiscipline. Thus, the item will be tagged with *Discipline: Social Sciences / Defense*

## Notes

Due to Zotero's handling of tags, executing the plugin's classification while having an open tag window will likely cause your system to run out of memory. Keep the tag window closed and nobody gets hurt. This really should be fixed, but it involves tampering with Zotero's internals.

The code was written to meet a deadline, and so could stand to be improved in many ways.

## Credits

This plugin was developed by [The Hague Center of Strategic Studies](http://www.hcss.nl/) to support the project [European Security Trends and Threats in Society](http://www.prio.no/Research-and-Publications/Project/?oid=3701106) (ETTIS EU FP7). The following people are credited with involvement:

- Stephan De Spiegeleire
- Tim Sweijs
- Jona Andersen
