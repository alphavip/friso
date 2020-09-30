
PROJECT(friso C)

SET (HDRS friso_API.h
          friso_ctype.h
          friso.h)
SET (SRCS friso_array.c
          friso.c
          friso_ctype.c
          friso_GBK.c
          friso_hash.c
          friso_lexicon.c
          friso_link.c
          friso_string.c
          friso_UTF8.c)
MESSAGE(STATUS ${SRCS})
ADD_LIBRARY(libfriso STATIC ${SRCS} ${HDRS})