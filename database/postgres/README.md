# PostgreSQL

## Blogs

1. [PostgreSQL Indexes: B-Tree](https://commandprompt.com/education/postgresql-indexes-b-tree/)

   Partial Indexes, Index Only Scans, Covering Indexes, Prefix Indexes (MySQL)

2. [How Postgres Makes Transactions Atomic](https://brandur.org/postgres-atomicity)


## PPTs

1. [Scalable MVCC Solution for Many Core Machines](https://www.pgcon.org/2015/schedule/events/810.en.html)
2. [The Future is CSN](https://postgrespro.ru/media/2019/10/26/future_is_csn.pdf)
3. [Solving Postgres Wicked Problems](https://www.socallinuxexpo.org/sites/default/files/presentations/solving-postgres-wicked-problems.pdf)

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


## Talks

* [Andres Freund](https://anarazel.de/talks/)
