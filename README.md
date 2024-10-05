# postgres-howtos
postgres-howtos in chinese，original repo🔗：https://gitlab.com/postgres-ai/postgresql-consulting/postgres-howtos

This project has been started by [@NikolayS]() on 2023-09-26 https://twitter.com/samokhvalov/status/1706748070967624174:

> I'm going to start a PostgreSQL marathon: each day I'll be posting a new "howto" recipe. Today is the day zero, and the first post is here.

> My goal is to create at least 365 posts 😎

> Why am I doing it?
>
> 1. Postgres docs are awesome but often lack practical pieces of advice (howtos)
> 2. 20+ years of database experience, from small startups to giants like Chewy, GitLab, Miro - always have a feeling that I need to share
> 3. eventually I aim to have a structured set of howtos, constantly improving it - and make the systems we develop at [Postgres.ai](https://Postgres.ai) / [Database_Lab](https://twitter.com/Database_Lab) better and more helpful.

[Subscribe](https://twitter.com/samokhvalov/status/1706748070967624174), like, share, and wish me luck with this -- and let's go! 🏊

一个很不错的学习资源，都是总结的一些实践经验，我会不定期翻译一篇，并添加笔者自己的理解。

觉得项目不错，不妨点个 ⭐️ 再走 ~

## 目录

- 0001 [EXPLAIN ANALYZE or EXPLAIN (ANALYZE, BUFFERS)?](https://github.com/xiongcccc/postgres-howto/blob/master/EXPLAIN%20ANALYZE%20or%20EXPLAIN%20(ANALYZE%2C%20BUFFERS).md)
- 0002 [How to troubleshoot and speed up Postgres stop and restart attempts](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20troubleshoot%20and%20speed%20up%20Postgres%20stop%20and%20restart%20attempts.md)
- 0003 [How to troubleshoot long Postgres startup](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20troubleshoot%20long%20Postgres%20startup.md)
- 0004 [Understanding how sparsely tuples are stored in a table](https://github.com/xiongcccc/postgres-howto/blob/master/Understanding%20how%20sparsely%20tuples%20are%20stored%20in%20a%20table.md)
- 0005 [How to work with pg_stat_statments, part 1](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20work%20with%20pg_stat_statements%2C%20part%201.md)
- 0006 [How to work with pg_stat_statments, part 2](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20work%20with%20pg_stat_statements%2C%20part%202.md)
- 0007 [How to work with pg_stat_statments, part 3](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20work%20with%20pg_stat_statements%2C%20part%203.md)
- 0008 [How to speed up pg_dump when dumping large databases](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20speed%20up%20pg_dump%20when%20dumping%20large%20databases.md)
- 0009 [How to understand LSN values and WAL filenames](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20understand%20LSN%20values%20and%20WAL%20filenames.md)
- 0010 [How to troubleshoot Postgres performance using FlameGraphs and eBPF (or perf)](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20troubleshoot%20Postgres%20performance%20using%20FlameGraphs%20and%20eBPF%20(or%20perf).md)
- 0011 [Ad-hoc monitoring](https://github.com/xiongcccc/postgres-howto/blob/master/Ad-hoc%20monitoring.md)
- 0012 [How to find query examples for problematic pg_stat_statements records](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20find%20query%20examples%20for%20problematic%20pg_stat_statements%20records.md)
- 0013 [How to benchmark](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20benchmark.md)
- 0014 [How to decide when a query is too slow and needs optimization](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20decide%20when%20a%20query%20is%20too%20slow%20and%20needs%20optimization.md)
- 0015 [How to monitor CREATE INDEX / REINDEX progress in Postgres 12+](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20monitor%20CREATE%20INDEX%20%3A%20REINDEX%20progress%20in%20Postgres%2012%2B.md)
- 0016 [How to get into trouble using some Postgres features](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20get%20into%20trouble%20using%20some%20Postgres%20features.md)
- 0017 [How to determine the replication lag](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20determine%20the%20replication%20lag.md)
- 0018 [Over-indexing](https://github.com/xiongcccc/postgres-howto/blob/master/Over-indexing.md)
- 0019 [How to import CSV to Postgres](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20import%20CSV%20to%20Postgres.md)
- 0020 [How to use pg_restore](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20use%20pg_restore.md)
- 0021 [How to set application_name without extra queries](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20set%20application_name%20without%20extra%20queries.md)
- 0022 [How to analyze heavyweight locks, part 1](https://github.com/xiongcccc/postgres-howto/blob/master/How%20to%20analyze%20heavyweight%20locks%2C%20part%201.md)
