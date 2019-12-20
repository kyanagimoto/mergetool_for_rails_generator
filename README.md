# Merge tool for rails generator

When upgrade rails from 5.2 to 6, be able to merge like git-merge, when set `export THOR_MERGE=mergetool_for_rails_generator`

```
cp mergetool_for_rails_generator /usr/local/bin/
chmod a+x /usr/local/bin/mergetool_for_rails_generator

bundle exec rails app:update
```

