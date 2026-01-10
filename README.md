# org.msscf.msscf.v2_13.cfkbase
Mark's Code Fractal CFKBase 3.1 Code Fractal Knowledge Base

	Copyright 2016-2025 Mark Stephen Sobkow

	These files are part of Mark's Code Fractal CFKBase.

	Mark's Code Fractal CFKBase is available under dual commercial license from
	Mark Stephen Sobkow, or under the terms of the GNU General Public License,
	Version 3 or later.

	Mark's Code Fractal CFKBase is free software: you can redistribute it and/or
	modify it under the terms of the GNU General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.

	Mark's Code Fractal CFKBase is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.

	You should have received a copy of the GNU General Public License
	along with Mark's Code Fractal CFKBase.  If not, see &lt;https://www.gnu.org/licenses/&gt;.

	If you wish to modify and use this code without publishing your changes,
	or integrate it with proprietary code, please contact Mark Stephen Sobkow
	for a commercial license at mark.sobkow@gmail.com

Overview
--------
The rules defined herein presume a specific combination of tools and releases.
Java JDK 17, GWT 2.12.2, and Spring 4.0. GWT is the limiting technology for the
supported JDK, but that only applies with GWT code aspects of the overall outputs
for the builds. If you do not use nor require GWT, simply don't build those
modules nor ship them; you can obviously compile the other code with higher
releases of JDK than 17 without changing anything more than your copy of
the pom.xml and your package names and hierarchy to reflect the branch.

As of 2026-01-10 16h15 CST, the output code base and rule base are actually
JDK 25 compatible and even require JDK 25 for the core interfaces produced.
Those embedded interface constants will have to move to a hierachy of classes
with static class members instead, but in the same package. Then the rules need
to be updated to reference the new classes instead of the interfaces, and we should
be back on the road with New Code...
