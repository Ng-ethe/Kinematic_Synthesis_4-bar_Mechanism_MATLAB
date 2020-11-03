# Kinematic_Synthesis_4-bar_Mechanism_MATLAB
A MATLAB function to synthesize a 4 bar mechanism.

A four bar linkage is required to generate the following function,
theta4 = 65 + 0:43*theta2
for 15 <= theta2 <= 165 (in degrees). Where theta2 and theta4 define the rotation angles of the input and output
links respectively. It is further required that the length of the fixed link be 410mm.
Write a computer program in MATLAB to,

(a) Evaluate the link lengths ratios K1, K2 and K3 using three precision points, and
hence determine the lengths of the other links. Use Chebyshev's spacing. De-
termine the transmission angles for the given range of input angles and at an
increment of 5 degrees, and plot the variation of the transmission angles with the input
angles. Comment on the quality of transmission of the linkage.

(b) Evaluate the link lengths ratios K1, K2 and K3 using the least square method
for 5 precision points, and hence determine the length of the other links. Use
Chebyshev's spacing.

(c) Calculate the structural errors throughout the given range of input angles and
at an increment of 5 degrees for the two cases in (a) and (b). Plot the variation of the
structural errors as a function of the input angles for the two cases and in the same
axis. Comment on the results.
