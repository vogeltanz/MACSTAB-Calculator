# MACSTAB Calculator
MAC/STAB Calculator is an application for the calculation of the Mean Aerodynamic Chord (MAC) of an arbitrary wing planform and for the STABility estimation (in conceptual design) of a wing/tail aircraft configuration.
<BR>
<BR>
The application helps to reduce the financial cost of the conceptual design and analysis of small subsonic aircraft. MAC/STAB Calculator is an application for the calculation of the Mean Aerodynamic Chord (MAC) of an arbitrary wing planform and for the STABility estimation (in conceptual design) of a wing/tail aircraft configuration. The knowledge of the mean aerodynamic chord is necessary condition when stability estimation or CFD analysis (independent of the dimension; 2D or 3D) should be performed. The stability calculation is based on the tail efficiency, the position of Center of Gravity and Neutral Point which are set by user (recommendation is included), and also on MACs, areas, and aspect ratios of wing and tail. The appropriate stability is determined by the calculated distance between leading edges and also aerodynamic centers of wing and tail; however, there is always compromise between good maneuverability and high stability. One specialty of this application is option to analyze an image file and convert a wing planform or an airfoil to geometry parameters which then may be processed. This function can be useful in reverse engineering of an arbitrary wing. The whole geometry of wing and tail (including airfoils) may be exported to VSP2 format which can be opened using OpenVSP 2.3.0, or imported to OpenVSP >=3.5.0. Then, the exported wing and tail may be used in conceptual design of an aircraft, or may be analyzed, converted, modified, and printed.
<BR>
<BR>
Input and Output project format: MACSTAB
<BR>
Input format with wing planform geometry: NML Output format for wing planform geometry: NML, VSP2
<BR>
Input image format for geometry analysis of wing planform or airfoil: PNG (1 bit – 2 colors)
<BR>
Input formats with airfoil geometry (applied during VSP2 export): Selig (dat), Lednicer (dat), NASA/OpenVSP (af)
<BR>
Output format for airfoil geometry (applied during airfoil image analysis and conversion): Selig (dat)
<BR>
Output format for calculated parameters: NMLOUT
<BR>
Output format for saving of displayed image in MAC/STAB application: PNG (24 bit)
<BR>
<BR>
<BR>
Inspired by:
<BR>
    GETMAC application: http://www.pdas.com/getmac.html
    Aircraft Center of Gravity Calculator: http://adamone.rchomepage.com/cg_calc.htm
<BR>
This application uses or utilizes the following libraries and console applications:
<BR>
    wxWidgets 3.0.2 library: https://www.wxwidgets.org/
<BR>
<BR>
<BR>
<b>If you use this software please cite the following references in your work (books, articles, reports, etc.):</b>
<BR>
URL:<BR>
https://github.com/vogeltanz/MACSTAB-Calculator
<BR>
paper:<BR>
Vogeltanz, Tomas. 2016. Application for Calculation of Mean Aerodynamic Chord of Arbitrary Wing Planform. AIP Conference Proceedings, vol. 1738 : 120018. ISSN: 0094-243X. DOI: 10.1063/1.4951901. Available at: http://aip.scitation.org/doi/abs/10.1063/1.4951901
