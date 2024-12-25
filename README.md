java c
EEEM061:       Advanced 5G Wireless Technologies 
Semester 2   2023/4 
Q1. 
(a)                         In   relation to single-user, 5G   Multiple-Input   Multiple-Output   (MIMO) systems:(i)                            Explain,   in   less than   100 words, what a   MIMO   channel   is   and   how   this   can   be      represented   in   matrix form   in the case of flat fading   (i.e.,   single tap)   channels. [10 %] 
(ii)                      Give   the   mathematical   relationship   that   links the   transmit   and   received   vectors over a   MIMO channel.   Define   the   parameters that you   use   and      explain the dimensions of the vectors   and   matrices. [10 %] 
(b)                      In   relation to   detection/decoding   of wireless   communication   systems:
(i)                            Give the   definition of   Log-Likelihood-Ratio   (LLR) and explain   in   less than   100   words, what   information can   be obtained from   its amplitude   and   its   sign. [10 %] 
(ii)                         Based   on the definition of   part   (ii),   if a   bit   b   hasan   LLR   value   of   0.5   calculate   the   probability of this   bit to   be equal to one   (b    =    1)   and the   probability of            this   bit to   be   equal to   (b   =   0). [10 %] 
(c)                         Assume   a   1   ×   2 Single-Input,   Multiple-Output   (SIMO) system, where the
corresponding flat-fading channels are h1       =    1   and h2      =   j and the additive white   Gaussian   noise variance at   each   receive antennas   is one. Also   assume that transmitted symbols   belong to a 4-QAM constellation   (i.e.,   1   +   j,   1   −   j,   −1   +   j,   −1   −   j). 
(i)                            Explain what   kind   of   processing should   be   performed   at the   receiver   in
order to   maximize the corresponding signal-to-noise   (SNR)   ratio and derive   the equation describing the   post-processed   received signal. Then, calculate   the corresponding SNR. [20 %] 
(ii)                         If the signals at   each   receive antenna   are   y1       =   2   − j   andy2       =   −1.5,
perform. symbol detection   based on the   method you   described   in   part   (i). [10 %] 
(iii)                      If the signals at   each   receive antenna   are   y1         =   2   − j   andy2       =    1.5,    and   if   you   know that   repetition coding of ½   rate   has   been   applied, first   explain      how one would   perform. optimal detection/decoding. Then,   optimally decode the transmitted   bit, when you   know that Gray coding   has   been applied for   bit-to-symbol   mapping, and that the   bits   00 are   mapped   onto   the symbol   1   +   j. Justify your answer. 
[30 %] [SEE NEXT PAGE]
Q2. 
(a)                        In   relation to wireless transmissions:
(i)                            Fig.   1   shows channel frequency   responses of two different   channels.   In   less than   100 words explain   1) what are   characteristics   of the time domain   impulse   responses for these channels; 2)   how to counter   the   effect of these   channels. [10%] Figure   1
(ii)                         In   less than   100 words explain the advantages   of   OFDM. [10%] 
(iii)                   Given   the   original   rate   ½   code   shown   in   Fig.   2,   suggest   a   technique   to      change the code   rate to 5/6 and   explain your   solution   mathematically   and schematically.Figure   2 [15%] 
(iv)                      In   less than   100 words explain the three   main   benefits   of   non-orthogonal   multiple access   (NOMA)   in comparison to orthogonal   multiple   access (OMA). [10%] 
(b)                      In   relation to   Reconfigurable   Intelligent   Sur代 写EEEM061: Advanced 5G Wireless Technologies Semester 2 2023/4R
代做程序编程语言faces   (RISs),   the      far-field   path   loss   model of the end-to-end channel through   RIS   is   expressed   as

where Rc    is the   reflection coefficient, N is the   number   of elements   on   the   surface,A is   the   area   of   each   element,dg      is   the   distance   between   the transmitter and the surface,dh      is the distance   between the   surface and   the   user.
(i)                               Consider the size of each   element   is 2/λ,    the   area   of   each   element   is   A= 2/λ × 2/λ, where λ is the wavelength   and   c   is the   speed   of   light. Assume   that   N   =   2000,   f   =   3.5 GHz, dg       =   6   m,and    dℎ  =   3   m. Calculate the end-to-   end channel gain through this   RIS.   For simplicity, assume   Rc       =    1. [20%] 
(ii)                      Suppose that   there   is   a   blockage   between   the   transmitter   and   the   user.   In this case, the   direct channel   between the transmitter   and the   user   is      modelled as follows:
patℎlossdirect   (dB)   =   peL   − 28   log10   (ddirect   ),
in the decibel scale, where the   penetration   loss peL    =   −35dB.
Calculate the gain of direct   link   between the transmitter   and the   user   when   ddirect      =   6   m. [10%] 
(iii)                      In   less than   100 words, explain what   can   be   inferred   by comparing   the   obtained   results   in   part   (i) and   part   (ii). [10%] 
(iv)                   Suppose that   the   channel   gain   has   to   be   greater   than   -25   dB   for   reliable   transmission.   Determine the   minimum   number of   RIS elements Nmin that   is   required to achieve   reliable communications. Justify your answer. [15%]
Q3. 
(a)                         In   relation to   5G wireless systems:
(i)                            In   less than   100 words explain the   purpose   of   network densification   and   discuss the two contradictory effects when the   cell   density   becomes higher. [10%] 
(ii)                         Explain the   main   requirements for the   massive   machine type
communications   (mMTC) and   ultra-reliable and   low   latency communications   (URLLC) services,   respectively, and   discuss   how you can   use different   numerologies to support them.      Describe the   problems encountered   if these two services are   provided   by 4G-LTE   networks. [20%] 
(iii)                   Consider   an   OFDM   system   with   N   subcarriers,   where   its   peak   to   average      power   ratio   (PAPR)   is given   by PAPRdB =   10log10 N . Calculate the   PAPR   when   N=1,16,   64,   256,   respectively, and explain whether   it   is   preferrable   to   have a very small   number of subcarriers   in   OFDM   systems   in   order   to minimize   PAPR. [15%] 
(b)                      In   relation to   the   sparse   code   multiple   access   (SCMA)   system   with   10   users   sharing   5   subcarriers as shown   in   Fig.   3:

Figure   3
(i)                         Derive the signature   matrix   of   such   an   SCMA   system. [20%] 
(ii)                      Calculate the   value   of the   overloading   factor,   and   the   effective   spreading   dv and   the   multiplexing factor dc. Explain the   practical significance of   each   parameter. [15%] 
(iii)                      Illustrate   how to construct the four codewords   required to form   the   codebook   for the 7th   user   using the   following   permutation   pattern.   Explain the   main benefit of constellation   permutation.
Codeword 1 
Codeword 2 
Codeword   3 
Codeword 4 
1 
2 
4 
3 
2 
1 
3 
4 
Table: Permutation Pattern 
[20%] 







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
