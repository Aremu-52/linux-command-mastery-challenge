# Day 20 Practice Drill – Text Processing Checkpoint

## Task
From a raw log file, build one pipeline that filters for 'error' entries, extracts the timestamp column, sorts the results, and removes duplicates, all in a single chained command.

## Commands I ran

```bash
cat > sample.log << EOF
2026-09-01 10:00:01 INFO System started
2026-09-01 10:01:15 ERROR Disk full
2026-09-01 10:02:30 WARNING High memory usage
2026-09-01 10:03:45 ERROR Disk full
2026-09-01 10:04:10 INFO Backup completed
2026-09-01 10:05:22 ERROR Connection failed
2026-09-01 10:06:00 ERROR Disk full
2026-09-01 10:07:33 INFO User login
EOF

grep ERROR sample.log
grep -r ERROR .
grep -i error sample.log
sort sample.log
sort -n sample.log
sort sample.log | uniq
cut -d' ' -f1 sample.log
awk '{print $1}' sample.log
sed 's/ERROR/ISSUE/g' sample.log
grep ERROR sample.log | awk '{print $1, $2}' | sort | uniq

Result

Successfully filtered error lines.
Extracted timestamps.
Sorted and removed duplicates using a single pipeline.

What I learned
Pipes allow you to combine simple commands into powerful one-line solutions for log analysis and text processing.
text