# ishitasaha25bcy10122-csa2001-project
Here is the prolog code for a To-Do List Application.
Problem-In daily life, people manage numerous small, distinct tasks, relying solely on memory which is inefficient and prone to error. 
Solution-The project addresses the need for a simple yet dynamic task management. The given code is a lightweight, logic driven which can perfrom essential tasks like:
creating new items, viewing the current status, updating item statusand deleting item.

The prorgam is an example of Knowledge based system built using prolog coding.
The application acts as a Simple Reflex Agent, observes the environment and executes the corresponding action to maintain the coherent state.
The program is entirely written in First Order Predicate Logic.
The code successfully represents individual tasks, implement core operations through prolog predicates, maintains a sequence of task Ids and accurately tracks the status and also provides a clear menu-driven interface.

add_task,view_tasks, mark_complete, delete_task are necessary functions.
:-dynamic task/3.,next_id/1,menu/0,start/0 - modularise the code into logical groups
next_id to ensure sequential and non repeatition of IDs
read_line_to_string and format to write prolog rules and handle user I/O


