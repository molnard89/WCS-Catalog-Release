AA/2021/42614   Properties of HI-detected Coma and field galaxies     (Molnár+, 2022)
================================================================================
The Westerbork Coma Survey
    Molnár D.Cs., Serra P., van der Hulst T., Jarrett T.H., Boselli A., Cortese L., 
    Healy J., de Blok E.,Cappellari M.,Hess K.M.,Józsa G.I.G., McDermid R.M.,
    Oosterloo T.A.,Verheijen M.A.W.
    =ref ?
================================================================================
Keywords: galaxies: clusters: individual: Coma -
          galaxies: evolution - galaxies: interactions -
          galaxies: ISM - radio lines: galaxies -
          galaxies: fundamental parameters


Abstract:
  We present the blind Westerbork Coma Survey probing the HI
  content of the Coma galaxy cluster with the Westerbork Synthesis Radio
  Telescope. The survey covers the inner $\sim$ 1 Mpc around the cluster centre,
  extending out to 1.5 Mpc towards the south-western NGC 4839 group. The survey
  probes the atomic gas in the entire Coma volume down to a sensitivity of
  $\sim$ 10$^{19}$ cm$^{-2}$ and 10$^8$ M$_{\odot}$. Combining automated source
  finding with source extraction at optical redshifts and visual verification,
  we obtained 40 HI detections of which 24 are new. Over half of
  the sample displays perturbed HI morphologies indicative of
  an ongoing interaction with the cluster environment. With the use of ancillary
  UV and mid-IR, data we measured their stellar masses and star formation rates
  and compared the HI properties to a set of field galaxies spanning
  a similar stellar mass and star formation rate range. We find that $\sim$ 75
  % of HI-selected Coma galaxies have simultaneously
  enhanced star formation rates (by $\sim$ 0.2 dex) and are HI
  deficient (by $\sim$ 0.5 dex) compared to field galaxies of the same stellar
  mass. According to our toy model, the simultaneous HI deficiency
  and enhanced star formation activity can be attributed to either HI stripping 
  of already highly star forming galaxies on a very short timescale,
  while their H$_2$ content remains largely unaffected, or to HI stripping
  coupled to a temporary boost of the HI-to-H$_2$ conversion, causing a 
  brief starburst phase triggered by ram pressure before eventually 
  quenching the galaxy.

File Summary:
--------------------------------------------------------------------------------
 FileName       Lrecl   Records    Explanations
--------------------------------------------------------------------------------
ReadMe          80        .        this file
WCS_HIdet.cds   182       40       Coma cluster galaxies with HI-detections
                                   in the Westerbork Coma Survey
RefSamp.cds     132      192       Reference sample of field galaxies 


--------------------------------------------------------------------------------
Byte-by-byte Description of file: WCS_HIdet.dat.cds
--------------------------------------------------------------------------------
 Bytes    Format Units         Label     Explanations
--------------------------------------------------------------------------------
  1- 22   A22    ---           ID        ID of optical counterpart
 24- 41   F18.14 deg           RA        Right Ascension J2000
 43- 60   F18.15 deg           Dec       Declination J2000
 62- 73   F12.9  arcsec        off       Angular offset between the 
                                         optical and HI source centres
 75- 91   F17.11 km/s          vHI       line-of-sight velocity of 
                                         the HI detection
 93- 98   F6.1   Mpc           dc        projected distance to the centre
                                         of the Fornax cluster
100-103   F4.2   km/s          voff      difference between the optical and
                                         HI line-of-sight velocities
105-110   F6.3   logMsun       logMstar  stellar mass of the galaxy (1)
112-116   F5.3   logMsun       dlogMstar stellar mass uncertainty 
                                         of the galaxy
118-136   F19.16 log(Msun/yr)  logSFR    star formation rate of the 
                                         galaxy (2)
138-156   F19.17 log(Msun/yr)  dlogSFR   star formation rate uncertainty 
                                         of the galaxy
158-174   F17.15 logMsun       logMHI    HI mass of the galaxy (3)
176-176   I1     ---           HItype    HI morphological type (4)
178-178   I1     ---           Tail      flag indicating a tail at UV
                                         and/or Halpha wavelengths (5)
180-180   I1     ---           AGN       flag indicating the presence
                                         of an AGN (6)
182-182   I1     ---           NewDet    flag to indicate whether the
                                         source is a new HI detection (7)

--------------------------------------------------------------------------------
Note (1): calculated with the use of WISE 3.4 and 4.6 micron photometry
(extracted by T. H. Jarrett), with the method described in Cluver et al
(2014ApJ...782...90C). For details see Sect. 3.3 of Molnár+ 2022.
Note (2): calculated with the combination of GALEX NUV and WISE 22 micron 
photometry with the coefficient of Boquien et al (2016A&A...591A...6B).
For details see Sect. 3.3 of Molnár+ 2022.
Note (3): measured in our WSRT cubes. For details on the observations,
source detection, counterpart matching and verification, see Sect. 2
of Molnár+ 2022.
Note (4): HI morphological class of the galaxy. Details of the
classification method are described in Sect. 3.1 of Molnár+ 2022.
     1 = settled
     2 = one-sided asymmetry
     3 = unsettled
Note (5): tailed sources from Smith et al (2010MNRAS.408.1417S)
and Yagi et al (2010AJ....140.1814Y).
     0 = no tail observed or was not covered by either studies
     1 = has tail according to either surveys
Note (6): AGN hosts based on Mahajan et al (2010MNRAS.404.1745M), 
Gavazzi et al (2011A&A...534A..31G), or Toba et al (2014ApJ...788...45T)
     0 = not identified as an AGN host
     1 = found to harbour an AGN
Note (7): previously detected HI sources from Bravo-Alfaro et al 
2000AJ....119..580B), Bravo-Alfaro et al (2001A&A...379..347B),
or Gavazzi (2006A&A...449..929G) 
     0 = has been detected before
     1 = newly detected source
--------------------------------------------------------------------------------


Byte-by-byte Description of file: RefSamp.dat.cds
--------------------------------------------------------------------------------
 Bytes    Format Units         Label     Explanations
--------------------------------------------------------------------------------
  1-  6   A6     ---           ID        ID from the HRS or VGS (1)
  8- 16   F9.5   deg           RA        Right Ascension J2000
 18- 26   F9.5   deg           Dec       Declination J2000
 28- 45   F18.15 logMsun       logMstar  stellar mass of the galaxy (2)
 47- 65   F19.17 logMsun       dlogMstar stellar mass uncertainty 
                                         of the galaxy
 67- 79   F13.10 log(Msun/yr)  logSFR    star formation rate of the 
                                         galaxy (3)
 81- 91   F11.9  log(Msun/yr)  dlogSFR   star formation rate uncertainty 
                                         of the galaxy
 93-110   F18.15 logMsun       logMHI    HI mass of the galaxy (4)
112-132   F21.19 logMsun       dlogMHI   HI mass uncertainty of the galaxy

--------------------------------------------------------------------------------
Note (1): adopted from Boselli et al (2010PASP..122..261B, HRS) and Kreckel et al
(2011AJ....141....4K, VGS)
Note (2): calculated with the use of WISE 3.4 and 4.6 micron photometry
(extracted by T. H. Jarrett), with the method described in Cluver et al
(2014ApJ...782...90C). For details see Sect. 3.3 of Molnár+ 2022.
Note (3): calculated with the combination of GALEX NUV and WISE 22 micron 
photometry with the coefficient of Boquien et al (2016A&A...591A...6B).
For details see Sect. 3.3 of Molnár+ 2022.
Note (4): For HRS sources HI masses are from Boselli et al (2014A&A...564A..65B).
For VGS HI observations are dominantly ALFALFA measurements from 
Haynes et al (2011AJ....142..170H) and single-dish data from 
Springob et al (2005ApJS..160..149S).
--------------------------------------------------------------------------------

Acknowledgements: Dániel Cs. Molnár <daniel.molnar@inaf.it>

References:
================================================================================
     (prepared by author  / pyreadme )
(End)
