# Installation

## Local

1. [Install Java (1.7 or higher)](https://java.com/en/download/help/download_options.xml)
2. [Install Spark](https://spark.apache.org/downloads.html)
    a. Choose "Pre-built for Hadoop 1.X" as the package type
    b. Click the "Download Spark" link and download from a mirror
    c. Untar the file and rename the folder `spark`. The full path to this folder will be referred to as `$SPARK_HOME`
3. [Install Anaconda Python](http://continuum.io/downloads)
4. Rename `$SPARK_HOME/conf/spark-env.sh.template` to `$SPARK_HOME/conf/spark-env.sh` (`spark-env.cmd` o n Windows) and add `export PYSPARK_PYTHON=/path/to/anaconda/bin/python` to the end of the file.
5. Launch an IPython notebook with Pyspark: `IPYTHON_OPTS="notebook" $SPARK_HOME/bin/pyspark --master local[*]`