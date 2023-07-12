# nicpolpy_sag_2022
Zenodo: [![DOI](https://zenodo.org/badge/540730018.svg)](https://zenodo.org/badge/latestdoi/540730018)


The supporting information of NICPolpy paper: [Bach et al. 2022 SAG, 5, 4](http://www.nhao.jp/research/starsandgalaxies/05.html#2022J-4).

For any other details, see [NICpolpy](https://github.com/ysBach/NICpolpy).

## Citation ✅
Please consider one or both of the following citation(s) depending on what you used (BibTeX):

1. ``NICpolpy`` Zenodo (when you just want to mention which package was used).
```
@software{nicpolpy_v013,
  author       = {Yoonsoo P. Bach},
  title        = {ysBach/NICpolpy: NICpolpy v0.1.3},
  month        = dec,
  year         = 2022,
  publisher    = {Zenodo},
  version      = {publish},
  doi          = {10.5281/zenodo.7391454},
  url          = {https://doi.org/10.5281/zenodo.7391454}
}
```
2. The implementation details document ([SAG official website](http://www.nhao.jp/research/starsandgalaxies/05.html#2022J-4), peer-reviewed, non-SCI)
```
@ARTICLE{2022_SAG_NICpolpy,
       author = {{Bach}, Yoonsoo P. and {Ishiguro}, Masateru and {Takahashi}, Jun and {Geem}, Jooyeon},
        title = "{Data Reduction Process and Pipeline for the NIC Polarimetry Mode in Python, NICpolpy}",
      journal = {Stars and Galaxies (arXiv:2212.14167)},
     keywords = {methods: data analysis, methods: observational, techniques: image processing, techniques: polarimetric},
         year = 2022,
        month = dec,
       volume = {5},
          eid = {4},
        pages = {4},
archivePrefix = {arXiv},
       eprint = {2212.14167},
 primaryClass = {astro-ph.IM},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2022arXiv221214167B},
}
```


# Important Notes
* You may have to download ``cal-flat_xxxxxxxx-lv1/`` AND ``masks/`` contents before using ``NICpolpy``.
* See ``example/`` for an example usage of ``NICpolpy``.


## Contents
1. ``cal-flat_20180507-lv1/``: The level 1 flats taken on 2018-05-07 are combined to generate these master flat.
1. ``cal-flat_20200603-lv1/``: The level 1 flats taken on 2020-06-03 are combined to generate these master flat.
1. ``masks/``: The initial mask (``imask``) files.
1. ``example/``: Example of using ``NICPolpy``.
   1. ``sample_data_and_code/``: About 100 sample FITS files and the [reduction code](https://nbviewer.org/github/ysBach/nicpolpy_sag22sm/blob/main/example/sample_data_and_code/20190417_SP.ipynb) (Jupyter notebook) using ``NICPolpy``.
   2. ``sample_result_logdirectory.zip``: **If you do not want to run the code**, please just unzip this file to see the log directory contents.
2. ``flat_analyses/``: The directory containing the flat analyses.
   1. Please see ``sm1.pptx`` for explanations of figures.
   2. ``media/``: The final videos used in ``sm1.pptx``.
   3. ``figs/``: The raw figure files to make movies
   4. Others are summary files of individual flat frames, shell script of video-maker, and raw movie files.


