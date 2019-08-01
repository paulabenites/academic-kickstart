+++
# A Recent Blog Posts section created with the Pages widget.
# This section displays recent blog posts from `content/post/`.

widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 50  # Order that this section will appear.

title = "Released Code"
subtitle = ""

[content]

  # Page type to display. E.g. post, talk, or publication.
  page_type = "post"

  # Choose how much pages you would like to display (0 = all pages)
  count = 5

  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    exclude_featured = false

[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 2

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"

  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"

  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  

[advanced]
 # Custom CSS. 
 css_style = ""

 # CSS class.
 css_class = ""

+++

> **Mimesis Namespace Generator**
>
> Development team: Cristina Abad and Shadi Noghabi
>
> Can  create large and realistic hierarchical namespaces. This tool preserves  the following distributions (as given by the configuration file used):  directories at each depth, subdirectories per directory, files at each  depth, files per directory, file sizes, file creation stamps. Details on  [IEEE/ACM UCC 2012](https://wiki.engr.illinois.edu/download/attachments/194990492/cabad_UCC_2012.pdf?version=1&modificationDate=1348001615000) publication. Repository on [Github](https://github.com/s-noghabi/Mimesis-Namespace-Generator). 
>
> 
>  
>
> **MimesisBench**
>
> Development team: Cristina Abad
>
> Metadata-intensive benchmark for the HDFS name node. Access model described on my [IFIP Performance 2013 paper](https://wiki.engr.illinois.edu/download/attachments/194990492/cabad_IFIP_Performance_2013.pdf?version=1&modificationDate=1377532487000). Details of the benchmark on my [ICAC 2014](https://www.usenix.org/system/files/conference/icac14/icac14-paper-abad.pdf) publication. Repository on [Github](https://github.com/cristina-abad/MimesisBench).
>
> 
>
> **KV-Replay**Development team: Edwin Boza and Cristina AbadTool based on YCSB that can replay real traces under varying models. Details in the IC2E 2017 paper. Repository on [Github](https://github.com/ebozag/KV-replay).

**Multi-tier storage system simulator**Development team: César San-Lucas and Cristina AbadPython  program that simulates several multi-tiered storage system policies and  supports synthetic as well as trace-based workloads. Details in the  ETCM 2016 paper. Repository on [Github](https://github.com/SLACE93/multi-tier-storage-systems-simulator).
**CLOUDCAL: Cloud budget estimation tool**Development team: Edwin Boza and Cristina AbadPython  program that simulates several cloud service configurations and  calculates cost as well as average and tail latencies. Details in the  ETCM 2017 paper. Repository on [Github](https://github.com/ebozag/CLOUDCAL).



**Open-source implementation of SHARDSDevelopment team: Jorge MurilloOpen-source  implementation of the SHARDS miss rate estimation data structure, to be  used in the work outlined in the ICPE 2017 paper. Repository on Github.**

**Memchached+SHARDSDevelopment team: Gustavo Totoy and Jorge MurilloInstrumented version of Memcached so that it calculates full miss rate curves using SHARDS. Repository on Github.**