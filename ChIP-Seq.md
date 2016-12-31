# Top 10 softwares for ChIP-seq data analysis.                    
####  Only for the 2nd generation sequencing of bulk cell populations.
##### Softwares for Single-cell ChIP-seq data analysis, please see :                         
##### https://github.com/CTLife/Top10/blob/master/Single-cell_ChIP-seq.md   
                                 
-----------------------                          
                                                             
## I. Check quality for FASTQ files
  1. FastQC : http://www.bioinformatics.babraham.ac.uk/projects/fastqc/              
  2. FastQ Screen : http://www.bioinformatics.babraham.ac.uk/projects/fastq_screen/                  
  3. NGS QC Toolkit : http://www.nipgr.res.in/ngsqctoolkit.html                               
  4. fastq-tools : https://github.com/dcjones/fastq-tools                                  
  5. fastqp : https://pypi.python.org/pypi/fastqp            
  6. QC3 : https://github.com/slzhao/QC3                      
  7. PRINSEQ : http://prinseq.sourceforge.net/              
  8. Rqc : https://bioconductor.org/packages/release/bioc/html/Rqc.html                                           
  9. seqTools : http://www.bioconductor.org/packages/release/bioc/html/seqTools.html     
  10. ShortRead : http://bioconductor.org/packages/release/bioc/html/ShortRead.html                                              
  MultiQC : https://github.com/ewels/MultiQC   (Aggregate the results from FastQC or FastQ Screen analyses across many samples into a single report.)             
  Other tools : [fastools](https://pypi.python.org/pypi/fastools) , [fqtools](https://github.com/alastair-droop/fqtools)  ,  [NGSUtils](http://ngsutils.org/) , [ngs-bits](https://github.com/imgag/ngs-bits) , [SolexaQA](http://solexaqa.sourceforge.net/)  , [systemPipeR](https://bioconductor.org/packages/release/bioc/html/systemPipeR.html)                                                                     
                   
-------------------------
             
## II. Filter and correct the raw reads
  1. Trimmomatic : http://www.usadellab.org/cms/?page=trimmomatic     
  2. cutadapt ： https://pypi.python.org/pypi/cutadapt     
  3. Galore : http://www.bioinformatics.babraham.ac.uk/projects/trim_galore/         
  4. AdapterRemoval :  https://github.com/MikkelSchubert/adapterremoval              
  5. Flexbar : https://github.com/seqan/flexbar 
  6. SeqPrep : https://github.com/jstjohn/SeqPrep               
  7. SeqPurge : https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-1069-7                   
  8. Lighter : https://github.com/mourisl/Lighter        
  9. Karect : http://aminallam.github.io/karect/          
  10. CoLoRMap : https://github.com/sfu-compbio/colormap                       
                                                                                                      
-------------------------
                                                                              
## III. Reads mapping (Mappers or Aligners)
  1. BWA-mem and BWA-aln:    https://github.com/lh3/bwa        
  2. Bowtie2 :      https://github.com/BenLangmead/bowtie2   
  3. Stampy :   www.well.ox.ac.uk/bioinformatics/Software/Stampy-latest.tgz   
  4. Novoalign : http://www.novocraft.com/support/download/  
  5. Subread : http://subread.sourceforge.net/     
  6. Yara : https://www.seqan.de/apps/yara/       
     RazerS 3 : https://www.seqan.de/apps/razers-3/      
  7. mrsFAST-Ultra :  http://sfu-compbio.github.io/mrsfast/      
  8. BBMap : https://sourceforge.net/projects/bbmap/            
  9. GMAP-GSNAP : http://research-pub.gene.com/gmap/                 
  10. deBGA :  https://github.com/hitbc/deBGA                      
                                          
-------------------------
                                              
## IV. Check quality for BAM files
1. Sambamba :  https://github.com/lomereiter/sambamba   
2. Biobambam2 : https://github.com/gt1/biobambam2  
3. NGS-QC Generator : http://www.ngs-qc.org/                                                 
4. htSeqTools : http://bioconductor.org/packages/release/bioc/html/htSeqTools.html                  
5. SAMtools :  http://www.htslib.org/                                      
6. Subread utilities : http://subread.sourceforge.net/                            
7. FASTQC : http://www.bioinformatics.babraham.ac.uk/projects/fastqc/                             
8. SAMstat : https://sourceforge.net/projects/samstat/                               
9. BAMStats : https://github.com/guigolab/bamstats                                         
10. qualimap : http://qualimap.bioinfo.cipf.es/                                              
11. ezBAMQC : https://pypi.python.org/pypi/ezBAMQC                                           
12. PRESEQ : https://github.com/smithlabcode/preseq                                           
13. Picard : https://github.com/broadinstitute/picard                                       
14. fastqp : https://github.com/mdshw5/fastqp                         
15. BamQC : https://github.com/s-andrews/BamQC               
16. BamTools : https://github.com/pezmaster31/bamtools                      
17. VCFtools : https://vcftools.github.io/perl_module.html             
18. BCFtools : https://samtools.github.io/bcftools/                              
                                                                                      
                                                                                                     
-------------------------
                                 
## V. Filter and correct the mapped reads
                         
## VI. Call peaks and differential peaks
                     
## VII. Conversion, Normalization and Reads density calculation
                                  
## VIII. Peaks annotation      
                                        
