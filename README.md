# gha-matrix-env-test

GitHub Actions の検証用の使い捨てリポジトリ。

**検証したいこと**: matrix の各 leg が同じ `environment:` を参照したとき、
required reviewers の承認は「1回で全 leg 通る」のか「leg ごとに要る」のか。

中身は echo のみ。AWS / terraform / secret は一切含まない。
