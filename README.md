# Task Master for Movable Type #

Task Master is a tool script for Movable Type that gives you power over periodic tasks.

## Usage: ##

    tools/task-master <command> [arguments...]

Runs the task master command with the given arguments

### Commands: ###

* `status <task key> [<task key> ...]`

  Output the last time a given task or tasks was run.
  
* `run <task key> [<task key> ...]`

  Run the given task or tasks, if they were not run within their period recently.
  
* `forcerun <task key> [<task key> ...]`

  Run the given task or tasks, regardless of their most recent run time.

* `list`

  List the known periodic tasks, their frequencies and owning components.
  
## Author ##

Task Master for Movable Type was written by David Raynes &lt;<rayners@gmail.com>>

## License ##

[Artistic 2.0](http://www.perlfoundation.org/artistic_license_2_0)




