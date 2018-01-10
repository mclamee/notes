**Docker**: An additional layer of abstraction of linux operating system level virtualization.  
  Docker can wrap up a piece of software in a complete filesystem that contains everything  
  it needs to run: code, runtime, system tools, system libraries - anything you can install  
  on a server. This guarantees that it will always run the same regardless of the environment   
  it is running in.

* **LXC**: operating system level virtualization / linux only
* **cgroups\(control groups\)**: a software in linux system that provide unified interface to control single process virtualizatin / operating system level virtualization
* **linux namespaces**: a linux feature that can isolate resources depends on the kind of namespace.
* **union mount**: a way of combining muliple directories into one that appears to contain their combined contents.
* **aufs**: a filesystem based on union mounting. rejected merging into mainline Linux. Used by docker to privde same appearance accross fiesystems.



