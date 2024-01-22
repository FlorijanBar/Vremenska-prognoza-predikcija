# Vremenska-prognoza-predikcija
Using web scraping, 3 weather stations in the local area were selected: Čakovec, Varaždin and Koprivnica.
Their data is monitored for a period of 30 days, the month of April 2023, and saved in an excel file.
Based on the collected data using UI, an Mlp (Multilayer Percepton) neural network was created, which will enable a forecast for the same time period of the next calendar year for the specified monitoring period, the month of April 2024.
Worked in Jupyter Notebook which is part of Anaconda environment.

![html2](https://github.com/FlorijanBar/Vremenska-prognoza-predikcija/assets/101203001/fba42ce1-5f48-410c-98be-5d8162100627)
![Snimka zaslona 2024-01-22 144141](https://github.com/FlorijanBar/Vremenska-prognoza-predikcija/assets/101203001/23080582-6225-43a7-b4cd-7d17771bb109)




The application has one main interface that displays all the main features and 5 interfaces that are part of the main features, and buttons for each feature. By clicking on a certain feature, a new interface opens with that feature that we have selected. In order to always return to the main interface, it is necessary to minimize the current interface or close it.
Interfaces created using Tkinter and PyQt.
Included excel files, Zagreb-test is used and required to test for button: Treniranje-testiranje-pojedinačno
