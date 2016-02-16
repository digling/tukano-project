# Conventions for Data Handling

Here we list and collect our conventions for data creation and representation in different stages of the projects. See our [workflow description](https://github.com/digling/tukano-project/blob/master/workflow.md) for the general workflow we decided to follow.

## IPA Conventions for the quasi-phonemic (FUN, $$) field

1. all vowel sequences, including identical ones, will be treated as two separate entities (as if belonging to different syllables)
2. glides will be represented as j and w irrespective of their placement in the root template
3. affricates (and other coarticulated consonants that are to be considered one segment) t͡ʃ and not tʃ

## Polysemous words
Polysemous entries in reflex have one entry per meaning, but those entries are linked, so you can find them easily. Here is the easiest way of doing it based on my experience with TG:
i. for entries that are present just once in the spreadsheet but have multiple meanings (presumably only one of their meanings was on the 740 list, but all or some of them are noted in the original translation field TRA):
a. create a new row and copy all the information for the polysemous entry in that row (you should have as many rows as meanings in total)
b. erase the id number in all new rows (this is very important as all entries need to have unique id  numbers)
c. copy the id number of the initial row into the ORP field (this number needs to be identical across all rows of a polysemous entry
d. write 1, 2, 3 etc in the ORF field to represent the order of meanings (this could be arbitrary if the source doesn't specify an order)
e. adjust the original and unified translations so there is one meaning per row

ii. for entries that are present more than once in the spreadsheet (presumably because at least two of their meanings were in the 740 list)
a. sort the spreadsheet according to the FUN field (this makes identical forms to be consecutive so you can spot them easily)
b. for every set of identical forms give them the same ORP number by copying one if the id numbers in all ORP cells (it doesn't matter which). (Do not erase any id numbers, they are unique already)
c. enter 1, 2, 3, etc in the ORF field to represent the order of meanings
d. make sure that the translations fields have one meaning each and adjust accordingly

LAST STEP: After you have done all adjustments involving polysemous words, sort the spreadsheet according to the ID field. All the newly created rows that have no ID numbers will be at the bottom. Assign them consecutive unique numbers (this way we are sure they are unique).

## Treatment of LAX rows
the concept in english followed by the tag -LAX will be moved automatically to the CSA field (comment of the compiler), while all translation fields except the original translation one will be left empty. The TUE field (unified english translation) needs to be filled in appropriately by the person correcting the corresponding importation template.
