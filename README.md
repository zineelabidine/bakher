# solving the Pitzer equation using "Fminsearch" (matlab)

thermodynamic modeling of phosphoric acid using "Pitzer equation" : 

# Description:
A calculation method is presented in this study to evaluate the ion interaction parameters for the Pitzer model of freezing point and the isopiestic molalities of aqueous phosphoric acid solution.
the code is in matlabe for evaluation of the parameters of Pitzer using the function "Fminsearch".
the equation and mathematical background is presented in our manuscript:

"" Thermodynamic properties and Pitzer’s parameters determination for orthophosphoric acid from the Freezing Point and isopiestic measurement data, Z. Bakher and M. Kaddami, Brazilian Journal of Chemical Engineering, 2018""
# Pitzer model:
The Pitzer model was applied in the treatment of non-ideality, in the case of electrolyte 1-1 the osmotic coefficient  of the solution and mean activity coefficient   of electrolyte can be written as:
'eq 11,12,13,14,15,16,17,18'

Where + and ν- are the numbers of M and X ions in the formula, Z+ and Z- given their respective charges, m is the conventional molality, AD-H is Debye-Huckel constant with d1 is water density and  is permittivity of the vacuum, D  dielectric permeability of pure water at temperature T [K], N0 is Avogadro’s number, K is Boltzmann constant, the value of AD-H is 0.392 Kg1/2.mol-1/2 at 298.15 K.
The Pitzer values of two parameters α and b are 2.0 and 1.2 respectively.I is the stoichiometric ionic strength of the solution [mol/Kg] .

in our work the variation of Pitzer’s parameters values for Phosphoric acid resulted in the following equations:
B0=a0+b0T+c0ln(T) 
eq 37
B1=a1+b1T+c1T^2
eq 38
C1=a+bT+cln(T) 

# contact:
for contribution to the Pitzer equation resolution project or for more information on modeling electrolytic systems, please contact me at:
z.bakher@uhp.ac.ma
