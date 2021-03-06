.. note::
    :class: sphx-glr-download-link-note

    Click :ref:`here <sphx_glr_download_generated_gallery_plot_breast_cancer.py>` to download the full example code
.. rst-class:: sphx-glr-example-title

.. _sphx_glr_generated_gallery_plot_breast_cancer.py:


Breast Cancer
================



This example generates a Mapper built from the `Wisconsin Breast Cancer Dataset <https://www.kaggle.com/uciml/breast-cancer-wisconsin-data>`_.

`Visualization of the breast cancer mapper <../../_static/breast-cancer.html>`_


The reasoning behind the choice of lenses in the demonstration above is:

- **For lens1:** Lenses that make biological sense; in other words, lenses that highlight special features in the data, that I know about. 
- **For lens2:** Lenses that disperse the data, as opposed to clustering many points together.

In the case of this particualr data, using an anomaly score (in this case calculated using the IsolationForest from sklearn) makes biological sense since cancer cells are anomalous. For the second lens, we use the :math:`l^2` norm.

For an interactive exploration of lens for the breast cancer, see the `Choosing a lens notebook <../../notebooks/Cancer-demo.html>`_.



.. image:: ../../../examples/images/breast-cancer.png


.. image:: /generated/gallery/images/sphx_glr_plot_breast_cancer_001.png
    :class: sphx-glr-single-img


.. rst-class:: sphx-glr-script-out

 Out:

 .. code-block:: none

    KeplerMapper(verbose=3)
    ..Composing projection pipeline of length 1:
            Projections: l2norm
            Distance matrices: False
            Scalers: MinMaxScaler(copy=True, feature_range=(0, 1))
    ..Projecting on data shaped (569, 31)

    ..Projecting data using: l2norm

    ..Scaling with: MinMaxScaler(copy=True, feature_range=(0, 1))

    Mapping on data shaped (569, 31) using lens shaped (569, 2)

    Minimal points in hypercube before clustering: 2
    Creating 225 hypercubes.
    Cube_0 is empty.

    Cube_1 is empty.

    Cube_2 is empty.

    Cube_3 is empty.

    Cube_4 is empty.

    Cube_5 is empty.

    Cube_6 is empty.

       > Found 2 clusters in hypercube 7.
    Cube_8 is empty.

    Cube_9 is empty.

       > Found 2 clusters in hypercube 10.
       > Found 2 clusters in hypercube 11.
    Cube_12 is empty.

    Cube_13 is empty.

    Cube_14 is empty.

       > Found 2 clusters in hypercube 15.
    Cube_16 is empty.

    Cube_17 is empty.

    Cube_18 is empty.

    Cube_19 is empty.

    Cube_20 is empty.

       > Found 2 clusters in hypercube 21.
       > Found 2 clusters in hypercube 22.
    Cube_23 is empty.

       > Found 2 clusters in hypercube 24.
    Cube_25 is empty.

       > Found 2 clusters in hypercube 26.
       > Found 2 clusters in hypercube 27.
    Cube_28 is empty.

       > Found 2 clusters in hypercube 29.
       > Found 2 clusters in hypercube 30.
       > Found 2 clusters in hypercube 31.
       > Found 2 clusters in hypercube 32.
       > Found 2 clusters in hypercube 33.
       > Found 2 clusters in hypercube 34.
       > Found 2 clusters in hypercube 35.
       > Found 2 clusters in hypercube 36.
    Cube_37 is empty.

       > Found 2 clusters in hypercube 38.
       > Found 2 clusters in hypercube 39.
    Cube_40 is empty.

       > Found 2 clusters in hypercube 41.
    Cube_42 is empty.

       > Found 2 clusters in hypercube 43.
       > Found 2 clusters in hypercube 44.
       > Found 2 clusters in hypercube 45.
       > Found 2 clusters in hypercube 46.
    Cube_47 is empty.

    Cube_48 is empty.

       > Found 2 clusters in hypercube 49.
    Cube_50 is empty.

    Cube_51 is empty.

       > Found 2 clusters in hypercube 52.
       > Found 2 clusters in hypercube 53.
    Cube_54 is empty.

       > Found 2 clusters in hypercube 55.
       > Found 2 clusters in hypercube 56.
       > Found 2 clusters in hypercube 57.
       > Found 2 clusters in hypercube 58.
       > Found 2 clusters in hypercube 59.
       > Found 2 clusters in hypercube 60.
       > Found 2 clusters in hypercube 61.
       > Found 2 clusters in hypercube 62.
       > Found 2 clusters in hypercube 63.
       > Found 2 clusters in hypercube 64.
    Cube_65 is empty.

       > Found 2 clusters in hypercube 66.
       > Found 2 clusters in hypercube 67.
       > Found 2 clusters in hypercube 68.
       > Found 2 clusters in hypercube 69.
       > Found 2 clusters in hypercube 70.
       > Found 2 clusters in hypercube 71.
       > Found 2 clusters in hypercube 72.
       > Found 2 clusters in hypercube 73.
       > Found 2 clusters in hypercube 74.
       > Found 2 clusters in hypercube 75.
       > Found 2 clusters in hypercube 76.
       > Found 2 clusters in hypercube 77.
       > Found 2 clusters in hypercube 78.
       > Found 2 clusters in hypercube 79.
       > Found 2 clusters in hypercube 80.
       > Found 2 clusters in hypercube 81.
       > Found 2 clusters in hypercube 82.
       > Found 2 clusters in hypercube 83.
       > Found 2 clusters in hypercube 84.
       > Found 2 clusters in hypercube 85.
       > Found 2 clusters in hypercube 86.
       > Found 2 clusters in hypercube 87.
       > Found 2 clusters in hypercube 88.
       > Found 2 clusters in hypercube 89.
       > Found 2 clusters in hypercube 90.
       > Found 2 clusters in hypercube 91.
       > Found 2 clusters in hypercube 92.
       > Found 2 clusters in hypercube 93.
       > Found 2 clusters in hypercube 94.
       > Found 2 clusters in hypercube 95.
       > Found 2 clusters in hypercube 96.
       > Found 2 clusters in hypercube 97.
       > Found 2 clusters in hypercube 98.
       > Found 2 clusters in hypercube 99.
       > Found 2 clusters in hypercube 100.
       > Found 2 clusters in hypercube 101.
       > Found 2 clusters in hypercube 102.
    Cube_103 is empty.

       > Found 2 clusters in hypercube 104.
       > Found 2 clusters in hypercube 105.
       > Found 2 clusters in hypercube 106.

    Created 297 edges and 154 nodes in 0:00:00.828818.
    Wrote visualization to: output/breast-cancer.html




|


.. code-block:: default


    import sys
    try:
        import pandas as pd
    except ImportError as e:
        print("pandas is required for this example. Please install with `pip install pandas` and then try again.")
        sys.exit()

    import numpy as np
    import kmapper as km
    import sklearn
    from sklearn import ensemble

    # For data we use the Wisconsin Breast Cancer Dataset
    # Via: 
    df = pd.read_csv("data/breast-cancer.csv")
    feature_names = [c for c in df.columns if c not in ["id", "diagnosis"]]
    df["diagnosis"] = df["diagnosis"].apply(lambda x: 1 if x == "M" else 0)
    X = np.array(df[feature_names].fillna(0))  # quick and dirty imputation
    y = np.array(df["diagnosis"])

    # We create a custom 1-D lens with Isolation Forest
    model = ensemble.IsolationForest(random_state=1729)
    model.fit(X)
    lens1 = model.decision_function(X).reshape((X.shape[0], 1))

    # We create another 1-D lens with L2-norm
    mapper = km.KeplerMapper(verbose=3)
    lens2 = mapper.fit_transform(X, projection="l2norm")

    # Combine both lenses to create a 2-D [Isolation Forest, L^2-Norm] lens
    lens = np.c_[lens1, lens2]

    # Create the simplicial complex
    graph = mapper.map(lens,
                       X,
                       cover=km.Cover(n_cubes=15, perc_overlap=0.4),
                       clusterer=sklearn.cluster.KMeans(n_clusters=2,
                                                        random_state=1618033))

    # Visualization
    mapper.visualize(graph,
                     path_html="output/breast-cancer.html",
                     title="Wisconsin Breast Cancer Dataset",
                     custom_tooltips=y)


    import matplotlib.pyplot as plt
    km.draw_matplotlib(graph)
    plt.show()

.. rst-class:: sphx-glr-timing

   **Total running time of the script:** ( 0 minutes  1.926 seconds)


.. _sphx_glr_download_generated_gallery_plot_breast_cancer.py:


.. only :: html

 .. container:: sphx-glr-footer
    :class: sphx-glr-footer-example



  .. container:: sphx-glr-download

     :download:`Download Python source code: plot_breast_cancer.py <plot_breast_cancer.py>`



  .. container:: sphx-glr-download

     :download:`Download Jupyter notebook: plot_breast_cancer.ipynb <plot_breast_cancer.ipynb>`


.. only:: html

 .. rst-class:: sphx-glr-signature

    `Gallery generated by Sphinx-Gallery <https://sphinx-gallery.readthedocs.io>`_
