## 1.2.4 (2020-02-10)

Fix:
- third_party/Develbar/hooks/Develbar.php

Changes:

- allow closure usage.

## 1.2.3 (2020-02-09)

Fix:
- third_party/Develbar/views/ajax.php

Changes:

- Ajax request no name fix.

## 1.2.2 (2020-01-28)

Add:

- Support for japanese.

Fix:

- README.md
- config/hooks.php
- third_party/DevelBar/config/develbar.php

Changes:

- You can set $config['documentation_link'] the develbar_lang.php, and link fix.
- Iindent fix.

## 1.2.1 (2018-06-20)

Fix:

- Hooks, Allow Closure usage.

## 1.2 (2017-01-18)

Fix:

- Profiling database not possible when using PDO

## 1.1 (2017-01-18)

Fix:

- Profiler link not visible on ajax pannel (JS Error)

## 1.0 (2017-03-21)

Changes:

- New Profiler page for Ajax request

## 0.8 (2017-03-16)

Changes:

- New Tab for Ajax request

## 0.7 (2017-03-15)

Changes:

- Database queries display.
- Global Execution time for multiple database queries.
- Display views variables

## 0.6 (2015-05-21)

Changes:

- var_dump function is used instead of print_r() to show configuration and session details.

## 0.5 (2015-05-17)

Bugfixes:

- Support of HMVC, Overriding core/MY_Loader.php
- Breaking view when adding config data which contains html tags

## 0.4 (2015-04-22)

Bugfixes:

- Add translation packages for some languages ( French, German, Russian, Italian, Spanish )
- Set the default translation to English if the translantion file does not exists.
