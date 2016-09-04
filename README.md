#[Ethylene detection in fruit supply chains](http://www.ncbi.nlm.nih.gov/pubmed/24797138)
-----------------------------------------------------

The main focus of this paper is on measuring principles that are suitable to be applied along the cold chain of fresh fruits, i.e. inside moving trucks and containers, as well as during storage and post-harvest processing.
_______

##Photoacoustic Spectroscopy

| Squad Number | Diagnosis       | Expert Commentary   |
|--------------|---------------|--------------|
| 1            | [Photoacoustic spectroscopy of CO~2~ laser in the detection of gaseous molecules, Lima et al](http://iopscience.iop.org/article/10.1088/1742-6596/274/1/012086/meta) | In this work, a photoacoustic laser spectrometer with CO2 emission in the infrared range and a resonant photoacoustic cell was used. The resonance frequency of 2.4 kHz to photoacoustic cell, was estimated detection limit of the spectrometer ethylene, 16 ppbV was obtained|
|2 | [Detection of Greenhouse Gas Precursors from Diesel Engines Using Electrochemical and Photoacoustic Sensors, Mothe et al](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3230984/) | As their function has a linear behavior is possible to extend this linearity to ppmV levels. Therefore, PA spectroscopy revealed itself as a very precise and sensitive technique, since it was able to detect and monitor ethylene in their samples. 6 to 45 ppmV for ethylene concentration was obtained |
|3| [Mobile laser spectrometer with novel resonant multipass photoacoustic cell for trace-gas sensing, Nägele et al](http://link.springer.com/article/10.1007%2FPL00021151)|The development and application of a mobile laser-photoacoustic spectrometer for in situ multicomponent monitoring of trace gases in different environments is reported. Sub-ppbV (< 10^-9^ per volume) - concentrations can be measured with a novel resonant multipass photoacoustic cell. The cell is designed for flow mode operation in order to reduce adsorption effects. For ethene (C~2~H~4~) buffered in synthetic air a minimum detection limit of 70 ppt V (70×10^-12^ per volume) is achieved corresponding to a minimum measurable absorption coefficient α~min~ =2×10^-9^ / cm for a signal-to-noise ratio of 3. The multicomponent capability of the system is demonstrated with continuous sequential measurements of ethene, methanol, ethanol, CO~2~, and H~2~O of air from a fruit storage chamber.|


- **Method** : Laser beam polarized and chopped in specific frequency. Based on chemical structure, specific gas compound absorbs light light at specific wavelenght. Gas periodically heated according to copping frequency. Pressure changes caused by temperature changes measured by microphone. 

- **Result** : Photoacoustic amplitude rises with concentration of specific gas component. 

- **Disadvantage** : Inherent sensitivity towards ambient noise and vibration added to humidity, temperature. 

###2.Electrochemical Sensors
- **Chemoresistive Sensor** : Device that detects a gas through change of sensor's area/surface resisitivity caused by chemical bindings of molecules. Mixture of copper complex & single-walled carbon nanotubes placed between two gold electrodes. Resistivity changes as copper complex partly bind ethylene. 

	####Experiments 
	1. **Zevenberg(1990)** devised an system in which ethylene dissolves in a thin ionic liquid covering gold electrode. Voltage between this working and an counter electrode causes oxidization of ethylene inducing current measured for determining ethylene concentration. 

	2. **Agarwal** devised a system based on change of a capacitor. Oxygen ionized negatively on SnO~2~ surface increasing the depletion width as well as conducting region. 

- These sensors are optimized for detection however showing high cross-selectivity for other gases and poor sensitivity. Future work looks promising. 

- **Electro-catalytic Sensor** : Based on ethylene oxidation on a gold Nafion anode with weak sulfuric acid as electrolyte. Nanoparticles catalyze particularly oxidation of double carbon bonds. Current generated dependent on oxidation rate or ethylene concentration in air. 

	- Ethylene concentration measured *in-situ* in apple supply chain for exploring portability for this new technology. 

- **ETH1010**, very small and sensitive tool, showed good long term stability dueing field tests. Well suited for use in fruit supply chain. 

###3.Gas Chromatography

- Common measurement principle for evaluating concentration of one or more gases in air sample. Systems based on this principle are normally fairly large and expensivehence not suitable for mobile applications.
 
- **Components** : Injection unit, GC column, non-selective gas sensor. 

- **Method** : Carrier gas called **mobile phase** flows with fixed flow rate throughout, specific for every column. Two types of columns, **packed** and **capillary**, filled with stationary phase. Based on type, stationary phase can be thin film on wall(capillary column), or small particles filled into column(packed column). Sample gas mixture injected in system ahead of column. Inert gases like nitrogen/helium used to avoid interactions/pollution from carrier gas. 
- Different components having different pass-through/retention times, owing to seperation and arriving sensor at different times. Knowing them, every peak in output signal can be assigned to specific gas components. This intensity and arrival time indicates gas compound concentration. 

- **NOTE** : Besides column lenght and stationary phase, temeperature also a necessary issue. 

- **Developments** : A small, robust mobile system sufficiently sensitive for use insode container during transport. So far tested in labs. Future works include field test for banana transports. 
	- **Challenge** : Miniaturization of gas chromatographic column and pre-concentrator. 

###4.Non-dispersive(NDIR) Infrared Spectroscopy
- Provides a relatively simple, robust solution for IR-active gases measurement. Gas moleclues absorb IR radiation at specific wavelength. Radiation attenuation is measured and gas concentration can be clculated through Lambert-Beer law.

- **Benefit** : As ethylene is IR-active mainly around 10 micrometers, this absorption is capable for measuring small concentrations. However, for that wavelength range, either expenisve or have a comparably low intensity. Can be partly compensated by choosing optimal length of optical path. 

- **Developments** : 
	1.Filter spectrometer for ethylene monitoring in fruit applications. Aimed at small and low-cost optical system for ethylene detection in mid-infrared region at 10.6 micrometer wavelength. 
		**Challenge** : Ammonia, ethanol, acetaldehyde can interfere in ethylene IR measurements of ethylene. Ethanol and acetaldehyde caused from fruit stress, while ammonia from leaking of cooling system. As a result, absorption other than at 10.6 micrometer also need to be determined i.e. multi-spectral measurement. 

	2.For reaching required optical path length for detection of low ethylene concentrations, miniaturized White cell based on multiple reflections b/w three spherical concave mirrors, all having same curvature radius has been developed. Optical set-up provides high light transmission where radiation losses occur via absorption and scattering on reflecting surfaces. Dependent on mirror adjustments. 

	3.For multi-spectral measurements, thermopile detector array with integrated optical filters and microstructured Si Fresnel lenses has been developed. Consisting of a substrated chip with an array of 2 x 2 thermopile elements based on silicon technology attached to package base. 

- Above mentioned systems are quite small, relatively cost efficient, and can be designed for multiple gas detection. However at present, available systems not sensitive enough for quality prediction during transport. Can be further improved by combining system and a pre-concentrator (Sklorz). 

- These systems would be an impressive alternative for ripening facilities as achieved sensitivity is sufficient enough. Measuring CO~2~ at same time an important advantage during ripening. 

- New, improved SmartGAS NDIR system available soon in future. Also will be tested in banana container. Combination of this with a pre-concentrator shows great potential for overcoming sensitivity issue of such devices. Development of shelf life models using ethylene will be a potential option. 

##Comparison of ethylene measurement methods
- System with best sensitivity is **photoacoustic sensor**, with disadvantages of high price and high sensitivity to both noises and vibrations. 

- EDT300, a device for research, showed good performance in airplane. Use in a container might be more challenging. Investigations and field tests should be conducted. 

- Other three methods are on the verge of usage for fruit supply chain : **NDIR device, micro-GC system, electro-catalytic sensor ETH100**.  Showed good overall performances with reasonable price range. 

- At present. NDIR only suited for usage in ripening facilities. 
