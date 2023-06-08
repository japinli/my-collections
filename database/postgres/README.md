# [PostgreSQL][]

## Blogs

### Site Blogs

1. [PostgreSQL Planet](https://planet.postgresql.org/)
2. [PostgresPro](https://postgrespro.com/blog)
3. [Cybertec](https://www.cybertec-postgresql.com/en/blog/)
4. [Fujitsu PostgreSQL Blog](https://www.postgresql.fastware.com/blog)

### Personal Blogs

1. [Bruce Momjian](https://momjian.us/)
2. [Andreas Scherbaum](https://andreas.scherbaum.la/)
3. [张树杰 Zhang ShuJie](http://zhangshujie.cn/)
4. [Peter Eisentraut](http://peter.eisentraut.org/)


### Articles

1. [PostgreSQL Indexes: B-Tree](https://commandprompt.com/education/postgresql-indexes-b-tree/)

   Partial Indexes, Index Only Scans, Covering Indexes, Prefix Indexes (MySQL)

2. [How Postgres Makes Transactions Atomic](https://brandur.org/postgres-atomicity)


## Books

1. [The Internals of PostgreSQL](https://www.interdb.jp/pg/)
2. [PostgreSQL 14 Internals](https://postgrespro.com/community/books/internals)


## PPTs

1. [Scalable MVCC Solution for Many Core Machines](https://www.pgcon.org/2015/schedule/events/810.en.html)
2. [The Future is CSN](https://postgrespro.ru/media/2019/10/26/future_is_csn.pdf)
3. [Solving Postgres Wicked Problems](https://www.socallinuxexpo.org/sites/default/files/presentations/solving-postgres-wicked-problems.pdf)
4. [Don't Need a Database Backup Policy](https://www.postgresql.eu/events/pgdaymed2023/sessions/session/4506/slides/375/Don't%20Need%20DB%20Backup%20Policy%20V4.pdf)

   * Wraparound - Native 64-bit transaction ids
   * Failover Will Probably Lose Data - Multimaster replcation
   * Inefficient Replication That Spreads Corruption - Row-level replication
   * MVCC Garbage Frequently Painful - Non-persistent undo log
   * Process-Per-Connection = Pain at Scale - Migration to multithread model
   * Primary Key Index is a Space Hog - Index-organized tables
   * Major Version Upgrades Can Require Downtime - Multimaster + per-node upgrade
   * Somewhat Cumbersome Replication Setup - Simple setup of raft-based multimaster
   * Ridiculous No-Planner-Hints Dogma - In-core planner hints
   * No Block Compression - Block-level compression

4. [Transaction Processing in PostgreSQL](https://www.postgresql.org/files/developer/transactions.pdf)


## Talks

* [Andres Freund](https://anarazel.de/talks/)


[PostgreSQL]: https://www.postgresql.org/docs/current/index.html
