# Index of MARCS Single Precision Reals

# CIAH2H

	75   :: propac=1.e-30                                                         


# CIAH2H2

	75   :: propac=1.e-30                                                         


# CIAH2HE

	75   :: propac=1.e-30                                                         


# CIAHHE

	75   :: propac=1.e-30                                                         


# ARCHIV

	156  :: cc        print 215, k,log10(max(1.e-30,xmettryck(k,1))),             
	186  :: C  10 PRESMP(I)=AMAX1(PRESMO(I),1.E-298)          
	187  :: 10 PRESMP(I)=MAX(PRESMO(I),1.E-30)                
	217  :: cc      EMU=(1.38*RO*T(K))/(1.67E-8*PG)           
	218  :: EMU=(1.380658*RO*T(K))/(1.660540e-8*PG)           


# BPL

	13   :: cplank=1.e-15                                                         


# CHECKPART

	33   :: if (abs(1.-(partition(nt)/sngl(qmol(index)))).gt.1.e-4) then          


# DETABS

	179  :: rhokt=rho*1.38066e-16*t(ntp)                                          
	180  :: kt=1.38066e-16*t(ntp)                             
	183  :: ***      hnh=presneutral(ntp,1)/(rho*1.38066e-16*t(ntp))
	190  :: * in case you would wonder about this 1.e-18 factor for H-
	191  :: fakt(1)=1.e-18*partryck(ntp,1)/rhokt              
	192  :: fakt(19)=pe(ntp)*presneutral(ntp,1)/rhokt*1.e-26  
	195  :: xfakh=2.0898e-26*presneutral(ntp,1)/(rhokt*part(1,1))
	219  :: fakt(20)=(presneutral(ntp,1)/rhokt*1.e-25)*       
	220  :: &         (presneutral(ntp,1)/kt*1.e-25)          
	222  :: fakt(21)=(presneutral(ntp,1)/rhokt*1.e-20)*       
	223  :: &         (presion(ntp,1)/kt*1.e-20)              
	230  :: fakt(24)=(pe(ntp)/kt)*(presion(ntp,2)/rhokt)*1.e-20*1.e-20
	232  :: fakt(25)=pe(ntp)*presneutral(ntp,2)/rhokt*1.e-26  
	238  :: fakt(28)=(pe(ntp)/kt)*(presion(ntp,6)/rhokt)*1.e-20*1.e-20
	240  :: fakt(29)=(pe(ntp)/kt)*(presion2(ntp,6)/rhokt)*1.e-20*1.e-20
	242  :: fakt(30)=pe(ntp)*presneutral(ntp,6)/rhokt*1.e-27  
	248  :: fakt(33)=pe(ntp)*presneutral(ntp,7)/rhokt*1.e-27  
	254  :: fakt(36)=pe(ntp)*presneutral(ntp,8)/rhokt*1.e-26  
	256  :: fakt(37)=pe(ntp)*partryck(ntp,7)/rhokt*1.e-26     
	258  :: fakt(38)=pe(ntp)*partryck(ntp,4)/rhokt*1.e-26     
	281  :: fakt(48)=partryck(ntp,6)*13.02/6.023e23/rhokt     
	283  :: fakt(49)=partryck(ntp,5)*17.01/6.023e23/rhokt     
	286  :: fakt(50)=(pe(ntp)/kt)*(presion(ntp,12)/rhokt)*1.e-20*1.e-20
	288  :: fakt(51)=(pe(ntp)/kt)*(presion(ntp,14)/rhokt)*1.e-20*1.e-20
	302  :: fakt(52)=(pe(ntp)/kt)*(presmetion/rhokt)*1.e-20*1.e-20
	306  :: ELS(NTP)=4.8206E-9*PE(NTP)/(T(NTP)*RO)            
	311  :: cc      ph2=ph2*1.38e-16*0.987e-6*273.            
	313  :: c      phtva(ntp)=(partryck(ntp,2)*273./t(ntp)*0.987e-6)*
	314  :: c     &           (partryck(ntp,2)*273./t(ntp)*0.987e-6)/rho
	315  :: phtva(ntp)=(partryck(ntp,2)/t(ntp)*2.6945e-04)**2/rho
	317  :: cc      PHEL(NTP)=PHEL(NTP)*1.38E-16*0.987E-6*273.
	319  :: c      phel(ntp)=(presneutral(ntp,2)*273./t(ntp)*0.987e-6)*
	320  :: c     &           (partryck(ntp,2)*273./t(ntp)*0.987e-6)/rho
	321  :: phel(ntp)=(presneutral(ntp,2)/t(ntp)*2.6945e-04)* 
	322  :: ,  (partryck(ntp,2)/t(ntp)*2.6945e-04)/rho        
	323  :: ph2h(ntp)=(presneutral(ntp,1)/t(ntp)*2.6945e-04)* 
	324  :: ,  (partryck(ntp,2)/t(ntp)*2.6945e-04)/rho        
	325  :: phhe(ntp)=(presneutral(ntp,1)/t(ntp)*2.6945e-04)* 
	326  :: ,  (presneutral(ntp,2)/t(ntp)*2.6945e-04)/rho     
	453  :: OMEGA=1./XLA(JP)*1.E+8                            
	502  :: RAYH=XRAY2*XRAY2*(5.799E-13+XRAY2*(1.422E-6+XRAY2*2.784))*
	511  :: RAYHe=0.66520e-24*4.*(500./xla(jp))**4*heray(ntp) 
	514  :: RAYH2=XRAY2*XRAY2*(8.14E-13+XRAY2*(1.28E-6+XRAY2*1.61))*H2RAY(NTP)


# DIE_PE

	69   :: ECONST=4.342945E-1                                                    
	72   :: cc        epsdie=1.e30                            
	90   :: DHH=(((0.1196952E-02*T-0.2125713E-01)*T+0.1545253E+00)*T
	91   :: &    -0.5161452E+01)*T+0.1277356E+02              
	384  :: epsf=1.e-10                                       
	554  :: errx=1.e10                                        
	580  :: alamin=1.e-3                                      


# DIE_PE_LU

	68   :: ECONST=4.342945E-1                                                    
	71   :: cc        epsdie=1.e30                            
	87   :: DHH=(((0.1196952E-02*T-0.2125713E-01)*T+0.1545253E+00)*T
	88   :: &    -0.5161452E+01)*T+0.1277356E+02              
	324  :: epsf=1.e-10                                       
	492  :: errx=1.e10                                        
	518  :: alamin=1.e-3                                      


# EQMOL_PE

	99   :: real eh2,eh2p,ehm,ehj,eh2o,eoh,ech,eco,ecn,ec2,en2,eo2,eno,enh        
	131  :: ECONST=4.342945E-1                                
	132  :: AVO=0.602217E+24                                  
	136  :: atmass(99)=5.4858e-4                              
	141  :: eps=1.e-4                                         
	319  :: ndensity=pg/1.38066e-16/tem                       
	320  :: molweight=(molweight+pe*atmass(99))/1.38066e-16/tem
	493  :: rho=rho*1.2123e-8/tt                              
	494  :: * 1.2123e-8 == mH/k = amu*1.00797/k               
	650  :: c      EH=EH2+EH2P+EHM+EHJ+EH2O+EOH+ECH+ECO+ECN+EC2+EN2+EO2+ENO+ENH


# EQMOL_PE_LU

	99   :: real eh2,eh2p,ehm,ehj,eh2o,eoh,ech,eco,ecn,ec2,en2,eo2,eno,enh        
	131  :: ECONST=4.342945E-1                                
	132  :: AVO=0.602217E+24                                  
	136  :: atmass(99)=5.4858e-4                              
	142  :: eps=1.e-4                                         
	322  :: ndensity=pg/1.38066e-16/tem                       
	323  :: molweight=(molweight+pe*atmass(99))/1.38066e-16/tem
	497  :: rho=rho*1.2123e-8/tt                              
	498  :: * 1.2123e-8 == mH/k = amu*1.00797/k               
	653  :: c      EH=EH2+EH2P+EHM+EHJ+EH2O+EOH+ECH+ECO+ECN+EC2+EN2+EO2+ENO+ENH


# GAUSI

	39   :: IF(ABS(FLK-FK)-1.E-7)2,1,1                                            


# HLINOPBPZ

	231  :: 1 0.000E+00, 4.696E+08, 9.980E+07, 3.017E+07, 1.155E+07, 5.189E+06,   
	232  :: 2 2.616E+06, 1.437E+06, 8.444E+05, 5.234E+05, 3.389E+05, 2.275E+05,
	233  :: 3 1.575E+05, 1.120E+05, 8.142E+04, 6.040E+04, 4.560E+04, 3.496E+04,
	234  :: 4 2.719E+04, 2.141E+04, 1.711E+04, 1.377E+04, 1.119E+04, 9.166E+03,
	235  :: 5 7.572E+03, 6.341E+03, 5.338E+03, 4.523E+03, 3.854E+03, 3.302E+03,
	236  :: 6 2.844E+03, 2.460E+03, 2.138E+03, 1.866E+03, 1.635E+03, 1.438E+03,
	237  :: 7 1.269E+03, 1.124E+03, 9.983E+02, 8.894E+02, 7.947E+02, 7.120E+02,
	238  :: 8 6.396E+02, 5.759E+02, 5.198E+02, 4.703E+02, 4.263E+02, 3.873E+02,
	239  :: 9 3.526E+02, 3.215E+02, 2.938E+02, 2.689E+02, 2.465E+02, 2.264E+02,
	240  :: A 2.082E+02, 1.918E+02, 1.769E+02, 1.634E+02, 1.512E+02, 1.400E+02,
	241  :: 1 1.298E+02, 1.206E+02, 1.121E+02, 1.043E+02, 9.720E+01, 9.066E+01,
	242  :: 2 8.465E+01, 7.912E+01, 7.403E+01, 6.933E+01, 6.498E+01, 6.097E+01,
	243  :: 3 5.725E+01, 5.381E+01, 5.061E+01, 4.765E+01, 4.489E+01, 4.232E+01,
	244  :: 4 3.994E+01, 3.771E+01, 3.563E+01, 3.369E+01, 3.188E+01, 3.019E+01,
	245  :: 5 2.860E+01, 2.712E+01, 2.572E+01, 2.442E+01, 2.319E+01, 2.204E+01,
	246  :: 6 2.096E+01, 1.994E+01, 1.898E+01, 1.808E+01, 1.722E+01, 1.642E+01,
	247  :: 7 1.566E+01, 1.495E+01, 1.427E+01, 1.363E+01/     
	252  :: 1 0.000E+00, 6.265E+08, 1.897E+08, 8.126E+07, 4.203E+07, 2.450E+07,
	253  :: 2 1.236E+07, 8.249E+06, 5.782E+06, 4.208E+06, 3.158E+06, 2.430E+06,
	254  :: 3 1.910E+06, 1.567E+06, 1.274E+06, 1.050E+06, 8.752E+05, 7.373E+05,
	255  :: 4 6.269E+05, 5.375E+05, 4.643E+05, 4.038E+05, 3.534E+05, 3.111E+05,
	256  :: 5 2.752E+05, 2.447E+05, 2.185E+05, 1.959E+05, 1.763E+05, 1.593E+05,
	257  :: 6 1.443E+05, 1.312E+05, 1.197E+05, 1.094E+05, 1.003E+05, 9.216E+04,
	258  :: 7 8.489E+04, 7.836E+04, 7.249E+04, 6.719E+04, 6.239E+04, 5.804E+04,
	259  :: 8 5.408E+04, 5.048E+04, 4.719E+04, 4.418E+04, 4.142E+04, 3.888E+04,
	260  :: 9 3.655E+04, 3.440E+04, 3.242E+04, 3.058E+04, 2.888E+04, 2.731E+04,
	261  :: A 2.585E+04, 2.449E+04, 2.322E+04, 2.204E+04, 2.094E+04, 1.991E+04,
	262  :: 1 1.894E+04, 1.804E+04, 1.720E+04, 1.640E+04, 1.566E+04, 1.496E+04,
	263  :: 2 1.430E+04, 1.368E+04, 1.309E+04, 1.254E+04, 1.201E+04, 1.152E+04,
	264  :: 3 1.105E+04, 1.061E+04, 1.019E+04, 9.796E+03, 9.419E+03, 9.061E+03,
	265  :: 4 8.721E+03, 8.398E+03, 8.091E+03, 7.799E+03, 7.520E+03, 7.255E+03,
	266  :: 5 7.002E+03, 6.760E+03, 6.530E+03, 6.310E+03, 6.100E+03, 5.898E+03,
	267  :: 6 5.706E+03, 5.522E+03, 5.346E+03, 5.177E+03, 5.015E+03, 4.860E+03,
	268  :: 7 4.711E+03, 4.569E+03, 4.432E+03, 4.300E+03/     
	349  :: PARAMETER (CLIGHT = 2.99792458E18)                
	350  :: PARAMETER (CLIGHTCM = 2.99792458E10)              
	365  :: DATA SIGMA /3.304E-18, 6.497E-18, 1.178E-17/      
	373  :: FO = 1.25E-9*XNE**0.66667 ! Holtsmark normal field strength
	428  :: RESONT = RESONT * 2.07E-24/GNM                    
	429  :: VDW = 4.45E-26/GNM*(XM2*(7.*XM2+5.))**0.4         
	430  :: STARK = 1.6678E-18*FREQNM*XKNM                    
	735  :: DATA Y1WTM/1.E18, 1.E17, 1.E16, 1.E14/            
	738  :: PARAMETER (CLIGHT = 2.9979258E18)                 
	740  :: PARAMETER (H = 6.62618E-27)  !Planck in cgs       
	741  :: PARAMETER (K = 1.38066E-16)  !Boltzmann in cgs    
	758  :: FO = XNE16**4*1.25E-9      ! Holtsmark normal field strength
	762  :: C2D = FO**2/5.96E-23/XNE                          
	763  :: GCON1 = 0.2+0.09*SQRT(T4)/(1.+XNE/1.E13)          
	764  :: GCON2 = 0.2/(1.+XNE/1.E15)                        
	810  :: Y1WHT = 1.E14                                     
	812  :: Y1WHT = 1.E13                                     
	837  :: IF ((Y2.LE.1.E-4).AND.(Y1.LE.1.E-5)) THEN         
	842  :: IF (GAM.LE.1.E-20) GAM = 0.                       


# HLINOPMODI

	228  :: 1 0.000E+00, 4.696E+08, 9.980E+07, 3.017E+07, 1.155E+07, 5.189E+06,   
	229  :: 2 2.616E+06, 1.437E+06, 8.444E+05, 5.234E+05, 3.389E+05, 2.275E+05,
	230  :: 3 1.575E+05, 1.120E+05, 8.142E+04, 6.040E+04, 4.560E+04, 3.496E+04,
	231  :: 4 2.719E+04, 2.141E+04, 1.711E+04, 1.377E+04, 1.119E+04, 9.166E+03,
	232  :: 5 7.572E+03, 6.341E+03, 5.338E+03, 4.523E+03, 3.854E+03, 3.302E+03,
	233  :: 6 2.844E+03, 2.460E+03, 2.138E+03, 1.866E+03, 1.635E+03, 1.438E+03,
	234  :: 7 1.269E+03, 1.124E+03, 9.983E+02, 8.894E+02, 7.947E+02, 7.120E+02,
	235  :: 8 6.396E+02, 5.759E+02, 5.198E+02, 4.703E+02, 4.263E+02, 3.873E+02,
	236  :: 9 3.526E+02, 3.215E+02, 2.938E+02, 2.689E+02, 2.465E+02, 2.264E+02,
	237  :: A 2.082E+02, 1.918E+02, 1.769E+02, 1.634E+02, 1.512E+02, 1.400E+02,
	238  :: 1 1.298E+02, 1.206E+02, 1.121E+02, 1.043E+02, 9.720E+01, 9.066E+01,
	239  :: 2 8.465E+01, 7.912E+01, 7.403E+01, 6.933E+01, 6.498E+01, 6.097E+01,
	240  :: 3 5.725E+01, 5.381E+01, 5.061E+01, 4.765E+01, 4.489E+01, 4.232E+01,
	241  :: 4 3.994E+01, 3.771E+01, 3.563E+01, 3.369E+01, 3.188E+01, 3.019E+01,
	242  :: 5 2.860E+01, 2.712E+01, 2.572E+01, 2.442E+01, 2.319E+01, 2.204E+01,
	243  :: 6 2.096E+01, 1.994E+01, 1.898E+01, 1.808E+01, 1.722E+01, 1.642E+01,
	244  :: 7 1.566E+01, 1.495E+01, 1.427E+01, 1.363E+01/     
	249  :: 1 0.000E+00, 6.265E+08, 1.897E+08, 8.126E+07, 4.203E+07, 2.450E+07,
	250  :: 2 1.236E+07, 8.249E+06, 5.782E+06, 4.208E+06, 3.158E+06, 2.430E+06,
	251  :: 3 1.910E+06, 1.567E+06, 1.274E+06, 1.050E+06, 8.752E+05, 7.373E+05,
	252  :: 4 6.269E+05, 5.375E+05, 4.643E+05, 4.038E+05, 3.534E+05, 3.111E+05,
	253  :: 5 2.752E+05, 2.447E+05, 2.185E+05, 1.959E+05, 1.763E+05, 1.593E+05,
	254  :: 6 1.443E+05, 1.312E+05, 1.197E+05, 1.094E+05, 1.003E+05, 9.216E+04,
	255  :: 7 8.489E+04, 7.836E+04, 7.249E+04, 6.719E+04, 6.239E+04, 5.804E+04,
	256  :: 8 5.408E+04, 5.048E+04, 4.719E+04, 4.418E+04, 4.142E+04, 3.888E+04,
	257  :: 9 3.655E+04, 3.440E+04, 3.242E+04, 3.058E+04, 2.888E+04, 2.731E+04,
	258  :: A 2.585E+04, 2.449E+04, 2.322E+04, 2.204E+04, 2.094E+04, 1.991E+04,
	259  :: 1 1.894E+04, 1.804E+04, 1.720E+04, 1.640E+04, 1.566E+04, 1.496E+04,
	260  :: 2 1.430E+04, 1.368E+04, 1.309E+04, 1.254E+04, 1.201E+04, 1.152E+04,
	261  :: 3 1.105E+04, 1.061E+04, 1.019E+04, 9.796E+03, 9.419E+03, 9.061E+03,
	262  :: 4 8.721E+03, 8.398E+03, 8.091E+03, 7.799E+03, 7.520E+03, 7.255E+03,
	263  :: 5 7.002E+03, 6.760E+03, 6.530E+03, 6.310E+03, 6.100E+03, 5.898E+03,
	264  :: 6 5.706E+03, 5.522E+03, 5.346E+03, 5.177E+03, 5.015E+03, 4.860E+03,
	265  :: 7 4.711E+03, 4.569E+03, 4.432E+03, 4.300E+03/     
	346  :: PARAMETER (CLIGHT = 2.9979258E18)                 
	347  :: PARAMETER (CLIGHTCM = 2.99792458E10)              
	361  :: DATA SIGMA /3.304E-18, 6.497E-18, 1.178E-17/      
	369  :: FO = 1.25E-9*XNE**0.66667 ! Holtsmark normal field strength
	424  :: RESONT = RESONT * 2.07E-24/GNM                    
	425  :: VDW = 4.45E-26/GNM*(XM2*(7.*XM2+5.))**0.4         
	426  :: STARK = 1.6678E-18*FREQNM*XKNM                    
	716  :: DATA Y1WTM/1.E18, 1.E17, 1.E16, 1.E14/            
	719  :: PARAMETER (CLIGHT = 2.9979258E18)                 
	721  :: PARAMETER (H = 6.62618E-27)  !Planck in cgs       
	722  :: PARAMETER (K = 1.38066E-16)  !Boltzmann in cgs    
	731  :: FO = XNE16**4*1.25E-9      ! Holtsmark normal field strength
	735  :: C2D = FO**2/5.96E-23/XNE                          
	736  :: GCON1 = 0.2+0.09*SQRT(T4)/(1.+XNE/1.E13)          
	737  :: GCON2 = 0.2/(1.+XNE/1.E15)                        
	783  :: Y1WHT = 1.E14                                     
	785  :: Y1WHT = 1.E13                                     
	810  :: IF ((Y2.LE.1.E-4).AND.(Y1.LE.1.E-5)) THEN         
	815  :: IF (GAM.LE.1.E-20) GAM = 0.                       


# HYDROPACMODI

	39   :: data  h1bfgc/1.0711223,  -3.0033216e-04,                              
	40   :: ;             1.0648009,  -5.1846584e-05,         
	41   :: ;             1.0478152,  -1.7104666e-05,         
	42   :: ;             1.0443061,  -8.2075951e-06,         
	43   :: ;             1.0421281,  -4.6750806e-06,         
	44   :: ;             1.0402398,  -2.9468910e-06,         
	45   :: ;             1.0347312,  -1.9145532e-06,         
	46   :: ;             1.0335221,  -1.3661146e-06,         
	47   :: ;             1.0335879,  -1.0323393e-06,         
	48   :: ;             1.0282216,  -7.4292798e-07,         
	49   :: ;             1.0337342,  -6.4224310e-07,         
	50   :: ;             1.0325113,  -5.1576699e-07,         
	51   :: ;             1.0321166,  -4.2484186e-07,         
	52   :: ;             1.0324288,  -3.6090637e-07,         
	53   :: ;             1.0329178,  -3.0957602e-07/         
	80   :: ne(k)=pe(k)/(t(k)*1.38066e-16)                    
	81   :: nh1(k)=presneutral(k,1)/(t(k)*1.38066e-16)        
	82   :: nhe1(k)=presneutral(k,2)/(t(k)*1.38066e-16)       
	85   :: hckt(k)=2.99792458e10*6.626075e-27/1.380658e-16*1.e8/t(k)
	86   :: dopple(k)=sqrt( xit**2 * 1.e10 +                  
	87   :: &                 2.*1.380658e-16*t(k)/1.6738e-24) /
	88   :: &                 2.99792458e10                   
	110  :: alpha = 1.044e-26 * h1bfg * xlb(l)**3 / (i**5)    
	119  :: if(contrib/osopx(k,l) .le. 1.e-4) goto 5          
	155  :: diffp=1.e30                                       
	225  :: if (contrib/osopx(k,l).le.1.e-4) goto 11          
	253  :: if (contrib/osopx(k,l).le.1.e-4) goto 12          
	285  :: data h/6.626e-27/, c/2.997925e10/, ionH/2.17991e-11/
	289  :: x=1./(float(ni)**2) - h*c/(wave(ij)*1.e-8*ionH)   
	324  :: DATA IONH/2.17991E-11/                            
	325  :: DATA A0  /5.29177E-9/                             
	326  :: DATA E   /4.803207E-10/                           


# INABS

	170  :: XKAP(JJ,K)=1.E-37                                                     
	216  :: if (ABS(1.-DIFF/DELT(KOMP,J)).ge.1.E-4) then      
	447  :: ABKOF(LL)=1.E-37                                  
	520  :: *I3,' SET ',I2,' XTET NR ',I2,' ABKOF PUT=1.E-37   ***INABS***')


# INJON

	408  :: EEV=1.602095E-12                                                      
	409  :: XMH=1.67339E-24                                   
	410  :: XKBOL=1.38066e-16                                 


# JON

	76   :: data pep/-1.e10/                                                      
	85   :: if ((abs((t-tp)/t).lt.1.e-8).and.(abs((pe-pep)/pe).lt.1.e-8))
	100  :: IF(ABS((T-TP)/T).LT.1.E-8)GO TO 53                
	128  :: 53 DXI=4.98E-4*TETA*SQRT(PE)                      
	291  :: cc      if ((abs((t-tp)/t).lt.3.e-2).and.(abs((pe-pep)/pe).lt.0.5))
	293  :: if ((abs((t-tp)/t).lt.1.e-1).and.(abs(log10(pe/pep)).lt.1.0))
	301  :: * if first call, pep=-1.e10, so this scaling of pgin will be skipped


# MOLFYS

	13   :: DATA A1/12.739,-5.1172,1.2572E-1,-1.4149E-2,6.3021E-4/,               
	33   :: DEH2nodis=(B1(5)*TE(5)+DEH2)*8.617E-5*T           
	34   :: DEH2Pnodis=(B2(5)*TE(5)+DEH2P)*8.617E-5*T         


# MOMEQCHECK

	19   :: if ((abs((pgjon(k)-pgcheck(k))/pgcheck(k)).gt.1.e-3))                 


# OSLISTMO

	225  :: PTIO(I)=AMAX1(PTIO(I),1.E-30)                                         
	508  :: +'flux (= sigma*Teff**4)',1PE11.3,'  erg/s/cm**2'/' Acceleration',


# OSMAINB

	42   :: !DATA TSUN,GSUN,RSUN/5777.,4.44,6.9598E10/                            
	75   :: c      HPLNCK=6.62608E-27                         
	76   :: c      BOLTZK=1.38066e-16                         
	77   :: c      CLIGHT=2.997925E10                         
	78   :: c      ECHARG=4.80298E-10                         
	80   :: c stefan changed 021106 (fron 5.675e-5 )          
	81   :: c      STEFAN=5.67040E-5                          
	194  :: IF (XMAX .EQ. 0.) XMAX = 1.E10                    


# OSMET_35

	61   :: xiturb(1)=xiturb(1)*1.e-5                                             
	63   :: if (abs(xiturb(1)-xit).gt.1.e-6) then             


# OSMET_SEPARATE_35

	37   :: xiturb(1)=xiturb(1)*1.e-5                                             
	39   :: if (abs(xiturb(1)-xit).gt.1.e-6) then             


# OSOPAC_35

	133  :: *      data epsilon/8.e-5/                                            
	266  :: c        hydroconst(k)=presneutral(k,1)/(rosav(k)*t(k)*1.38066e-16)
	706  :: xiturb(nxi)=xiturb(nxi)*1.e-5                     
	915  :: *  TEST GREY MODEL WITH KAPPA=1.e-2 cm2/g         
	921  :: ***        osopx(K,lambda)=1.e-2                  


# OSSOLVE

	556  :: if (info) write(20,'(1x,i3,4(1pe12.3))')                              
	653  :: if (info.and.j.eq.100.and.k.eq.1) write(20,'(1x,7(1pe10.2))')
	677  :: if (info.and.j.eq.100) write(20,'(1x,7(1pe10.2))')
	1096 :: x(k)=1.e-6                                        
	1116 :: x(k)=1.e-6                                        
	1136 :: x(k)=1.e-6                                        
	1380 :: PG1PE=0.                                          
	1750 :: if(abs((rr(k)-rrprev(k))/rr(k)).gt.3.e-4) then    
	2251 :: * F7.0,4F5.1,1PE10.3,2(0PF6.1),2I4,F6.3)          
	2263 :: & ' ERGS/CM**2/S ;nominal                         


# PEMAKE

	9    :: c KE                                                                  
	10   :: DATA IT,N,EPS/0,20,1.E-2/                         


# SCALE

	53   :: radius=6.9598e10 * 10.**(relrad)                                      


# SETDIS

	20   :: xlinup=1.e30                                                          


# STARTM

	62   :: DT1=1.E10                                                             
	80   :: PPE(1)=1.E-3                                      
	88   :: c????	if(teff.lt.4000.) ross(1)=1.e-2             


# TRANFR

	209  :: ysurf(i)=1.e-30                                                       
	382  :: & /'0BPLAN=',10(/10E12.4)/'0RR=',10(/10E12.4)/'0RHO=',10(/10E12.4)
	383  :: & /'0ROSS=',10(/10E12.4)/'0SOURCE=',10(/10E12.4)  
	384  :: & /'0YSURF,PFEAU='/(10E12.4))                     


# TRYCK

	53   :: DATA EPS,RELT,RELPE,PEDEF/1.E-3,1.E-3,1.E-3,1./                       
	225  :: DATA EPS,RELT,RELPE,PEDEF/1.E-3,1.E-3,1.E-3,1./   
