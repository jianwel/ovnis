# additional include paths necessary to compile the C++ library
AM_CXXFLAGS = -I$(top_srcdir) @AM_CPPFLAGS@ -DNS3_LOG_ENABLE

# the library names to build (note we are building static libs only)
#lib_LIBRARIES = libovnis.a

# where to install the headers on the system
#libovnis_adir = $(includedir)

# the list of header files that belong to the library (to be installed later)
#libovnis_a_HEADERS = ./applications/ovnis-application.h ./devices/wifi/channel-cell.h ./devices/wifi/ovnis-adhoc-wifi-mac.h ./devices/wifi/ovnis-error-rate-model.h ./devices/wifi/ovnis-wifi-channel.h ./devices/wifi/ovnis-wifi-phy.h ./helper/ovnis-wifi-helper.h ./ovnis-constants.h ./ovnis.h ./traci/traci-client.h ./xml-sumo-conf-parser.h 
                         

# the sources to add to the library and to add to the source distribution
#libovnis_a_SOURCES =    \
#                       $(libmylib_a_HEADERS) \
#                        ./devices/wifi/ovnis-adhoc-wifi-mac.cc ./devices/wifi/ovnis-error-rate-model.cc ./devices/wifi/ovnis-wifi-channel.cc ./devices/wifi/ovnis-wifi-phy.cc ./helper/ovnis-wifi-helper.cc ./traci/traci-client.cc ./applications/ovnis-application.cpp ./devices/wifi/channel-cell.cpp ./ovnis.cpp ./xml-sumo-conf-parser.cpp


lib_LTLIBRARIES = libovnis.la
libovnis_ladir = $(includedir)
libovnis_la_HEADERS = ./applications/ovnis-application.h ./devices/wifi/channel-cell.h ./devices/wifi/ovnis-adhoc-wifi-mac.h ./devices/wifi/ovnis-error-rate-model.h ./devices/wifi/ovnis-wifi-channel.h ./devices/wifi/ovnis-wifi-phy.h ./helper/ovnis-wifi-helper.h ./ovnis-constants.h ./ovnis.h ./traci/traci-client.h ./xml-sumo-conf-parser.h 

#libovnis_la_LIBADD = 
libovnis_la_SOURCES = \
                     ${libovnis_la_HEADERS} \
                       ./devices/wifi/ovnis-adhoc-wifi-mac.cc ./devices/wifi/ovnis-error-rate-model.cc ./devices/wifi/ovnis-wifi-channel.cc ./devices/wifi/ovnis-wifi-phy.cc ./helper/ovnis-wifi-helper.cc ./traci/traci-client.cc ./applications/ovnis-application.cpp ./devices/wifi/channel-cell.cpp ./ovnis.cpp ./xml-sumo-conf-parser.cpp

#libovnis_la_LDFLAGS = -version-info 0:1
