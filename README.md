# automsim

A terminal-based simulator for finite automata and pushdown automata, written in C.

This project was born from my interest in formal logic and automata theory — subjects 
I studied academically and kept thinking about long after. Rather than leaving these machines 
on paper, I wanted to build a tool that makes them tangible: define an automaton in a plain-text `.aut` file, 
provide an input string, and step through the simulation interactively, watching each state transition in real 
time with an ASCII graph and ANSI-colored output.

**Supported models:**
- DFA — Deterministic Finite Automaton
- PDA — Pushdown Automaton (with explicit stack visualization)
