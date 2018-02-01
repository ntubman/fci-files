Results for the Green's function calculations along the imaginary 
frequency and energy axis. We compute the Green's functions for 
Matsubara frequencies following:

            w_n = PI / beta * (2 * n + 1) .....(1)
            
where n runs from [-nmax / 2,..., nmax / 2] and beta defines the 
range on which we can compute the imaginary time Green's function,
namely t in (0,beta).

For each system, we provide a folder. In
each folder, there are the following files:

          1. nmax_beta.txt: File name indicates the parameters nmax 
                            and beta.
          2. GFfreq.dat: Green's function matrix elements along the 
                         imaginary frequency axis. The format is 
                         specified in the first line.
          3. GFtime.dat: Green's function matrix elements along the
                         imaginary time axis. The format is specified
                         in the first line.
          4. imGF_1_1_time.png: Imaginary part of the [1,1] element
                                of the Green's function along the 
                                imaginary time axis.
          5. reGF_1_1_time.png: Real part of the [1,1] element
                                of the Green's function along the 
                                imaginary time axis.
          6. logReGF_1_1_time.png: Log of the absolute of the real 
                                   part of the [1,1] element of the 
                                   Green's function along the imaginary 
                                   time axis.                               
          7. imGF_1_1_freq.png: Imaginary part of the [1,1] element
                                of the Green's function along the 
                                imaginary frequency axis.                                   
