ttk_add_base_library(morseSmaleQuadrangulation
  SOURCES
    MorseSmaleQuadrangulation.cpp
  HEADERS
    MorseSmaleQuadrangulation.h
  DEPENDS
    barycentricSubdivision
    dijkstra
    geometry
    triangulation
    )
