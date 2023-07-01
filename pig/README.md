# Conclusion
Company names fuzzy matching stage takes too long - it would require performance tuning. Joining two datasets on a city column only partly reduces data crossing; the join result contains too much data. What could also be considered is that fuzzy matching UDF could be optimized, in the underlying FuzzyWuzzy library.
# Run example
```
docker exec -it master pig /usr/local/pig-scripts/tmp_mix.pig
```
# Note
The recommended way to build JAR files is using code editor, to properly add JAR metadata
