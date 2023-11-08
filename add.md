[< к содержанию](./readme.md)

---

## git add, git kommit

Для добавления под версионный контроль существующие файлы (в отличие от пустого каталога), вам стоит добавить их в индекс и осуществить первый коммит изменений. Добиться этого вы сможете запустив команду ***git add*** несколько раз, указав индексируемые файлы, а затем выполнив ***git commit***:

``
$ git add task4.md
``

``
$ git commit -m "First Commit"
``

``
[master (root-commit) 911e8c9] First Commit
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 task4.md
``