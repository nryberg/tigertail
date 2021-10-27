# Tiger Tail

A tool to catch hold of patterns and not let go until you've got something interesting and informative.  

Given a set of data, with reasonable cardinality, you should be able to tease out the patterns and create fast click throughs.  

The converted data is built out as .md text files that can be consumed by Hugo docsite generator, with a reasonably clean them applied to it.

The tool has to have some guidance as to the facets that can be aggregated and reported.  Any duplication is treated as a list within a specific category.  

For example, for the following table

Color | Shape 
-- | --
Red | Round
Red | Square
Red | Triangle

You'll generate a color category page with three entries.  Each entry links out to a details page that has a back link to the category.

Category : Color

Red
---
- Round
- Square
- Triangle