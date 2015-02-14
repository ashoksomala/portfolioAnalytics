## Portfolio Analytics Library (PAL)

This repository aims to develop a simple python library that provides semi-analytical functions useful for testing the accuracy of credit portfolio simulation models

The basic formulas are reasonably simple and well known: They underpin the calculation of RWA (risk weighted assets), and in turn required capital, thus ensuring stability for the entire banking systems worldwide

### Current Functions

* vasicek_base
* vasicek_base_el
* vasicek_base_ul
* vasicek_lim
* vasicek_lim_el
* vasicek_lim_ul
* vasicek_lim_q

The Vasicek Base family produces finite pool loss probabilities and measures (EL, UL)
The Vasicek Lim family produces asymptotic pool loss probabities and measures (EL, UL, Quantile)

### Risk Forum 
Use the [forum](https://www.openrisk.eu/commons/forum/viewforum.php?f=20) for discussions

### Risk Manual
Use the [manual](https://www.openrisk.eu/commons/risk_manual/Main_Page) for documentation of use cases

### Contributions

If you want to contribute to PAL please sign first the <a href="https://www.clahub.com/agreements/open-risk/OpenCPM">Contributor License Agreement</a>

Check the TODO list for ideas of where to take this library next
