## 2026-09-01 - Week 0: Toolchain, CMake skeleton, first PR with code
**What I did:**
- Wrote CMakeLists.txt with simple main.cpp
- built it and ran it
**Why:**
- Every thing on this project builds on this skeleton and file that i created
- Has to work with simple stuff so when we expand it will work
**What broke / what surprised me:**
- N/A
**What I learned:**
- C++ complies in steps, paste in headers, compile each file, link them together
**New terms:**
**Next step:**
- Add CI so GitHub builds every PR
- Turn on branch protection

## 2026-09-27 — ThinkPad environment setup for uav-trackloop

**What I did:** 
- Checked my Linux setup 
- installed the missing tools 
- made a GitHub repo, and pulled it down onto my machine. 
- made the folders the project needs.
- first attempt at Cmake file

**Why:** Wanted a clean, working setup before writing any real code, so
nothing about the environment gets in the way later.

**What broke / what surprised me:** 
- first check command silently skipped some of the checks
- in linux if we chain commands and a command fails, the following will not run 

**What I learned:** 
- Chaining commands with && means if one fails, everything after it in the line gets skipped
- Compiling and running in C++ are different 
- Cmake file is able to do this without all one command

**New terms:** 
- Command chaining (&&) 
- Snap vs apt — two different ways to install software on Ubuntu; went with apt to keep everything consistent
with the rest of the setup.
- Cmake.txt

**Next step:** Figure out what a CMakeLists.txt file actually needs to say,
then write the first one.
