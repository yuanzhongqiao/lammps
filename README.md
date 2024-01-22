This is the LAMMPS software package.

LAMMPS stands for Large-scale Atomic/Molecular Massively Parallel
Simulator.

<h1> **LAMMPS ** </h1>

LAMMPS，全称Large-scale Atomic/Molecular Massively Parallel Simulator，即大规模原子分子并行模拟器，主要用于分子动力学相关的一些计算和模拟工作。以下是LAMMPS的一些主要应用和功能：

分子动力学模拟：LAMMPS是一个用于模拟分子动力学的开源程序包，可以模拟气态、液态或固态相形态下、各种系综下、百万级的原子分子体系，广泛应用于材料科学、生物物理学、化学等领域的研究。
支持多种力场和势函数：LAMMPS可以支持多种力场和势函数，包括多种多体势函数，这使得它可以模拟多种不同类型的原子和分子间相互作用。
并行计算能力：LAMMPS具有良好的并行扩展性，可以在高性能计算机上实现大规模的并行计算，提高模拟的效率和精度。
开放性：LAMMPS是一个开源程序包，用户可以免费获取源代码并根据自己的需要进行修改和扩展。此外，LAMMPS还提供了丰富的文档和社区支持，使得用户可以更容易地学习和使用它。
总的来说，LAMMPS是一个功能强大的分子动力学模拟工具，可以帮助研究人员深入理解原子和分子的运动规律以及它们之间的相互作用，为材料设计、药物研发等领域提供重要的理论支持。
 


Copyright (2003) Sandia Corporation.  Under the terms of Contract
DE-AC04-94AL85000 with Sandia Corporation, the U.S. Government retains
certain rights in this software.  This software is distributed under
the GNU General Public License.

----------------------------------------------------------------------

LAMMPS is a classical molecular dynamics simulation code designed to
run efficiently on parallel computers.  It was developed at Sandia
National Laboratories, a US Department of Energy facility, with
funding from the DOE.  It is an open-source code, distributed freely
under the terms of the GNU Public License (GPL) version 2.

The code is maintained by the LAMMPS development team who can be emailed
at developers@lammps.org.  The LAMMPS WWW Site at www.lammps.org has
more information about the code and its uses.

The LAMMPS distribution includes the following files and directories:

README                     this file
LICENSE                    the GNU General Public License (GPL)
bench                      benchmark problems
cmake                      CMake build files
doc                        documentation
examples                   simple test problems
fortran                    Fortran wrapper for LAMMPS
lib                        additional provided or external libraries
potentials                 interatomic potential files
python                     Python wrappers for LAMMPS
src                        source files
tools                      pre- and post-processing tools

Point your browser at any of these files to get started:

https://docs.lammps.org/Manual.html         LAMMPS manual
https://docs.lammps.org/Intro.html          hi-level introduction
https://docs.lammps.org/Build.html          how to build LAMMPS
https://docs.lammps.org/Run_head.html       how to run LAMMPS
https://docs.lammps.org/Commands_all.html   Table of available commands
https://docs.lammps.org/Library.html        LAMMPS library interfaces
https://docs.lammps.org/Modify.html         how to modify and extend LAMMPS
https://docs.lammps.org/Developer.html      LAMMPS developer info

You can also create these doc pages locally:

% cd doc
% make html                # creates HTML pages in doc/html
% make pdf                 # creates Manual.pdf
