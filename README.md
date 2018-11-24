# ggplot2 Reference
This repository is intended as a detailed reference to the ggplot2 R package, and serves as a tutorial for interested learners.
You can find Jupyter notebooks covering mostly all aspects of ggplot2 - Layers, Scales, Guides, Facetting, Themes, etc.

Find out more at https://ggplot2.tidyverse.org/

## Layer - geoms
| Function | Description |
| --- | --- |
| 1) [geom_abline()][1] | Reference lines: horizontal, vertical and diagonal |
| 2) [geom_bar()][2] | Bar Charts |
| 3) [geom_bin2d()][3] | Heatmap of 2D bin counts |
| 4) [geom_blank()][4] | Draw nothing |
| 5) [geom_boxplot()][5] | A box and whiskers plot (in the style of Tukey) |
| 6) [geom_contour()][6] | 2D contours of a 3D surface |
| 7) [geom_count()][7] | Count overlapping points |
| 8) [geom_density()][8] | Smoothed density estimates |
| 9) [geom_density_2d()][9] | Contours of a 2D density estimate |
| 10) [geom_dotplot()][10] | Dot plot |
| 11) [geom_errorbarh()][11] | Horizontal error bars |
| 12) [geom_hex()][12] | Hexagonal heatmap of 2D bin counts |
| 13) [geom_histogram()][13] | Histograms and frequency polygons |
| 14) [geom_jitter()][14] | Jittered points |
| 15) [geom_errorbar()][15] | Vertical intervals: lines, crossbars & errorbars |
| 16) [geom_map()][16] | Polygons from a reference map |
| 17) [geom_line()][17] | Connect observations |
| 18) [geom_point()][18] | Points |
| 19) [geom_polygon()][19] | Polygons |
| 20) [geom_qq_line()][20] | A quantile - quantile plot |
| 21) [geom_quantile()][21] | Quantile regression |
| 22) [geom_ribbon()][22] | Ribbons and area plots |
| 23) [geom_rug()][23] | Rug plots in the margins |
| 24) [geom_segment()][24] | Line segments and curves |
| 25) [geom_smooth()][25] | Smoothed conditional means |
| 26) [geom_spoke()][26] | Line segments parameterized by location, direction and distance |
| 27) [geom_text()][27] | Text |
| 28) [geom_raster()][28] | Rectangles |
| 29) [geom_violin()][29] | Violin plot |
| 30) [geom_sf()][30] | Visualize sf objects |

## Layer - stats
| Function | Description |
| --- | --- |
| 1) [stat_ecdf()][31] | Compute empirical cumulative distribution |
| 2) [stat_ellipse()][32] | Compute normal confidence ellipses |
| 3) [stat_function()][33] | Compute function for each x value |
| 4) [stat_identity()][34] | Leave data as is |
| 5) [stat_summary_2d()][35] | Bin and summarize in 2D (rectangles & hexagons) |
| 6) [stat_summary_bin()][36] | Summarize y values at unique / binned x |
| 7) [stat_unique()][37] | Remove duplicates |

[1]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_abline().ipynb
[2]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_bar().ipynb
[3]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_bin2d().ipynb
[4]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_blank().ipynb
[5]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_boxplot().ipynb
[6]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_contour().ipynb
[7]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_count().ipynb
[8]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_density().ipynb
[9]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_density_2d().ipynb
[10]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_dotplot().ipynb
[11]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_errorbarh().ipynb
[12]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_hex().ipynb
[13]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_histogram().ipynb
[14]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_jitter().ipynb
[15]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_errorbar().ipynb
[16]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_map().ipynb
[17]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_line().ipynb
[18]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_point().ipynb
[19]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_polygon().ipynb
[20]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_qq_line().ipynb
[21]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_quantile().ipynb
[22]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_ribbon().ipynb
[23]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_rug().ipynb
[24]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_segment().ipynb
[25]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_smooth().ipynb
[26]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_spoke().ipynb
[27]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_text().ipynb
[28]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_raster().ipynb
[29]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_violin().ipynb
[30]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20geoms/geom_sf().ipynb
[31]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20stats/stat_ecdf().ipynb
[32]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20stats/stat_ellipse().ipynb
[33]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20stats/stat_function().ipynb
[34]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20stats/stat_identity().ipynb
[35]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20stats/stat_summary_2d().ipynb
[36]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20stats/stat_summary_bin().ipynb
[37]: https://github.com/Anacoder1/ggplot2_Reference/blob/master/Layers%20-%20stats/stat_unique().ipynb
