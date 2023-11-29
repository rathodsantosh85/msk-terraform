freud-mda
==

The FREUD MD Archive is a Linux big data component that performs two functions:
* Receives Kafka messages containing the MajorDomo stream and writes them to a short term Hive-accessible archive.
* Provides Hive (SQL-like) functionality to query the archive for data science and machine learning purposes.

The components are in the 'com.ps.freud.mda' namespace.
