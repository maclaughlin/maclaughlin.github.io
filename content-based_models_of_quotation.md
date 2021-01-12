## Datasets

This page contains two of the datasets (KJB-CA and LAT-EJC) from our paper Content-based Models of Quotation (EACL-21). Unfortunately, we are unable to share any data from the JSTOR Understanding Series (KJB-JA, SHAK-JA, ABL-JA). Please contact JSTOR https://www.jstor.org/dfr/ to discuss getting access to this data.

If you use either of our datasets, please cite our paper: 

```bibtex
@inproceedings{maclaughlin-smith-2021-content,
  author={Ansel MacLaughlin and David A. Smith},
  title={Content-based Models of Quotation},
  booktitle={EACL},
  year={2021}
}
```

### kjb-ca.jsonl: King James Bible - Chronicling America: 

* JSON Lines file (each line contains a JSON record)
* Each record contains information for a single verse and has the following fields:
  * text: the text of the verse (e.g. "In the beginning God created the heaven...")
  * testament: Old Testament (OT) or New Testament (NT)
  * book: the corresponding book (e.g. Genesis)
  * chapter: the verse's chapter in the book (e.g. 1)
  * verse: the verse number in the chapter (e.g. 4)
  * quote: number of times the corresponding verse was quoted in the Chronicling America collection
* This data is simply a processed version of the America's Public Bible dataset from https://americaspublicbible.org/


### lat-ejc.jsonl: Latin Text - JSTOR Early Journal Content: 

* JSON Lines file (each line contains a JSON record)
* Each record contains information for a single quote and has the following fields:
  * book: the URN[http://sites.tufts.edu/perseusupdates/2021/01/05/what-is-a-cts-urn/] (e.g. urn:cts:greekLit:tlg2042.tlg028.1st1K-lat1)
* This data is simply a processed version of the America's Public Bible dataset from https://americaspublicbible.org/

