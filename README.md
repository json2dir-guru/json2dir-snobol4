# json2dir-snobol4

json2dir in SNOBOL4: `json2dir.sno` (CSNOBOL4) checks UTF-8, parses the JSON document with a recursive SNOBOL4 pattern, validates it and emits a shell script, and the POSIX sh launcher `json2dir` runs that script.

    JSON2DIR_SNOBOL4=/path/to/snobol4 ./json2dir < tree.json
