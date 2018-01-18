# ONT_Barcoding

With the recent release of Albacore_2.1.7, I ran it on my barcoded data and compared it to v2.1.3

Here are some quick and dirty stats...

First up I didn't really get much of a difference....
This may be be because I wasn't affected by the bug. It had already recovered ~70% of the total reads.



I also got some interesting results running LSK108 kit --barcoding where it picked up some other barcodes. Here is the unfiltered quality scores of the barcodes

And if we filter that by Q >= 7

And here is the % match of the barcodes (taking the best match)



It's only ~50 reads that got classified out of the 12 NB barcodes, so I can just filter them out, but figured it was worth mentioning. 
