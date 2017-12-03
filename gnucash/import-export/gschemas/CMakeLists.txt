
SET(generic_import_GSCHEMA org.gnucash.dialogs.import.generic.gschema.xml)

ADD_GSCHEMA_TARGETS(generic-import-gschema "${generic_import_GSCHEMA}")

SET_DIST_LIST(generic_import_gschema_DIST CMakeLists.txt org.gnucash.dialogs.import.generic.gschema.xml.in.in)