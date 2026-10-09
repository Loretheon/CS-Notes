# Data Management
Since the mid-1970s, the study of Data Management (DM) has meant an almost exclusive study of
relational database systems. Depending on institutional context, students have studied, in varying
proportions, the following.
• Data modeling and database design: for example, E-R Data model, relational model,
normalization theory
• Query construction: e.g., relational algebra, SQL
• Query processing: e.g., indices (B+tree, hash), algorithms (e.g., external sorting, select, project,
join), query optimization (transformations, index selection)
• DBMS internals: e.g., concurrency/locking, transaction management, buffer management
Today's graduates are expected to possess DBMS user (rather than implementor) skills. These
primarily include data modeling and query construction; ability to take an unorganized collection of data,
organize it using a DBMS, and access/update the collection via queries.
Additionally, students need to study the following.
● The role data plays in an organization. This includes the Data Life Cycle: Creation-Processing-
Review/Reporting-Retention/Retrieval-Destruction.
● The social/legal aspects of data collection: e.g., scale, data privacy, database privacy (compliance)
by design, de-identification, ownership, reliability, database security, and intended and unintended
applications.
● Emerging and advanced technologies that are augmenting/replacing traditional relational systems,
particularly those used to support (big) data analytics, including NoSQL (e.g., JSON, XML, key-
value store databases), cloud databases, MapReduce, and dataframes.
● The existing and emerging roles for those involved with data management, which include the
following.

Product feature engineers: those who use both SQL and NoSQL operational databases.
Analytical engineers/data engineers: those who write analytical SQL, Python, and Scala
code to build data assets for business groups.
Business analysts: those who build/manage data most frequently with Excel spreadsheets.
Data infrastructure engineers: those who implement a data management system in a variety
of data applications (e.g., OLTP).
“Everyone” who produces or consumes data must understand the associated social, ethical,
and professional issues.
One role that transcends all the above categories is that of data custodian. Previously, data were seen
as a resource to be managed (Information Systems Management) just like other enterprise resources.
Today, data are seen in a larger context. Data about customers can now be seen as belonging to (or in
some national contexts, as owned by) those customers. There is now an accepted understanding that
the safe and ethical storage, and use, of institutional data is part of being a responsible data custodian.
Furthermore, we acknowledge the tension between a curricular focus on professional preparation
versus the study of a knowledge area as a scientific endeavor. This is particularly true with Data
Management. For example, proving (or at least knowing) the completeness of Armstrong’s Axioms is
fundamental in functional dependency theory. However, most computer science graduates will never
utilize this concept during their professional careers. The same can be said for many other topics in the
Data Management canon. Conversely, if our graduates can only normalize data into Boyce-Codd
normal form (using an automated tool) and write SQL queries, without understanding the role that
indices play in efficient query execution, we have done them and society a disservice.
To this end, the number of CS Core hours is relatively small relative to the KA Core hours. This
approach is designed to allow institutions with differing contexts to customize their curricula
appropriately. An institution that focuses on OLTP implementation, for example, would prioritize efficient
storage and data access, while an institution that focuses on product features would prioritize
programmatic access to extant databases.
However, an institution manages this tension, we wish to give voice to one of the ironies of computer
science curricula. Students typically spend much of their educational life reading (and writing) data from
a file or interactively, while outside of the academy the predominant data comes from databases
accessed programmatically. Perhaps in the not-too-distant future students will learn programmatic
database access early on and then continue this practice as they progress through their curriculum.
Finally, we understand that while the Data Management KA may be orthogonal to the SEC (Security)
and SEP (Society, Ethics, and the Profession) KAs, it is also ground zero for these (and other)
knowledge areas. When designing persistent data stores, the question of what should be stored must
be examined from both legal and ethical perspectives. Are there privacy concerns? And just as
importantly, how well protected is the data?


## Knowlege Units
- The Role of Data
- Core Database Systems Concepts
- Data Modeling
- Relational Databases
- Query Construction
- Query Processing
- DBMS Internals
- NoSQL Systems
- Data Security & Privacy
- Data Analytics
- Distributed Databases/Cloud Computing
- Semi-structured and Unstructured Databases
- Society, Ethics, and the Profession