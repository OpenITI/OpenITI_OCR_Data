# OpenITI OCR Data

Data for OCR analysis based on OpenITI corpus: texts files with PDFs of corresponding editions.

## Structure

All data is placed in subfolder `data`; subfolders inside are named after specific `URIs` from OpenITI, which include PDF files named `Vxx.pdf`, where `xx` is the volume number; `IDXXXXXX` is the ID of a specific edition. `OpenITI_URIs.txt` inside the folder includes the list of files (OpenITI URIs) that are based on the edition in PDFs (one URI per line)

```
OpenITI_OCR_Data
├── data
   ...
    └── 0748Dhahabi.TarikhIslam.IDXXXXXX-ara1
        ├── OpenITI_URIs.txt
        ├── V00.pdf
        ├── V01.pdf
        ├── V02.pdf
        ├── V03.pdf
        ├── V04.pdf
        ├── V05.pdf
        ├── V06.pdf
        ├── V07.pdf
        ├── V08.pdf
        ├── V09.pdf
        ├── V10.pdf
        ├── V11.pdf
        ├── V12.pdf
        ├── V13.pdf
        ├── V14.pdf
        └── V15.pdf
```

## Contents of `OpenITI_URIs.txt`

```
0748Dhahabi.TarikhIslam.Shamela0035100-ara1.mARkdown
0748Dhahabi.TarikhIslam.Sham30K0004263-ara1
```
