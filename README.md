Wire gauge is the resistance per unit length in decibels, where 10 AWG
wire has 1 ohm per thousand feet resistance. Therefore, every increase
of 3 AWG ($\approx 10\times\log_{10}2$) increases the resistance per
unit length by a factor of two. The general formula for the gauge of
wire given the resistance per thousand feet $R$ is

$$\mathrm{AWG} = 10 \times\log_{10}R + 10$$

or

$$R = 10^{\mathrm{AWG}-10 \over 10}$$

ohms per thousand feet.

Wire of length $L$, cross-sectional area $A$ and conductivity $\sigma$
has resistance $L/\sigma A$, or resisitance per unit length $R =
1/\sigma A$. Using the formula above gives

$$A \propto 10^{-{\mathrm{AWG}-10 \over 10}}\qquad\mathrm{or}\qquad 
  D \propto 10^{-{\mathrm{AWG}-10 \over 20}}$$

where $D$ is the diameter of the wire. Using the fact that 10 AWG wire
has a diameter of 0.10 inches gives

$$D = 10^{-{\mathrm{AWG}+10 \over 20}}.$$

Solving this equation for wire gauge given diameter

$$\mathrm{AWG}=-20\times\log_{10} D - 10.$$

A reasonable value for the current carrying capacity of a wire can be
estimated from the rule that the cross-sectional area should be 700
"circular mils" per amp. The (rather perverse) definition of a circular
area measured in "circular mils" is that it is the area of the square
whose side has the same length as the diameter of the circle, i.e. just
the diameter (in mils or 0.001 inch) squared. The current carrying
capacity in amps is therefore (with $D$ measured in inches)

$$I={10^{6}\times D^2\over 700}$$

or in terms of AWG

$$I={1\over 700}\times10^{50-\mathrm{AWG}\over 10}$$

solving for AWG in terms of current

$$\mathrm{AWG}=50 - 10\times\log_{10}(700\times I)$$

The power dissipated in the wire per foot is

$$P=I^2R.$$

Substituting $I$ and $R$ given by the formulas above gives

$$P=\Big({1\over 700}\Big)^2\times10^{90-\mathrm{AWG}\over 10}$$

Watts per thousand feet.
