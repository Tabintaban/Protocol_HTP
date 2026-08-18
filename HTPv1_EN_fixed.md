**Hydrogen Tunneling Protocol (HTP)**

**Protocol / Model Name**

**Version: v1.0**

**Status: Fixed**

**Date of fixation (UTC): 19.01.2026**

**Author**

-   **Pseudonym / Identifier:** \_NOMOS-H\_

-   **Public Key Fingerprint:** 2D0C4604CCF007C1AFDDADBBDBB49B9C183EB014

**Content Integrity**

-   **Document Hash (SHA-256):**
    9cfbbbf78e3d6c987d4e98e29510a8fef84968a4e952c74ac344061b8f4cea6f\_

-   **IPFS CID:** QmR2PKs1TcyJdY6QRu7KFbX9R2xUwzDxnG2a97NAxSnoFn

-   **Blockchain Anchor (tx / block):** HTPv1_EN.docx.ots

**1. Purpose**

For water splitting there is a limitation in the form of a thermodynamic
limit

ΔG° = 237 kJ/mol H₂O

This is the thermodynamic limit - it is impossible to split water less
than this energy in principle.

In terms of liters per minute, this limit is 219 watts \* minute/liter.

There is also another limitation in the form of a covalent bond in a
water molecule

O-H single bond energy: ≈ 459-463 kJ/mol

(often average ≈ 460 kJ/mol)

In electron volts:

460 kJ/mol ≈ 4.77 eV per bond

For the entire water molecule

There are two covalent O-H bonds in the water molecule, therefore:

Total bond energy:

≈ 920 kJ/mol (≈ 9.5 eV per molecule)

Thus, in order to split a water molecule, it is necessary to expend
energy less than 237 kJ/mol and overcome the energy barrier of 460
kJ/mol.

The existing classical methods of splitting water molecules, among them
the most energetically advantageous, is electrolysis, are not able to
provide energy costs less than the thermodynamic limit.

To solve this problem, the tunneling of a hydrogen proton from a water
molecule is intended.

Physical principle.

An alternating pulsating electromagnetic field is created, which creates
a temporary modulation of the potential O-H coupling surface,
effectively reducing the height and/or width of the tunnel barrier for
the proton. As a result, the probability of hydrogen proton tunneling
from a covalent bond increases. As a result, the water molecule is
destroyed, hydrogen and oxygen on the gas.

A distinctive feature of this method from electrolysis is that an
alternating electromagnetic field creates conditions for proton
tunneling in the entire volume of water and the entire volume of water
produces hydrogen and oxygen gas.

In electrolysis, the splitting of water occurs at the electrode-water
contact.

**2. Scope and Non-Goals**

**2.1 Scope**

This paper, **Hydrogen Tunneling Protocol (HTP) v1.0**, sets the
framework for a theoretical physics and mathematics model describing the
external field-induced dissociation of water molecules into molecular
hydrogen and oxygen through the photon-assisted proton tunneling
mechanism.

**The model is applied within the following framework:**

**1.** **Theoretical study:** The model serves as a tool for calculating
the probability of proton tunneling and assessing the theoretical
efficiency (volumetric probability \'P \_ vol\') of water dissociation
in a given oscillating electromagnetic field.

**2. Determination of critical parameters:** The model allows you to
determine the qualitative and ordinal relationships between the
parameters of the external field (strength \'E ₀\', frequency \'ω\'),
the properties of the substance (parameters of the Morse potential) and
the output characteristic of the process (gas generation rate).

**3. Checking the fundamental possibility:** The document defines the
conditions under which volumetric dissociation of water can
theoretically occur without the need to overcome the full energy of the
O-H bond in a classical way and without localizing the process on the
surface of the electrodes.

**4. Pure water context:** The model is valid for a system representing
the volume of pure (deionized) liquid water between the electrodes at
temperatures that exclude significant thermal dissociation.

**2.2 Explicit Non-Goals**

This protocol is **NOT** and does **NOT** have the following objectives:

**1. Engineering or design documentation:** The document does not
contain specifications, diagrams, drawings or instructions for creating
a physical device (\"reactor\" or \"generator\") to implement the
described process.

**2. Assurance of practical implementation:** The model does not
guarantee that the described effect can be practically implemented using
existing technologies for creating fields of the required parameters or
that it will be energy efficient in real conditions, taking into account
all losses.

**3. Optimization for commercial efficiency:** The purpose of the model
is not to search for parameters that provide an excess of a single
energy output (gas output to spent energy) or overcoming the
thermodynamic limit (Δ G) in a real macroscopic system with full energy
consumption.

**4. Working with electrolytes:** The model is not initially applicable
and is not intended to describe the dissociation of water in the
presence of acids, alkalis, salts or any other ionic conductors
(electrolytes), where classical electrolysis becomes the dominant
mechanism.

**5. Description of by-processes:** The document does not address or
model possible competing or by-side physico-chemical processes such as
medium heating by dielectric losses, peroxide formation, ozone,
excitation of electronic states, or radiolysis.

**6. Safety Guide**: The document does not provide instructions or
warnings on the safe handling of gases (hydrogen-oxygen mixture), high
voltages or other potential hazards that may arise when trying to pilot
test.

**3. Definitions**

This section defines the key terms used in the description of the
physical and mathematical model of the Hydrogen Tunneling Protocol
(HTP). Definitions are given in the context of this document.

-   **Proton Tunneling:** Quantum mechanical process in which a proton
    (the nucleus of a hydrogen atom, H⁺) overcomes a potential energy
    barrier (covalent O-H bond) without the classical achievement of
    energy equal to the height of the barrier due to its wave function.
    In context, HTP is the primary mechanism for breaking the O-H bond.

-   **Morse Potential:** An analytical model approximating the potential
    energy of a diatomic bond (in this case, O-H). It is described by
    the equation \'U ₀ (x) = D ₑ (1 - e \^ {-ax}) ²\', where \'D ₑ\' is
    the dissociation energy, \'a\' is the \"stiffness\" parameter, \'x\'
    is the displacement from the equilibrium position. More precisely
    than a harmonic oscillator, describes the asymmetry and finite depth
    of a real potential well.

-   **Thermodynamic Limit (Δ G):** The minimum theoretically required
    energy to split one mole of liquid water into hydrogen and oxygen
    gases under standard conditions. It is 237 kJ/mol H₂O (or 1.23 eV
    per molecule). It is a fundamental limitation for any water
    electrolysis process.

-   **O-H Bond Dissociation Energy (D ₑ):** The energy required to break
    one covalent oxygen-hydrogen bond in an isolated water molecule. In
    the model, Morse corresponds to the depth of a potential hole. It is
    approximately 460 kJ/mol (≈ 4.77 eV) for one bond.

-   **Photon-assisted Tunneling:** A type of tunneling in which a system
    (proton) absorbs or emits one or more quanta (photons) of energy
    from an external oscillating field, which effectively changes the
    height and width of the tunnel barrier through which the transition
    occurs. Key mechanism in HTP to reduce activation energy.

-   **Multiphoton Process**: A process in which the interaction of a
    quantum system with an electromagnetic field occurs through the
    absorption or emission of several photons (\'nℏ ω\') in one
    elementary act. In the HTP tunneling probability equation (Eq. 3) is
    described by summing over all possible channels with different
    number \'n\'.

-   **Coherent/Resonant Electromagnetic Field:** An external alternating
    field with a certain frequency (\'ω\') and phase, created for
    targeted interaction with a quantum system (O-H coupling
    oscillations). In HTP, the field must be synchronized in time and
    space to effectively modulate the Morse potential.

-   **Effective Tunnel Barrier Width (s):** The conditional distance
    between the classical pivot points (\'x ₁\' and \'x ₂\') in a
    potential where the kinetic energy of the proton is zero. Determines
    the exponential factor in the probability of tunneling by the VKB
    approximation. Field modulation changes this width.

-   **Wentzel-Kramers-Brillouin Approximation (WKB):** A semi-classical
    method in quantum mechanics for estimating the probability of
    tunneling through a smoothly varying potential barrier. Used in HTP
    to derive a proton tunneling probability expression (Eq. 3).

-   **Volumetric Probability/Efficiency (P_vol):** Macroscopic parameter
    of the model, which determines the proportion of water molecules in
    a given volume that undergo dissociation due to tunneling during the
    field exposure period. It is calculated as the spatial and temporal
    averaging of the probability of tunneling of an individual molecule.
    Distinguishes HTP from surface electrolysis.

-   **Electrolysis:** The classical electrochemical process of
    decomposing water into hydrogen and oxygen by direct current,
    occurring only on the surface of electrodes (anode and cathode). It
    is associated with overcoming both the thermodynamic limit (ΔG°) and
    additional overvoltages.

**4. Assumptions and Conditions**

> This model is based on a number of fundamental assumptions and
> operates within strictly defined conditions. Departing from these
> premises renders the model inapplicable or requiring substantial
> modification.

**4.1. Fundamental physical assumptions:**

-   **A1. Quantum mechanical description of a proton:** A proton in a
    water molecule is considered as a quantum particle whose behavior
    (in particular, tunneling) is correctly described by the
    non-stationary Schrödinger equation. Relativistic effects are
    neglected.

```{=html}
<!-- -->
```
-   **A2. O-H isolated bond model:** The potential energy of a proton
    within one covalent O-H bond is approximated by the one-dimensional
    Morse potential \'U ₀ (x)\'. The interaction of this bond with
    neighboring water molecules (through hydrogen bonds or dipole-dipole
    interactions) in the zero approximation is not taken into account,
    being considered a second-order perturbation.

-   **A3. Adiabatic approximation for electrons**: It is assumed that
    the electronic subsystem of the water molecule manages to instantly
    adapt to the movement of heavy nuclei (Born-Oppenheimer adiabatic
    approximation). Thus, the Morse potential is considered the
    effective potential created for the proton averaged over the
    positions of the electrons.

**4.2. Environmental conditions:**

-   **E1. Field coherence and homogeneity**: The external
    electromagnetic field is modeled as classical, linearly polarized,
    coherent and spatially homogeneous within the active volume between
    the electrodes. Its amplitude (\'E ₀\') and frequency (\'ω\') are
    controlled parameters.

-   **E2. Dipole approximation:** The wavelength of the external
    electromagnetic field is assumed to be much larger than the
    geometric dimensions of the system (distance between the
    electrodes). This allows the use of a dipole approximation in which
    the spatial dependence of the field potential is reduced to the
    linear form \'\~ qE ₀ x cos (ω t)\'.

-   **E3. No dissipative losses in the medium**: The tunneling modeling
    stage does not take into account the energy losses of the external
    field for heating the medium (dielectric losses), joule heat or
    radiation. The medium (water) is considered as an ideal dielectric
    without free charge carriers.

**4.3. Substance (water) related conditions:**

-   **E4. Pure deionized water:** The model considers an environment
    consisting solely of H ₂ O molecules. The presence of dissolved
    salts, ions, acids or electrolytes is excluded, since this
    fundamentally changes the mechanism of conduction and charge
    transfer to electrolysis.

-   **E5. Low temperature mode:** The temperature of the system is
    assumed to be low enough so that the thermal dissociation of
    molecules (overcoming the barrier due to kT energy) and the thermal
    broadening of energy levels are negligible compared to the
    probability of field-induced tunneling.

**4.4.** **Mathematical and model assumptions:**

-   **A4. Applicability of the VKB approximation:** To calculate the
    probability of tunneling, a semiclassical VKB approximation is used,
    which is true for smoothly varying potentials when the de Broglie
    wavelength of the proton is small compared to the characteristic
    scale of the potential change.

-   **A5. Stationarity of the initial state:** At the initial moment of
    time, the proton in each molecule is in the basic oscillatory state
    (v = 0) of the Morse potential for the O-H bond. Excited oscillatory
    states are neglected.

-   **A6. Independence of dissociation acts**: The act of tunneling a
    proton in one molecule is considered a statistically independent
    event that does not affect the probability of tunneling in
    neighboring molecules during a time that is small compared to the
    field period. This assumption underlies the calculation of the
    volumetric probability \'P \_ vol\'.

**5. Core Physical--Mathematical Model**

**5.1 Variables and Parameters**

-   **\'U ₀ (x)\':** Potential energy of a proton in a water molecule
    (Morse model).

-   **\'x\':** Proton coordinate along O-H bond axis.

-   **\'D ₑ\':** Potential well depth (O-H bond dissociation energy).

-   **\'a\':** Parameter that defines the width of the Morse pit.

-   **\'V \_ ext (t)\':** External oscillating potential generated by an
    alternating electromagnetic field.

-   **\'E (t) = E ₀ cos (ω t)\':** Alternating electric field strength.

-   **\'q\':** Proton charge.

-   **\'ω\':** Cyclic frequency of the external field.

-   **\'E\':** Proton energy in the initial bound state.

-   **\'s\':** Effective width of tunnel barrier for proton in Morse
    potential.

-   **\'m \_ p\':** Proton mass.

-   **\'h, l\':** Geometrical dimensions of electrode plates.

-   **\'T\':** Probability of tunneling for a single molecule over the
    exposure period.

-   **\'P \_ vol\':** Volumetric probability (efficiency) of tunneling
    for the entire water sample between the electrodes**.**

**5.2 Core Relations / Equations**

**(Equation 1): Morse potential for O-H covalent bond**

The potential energy of a proton in the absence of an external field is
described by the Morse potential:

$$U_{0}(x) = D_{e}{(1 - e^{- ax})}^{2}$$

Where \'x \' is the displacement of the proton from the equilibrium
position. This potential is asymmetric and has a final height of barrier
for dissociation.

**(Equation 2): Alternating electromagnetic field effect**

External coherent field creates periodic potential modulation:

$$U(x,t) = U_{0}(x) + V_{ext}(t) = D_{e}{(1 - e^{- ax})}^{2} + qE_{0}x\cos(\omega t)$$

The term \'qE ₀ x cos (ω t)\' represents a linear potential that
periodically \"tilts\" the Morse pit, effectively reducing the height
and width of the tunnel barrier on the proton\'s path to the
dissociation state.

**(Equation 3): Probability of photon-assisted proton tunneling**

Within the Wentzel-Kramers-Brillouin (WKB) approximation given field
modulation, the probability of a proton tunneling with energy \'E\'
across a barrier of width \'s\' over the field oscillation period can be
expressed as the superposition of channels with absorption/emission of
\'n\' field photons:

$$T(s,E,t) = \sum_{n = - \infty}^{\infty}{}J_{n}^{2}(\frac{qE_{0}s}{\hslash\omega}) \cdot \exp\lbrack - \frac{2}{\hslash}\int_{x_{1}^{(n)}}^{x_{2}^{(n)}}{}\sqrt{2m_{p}(U_{0}(x) - E - n\hslash\omega)}dx\rbrack$$

where \'J \_ n\' is the Bessel function of the first kind of order
\'n\', which describes the strength of the connection with the field,
and the integral is taken between the classical rotation points \'x ₁\'
and \'x ₂\', found from the condition \'U ₀ (x) = E + nŋω\'. The
probability of tunneling increases for channels, where \'nŋ ω\'
compensates for the difference \'U ₀ (x) - E\'.

**(Equation 4): Volumetric probability (efficiency) of the process**

Since the alternating field penetrates the entire volume of water
between the electrodes with an area of \'h × l\', each molecule in this
volume has a non-zero probability of dissociation. The total macroscopic
probability (or efficiency) of the process for the entire sample is
determined by averaging over the area of the electrodes:

$$P_{vol} = \frac{1}{hl}\int_{0}^{h}{}\int_{0}^{l}{}\langle T(s,E,E_{0}(y,z),\omega)\rangle_{t}dydz$$

where \'⟨\... ⟩ \_ t\' denotes averaging over time (field period), and
\'E ₀ (y, z)\' is the spatial distribution of field amplitude. With a
homogeneous field \'E ₀ \', the formula is simplified.

**Physical interpretation of the model:**

The alternating field does not simply impose a constant potential
gradient (as in electrolysis), but creates a dynamic modulation of the
initial coupling potential (Equation 2). This allows protons to cross
the barrier through multiphoton processes (Equation 3), effectively
reducing the activation energy required for dissociation. The key
difference from electrolysis is formalized in Equation 4: the process is
not localized on the surface of the electrode, but distributed over the
entire volume, where there is sufficient coherent field strength. This
leads to the volumetric nature of gas generation.

**6. Input and Output Description**

This section formally defines the input parameters (set conditions) and
output values (calculation results) for the physical and mathematical
**model of the Hydrogen Tunneling Protocol (HTP).** The relationship
between inputs and outputs is given by the equations in Section 5.

**6.1 Inputs**

Input parameters are a set of constants and control variables that fully
determine the state of the system for calculating according to the
model.

**A. Fundamental physical constants:**

-   **\`q\`:** Elementary charge (proton charge), ≈ 1.602×10⁻¹⁹ Cl.

-   **\`m_p\`:** Proton mass, ≈ 1.673×10⁻²⁷ kg.

-   **\`ħ\`:** Planck\'s reduced constant, ≈ 1.055×10⁻³⁴ J· s.

-   **\`N_A\`:** Avogadro number, ≈ 6.022×10²³ mol⁻¹.

**B. Параметры вещества (вода / связь O--H):**

-   **\`Dₑ\`:** Dissociation energy (pit depth) of Morse potential for
    O-H bond. Recommended/reference value: ≈ 7.36×10⁻¹⁹ J per bond (460
    kJ/mol).

-   **\`a\`:** The \"stiffness\" parameter of the Morse potential, which
    determines the width of the pit. Recommended/reference value: ≈
    2.2×10¹⁰ m ⁻¹ (based on spectroscopic data).

-   **\`ρ_m\`:** The numerical density of water molecules in volume.
    Design value: ≈ 3.34×10²⁸ м⁻³ (for liquid water at 25 °C).

**C. External exposure parameters (control variables):**

-   **\`E₀\`:** Amplitude of applied alternating electric field
    strength. \[Volt/meter, V/m\]. Key control variable.

-   **\`ω\`:** Cyclic frequency of the applied alternating electric
    field. \[radian/second, rad/s\]. Key control variable.

-   **\`τ\`:** Field exposure duration (optional for integral output
    calculation). \[second, s\].

**D. Geometric parameters of the system:**

-   **\`A\`:** Active electrode area (height \'h\' × length \'l\').
    \[meter ², m ²\].

-   **\`d\`:** The distance between the electrodes (determines the
    volume, \'V = A \* d\'). \[meter, m\].

**E. Initial System State Settings:**

-   **\`E\':** Initial proton energy at Morse potential. In the standard
    scenario, it is taken equal to the energy of the main oscillatory
    level (v = 0). \[Joule, J\].

**6.2 Outputs**

The output values are the result of calculations from the model based on
the specified input parameters.

**A. The main calculated probabilities (dimensionless values):**

-   **\'T (n)\':** Probability of proton tunneling in one period of
    field oscillation for a particular \'n\' -photon channel (see Eq.
    3). Vector of values for series\' n \'.

-   **\'T \_ total\':** The total probability of proton tunneling from a
    molecule over a single field period, calculated as\' Σ T (n) \'over
    all significant\' n \'channels.

-   **\'P \_ vol\'**: Volumetric probability (macroscopic efficiency) -
    the proportion of molecules in a given volume that have undergone
    dissociation in one field period (see Ur. 4). It is an integral
    characteristic for the system.

**B. Derived macroscopic parameters:**

-   **\`R_mol\`:** Theoretical rate of dissociation (number of acts per
    second). Calculated as \`R_mol = (P_vol \* ρ_m \* V \* ω) / (2π) \`.
    \[с⁻¹\].

-   **\`R_vol\`:** Theoretical gas mixture generation rate (H ₂ + ½ O ₂)
    under standard conditions. Calculated as \`R_vol = R_mol \* (22.4 /
    mol) / N_A\'. \[liter/second, l/s\].

-   **\`W_min\`:** Theoretical minimum power spent only on the act of
    dissociation (excluding losses). Calculated as \`W_min = R_mol \*
    Dₑ\`. \[Watt, W\]. \* Note: This value is a theoretical minimum and
    serves for comparison with the thermodynamic limit (237 kJ/mol), but
    does not reflect the full energy consumption of the real system. \*

**C. Информационные выходы модели:**

-   **\`n_optimal\`:** The order \'n\' of the multiphoton channel
    contributing most to \'T \_ total\'. Indicates the predominant
    interaction mechanism (single-photon, multiphoton).

-   **\`s_eff\`:** Effective width of tunnel barrier calculated for
    conditions determined by field (\`E₀\`, \`ω\`). \[meter, m\].

**7. Applicability Limits**

This section defines the conditions under which the mathematical model
and the physical principles of HTP (v1.0) are considered valid (fair),
as well as the conditions under which the model is not applicable or its
predictions are not defined.

**7.1 Valid Conditions**

The model is considered applicable and provides physically meaningful
assessments when the following conditions are met at the same time:

-   **1. Condition of the substance:** The target is pure (deionized)
    liquid water (H₂O) in phase, excluding the presence of a significant
    concentration of free ions (H⁺, OH⁻) or dissolved electrolytes. The
    concentration of impurities shall be negligible to ensure the
    dielectric properties of the medium.

-   **2. Energy mode:** The average energy of thermal motion of
    molecules (\'k \_ BT\') is significantly less than both the depth of
    the potential Morse well (\'D ₑ\') and the energy of quanta of the
    external field (\'ħω\'), so that the effects of thermal excitation
    and broadening of levels can be neglected. This corresponds to the
    low temperature mode (conventionally, T \<350 K).

-   **3. External Field Options:**

    -   **Frequency (\'ω\'):** Must be comparable to the inverse
        characteristic tunneling time or intrinsic oscillatory frequency
        of the proton in the Morse pit (of the order of 10¹³ - 10¹⁴
        rad/s). The field must be resonant or quasi-resonant with
        transitions between virtual levels in the barrier.

    -   **Voltage (\'E ₀\'):** Should be sufficient for significant
        potential modulation (i.e., \'qE ₀ \* a ⁻ ¹\' should be
        comparable to \' ħω\'), but not exceed the electrical breakdown
        threshold for water (≈ 0.065 - 0.07 V/nm for a constant field;
        for a variable high-frequency field, the limits may be
        different).

-   **4. Geometrical and field conditions:** The radiation wavelength of
    the external field significantly exceeds all geometrical dimensions
    of the system (distance between electrodes \'d \'). This ensures the
    implementation of dipole approximation and allows us to consider the
    field homogeneous in the calculated volume.

-   **5. Quantum mechanical prerequisites:** The probability of
    tunneling for an individual molecule over a period (\'T \_ total\')
    is small (\'T \_ total \<\<1\'). This is a condition for the
    applicability of perturbation theory and the independence of
    dissociation acts laid down in the model.

**7.2 Invalid / Undefined Conditions**

The HTP (v1.0) model is **not applicable**, **not valid** or **gives
uncertain results** in the following cases:

-   **1. Availability of electrolytes:** Any substantial addition of
    acids, alkalis or salts to water. This puts the system into the mode
    of classical ion conduction (electrolysis), which is fundamentally
    different from the described volumetric quantum tunneling and is
    described by other (electrochemical) laws.

-   **2. Constant (DC) or low frequency electric field:** In this case,
    the process is reduced to classical electrolysis or dipole
    orientation, and the model of tunneling assisted by field photons
    loses its physical meaning. Pit \"tilt\" effect becomes static.

-   **3. Ultra-high field strengths:** With \'E ₀\' approaching the
    threshold of electric breakdown of water or causing strong nonlinear
    polarization, the dielectric response of the medium ceases to be
    linear, and the model based on simply adding the linear term \'qE ₀
    x cos (ω t)\' to the Morse potential becomes incorrect. Shock
    ionization and plasma formation may also occur.

-   **4. Ignoring intermolecular interactions under key conditions:** In
    environments where hydrogen bonds or dipole-dipole interactions
    dramatically change the potential surface for a proton (e.g. ice,
    clusters, highly structured water), using the Morse potential for an
    isolated O-H bond becomes too rough an approximation.

-   **5. High-temperature mode (T\>\> 350 K):** When thermal energy
    becomes comparable to the \'ħω\' or \'D ₑ \', thermal excitation of
    vibrational levels and thermal dissociation begin to dominate
    induced tunneling, which requires a radical revision of the model
    taking into account statistical ensembles**.**

-   **6. Neglecting field energy dissipation**: In a real system, part
    of the field energy is inevitably dissipated to heating (dielectric
    loss). The HTP (v1.0) model does not take into account these losses,
    therefore its predictions for the total power consumption (\'W \_
    min\') are an absolute theoretical minimum that is unattainable in
    practice. Any attempt to use the model to calculate the full
    efficiency of a real device without taking into account dissipation
    is incorrect.

**8. Control and Authorization Principle**

This section describes the abstract principle of controlling a process
initiated by the HTP protocol, without reference to a specific technical
implementation. Control and authorization in the context of HTP is
equivalent to control over the parameters that trigger the quantum
mechanical tunneling process.

**8.1. Control Principle:**

The hydrogen tunneling process is controlled \*\*exclusively\*\* through
the exact setting of the parameters of the external coherent
electromagnetic field applied to the volume of water. The key control
variables defined in Section 6 are:

-   **Field tension (\`E₀\`):** Amplitude value.

-   **Field frequency (\'ω\'):** Cyclic frequency.

-   **Duration of exposure (\'τ\'):** Time during which the field is
    applied to the system.

A change in any of these variables, or a combination thereof, results in
a change in the probability of tunneling (\'T \_ total\') and the
resulting macroscopic gas generation rate (\'R \_ vol\'). Thus, **the
control signal** for HTP is not power or current, but **an accurate**
**electromagnetic pattern** with given \'E ₀\' and \'ω\'.

**8.2. Authorization Principle:**

In the context of HTP, \"**authorization**\" (permission to start the
process) is a binary state of the system and is determined by the
presence or absence in the active volume of water of an electromagnetic
field of **strictly defined parameters** corresponding to the resonant
or quasi-resonant conditions of the model (described in Sections 5 and
7).

-   **OFF/Unauthorized condition:** There is no alternating
    electromagnetic field in the water volume with parameters falling
    within the range sufficient to induce a non-trivial tunneling
    probability (\'T \_ total ≈ 0\'). This is the default state.

-   **State \"ON \"/Authorized:** In the volume of water there is an
    alternating electromagnetic field, whose parameters (\'E ₀\', \'ω\')
    lie within the limits determined by the model as sufficient for the
    occurrence of a significant, calculated tunneling probability (\'T
    \_ total\> T \_ threshold\', where \'T \_ threshold\' is a
    negligible value).

**8.3. Key implications of the principle:**

**1. Material key independence:** In this abstraction, authorization is
not tied to a physical key, password or digital certificate. It is tied
to **the knowledge** and **technical ability to generate** a specific
physical signal**.**

**2. Spatial localization of authorization:** The process is authorized
only in the volume where the field of required parameters exists. This
allows, in theory, to carry out zonal control**.**

**3. Inability to \"quiet\" start:** Since the process requires the
creation of a macroscopic field of significant strength and high
frequency, its start is energy-consuming and, presumably, detectable by
electromagnetic radiation or the power consumption of the field
generator**.**

\* Note: This section describes the principle at the physical model
level. Any engineering implementation of the control and authorization
system will require additional layers (for example, digital generator
control, parameter verification systems) that are beyond the scope of
this protocol (see Non-Goals, 2.2).

**9. Security and Responsibility Disclaimer**

This section contains legally significant disclaimers and warnings
regarding the status, interpretation, and potential use of the
information set forth in \"Hydrogen Tunneling Protocol (HTP) v1.0.\"

**9.1. Scientific and legal status of the document**

**1. Theoretical model:** HTP v1.0 is **a purely theoretical physics and
mathematics model and conceptual protocol**. It describes a hypothetical
physical principle and its formalization as a system of equations.

**2. Lack of experimental confirmation:** At the date of fixation
(19.01.2026), the principles set out in the document **have not been
demonstrated or experimentally verified** under controlled and
reproducible conditions sufficient to recognize the effect as scientific
fact.

**3. Not a patent:** This document is not a patent application, patent
or technology license. Its publication in this format does not guarantee
the establishment of any legal priority other than authorship of the
text and model as such**.**

**9.2. Limitation of liability of Author and Distributors**

The author of the document (identified by the pseudonym and key print)
and any persons distributing this document, to **the maximum extent
permitted by applicable law, deny any liability**, including, but not
limited to:

-   For any direct or indirect loss, injury, damage to property or
    damage to health arising from attempts **to implement, build, test
    or operate devices based** on the ideas of this document.

-   For technical, financial or commercial consequences resulting from
    trust in the model\'s predictions or conclusions.

-   For the accuracy, completeness or usefulness of the provided
    mathematical calculations and physical interpretations for any
    purpose other than theoretical analysis.

-   For infringement of the rights of third parties, including patent
    rights, which may occur when using the ideas of the document.

**9.3. Предупреждения о безопасности**

Any potential experimental activity inspired by this document involves
**serious and potentially deadly risks**, including, but not limited to:

-   **Electrical risks**: Working with high-voltage and high-frequency
    generators required to create fields with parameters \'E ₀\' and
    \'ω\'poses a risk of electric shock, arcing and fire**.**

-   **Gas risks:** The products of water dissociation are a
    stoichiometric mixture of hydrogen and oxygen (explosive gas), which
    is extremely explosive. Improper handling, accumulation or spark can
    cause detonation**.**

-   **Radiation risks:** The generation of electromagnetic fields of
    high intensity and frequency can create non-ionizing radiation, the
    effects of which on biological tissues are not fully understood and
    can be harmful**.**

-   **Substance risks:** High-voltage experiments with water may result
    in the formation of chemically aggressive or toxic by-products
    (ozone, peroxides, reactive oxygen species).

**9.4. Рекомендация**

Any work aimed at verifying the principles set forth shall be carried
out **exclusively** by qualified specialists in the relevant fields
(quantum physics, electrical engineering, chemical safety) in
professionally equipped laboratories in compliance with all applicable
safety standards, standards and protocols. The reader is hereby warned
that he is **fully and solely responsible** for his activities.

**10. Version Statement**

This document represents the **first fixed version (v1.0)**.\
No modifications are permitted.\
Future changes must be introduced only as new versions.

**11. Declaration of Authorship**

I, NOMOS-H, hereby declare authorship and priority\
of the content described in this document as of the fixation date stated
above.

**Cryptographic Signature**

(signature)

**End of Document**
