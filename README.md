# autoSeqMan
#### Batch Assembling Contigs for Sanger Sequences ####
With the wide application of DNA barcoding technology, more and more DNA sequences are generated through Sanger sequencing platform. SeqMan (in package DNASTAR) is an excellent program with an easy-to-use graphical user interface (GUI) to assemble the Sanger sequences into contigs. While, with increasing of data size, larger set of samples as well as more loci sequenced make the contig assembling very tricky, majorly because a lot of manual operations are needed by using SeqMan. Here, we present a software called [autoSeqMan] to automatedly assemble contigs with program SeqMan. There are two modules available in autoSeqMan, [Classification] and [Assembly]. The Classification function will make some preprocessing for the sequence files, and the Assembly function will generate a SeqMan script to consecutively assemble the contigs for the classified files. This program could greatly save time for the people. We hope this software will be useful and helpful for those without programming experience but with a large set of samples to analyze.

![image](https://raw.githubusercontent.com/Sun-Yanbo/autoSeqMan/master/homepage.jpg)

**Sun Yan-Bo** (*sunyanbo@mail.kiz.ac.cn*)

**Kunming Institute of Zoology, Chinese Academy of Sciences**

### Update history ###
[Version 1.0.0] 2017-12-20
1. fix errors in showing running process (20180109)
2. add `Rename` function for formating ab1 files (20180109)
3. improve button UI (20180112)
4. automatedly detect the address of 'SeqMan'(20180112)
5. improve `Rename` function (2018-1-24)