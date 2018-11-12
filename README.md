# NicheMapR
R implementation of Niche Mapper software for biophysical modelling

Copyright (C) 2018  Michael R. Kearney and Warren P. Porter

Citation: Kearney, M. R., and W. P. Porter. 2017. NicheMapR - an R 
package for biophysical modelling: the microclimate model. Ecography 
40:664–674.


This program is free software: you can redistribute it and/or modify it 
under the terms of the GNU General Public License as published by the 
Free Software Foundation, either version 3 of the License, or (at your
option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

-----------------------------------------------------------------------------------------------

# Notes on this version of NicheMapR
## Master Branch
This version of NicheMapR has been forked from mrke/NicheMapR shortly after the release of Linux support for this package. The file R/micro_global.R has been updated for use with Microsoft Azure so that, after package installation on a cluster, R knows where to access global_climate.nc and soilw.mon.ltm.v2.nc.

The original Linux port created by https://github.com/rafaqz/NicheMapR/ did not contain Kearney's recent changes which corrects RH after adibiatic lapse rate (release: https://github.com/mrke/NicheMapR/commit/8219492870100d5d68bb761da60d7b48413552c8; lines 626 - 636). I have deleted this code so that this custom climate db branch represents the original Linux port.

Please contact Simon Tarr for more information.

