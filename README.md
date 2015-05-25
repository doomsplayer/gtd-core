This is GTD-Core writte in rust
=====

I always want a full featured gtd app with user defined fields, user defined filters, infinite nest projects, and even user defined triggers!

So here is the core of my dream gtd.

* Expected USAGE:
  gtd-core task filter -e "(or (= .dueDate (today)) (= .status :nextAction))"
  gtd-core task filter `thefilterid`
  gtd-core task add "mytask"
  gtd-core task get-id "mytask"
  gtd-core task set -e "('theTaskId (.dueDate (today)))"

* goal:
- [ ] Infinite nest projects
- [ ] User defined fields
- [ ] User defined filters
- [ ] User defined triggers