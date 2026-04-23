# PES VCS Project

## Student Details
Name: Mohd Sinan  
SRN: PES1UG24AM165  

## Platform
Ubuntu 22.04  

---

## Project Overview
This project implements a simplified version control system similar to Git. It supports object storage, tree creation, staging area, commits, and log history.

---

## Features Implemented

### Phase 1 — Object Storage
- Stores file content as objects using SHA1 hashing
- Objects saved in `.pes/objects/`

### Phase 2 — Tree Objects
- Converts index entries into tree structure
- Represents directory-like hierarchy

### Phase 3 — Index / Staging
- `pes init` → initialize repo
- `pes add` → stage files
- `pes status` → view tracked files

### Phase 4 — Commit System
- `pes commit` → create snapshot
- `pes log` → view commit history

---

## Commands Used

```bash
./pes init
./pes add <file>
./pes status
./pes commit -m "message"
./pes log
