#
# Metos3D: A Marine Ecosystem Toolkit for Optimization and Simulation in 3-D
# Copyright (C) 2012  Jaroslaw Piwonski, CAU, jpi@informatik.uni-kiel.de
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.
#
#	Makefile

# define variables
DOCBASENAME = metos3d-model

all: pdf

pdf:
	@echo "#"
	@echo "# PDF"
	@echo "#"
	pdflatex ${DOCBASENAME}.tex > /dev/null 2>&1; \
	pdflatex ${DOCBASENAME}.tex > /dev/null 2>&1; \
	rm ${DOCBASENAME}.log; \
	rm ${DOCBASENAME}.out; \
	rm ${DOCBASENAME}.aux;
