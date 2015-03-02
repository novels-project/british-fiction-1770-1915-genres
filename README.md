Genre classifications for novels published in the British Isles 1770-1915
=========================================================================

The dataset `genres.json` contains (sub)genre classifications for novels
published between 1770 and 1915. The genres covered are

- gothic novels
- "silver fork" novels
- national tale novels

*The dataset is incomplete and focuses on 1800-1836.*

Novels are referenced by their Novels Project identifiers. Here is an example
of one entry:

```json
{
  "genre": "national tale",
  "novels_project_id": 581,
  "source": "Trumpener (1998)"
}
```

Sources
-------

Gothic novels benefit from a comprehensive bibliography. If a novel is
classified as gothic, it must appear in Lévy (1968) or be accompanied by a note
justifying its inclusion.

Silver fork novels and national tale novels lack comprehensive bibliographies
so the list of novels associated with those genres has been gathered from a
variety of sources. The set of novels classified as national tale novels begins
with Trumpener (1998). The set of novels classified as silver fork novels
begins with Adburgham (1983). Tentative additions have been made by Riddell
when a classification seems uncontroversial. As all changes are tracked via
version control and releases of the dataset are versioned; those using this
dataset are free to make adjustments where they see fit.

Coverage
--------

This dataset offers idiosyncratic coverage of novels belonging to these genres.
Currently the focus has been on finding novels which have been digitized. More
than 40% of novels published during this period have not been scanned or are
not available in publicly accessible repositories such as the Internet Archive.
It is best to treat the novels listed here as representing a *biased sample*.
Additional work is required for the list of national tale and silver fork
novels to be comprehensive.


References
----------
- Adburgham, Alison. *Silver Fork Society.* London: Constable, 1983.
- Lévy, Maurice. *Le Roman Gothique Anglais, 1764-1824.* Toulouse: Association des publications de la Faculté des lettres et sciences humaines., 1968.
- Trumpener, Katie. “National Tale.” In *Encyclopedia of the Novel*, edited by Paul E. Schellinger, 910–11. Chicago: Fitzroy Dearborn, 1998.
