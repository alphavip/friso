Project(frisotst C)

SET(TSTFRISOFILE tst-friso.c)
SET(TSTARRAYFILE tst-array.c)

add_executable(tstfriso ${TSTFRISOFILE})
target_link_libraries(tstfriso libfriso m)

add_executable(tstarrayfriso ${TSTARRAYFILE})
target_link_libraries(tstarrayfriso libfriso)