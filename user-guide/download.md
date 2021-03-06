## ANNOVAR main package

Please join the ANNOVAR mailing list at google groups [here](https://groups.google.com/forum/#!forum/annovar) to receive announcements on software updates.

The latest version of ANNOVAR (2015Mar22) can be downloaded [here](http://www.openbioinformatics.org/annovar/annovar_download_form.php) (registration required).

ANNOVAR is written in Perl and can be run as a standalone application on diverse hardware systems where standard Perl modules are installed.

## Additional databases

Many of the databases that ANNOVAR uses can be directly retrieved from UCSC Genome Browser Annotation Database by `-downdb` argument.

Several very commonly used annotation databases for human genomes are additionally provided below. In general, users can use `-downdb -webfrom annovar` in ANNOVAR directly to download these databases.

### - For gene-based annotation

| Build | Table Name | Explanation | Date |
|---|---|---|---|
| hg18 | refGene | FASTA sequences for all annotated transcripts in RefSeq Gene | 20150322 |
| hg19 | refGene | same as above | 20150322 |
| hg38 | refGene | save as above | 20150322 |
| hg18 | knownGene | FASTA sequences for all annotated transcripts in UCSC Known Gene | 20150322 |
| hg19 | knownGene | same as above | 20150322 |
| hg38 | knownGene | same as above | 20150322 |
| hg18 | ensGene | FASTA sequences for all annotated transcripts in ENSEMBL Gene | 20150322 |
| hg19 | ensGene | same as above | 20150322 |

---

### - For filter-based annotation

| Build | Table Name | Explanation | Date |
|---|---|---|---|
| hg18 | avsift | whole-exome SIFT scores for non-synonymous variants (obselete and should not be uesd any more) | 20120222 |
| hg19	|	avsift	|	same as above	| 20120222 |
| hg19 | avsnp138 | dbSNP138 with allelic splitting and left-normalization | 20141223 |
| hg19 | avsnp142 | dbSNP142 with allelic splitting and left-normalization | 20141228 | 
| hg18	|	ljb_sift	|	whole-exome LJBSIFT scores (1-SIFT!)	|	20120222 |
| hg19 | ljb_sift | same as above | 20120222 |
| hg18 | ljb2_sift | whole-exome SIFT scores (version 2) | 20130621 |
| hg19 | ljb2_sift | same as above | 20130621 |
| hg18 | ljb23_sift | whole-exome SIFT scores with missing values imputed | 20140222 |
| hg19 | ljb23_sift | same as above |  20140222 |
| hg18 | ljb26_sift | whole-exome SIFT scores with missing values imputed |  20140925 |
| hg19 | ljb26_sift | samea s above |  20140925 |
| hg18 | ljb_pp2 | whole-exome PolyPhen scores | 20120222 |
| hg19 | ljb_pp2 | same as above | 20120222 |
| hg18 | ljb2_pp2hdiv | whole-exome PolyPhen scores built on HumanDiv database (for complex phenotypes) | 20130621 |
| hg19 | ljb2_pp2hdiv | same as above | 20120222 |
| hg18 | ljb23_pp2hdiv | whole-exome PolyPhen 2 scores built on HumanDiv database (for complex phenotypes) | 20140222 |
| hg19 | ljb23_pp2hdiv | same as above | 20140222 |
| hg18 | ljb26_pp2hdiv | same as above | 20140925 |
| hg19 | ljb26_pp2hdiv | same as above | 20140925 |
| hg18 | ljb2_pp2hvar | whole-exome PolyPhen version 2 scores built on HumanVar database (for Mendelian phenotypes) | 20130621 |
| hg19 | ljb2_pp2hvar | same as above | 20130621 |
| hg18 | ljb23_pp2hvar | whole-exome PolyPhen 2 scores built on HumanVar database (for Mendelian phenotypes) | 20140222 |
| hg19 | ljb23_pp2hvar | same as above | 20140222 |
| hg19 | ljb26_pp2hvar | same as above | 20140925 |
| hg19 | ljb26_pp2hvar | same as above | 20140925 |
| hg18 | ljb26_cadd | whole-exome CADD scores, including raw score and categorical prediction | 20140915 |
| hg18 | ljb_phylop | whole-exome PhyloP scores | 20120222 |
| hg19 | ljb_phylop | same as above | 20120222 |
| hg18 | ljb2_phylop | whole-exome PhyloP scores | 20130621 |
| hg19 | ljb2_phylop | same as above | 20130621 |
| hg18 | ljb23_phylop | whole-exome PhyloP scores | 20140222 |
| hg19 | ljb23_phylop | same as above | 20140222 |
| hg18 | ljb26_phylop46way_placental | whole-exome PhyloP scores based on 46-way alignment placental subset | 20140925 |
| hg19 | ljb26_phylop46way_placental | same as above | 20140925 |
| hg18 | ljb26_phylop100way_vertebrate | whole-exome PhyloP scores based on 100-way alignment vertebrate subset | 20140925 |
| hg19 | ljb26_phylop100way_vertebrate | same as above | 20140925 |
| hg18 | ljb_lrt | whole-exome LRT scores | 20120222 |
| hg19 | ljb_lrt | same as above | 20120222 |
| hg18 | ljb2_lrt | whole-exome LRT scores (version 2) | 20130621 |
| hg19 | ljb2_lrt | same as above | 20130621 |
| hg18 | ljb23_lrt | whole-exome LRT scores | 20140222 |
| hg19 | ljb23_lrt | same as above | 20140222 |
| hg18 | ljb26_lrt | whole-exome LRT scores  | 20140915 |
| hg19 | ljb26_lrt | same as above | 20140915 |
| hg18 | ljb_mt | whole-exome MutationTaster scores | 20120222 |
| hg19 | ljb_mt | same as above | 20120222 |
| hg18 | ljb2_mt | whole-exome MutationTaster scores | 20130621 |
| hg19 | ljb2_mt | same as above | 20130621 |
| hg18 | ljb23_mt | whole-exome MutationTaster scores | 20140222 |
| hg19 | ljb23_mt | same as above | 20140222 |
| hg18 | ljb26_mt | whole-exome MutationTaster scores | 20140925 |
| hg19 | ljb26_mt | same as above | 20140925 |
| hg18 | ljb2_ma | whole-exome MutationAssessor scores | 20130621 |
| hg19 | ljb2_ma | same as above | 20140915 |
| hg18 | ljb23_ma | whole-exome MutationAssessor scores | 20140222 |
| hg19 | ljb23_ma | same as above | 20140222 |
| hg18 | ljb26_ma | whole-exome MutationAssessor scores | 20140925 |
| hg19 | ljb26_ma | same as above | 20140925 |
| hg18 | ljb2_fathmm | whole-exome FATHMM scores | 20130621 |
| hg19 | ljb2_fathmm | same as above | 20130621 |
| hg18 | ljb23_fathmm | whole-exome FATHMM scores | 20140222 |
| hg19 | ljb23_fathmm | same as above | 20140222 |
| hg18 | ljb26_fathmm | whole-exome FATHMM scores | 20140925 |
| hg19 | ljb26_fathmm | same as above | 20140925 |
| hg18 | ljb2_siphy | whole-exome SiPhy scores | 20130621 |
| hg19 | ljb2_siphy | same as above | 20130621 |
| hg18 | ljb23_siphy | whole-exome SiPhy scores | 20140222 |
| hg19 | ljb23_siphy | same as above | 20140222 |
| hg18 | ljb26_siphy | whole-exome SiPhy scores | 20140925 |
| hg19 | ljb26_siphy | same as above | 20140925 |
| hg18 | ljb_gerp++ | whole-exome GERP++ scores | 20120222 |
| hg19 | ljb_gerp++ | same as above | 20120222 |
| hg18 | ljb2_gerp++ | whole-exome GERP++ scores | 20130621 |
| hg19 | ljb2_gerp++ | same as above | 20130621 |
| hg18 | ljb23_gerp++ | whole-exome GERP++ scores | 20140222 |
| hg19 | ljb23_gerp++ | same as above | 20140222 |
| hg18 | ljb26_gerp++ | whole-exome GERP++ scores | 20140925 |
| hg19 | ljb26_gerp++ | same as above | 20140925 |
| hg18 | ljb23_metasvm | whole-exome MetaSVM scores | 20140222 |
| hg19 | ljb23_metasvm | same as above | 20140222 |
| hg18 | ljb26_metasvm | whole-exome MetaSVM scores | 20140925 |
| hg19 | ljb26_metasvm | same as above | 20140925 |
| hg18 | ljb23_metalr | whole-exome MetaLR scores | 20140222 |
| hg19 | ljb23_metalr | same as above | 20140222 |
| hg18 | ljb26_metalr | whole-exome MetaLR scores | 20140925 |
| hg19 | ljb26_metalr | same as above | 20140925 |
| hg18 | ljb26_vest | whole-exome VEST scores | 20140925 |
| hg19 | ljb26_vest | same as above | 20140925 |
| hg18 | ljb26_cadd | whole-exome CADD scores | 20140925 |
| hg19 | ljb26_cadd | same as above | 20140925 |
| hg18 | ljb_all | whole-exome LJBSIFT, PolyPhen, PhyloP, LRT, MutationTaster, GERP++ scores | 20120222 |
| hg19 | ljb_all | same as above | 20120222 |
| hg18 | ljb2_all | whole-exome SIFT scores, PolyPhen2 HDIV scores, PolyPhen2 HVAR scores, LRT scores, MutationTaster scores, MutationAssessor score, FATHMM scores, GERP++ scores, PhyloP scores and SiPhy scores | 20130621 |
| hg19 | ljb2_all | same as above | 20130621 |
| hg18 | ljb23_all | whole-exome SIFT scores, PolyPhen2 HDIV scores, PolyPhen2 HVAR scores, LRT scores, MutationTaster scores, MutationAssessor score, FATHMM scores, MetaSVM scores, MetaLR scores, GERP++ scores, PhyloP scores and SiPhy scores | 20140222 |
| hg19 | ljb23_all | same as above | 20140222 |
| hg18 | ljb26_all | whole-exome SIFT scores, PolyPhen2 HDIV scores, PolyPhen2 HVAR scores, LRT scores, MutationTaster scores, MutationAssessor score, FATHMM scores, MetaSVM scores, MetaLR scores, VEST scores, CADD scores, GERP++ scores, PhyloP scores and SiPhy scores from dbsnp version 2.6 | 20140925 |
| hg19 | ljb26_all | same as above |  20140925 |
| hg18 | cg46 | alternative allele frequency in 46 unrelated human subjects sequenced by Complete Genomics | 20120222 |
| hg19 | cg46 | same as above | index updated 2012Feb22 |
| hg18 | cg69 | allele frequency in 69 human subjects sequenced by Complete Genomics | 20120222 |
| hg19 | cg69 | same as above | 20120222 |
| hg19 | cosmic64 | COSMIC database version 64 | 20130520 |
| hg19 | cosmic65 | COSMIC database version 65 | 20130706 |
| hg19 | cosmic67 | COSMIC database version 67 | 20131117 |
| hg19 | cosmic67wgs | COSMIC database version 67 on WGS data | 20131117 |
| hg19 | cosmic68 | COSMIC database version 68 | 20140224 |
| hg19 | cosmic68wgs | COSMIC database version 68 on WGS data | 20140224 |
| hg19 | cosmic70 | same as above | 20140911 |
| hg18 | esp5400_aa | alternative allele frequency in African Americans in the NHLBI-ESP project with 5400 exomes | 20120711 |
| hg19 | esp5400_aa | same as above | 20120711 |
| hg18 | esp5400_ea | alternative allele frequency in European Americans in the NHLBI-ESP project with 5400 exomes | 20120711 |
| hg19 | esp5400_ea | same as above | 20120711 |
| hg18 | esp5400_all | alternative allele frequency in all subjects in the NHLBI-ESP project with 5400 exomes | 20120711 |
| hg19 | esp5400_all | same as above | 20120711 |
| hg18 | esp6500_aa | alternative allele frequency in African Americans in the NHLBI-ESP project with 6500 exomes | 20120621 |
| hg19 | esp6500_aa | same as above | 20120621 |
| hg18 | esp6500_ea | alternative allele frequency in European Americans in the NHLBI-ESP project with 6500 exomes | 20120621 |
| hg19 | esp6500_ea | same as above | 20120621 |
| hg18 | esp6500_all | alternative allele frequency in all subjects in the NHLBI-ESP project with 6500 exomes | 20120621 |
| hg19 | esp6500_all | same as above | 20120621 |
| hg18 | esp6500si_aa | alternative allele frequency in African Americans in the NHLBI-ESP project with 6500 exomes, including the indel calls and the chrY calls | 20130122 |
| hg19 | esp6500si_aa | same as above | 20130122 |
| hg18 | esp6500si_ea | alternative allele frequency in European Americans in the NHLBI-ESP project with 6500 exomes, including the indel calls and the chrY calls | 20130122 |
| hg19 | esp6500si_ea | same as above | 20130122 |
| hg18 | esp6500si_all | alternative allele frequency in all subjects in the NHLBI-ESP project with 6500 exomes, including the indel calls and the chrY calls | 20130122 |
| hg19 | esp6500si_all | same as above | 20130122 |
| hg18 | esp6500siv2_ea | alternative allele frequency in European American subjects in the NHLBI-ESP project with 6500 exomes, including the indel calls and the chrY calls. This is lifted over from hg19 by myself | 20141222 |
| hg19 | esp6500siv2_ea | same as above | 20141222 |
| hg38 | esp6500siv2_ea | same as above, lifted over from hg19 by myself |  20141222 |
| hg18 | esp6500siv2_aa | alternative allele frequency in African American subjects in the NHLBI-ESP project with 6500 exomes, including the indel calls and the chrY calls. This is lifted over from hg19 by myself. | 20141222 |
| hg19 | esp6500siv2_aa | same as above | 20141222 |
| hg38 | esp6500siv2_aa | same as above, lifted over from hg19 by myself | 20141222 |
| hg18 | esp6500siv2_all | alternative allele frequency in All subjects in the NHLBI-ESP project with 6500 exomes, including the indel calls and the chrY calls. This is lifted over from hg19 by myself. | 20141222 |
| hg19 | esp6500siv2_all | same as above | 20141222 |
| hg38 | esp6500siv2_all | same as above, lifted over from hg19 by myself | 20141222 |
| hg19 | exac01 | ExAC 65000 exome allele frequency data for ALL, AFR (African), AMR (Admixed American), EAS (East Asian), FIN (Finnish), NFE (Non-finnish European), OTH (other), SAS (South Asian)). | 20141101 |
| hg19 | exac02 | same as above but for version v0.2 | 20141101 |
| hg19 | exac03 | same as above but for version 0.3 | 20150302 |
| hg18 | 1000g (3 data sets) | alternative allele frequency data in 1000 Genomes Project | 20120222 |
| hg18 | 1000g2010 (3 data sets) | same as above | 20120222 |
| hg18 | 1000g2010jul (3 data sets) | same as above | 20120222 |
| hg18 | 1000g2012apr | I lifted over the latest 1000 Genomes Project data to hg18, to help researchers working with hg18 coordinates | 20120820 |
| hg19 | 1000g2010nov | same as above | 20120222 |
| hg19 | 1000g2011may | same as above | 20120222 |
| hg19 | 1000g2012feb | same as above | 20130308 |
| hg18 | 1000g2012apr (5 data sets) | This is done by liftOver of the hg19 data below. It contains alternative allele frequency data in 1000 Genomes Project for ALL, AMR (admixed american), EUR (european), ASN (asian), AFR (african) populations | 20130508 |
| hg19 | 1000g2012apr (5 data sets) | alternative allele frequency data in 1000 Genomes Project for ALL, AMR (admixed american), EUR (european), ASN (asian), AFR (african) populations | 20120525 |
| hg19 | 1000g2014aug (6 data sets) | alternative allele frequency data in 1000 Genomes Project for autosomes (ALL, AFR (African), AMR (Admixed American), EAS (East Asian), EUR (European), SAS (South Asian)). Based on 201408 collection v4 (based on 201305 alignment) | 20140915 |
| hg19 | 1000g2014sep (6 data sets) | alternative allele frequency data in 1000 Genomes Project for autosomes (ALL, AFR (African), AMR (Admixed American), EAS (East Asian), EUR (European), SAS (South Asian)). Based on 201409 collection v5 (based on 201305 alignment) | 20140925 |
| hg19 | 1000g2014oct (6 data sets) | alternative allele frequency data in 1000 Genomes Project for autosomes (ALL, AFR (African), AMR (Admixed American), EAS (East Asian), EUR (European), SAS (South Asian)). Based on 201409 collection v5 (based on 201305 alignment) but including chrX and chrY data finally! | 20141216 |
| hg18 | snp128 | dbSNP with ANNOVAR index files | 20120222 |
| hg18 | snp129 | same as above | 20120222 |
| hg19 | snp129 | liftover from hg18_snp129.txt | 20120809 |
| hg18 | snp130 | same as above | 20120222 |
| hg19 | snp130 | same as above | 20120222 |
| hg18 | snp131 | same as above | 20120222 |
| hg19 | snp131 | same as above | 20120222 |
| hg18 | snp132 | same as above | 20120222 |
| hg19 | snp132 | same as above | 20120222 |
| hg18 | snp135 | I lifted over SNP135 to hg18 | 20120820 |
| hg19 | snp135 | same as above | 20120222 |
| hg19 | snp137 | same as above | 20130109 |
| hg18 | snp138 | I lifted over SNP138 to hg18 | 20140910 |
| hg19 | snp138 | same as above | file and index updated 20140910 |
| hg18 | snp128NonFlagged | dbSNP with ANNOVAR index files, after removing those flagged SNPs (SNPs < 1% minor allele frequency (MAF) (or unknown), mapping only once to reference assembly, flagged in dbSnp as "clinically associated") | 20120524 |
| hg18 | snp129NonFlagged | same as above | 20120524 |
| hg18 | snp130NonFlagged | same as above | 20120524 |
| hg19 | snp130NonFlagged | same as above | 20120524 |
| hg18 | snp131NonFlagged | same as above | 20120524 |
| hg19 | snp131NonFlagged | same as above | 20120524 |
| hg18 | snp132NonFlagged | same as above | 20120524 |
| hg19 | snp132NonFlagged | same as above | 20120524 |
| hg19 | snp135NonFlagged | same as above | 20120524 |
| hg19 | snp137NonFlagged | same as above | 20130109 |
| hg19 | snp138NonFlagged | same as above | 20140222 |
| hg19 | nci60 | NCI-60 human tumor cell line panel exome sequencing allele frequency data | 20130724 |
| hg19 | clinvar_20131105 | CLINVAR database with Variant Clinical Significance (unknown, untested, non-pathogenic, probable-non-pathogenic, probable-pathogenic, pathogenic, drug-response, histocompatibility, other) and Variant disease name | 20140430 |
| hg19 | clinvar_20140211 | same as above | 20140430 |
| hg19 | clinvar_20140303 | same as above | 20140430 |
| hg19 | clinvar_20140702 | same as above | 20140712 |
| hg38 | clinvar_20140702 | same as above | 20140712 |
| hg19 | clinvar_20140902 | same as above | 20140911 |
| hg38 | clinvar_20140902 | same as above | 20140911 |
| hg19 | clinvar_20140929 | same as above | 20141002 |
| hg18 | popfreq_max | A database containing the maximum allele frequency from these tables: 1000G2012APR_ALL 1000G2012APR_AFR 1000G2012APR_AMR 1000G2012APR_ASN 1000G2012APR_EUR ESP6500si_ALL ESP6500si_AA ESP6500si_EA CG46 | 20130821 |
| hg19 | popfreq_max | same as above | 20130821 |
| hg18 | popfreq_all | A database containing the all allele frequency from these tables: popfreq_max, 1000G2012APR_ALL 1000G2012APR_AFR 1000G2012APR_AMR 1000G2012APR_ASN 1000G2012APR_EUR ESP6500si_ALL ESP6500si_AA ESP6500si_EA CG46 | 20140223 |
| hg19 | popfreq_all | same as above | 20140223 |
| hg18 | gerp++elem | conserved genomic regions by GERP++ | 20140223 |
| hg19 | gerp++elem | same as above | 20140223 |
| mm9 | gerp++elem | same as above | 20140223 |
| hg18 | gerp++gt2 | whole-genome GERP++ scores greater than 2 (RS score threshold of 2 provides high sensitivity while still strongly enriching for truly constrained sites. ) | 20120621 |
| hg19 | gerp++gt2 | same as above | 20120621 |
| hg19 | caddgt20 | whole-genome CADD scores that are within top 1% percentile, for most likely functional variants | 20140310 |
| hg19 | caddgt10 | whole-genome CADD scores that are within top 10% percentile, for most likely functional variants | 20140310 |
| hg19 | cadd | whole-genome CADD scores (350GB file, make sure you have sufficient disk space before downloading) | 20140223 |


---

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-48623707-1', 'openbioinformatics.org');
  ga('send', 'pageview');
</script>

<div id="disqus_thread"></div>
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES * * */
    var disqus_shortname = 'annovar';
    var disqus_identifier = 'download';
    var disquss_title = 'Download ANNOVAR';
    
    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>