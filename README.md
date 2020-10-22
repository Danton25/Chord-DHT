# Distributed-Hash-Table-CHORD
Distributed Hash Table using ring based CHORD

## Goal
Implement a Chord based Distributed HashTable functionality on Android devices. Although the design is based on Chord, it is a simplified version of Chord i.e we do not need to implement finger tables and finger-based routing; we also do not need to handle node leaves/failures.

### There are three tasks that have to be implemented: -

1. ID space partitioning/re-partitioning
2. Ring-based routing
3. Node joins

NOTE if there are multiple instances of the app, all instances should form a Chord ring and serve insert/query requests in a distributed fashion according to the Chord protocol

### Steps Involved:
  1) Writing the Content Provider
  2) Writing the Main Activity

### Other files:
  1) create_avd.py - To create AVDs
  2) run_avd.py - To run the AVDs (command: python run_avd.py 5)
  3) set_redir.py - To establish Connection among AVDs (command: python set_redir.py 10000)
  4) simpledht-grading.osx - Test script (command: $ chmod +x < grader executable> - $ ./< grader executable> apk file path)
    (‘-h’ argument will show you what options are available. Usage is shown below: - - $ < grader executable> -h)
