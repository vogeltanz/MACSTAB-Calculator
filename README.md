# MACSTAB Calculator
MAC/STAB Calculator is an application for the calculation of the Mean Aerodynamic Chord (MAC) of an arbitrary wing planform and for the STABility estimation (in conceptual design) of a wing/tail aircraft configuration.


The application helps to reduce the financial cost of the conceptual design and analysis of small subsonic aircraft. MAC/STAB Calculator is an application for the calculation of the Mean Aerodynamic Chord (MAC) of an arbitrary wing planform and for the STABility estimation (in conceptual design) of a wing/tail aircraft configuration. The knowledge of the mean aerodynamic chord is necessary condition when stability estimation or CFD analysis (independent of the dimension; 2D or 3D) should be performed. The stability calculation is based on the tail efficiency, the position of Center of Gravity and Neutral Point which are set by user (recommendation is included), and also on MACs, areas, and aspect ratios of wing and tail. The appropriate stability is determined by the calculated distance between leading edges and also aerodynamic centers of wing and tail; however, there is always compromise between good maneuverability and high stability. One specialty of this application is option to analyze an image file and convert a wing planform or an airfoil to geometry parameters which then may be processed. This function can be useful in reverse engineering of an arbitrary wing. The whole geometry of wing and tail (including airfoils) may be exported to VSP2 format which can be opened using OpenVSP 2.3.0, or imported to OpenVSP >=3.5.0. Then, the exported wing and tail may be used in conceptual design of an aircraft, or may be analyzed, converted, modified, and printed.


Input and Output project format: MACSTAB
Input format with wing planform geometry: NML Output format for wing planform geometry: NML, VSP2
Input image format for geometry analysis of wing planform or airfoil: PNG (1 bit – 2 colors)
Input formats with airfoil geometry (applied during VSP2 export): Selig (dat), Lednicer (dat), NASA/OpenVSP (af)
Output format for airfoil geometry (applied during airfoil image analysis and conversion): Selig (dat)
Output format for calculated parameters: NMLOUT
Output format for saving of displayed image in MAC/STAB application: PNG (24 bit)
