
set(ofx_GSCHEMA org.gnucash.dialogs.import.ofx.gschema.xml)

IF (WITH_OFX)
  ADD_GSCHEMA_TARGETS(ofx-gschema "${ofx_GSCHEMA}")
ENDIF(WITH_OFX)

SET_DIST_LIST(ofx_gschema_DIST CMakeLists.txt Makefile.am org.gnucash.dialogs.import.ofx.gschema.xml.in.in)