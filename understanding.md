# Tutorial videos

# Past presentations

# DFN tool comparison
| Current DFN tools | DOTC DFN tool |
|---|---|
| Accuracy: Since they are calibrated against limited and incomplete (1D) data, conventional tools often generate geologically unrealistic fracture models, and at best there will be a high level of uncertainty in the results. | Accuracy: Since it simulates the physical processes of fracture nucleation and propagation, the model output will automatically honour the geology, geomechanical properties and structural evolution of the reservoir. The detail of the output will reflect the detail of the input data, but even using basic input data the outputs will be geologically consistent. |
| Ease of use: Since there is very little constraint on the input parameters, a “trial and error” approach with a lot of tweaking is required to get reasonable results. It can therefore be very time consuming to generate models with the current tools. | Ease of use: Since this is a deterministic model it is easy to set up and run. It can typically be run with data already available in most models (e.g. curvature of top horizon, default mechanical properties for the known lithology) – a first pass model can be generated in c.½ day. However it is easy to build more detailed models, e.g. taking into account lateral variability in mechanical property due to facies variations, using existing Petrel functionality. |
| Uncertainty and risk analysis: Since the input parameters are very poorly constrained, and often do not represent geological attributes at all, it is difficult to systematically generate multiple realistic realisations, or to rank them in likelihood. It is of course easy to generate many realisations by changing input parameters but it is difficult to analyse these systematically to quantify the range of possible outcomes. | Uncertainty and risk analysis: Since it simulates fracture growth, it automatically generates multiple realisations at different stages of fracture development, which will accurately reflect the distribution of fractures we would expect for a low to high intensity of deformation. Where there is uncertainty in e.g. mechanical properties, we can use the Petrel workflow functionality to generate multiple realisations very quickly. |
| Usefulness: Since the output from the models is limited, and often merely reflects the input data put into the models, they are only able to provide limited input into quantifying parameters of interest (e.g. connected fracture volume, permeability anisotropy etc.) | Usefulness: The model generates (or can easily be modified to generate) many parameters and properties (e.g. fracture size distributions, fracture connectivity) that are required for complex flow modelling calculations. These properties come out of the simulation, and cannot be calculated directly from the model inputs. |





# References
- Welch, M.J., Lüthje, M., Oldfield, S.J. 2022. DFN Generator v2.0: A new tool to model the growth of large-scale natural fracture networks usi, doi: https://doi.org/10.5194/gmd-2022-22
- Welch, M.J., Lüthje, M., Oldfield, S.J. 2000. Modelling the Evolution of Natural Fracture Networks. Springer Nature Switzerland AG., https://doi.org/10.1007/978-3-030-52414-2. 
- Welch, M.J., Lüthje, M., Glad, A.C. 2019. Influence of fracture nucleation and propagation rates on fracture geometry: Insights from geomechanical modelling. Petroleum Geoscience, 25, 470-489, https://doi.org/10.1144/petgeo2018-161

Back to [index](index).