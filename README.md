# Dymola Specific Implementation
This is to archive a list of Dymola-specific Modelica libraries. 

Due to Modelica version update from `3.2.3` to `4.0.0`, current up-to-date Modelica compilers such as Dymola, OpenModelica all set `ModelicaStandardLibrary (MSL)` to `4.0.0` as default, together with `ModelicaServices`. For example, Dymola 2022 now open MSL 4.0.0 and ModelicaServices 4.0.0 for default. 

However, within the up-to-date Modelica tools, there are unavoidable needs that we want to run our own Modelica codes that are built on older versions of MSL and ModelicaServices, such as Version `3.2.3`.
To run MSL 3.2.3 successfully on Dymola 2022 or later, we need a Dymola-specific implementation of ModelicaService 3.2.3. 





