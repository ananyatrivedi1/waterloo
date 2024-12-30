Following is summary of the topics and concepts used in each of the uploaded assignments:

---

### **A0**
- **Setting up PySpark**: Initialization of SparkContext and configuration.
- **Basic RDD operations**: Filter, map, reduce, collect.
- **Pair RDDs**: Creation and operations such as reduceByKey, groupByKey.
- **File reading**: Reading data from text files into RDDs.
- **Transformations and actions**: Distinction between lazy and eager operations.

---

### **A1**
- **Advanced RDD operations**: Use of flatMap, sortByKey, and combining multiple RDDs.
- **Custom partitioning**: Implementing and using custom partitioners.
- **Joins**: Operations on paired RDDs, including inner and outer joins.
- **Aggregations**: AggregateByKey and combineByKey for reducing and merging values.
- **Performance tuning**: Importance of caching and understanding lineage.

---

### **A2**
- **DataFrames**: Introduction to Spark DataFrames as a higher-level abstraction.
- **Schema definition**: Explicitly defining schemas using StructType.
- **SQL queries**: Registering DataFrames as SQL views and executing SQL commands.
- **File formats**: Reading and writing in different formats (CSV, JSON, Parquet).
- **Basic queries**: Filtering, selecting, and grouping operations on DataFrames.

---

### **A3**
- **DataFrame transformations**: Complex operations such as groupBy, pivot, and agg.
- **Joins in DataFrames**: Handling multiple join types like inner, outer, and cross joins.
- **Window functions**: Using windowing operations for tasks like ranking and cumulative sums.
- **UDFs (User Defined Functions)**: Writing and applying custom Python functions to DataFrames.
- **Broadcast joins**: Optimizing joins when one dataset is small.

---

### **A4**
- **Spark SQL**: Advanced SQL queries on registered DataFrames.
- **Analytical queries**: Writing complex aggregations and nested queries.
- **Working with multiple datasets**: Joining, filtering, and deduplicating data from multiple DataFrames.
- **Performance considerations**: Efficient execution using caching and avoiding unnecessary shuffles.

---

### **A5**
- **TPC-H benchmark tables**: Manipulating tables with a well-known relational schema.
- **Structured query examples**:
  - Using SQL to find top records, aggregate results, and filter by conditions.
  - Equivalent DataFrame operations to achieve the same results.
- **Integration of multiple tables**: Joining datasets based on keys (e.g., nation, customer).
- **Complex queries**: Combining SQL and DataFrame operations to produce advanced results.
- **Optimization**: Understanding caching, partitioning, and query planning.

---

### **A6**
- **Streaming context setup**: Using Spark StreamingContext for real-time data processing.
- **DStreams**: Introduction to Discretized Streams and their transformations.
- **Window operations**: Sliding and tumbling windows to analyze data over specific time intervals.
- **Real-time analysis**:
  - Finding the smallest distance measured by sensors over a 3-second window.
  - Calculating movement ratios based on streamed data.
- **Custom streaming operations**: Leveraging functions like `foreachRDD` for specialized output.
- **Streaming optimizations**: Efficient use of reduce and window operations.

---

These assignments emphasize distributed data processing, transformation, and analysis using Spark’s RDDs, DataFrames, SQL, and Streaming.