bin_PROGRAMS = axel
axel_SOURCES = \
	axel.c \
	axel.h \
	sleep.h \
	conf.c \
	conf.h \
	conn.c \
	conn.h \
	ftp.c \
	ftp.h \
	http.c \
	http.h \
	search.c \
	search.h \
	ssl.c \
	ssl.h \
	tcp.c \
	tcp.h \
	text.c

axel_LDADD = $(SSL_LIBS) -lm

AM_CPPFLAGS = -DLOCALEDIR=\""$(localedir)"\"
AM_CPPFLAGS += -D_BSD_SOURCE -D_DEFAULT_SOURCE
