**TLB Simulator**


TLB Simulator is an interactive educational tool designed to demonstrate how virtual address translation works in modern operating systems. The simulator visualizes how virtual addresses are translated into physical addresses using a Translation Lookaside Buffer (TLB), while tracking TLB hits, misses, page faults, replacement policies, and memory access behavior in real time.

Built with an interactive frontend and a FastAPI backend, the project helps students and learners understand concepts such as paging, locality of reference, cache replacement algorithms, effective access time (EAT), dirty bits, accessed bits, and context switching.

The simulator provides step-by-step visualization of memory management operations, making it useful for Operating Systems learning, demonstrations, and academic projects.


**Features**
Virtual-to-physical address translation simulation

Real-time TLB hit and miss tracking

FIFO and LRU replacement policy implementation

Page table visualization with:

Valid bits

Dirty bits

Reference bits

Accessed bits

Global bits

Read/Write/Execute permissions

Page fault handling and write-back simulation

Context switching and TLB flushing

Thrashing detection based on miss rate

Effective Access Time (EAT) calculation

Step-by-step execution mode

Interactive UI for observing memory operations visually

Event logs and translation summaries


**Tech Stack**
Frontend

HTML

CSS

JavaScript

Backend

Python

FastAPI

GUI Version

Tkinter


**Project Structure**
TLB-Simulator/
├── index.html

├── main.py

├── land.py

├── README.md


**Concepts Demonstrated**
Translation Lookaside Buffer (TLB)

Paging and Address Translation
Page Tables

FIFO Replacement Policy

LRU Replacement Policy

Context Switching

Memory Management Unit (MMU)

Effective Access Time (EAT)

Thrashing

Virtual Memory Management


**Running the Project**

Frontend Simulator

Open:

index.html

in a browser.

FastAPI Backend

Run:

uvicorn main:app --reload

**API Docs:**

http://127.0.0.1:8000/docs

Tkinter GUI Version

**Run:**

python land.py

Educational Purpose

*This project was developed for learning and visualization of operating system memory management concepts. It helps users understand how TLBs improve system performance by reducing memory access time and optimizing address translation processes.*
