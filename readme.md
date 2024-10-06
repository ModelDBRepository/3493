NEURON mod files for the Na, K-A, and K-DR currents from the paper:
Safronov and Vogel, *J.Physiol*. 487:91-106 (1995).

- Running the kinetics_na.hoc or kinetics_k.hoc simulation files 
will show the activation and inactivation steady-states, 
the time constants, and a family of curves generated modeling 
the same protocols used in the paper.

- Markers show the experimental values estimated from Figs.4C 
(Na), 8C (KA), and 10C (KDR) of the paper.
Note that m is used rather than the more usual m^3 for activation
of the Na current. Na recovery from inactivation is not implemented.
 
## Under unix systems:
to compile the mod files use the command 
``` nrnivmodl ```
and run the simulation hoc file with the command 
``` nrngui kinetics_na.hoc ```
or 
``` nrngui kinetics_k.hoc ```

## Under Windows using NEURON 5.1:
to compile the mod files use the ``` mknrndll ``` command.
A double click on the simulation files
kinetics_na.hoc or kinetics_k.hoc
will open the simulation windows.

\
Questions on the model parameters should be directed to the 
authors.

Questions on how to use this model with NEURON
should be directed to michele@pa.ibf.cnr.it

Changelog:
----------
2024-10: Converted readme to markdown
