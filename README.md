# CMU Pronunciation Dictionary 0.6

The [CMU Pronunciation Dictionary](cmudict) is a General American English
pronunciation dictionary. It is used at Carnegie Mellon in their speech
understanding systems. The phone set for the dictionary contains 39 phones,
which can be found in [phoneset](phoneset) along with example usage.

Using John Wells' lexical sets, it has the following mergers:

 *  TRAP-BATH
 *  PALM-LOT
 *  STRUT-COMMA
 *  THOUGHT-CLOTH
 *  NORTH-FORCE
 *  NURSE-LETTER
 *  FLEECE-HAPPY

The Carnegie Mellon Speech Group does not guarantee the accuracy of this
dictionary, nor its suitability for any specific purpose. In fact, a number
of errors, omissions and inconsistencies are expected to remain in the
dictionary. The dictionary is intended to be continually updated by
correcting existing entries and by adding new ones. From time to time a
new major version will be released.

If you add words to or correct words in your version of this dictionary,
the Carnegie Mellon Speech Group would appreciate it if you could send
these additions and corrections to [Robert L. Weide](weide@cs.cmu.edu)
for consideration in a subsequent version. All final entries will be
approved by Robert L. Weide, editor of the dictionary.

## Dictionary Construction

The Carnegie Mellon Speech Group generated this dictionary using the
following independent sources:

 * a 20k+ general English dictionary, built by hand at Carnegie Mellon
  (extensively proofed and used).
 * a 200k+ UCLA-proofed version of the shoup dictionary.
 * a 32k subset of the Dragon dictionary.
 * a 53k+ dictionary of proper names, synthesiser-generated, unproofed.
 * a 200k dictionary generated with Orator, unproofed.
 * a 200k dictionary generated with Mitalk, unproofed.

All entries that occur solely in copyrighted sources, like the Dragon
dictionary, are not currently included in this dictionary.

All of the above sources were preprocessed and the transcriptions in the
current cmudict were selected from the transcriptions in the sources or a
combination thereof. Some potentially unreliable transcriptions have been
removed from this dictionary, including those based on only one source,
and will be reintroduced once the transcriptions have been verified.

## License

Copyright (C) 1993-1998 Carnegie Mellon University. All rights reserved.

Use of this dictionary for any research or commercial purpose is completely
unrestricted.  If you make use of or redistribute this material, we would
appreciate acknowlegement of its origin.
