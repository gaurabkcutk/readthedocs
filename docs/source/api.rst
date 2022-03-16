Atmosphere Process Distribution
===

This page summarizes existing timer grouping for generating a bar graph to show time spent in various atmosphere processes.

Label             Timer(s)

Convection        'a:moist_convection'
CLUBB             'a:macrop_tend'
Aerosol           'a:microp_aero_run' + 'a:tphysbc_aerosols'
Microphys         'a:microp_tend'
Radiation         'a:radiation'
Phys AFT SurFace  'a:phys_runs2'
Dynamics          'a:stepon_run3'
Phys/Dyn Coupling 'a:stepon_run1' + 'a:stepon_run2'
Hist              'a:wshist'
ATM Other         'CPL:ATM_RUN' - sun (all above timers)

