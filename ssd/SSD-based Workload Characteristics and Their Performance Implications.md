# SSD-based Workload Characteristics and Their Performance Implications

* Link to the paper
    * https://dl.acm.org/doi/pdf/10.1145/3423137
    * http://iotta.snia.org/traces/block-io
    * <a href="ssd/SSD-based Workload Characteristics and Their Performance Implications.pdf">PDF</a>



* Outline
  * What is the research and why does it matter?
    * I/O work load analysis
    * 
  * How does it work?
  * How is the research evaluated?
  * Conclusion



# Data Description 

| Device Major Number | Device Minor Number | CPU Core ID | Record ID | Timestamp (ns)   | Process ID | Trace Action | Operation Type | Sector Number + I/O Size | Process Name |
|---------------------|---------------------|-------------|-----------|------------------|------------|--------------|----------------|--------------------------|--------------|
| 259                 | 2                   | 0           | 1         | 0.000000000      | 4020       | Q            | R              | 282624 + 8               | [java]       |
