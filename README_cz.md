# MACSTAB Calculator
<BR>
Software: MAC/STAB Calculator
Aplikace přispívá ke snížení finančních nákladů na koncepční návrh a analýzu malého podzvukového letounu. MAC/STAB Calculator je aplikace pro výpočet střední aerodynamické tětivy (MAC) libovolného křídla a pro odhad STABility (v koncepčním návrhu) konfigurace letounu křídlo/ocas. Znalost střední aerodynamické tětivy je nezbytnou podmínkou pro odhad stability nebo provedení CFD analýzy (nezávisle na dimenzi; 2D nebo 3D). Výpočet stability se provádí z parametrů zadaných uživatelem, jako je efektivita ocasní plochy, pozice těžiště a neutrálního bodu (doporučené hodnoty jsou uvedeny v aplikaci), a také ještě z MACů, ploch, a poměrů stran křídla a ocasu. Vhodnou stabilitu určuje vypočítaná vzdálenost mezi náběžnými hranami a také ještě aerodynamickými středy křídla a ocasu; nicméně, se zde vždycky vyskytuje nutnost kompromisu mezi dobrou manévrovatelností a vysokou stabilitou. Jedna ze specialit této aplikace je možnost analyzovat obrázek a převést tvar nebo profil křídla na geometrické parametry, které poté mohou být dále zpracovány. Tato funkce může být užitečná v reverzním inženýrství aplikovaném na libovolné křídlo. Celá geometrie křídla a ocasu (včetně profilů) může být exportována do formátu VSP2, který lze otevřít v aplikaci OpenVSP 2.3.0, nebo importovat do OpenVSP >=3.5.0. Poté může být exportované křídlo a ocas využito v koncepčním návrhu letounu, nebo mohou být dále analyzovány (v CFD softwaru), převedeny do jiných formátů, modifikovány a popř. i vytisknuty na 3D tiskárně.
<BR>
<BR>
Vstupní a výstupní formát projektu: MACSTAB
<BR>
Vstupní formát s geometrií tvaru křídla: NML Výstupní formáty pro geometrii tvaru křídla: NML, VSP2
<BR>
Vstupní formát obrázku pro analýzu geometrie nebo profilu křídla: PNG (1 bit – 2 barvy)
<BR>
Vstupní formáty s geometrií profilu křídla (aplikováno při exportu VSP2): Selig (dat), Lednicer (dat), NASA/OpenVSP (af)
<BR>
Výstupní formát pro geometrii profilu křídla (aplikováno při analýze a převodu obrázku): Selig (dat)
<BR>
Výstupní formát pro vypočítané parametry: NMLOUT
<BR>
Výstupní formát pro uložení zobrazeného obrázku v aplikaci MAC/STAB: PNG (24 bit)
<BR>
<BR>
<BR>
Inspirováno:
<BR>
    GETMAC application: http://www.pdas.com/getmac.html<BR>
    Aircraft Center of Gravity Calculator: http://adamone.rchomepage.com/cg_calc.htm
<BR>
<BR>
Tato aplikace použivá následující knihovny a konzolové aplikace:
<BR>
    wxWidgets 3.0.2 library: https://www.wxwidgets.org/
<BR>
<BR>
<BR>
<b>Pokud používáte tento software, prosím, citujte následující reference ve vaší práci (knihy, články, reporty, atd.):</b>
<BR>
URL:<BR>
https://github.com/vogeltanz/MACSTAB-Calculator
<BR>
článek:<BR>
Vogeltanz, Tomas. 2016. Application for Calculation of Mean Aerodynamic Chord of Arbitrary Wing Planform. AIP Conference Proceedings, vol. 1738 : 120018. ISSN: 0094-243X. DOI: 10.1063/1.4951901. Available at: http://aip.scitation.org/doi/abs/10.1063/1.4951901
