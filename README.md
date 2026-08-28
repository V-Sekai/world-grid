# world-grid

Archived. Continued as
[world-grid-tools](https://github.com/V-Sekai/world-grid-tools), which holds
the same build harness with the two vendored subrepositories filtered out of
every commit.

Neither of them could be carried forward as a pinned checkout:

- `godot/` was pinned at `1ac4c768` on `groups-staging-4.4`. That branch no
  longer exists upstream and the commit is no longer fetchable.
- `grid/` pointed at `V-Sekai/grid`, which is this repository under its former
  name, so it vendored an older copy of itself.

This repository stays readable for its history.
