## architecture

TODO: move into wiki

just some drafting for architecture, subject to change!


Essentially, this is a package manager. Might be reasonable to "borrow" logic and code from existing
package managers.

### interface

An interface for the user to interact, mainly CLI, later maybe GUI. Should implement these features

1. backends
	* listing
	* selection
	* configs(?)
1. packages
	* list installed
	* search
	* install 

### backend

We want to provide a template that is easily adjustable to the specific backends. 

## technology

Definitely Rust. Web requests with rocket. Interface maybe clap 
