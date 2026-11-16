# MRMR 0.1.4.9001

Renova release, based on CRAN MRMR 0.1.4 (archived on CRAN 2021-10-06).

- `R/CreateOriginPeriods.R`: `class(OriginLength) != "Period"` -> `class(OriginLength)[1L] != "Period"`.
- `R/LatestDiagonal.R`: `class(x) == "Triangle"` -> `class(x)[1L] == "Triangle"`.
- `DESCRIPTION`: `Authors@R` added and `Author` rewritten as `Brian A. Fannin [aut, cre]` (metadata only).

Release preparation:

- `DESCRIPTION`: `Version` set to `0.1.4.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL version 2 text) was added; the `License` field is unchanged.
- `README.md` was rewritten for this release; the original README is kept as `README.upstream.md`. Both are excluded from the R build.
- `NEWS.md` was added for this release and is excluded from the R build; the existing `NEWS` file is unchanged.
