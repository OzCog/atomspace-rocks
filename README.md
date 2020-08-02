# AtomSpace RocksDB Backend

Version 0.0.1 -- Nothing here yet.


Example Usage
-------------
Well, see the examples directory for details. But, in brief:

```
$ guile
scheme@(guile-user)> (use-modules (opencog))
scheme@(guile-user)> (use-modules (opencog persist))
scheme@(guile-user)> (use-modules (opencog persist-rocks))
scheme@(guile-user)> (cog-rocks-open "rocks:///tmp/foo.rdb/")
scheme@(guile-user)> (load-atomspace)
```

That's it! You've loaded the entire contents of `foo.rdb` into the
AtomSpace!  Of course, loading everything is not generally desriable,
especially when the file is huge and RAM space is tight.  More granular
load and store is possible; see the [examples directory](examples) for
details.