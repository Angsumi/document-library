# Angsumi Document Download Centre

[Open the download page](https://angsumi.online/document-library/) · [Sequencing downloads](https://github.com/Angsumi/document-library/releases/tag/sequencing-data-v1)

578 organized records, with downloadable originals, searchable PDFs and plain-text transcripts. The page searches names, categories, source names and extracted text, and works on mobile.

Document files and OCR derivatives are in `Library/`. The 304 sequencing `.fastq.gz` originals are attached individually to the `sequencing-data-v1` release to keep the Pages deployment below GitHub’s 1 GB limit. Their download URLs are included in `catalog.json`. The CSV includes both original local paths and direct download URLs. SQLite uses release URLs for sequencing downloads.

OCR can contain errors; check important details against original scans. Distinct document versions are retained and duplicates have been removed. See [duplicate cleanup](DUPLICATES.md) and [review notes](REVIEW_NEEDED.md).

This repository and website are public, including identity, banking and family documents, as explicitly authorized by the owner. No account credentials, local configuration or prior Git history are included.

## Medical documents

[Medical download page](medical.html) · [Dated index](Medical_Documents/INDEX.csv) · [Document guide](Medical_Documents/README.md)

31 medical photographs are organized by year and document type in `Medical_Documents/`, with date-first filenames, searchable PDFs and copyable transcripts. The prescription dated 17 January 2003 has an unverified patient identity. The associated ultrasound-film date is explicitly flagged as inferred. The three Health City laboratory pages also have a combined report. The page offers year and date-range filters and chronological sorting.
