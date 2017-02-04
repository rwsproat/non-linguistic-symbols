# non-linguistic-symbols
This contains the corpora and some of the tools cited in:
Sproat, R. (2014). <a href="http://www.linguisticsociety.org/files/archived-documents/Sproat_Lg_90_2.pdf">"A Statistical Comparison of Written Language and Nonlinguistic Symbol Systems"</a>. Language, vol. 90(2), 457-481, June 2014.

For a description of some of the data, see also:

Katherine Wu, Jennifer Solman, Ruth Linehan and Richard Sproat. <a href="http://elanguage.net/journals/lsameeting/article/view/2845/pdf">"Corpora of Non-Linguistic Symbol Systems."</a> Linguistic Society of America, Portland, OR, January 2012.

The file corpora.zip contains all the corpora in XML format, along with the XML schema.

tools.zip contains a simple Python program xtract.py to extract data in various ways from the XML format. It also contains ngram-entropy, used to compute entropies on the output of an ngram model as computed using <a href="http://opengrm.org/">Open GRM's ngram library</a>. See the README for a typical use case.

Errata:

<ul>
<li>
References to the "Wilcoxon signed rank test" in the main paper should be replaced with "Wilcoxon rank sum test".
<li>
On page 476, the second bullet item from bottom of bullet list makes a reference to "Luwian" and "Hittite hieroglyphs". Of course Hittite hieroglyphs are really Luwian, and should have been deleted here.
</ul>

