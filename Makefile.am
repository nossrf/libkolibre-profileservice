## Copyright (C) 2012 Kolibre
#
# This file is part of kolibre-profileservice.
#
# Kolibre-profileservice is free software: you can redistribute it and/or modify
# it under the terms of the GNU Lesser General Public License as published by
# the Free Software Foundation, either version 2.1 of the License, or
# (at your option) any later version.
#
# Kolibre-profileservice is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU Lesser General Public License for more details.
#
# You should have received a copy of the GNU Lesser General Public License
# along with kolibre-profileservice. If not, see <http://www.gnu.org/licenses/>.
#

AUTOMAKE_OPTIONS = foreign

SUBDIRS = src tests

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libkolibre-profile.pc

include doxygen.am

EXTRA_DIST = patches wsdl mainpage.dox

AM_DISTCHECK_CONFIGURE_FLAGS = "PKG_CONFIG_PATH=${PKG_CONFIG_PATH}"
