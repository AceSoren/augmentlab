# Reverse-Engineering the NLS Concept
> NLS is an integrated collection of tools for anyone who does "knowledge work" --anyone who needs to research, organize; communicate, reshape, condense, transmit, or present information.

^NLS User Training Guide, 1977^
## Index
[*High-level*: User Interface](nls-interface.md)<br>
[*High-level*: Data Interaction](nls-interaction.md)<br>
[*High-level*: Administration](nls-admin.md)<br>
[*Mid-level*: High-level language known as TENEX](nls-tenex.md)<br>
[*Low-level*: Game Engine or Raylib](nls-runtime.md)<br>
[*Personal*: Improvements in today's environment](nls-improve.md)

## Purpose
The biggest innovation of the 1960s was the **NLS**, or *oN-Line System*, used by Engelbart and gang to visually and technologically assess large portions of information in short time in a collaborative fashion. To do this it has many features and outdated idiosyncracies that pull this off in a... Not *user friendly*, but expert-friendly manner.

As of today, the only surviving successor to the NLS is the **Hyperscope** web server-bound program, of which I have 1.1. I don't have a way of deploying it easily for local use, and its nature as a buff to websites makes it hard for me to use it myself since the only people who can access ways to edit it are *scholars and members of the company involved*. Efforts to **preserve** the NLS and its source code ceased in 2006, making it impossible to use the source code to my benefid and see how things work under the hood.

The only option left is to make a replica that, instead of reversing the technology itself, *reverse-engineers the methods behind it*. This page will have its own index to separate this effort from other notes and, at the same time, remain connected, just the way I like it.

[Return to Index](index.md)

[Go up](#reverse-engineering-the-nls-concept)