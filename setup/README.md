# Installation

## Local

1. [Install Java (1.7 or higher).](https://java.com/en/download/help/download_options.xml)
2. [Install Spark.](https://spark.apache.org/downloads.html)
    a. Choose "Pre-built for Hadoop 1.X" as the package type.
    b. Click the "Download Spark" link and download from a mirror.
    c. Untar the file and rename the folder `spark`. The full path to this folder will be referred to as `$SPARK_HOME`

3. Install Python2.7 and IPython.
    a. The easiest way: [Install Anaconda Python.](http://continuum.io/downloads)

4. Open a shell in `pyspark-for-data-science/setup` and launch an IPython notebook with Pyspark: `bash run-pyspark.sh` (`run-pyspark.cmd` for Windows).
5. Execute cells in the notebook by hitting `Shift + Enter`.