# bimsc26-datamgmt-session01

Bamb:U - Parametric Bamboo "Umbrella" generator

A lightweight parametric tool for generating bamboo structures using Grasshopper, Hops and Rhino Compute.

Overview
The goal is to explore how simple parametric rules can generate customizable, sustainable shading elements, and combine them into larger spatial layouts.
This MVP focuses on one umbrella type per project, with a small set of intuitive paamaters and automatically computes performance metrics.

Inputs
- Diameter (canopy size)
- Height (overall structure height)
- Subdivision (number of sections)
- Count (Number of modules)
- Offset (distance between modules

Output
- Geometry
- Covered Area
- Footprint Area
- Culms Count
- Connectors Count
- Total length
- Total weight
- Total cost

Tech Stack
- Grasshopper: parametric logic and geometry generation
- Hops: exposes Grasshopper definition as API endpoints
- Rhino Compute: remote compoutation engine for scalable geometry processing

Goals
The project aim to:
- Prototyping a configurable bamboo shading system (Potential added features: water collection)
- Explore parametric variations through simple inputs
- Provide quick feedback on material usage and cost

Roadmap
Planned future enhancement:
- Multiple design options (randomised module placement)
- Multiple modules type in the same project 
- Material options: whole culm vs stripe, treatment etc.
- Structural validation
- Calculate carbon footprint
- Basic shading ot environmental metrics
- Create database with material, rules, output
