This folder contains the LSoT reasoning, across interventions, for BenchmarkTest00251 java file which was flagged vulnerable for CWE-501 Trust Boundary Violation. 

Ground truth: Vulnerable.

The anonymization process creates a mapping JSON file to control and avoid collisions between anonymized names for Java files and classes. Through this mapping JSON file below:
```
{
  "BenchmarkTest00251.java": {
    "new_file": "cls_nxtvvi_0332.java",
    "original_class": "BenchmarkTest00251",
    "new_class": "cls_nxtvvi_0332",
    "original_base_string": "BenchmarkTest",
    "new_base_string": "base_nxtvvi_0332_"
  }
}
```
We know how to call and retrieve the original source code (in BenchmarkTest00251.java) and the anonymized version (in cls_nxtvvi_0332.java)
 
