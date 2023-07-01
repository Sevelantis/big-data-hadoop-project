# Conclusion
Significantly easier and faster to implement than using PIG. Functional programming nature allows to run more efficient queries. 
 
# Issues to address
- RAM memory tuning
- bottlenecks identification
- efficient queries
- Company names Fuzzy Matching underlying update to the latest version significantly impacted bottlenecks' processing time, the fix was to install the correct pip version. Instead: `pip install fuzzywuzzy` --> `pip install fuzzywuzzy[speedup]`

# Example run
```
time docker exec -it master spark-submit /usr/local/spark-scripts/tmp_companies_extracted.py
```
