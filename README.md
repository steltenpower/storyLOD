# FabmomentStructuring

Make sure you know what a Fablab is

Fablabs are great places to learn MAKING from a rich variety of people. 
Exchanging information through so-called fabmoments (reports on how something’s made) could be better facilitated through some changes:

standardize the notation of certain concepts, see http://fablab.metamatter.nl/ for ideas on what concepts (e.g. machine, material) and also notation. Try to reuse as much as possible from so-called open vocabularies (e.g. schema.org, that Google and others can read) or even better concepts that are already described properly (e.g. in DBpedia , WikiData, or something else in the LODcloud)

Change your fabmoment editor to make it very easy to use that standard notation (no spelling variants etc, plus linked data (RDFa) under the hood). This can be done through both in-text suggestions and visual buttons that will ‘stamp’ a term.

Have your linked data capable search engine spider all your fabmoments. The GUI interface of that search engine can next to entry of keywords also use the same visual buttons mentioned earlier. But now for the magic thing; by offering a so-called SPARQL endpoint you can even filter on properties you’ve never entered!!; say in a fabmoment you’ve not entered just Copper, but https://en.wikipedia.org/wiki/Copper in a user-friendly way, thereby allowing to use material properties defined there. You can now search for fabmoments where a material was used with a melting point above 1000 Celsius and get that fabmoment with copper returned.

And then connect all fablabs in the world (each with their own mix of languages) through this system …
