If the bottom mixing is too strong, you can adjust this. This is a good value for open ocean, med sea outflow, 
but in coastal region, a better value should be 0.02 (according to brandon):

BBL_EFFIC = 0.2                 !   [nondim] default = 0.2
                                ! The efficiency with which the energy extracted by
                                ! bottom drag drives BBL diffusion.  This is only
                                ! used if BOTTOMDRAGLAW is true.
