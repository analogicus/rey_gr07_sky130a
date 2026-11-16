
#- Core makefile provides the following commands:
# -----------------------------------------------------------
# gds: generate gds/<CELL>.gds
# cdl: generate cdl/<CELL>.cdl
# xsch: generate xsch/<CELL>.spice
# lvs: Check cdl/<CELL>.cdl versus ../design/<LIB>/<CELL>.mag
# lpe: Extract parasitics lpe/<CELL>.spi
# drc: Run design rule checks on ../design/<LIB>/<CELL>.mag
# -----------------------------------------------------------

PREFIX=
LIB=REY_GR07_SKY130A
CELL=tt_um_rey_gr07_analogicus

#- Provide cells you want to check for the lvsall drcall commands
CELLS = REY_GR07 tt_um_rey_gr07_analogicus

include ../tech/make/core.make
