
## About this tutorial

Please note that the steps below (in particular 1-3) do not capture all the
complexities behind genomics and systematics. Instead, the objective of this
tutorial is to guide users on the registration process in the SeqCode Registry,
assuming they already have a solid background on genome-based taxonomic
analyses.

## 1. Review the quality of your genome

The first step when considering to register a genome as the type material for a
novel taxon under the SeqCode is to evaluate the quality. You can see the
minimum quality requirements here:
[SeqCode Appendix I](https://registry.seqco.de/page/seqcode#data-quality-necessary-for-completion-of-seqcode-registryb)

You can use any of the many methods to evaluate quality, so long as you document
which method was used. Internally, the Registry revises estimates using MiGA,
but that's only to ensure quality-control.

For additional details on how these genomes are evaluated, see
[How are names internally curated?](../guide/curation.md).

## 2. Determine the degree of taxonomic novelty

The next step, is to determine up to which rank the new taxon is novel. For
example, if the genome can be confidently classified into a genus, but not a
species, you might consider proposing a novel species within that known genus.
If, instead, the genome cannot be classified confidently to genus, family, or
class, but it can be classified confidently to order, the novelty will be up
to the class level. In the extreme case, when the only confident classification
is at the domain level, phylum-level novelty might be warranted. This
determination should be made carefully, and in many cases conservatively, but
ultimately the decision is left for the authors and the peer-review process of
the effective publication to evaluate.

## 3. Create the name/s for the novel taxon/a

If the novelty in step 2 is determined to be just at the species level, you'll
only need a new specific epithet. If the novelty is at the rank of genus or
above, you'll also need a new name for the genus. All other taxa (above genus)
will be named on the basis of the genus, and the Registry will help you with
their spelling.

For additional resources on name creation, see
[How do I Fill the Etymology Table?](../guide/etymology.md).

## 4. Create a guided registration

The easiest way to register your names now is to
[follow a guided registration](https://registry.seqco.de/tutorials).
Select "New species and parent taxa" and follow the instructions there. Briefly:

0. Fill the species name and the most specific classification (both defined
   above). For example, if you determined that the genome belongs to a novel
   class of a known phylum, fill-up the species name and the phylum to which you
   believe the species belong.
1. Review the proposed new names for all intermediate ranks (if any) and
   continue.
2. Click again "continue" and define the type material of the species, which is
   the genome you characterized above. Make sure it's available in INSDC
   Nucleotide or Assembly databases; select the appropriate database, and then
   pick the accession. Include the reference strain *only* if the genome is
   derived from a culture. For MAGs and SAGs, leave this field empty.
3. Continue, fill-up additional details, and continue.
4. Add a description for the proposed species. Note that this refers to
   properties of the species and the circumscription, *not* the etymology.
5. Fill the etymology (refer to the in-page documentation for more details).
6. Continue the registration for all remaining names. For the most part, you
   will only need descriptions and etymologies (most of which might be
   automatically filled, with the exception of genus names).
7. Finally, all names will be added to a single Register List. Make sure to
   select "Create a new Register" if this lineage stands alone in an effective
   publication, or to select the appropriate register list if it belongs to
   a collection of lineages for which you already have an existing register.

## 5. Submit the list

You can repeat steps 1-4 for all the lineages that you report in the effective
publication. Once you're done with these, you can submit it. If you are
currently working on your manuscript or undegoing peer-review, click on
"Submit register list for evaluation" in the Register List page (this is called
*Path 1*). If you are registering names from an effective publication that is
already published, click on "Notify about effective publication" (this is called
*Path 2*).

