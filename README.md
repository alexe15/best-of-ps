<!-- markdownlint-disable -->

<h1 align="center">
    Popular Open Source Libraries for Power System Analysis
    <br>
</h1>

<p align="center">
    <strong>🏆  A ranked list of popular projects for Power System Analysis. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-78-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/jinningwang/best-of-ps/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/jinningwang/best-of-ps?color=green&label=updated"></a>
    <a href="https://github.com/jinningwang/best-of-ps/graphs/traffic" title="Visits Badge"><img src="https://badges.strrl.dev/visits/jinningwang/best-of-ps"></a>
</p>

This curated list contains 78 open-source projects with a total of 25K stars grouped into 13 categories. All projects are ranked by a project-popular score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/jinningwang/best-of-ps/issues/new/choose), submit a [pull request](https://github.com/jinningwang/best-of-ps/pulls), or directly edit the [projects.yaml](https://github.com/jinningwang/best-of-ps/edit/main/projects.yaml). Contributions are very welcome!

## Contents

- [Phasor](#phasor) _10 projects_
- [EMT](#emt) _2 projects_
- [Steady State](#steady-state) _22 projects_
- [Interface](#interface) _7 projects_
- [Optimizer](#optimizer) _11 projects_
- [Optimization Modeling Language](#optimization-modeling-language) _6 projects_
- [Machine/Reinforcement Learning for Power Grid](#machinereinforcement-learning-for-power-grid) _3 projects_
- [Co-Simulation Environment](#co-simulation-environment) _2 projects_
- [Gas](#gas) _2 projects_
- [Visualization](#visualization) _3 projects_
- [Messaging Environment](#messaging-environment) _2 projects_
- [Power System Data](#power-system-data) _7 projects_
- [Power Electronics](#power-electronics) _1 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(12 months no activity)_
- 💀&nbsp; Dead project _(1200 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; Power system analysis projects written in Python
- <img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13">&nbsp; Power system analysis projects written in Julia
- <img src="https://raw.githubusercontent.com/ml-tooling/best-of-ml-python/main/config/images/jupyter.ico" style="display:inline;" width="13" height="13">&nbsp; Jupyter related project

<br>

## Phasor

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Power System Phasor Simulation._

<details><summary><b><a href="https://ltb.curent.org/">LTB ANDES</a></b> (🥇23 ·  ⭐ 190 · 📈) - Transient Stability Simulator; CURENT LTB. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ml-tooling/best-of-ml-python/main/config/images/jupyter.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/CURENT/andes) (👨‍💻 20 · 🔀 92 · 📦 15 · 📋 55 - 12% open · ⏱️ 04.02.2024):

	```
	git clone https://github.com/CURENT/andes
	```
- [PyPi](https://pypi.org/project/andes) (📥 1.5K / month · 📦 2 · ⏱️ 04.02.2024):
	```
	pip install andes
	```
- [Conda](https://anaconda.org/conda-forge/andes) (📥 420K · ⏱️ 05.02.2024):
	```
	conda install -c conda-forge andes
	```
- [Docker Hub](https://hub.docker.com/r/cuihantao/andes) (📥 120 · ⏱️ 10.12.2020):
	```
	docker pull cuihantao/andes
	```
</details>
<details><summary><b><a href="http://dynawo.org">Dynaωo</a></b> (🥇21 ·  ⭐ 61 · ➕) - C++/Modelica simulation tools for power systems. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/dynawo/dynawo) (👨‍💻 48 · 🔀 20 · 📥 14K · 📋 1.3K - 7% open · ⏱️ 25.01.2024):

	```
	git clone https://github.com/dynawo/dynawo
	```
</details>
<details><summary><b><a href="https://www.nrel.gov/analysis/sienna.html">PowerSimulationsDynamics.jl</a></b> (🥈16 ·  ⭐ 150) - Dynamic Power System simulations; NREL Sienna. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NREL-Sienna/PowerSimulationsDynamics.jl) (👨‍💻 13 · 🔀 31 · 📋 130 - 32% open · ⏱️ 31.01.2024):

	```
	git clone https://github.com/NREL-Sienna/PowerSimulationsDynamics.jl
	```
</details>
<details><summary><b><a href="https://github.com/OpenIPSL/OpenIPSL">OpenIPSL</a></b> (🥈16 ·  ⭐ 65) - A library of power system models written with Modelica. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/OpenIPSL/OpenIPSL) (👨‍💻 32 · 🔀 47 · 📥 480 · 📋 120 - 13% open · ⏱️ 23.11.2023):

	```
	git clone https://github.com/OpenIPSL/OpenIPSL
	```
</details>
<details><summary><b><a href="https://github.com/modelica-3rdparty/PowerSystems">PowerSystems</a></b> (🥉13 ·  ⭐ 57) - Modelica 3rd party library for electrical power systems. <code><a href="https://modelica.org/licenses/ModelicaLicense2/">❗️Custom</a></code></summary>

- [GitHub](https://github.com/modelica-3rdparty/PowerSystems) (👨‍💻 10 · 🔀 35 · 📋 37 - 27% open · ⏱️ 20.03.2023):

	```
	git clone https://github.com/modelica-3rdparty/PowerSystems
	```
</details>
<details><summary><b><a href="https://www.epri.com/OpenDER">OpenDER</a></b> (🥉12 ·  ⭐ 45 · ➕) - Inverter-based DER simulation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/epri-dev/OpenDER) (👨‍💻 2 · 🔀 16 · 📦 1 · ⏱️ 25.01.2024):

	```
	git clone https://github.com/epri-dev/OpenDER
	```
- [PyPi](https://pypi.org/project/opender) (📥 160 / month · ⏱️ 05.12.2023):
	```
	pip install opender
	```
</details>
<details><summary><b><a href="https://github.com/changgang/steps">STEPS</a></b> (🥉12 ·  ⭐ 40) - Balanced large-scale AC-DC hybrid power system analysis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/changgang/steps) (👨‍💻 4 · 🔀 15 · 📥 17 · 📦 5 · 📋 2 - 50% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/changgang/steps
	```
</details>
<details><summary><b><a href="https://github.com/ANL-CEEESA/powersas.m">PowerSAS.m</a></b> (🥉8 ·  ⭐ 13) - Power grid analysis framework based on semi-analytical solutions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ANL-CEEESA/powersas.m) (👨‍💻 4 · 🔀 4 · ⏱️ 05.01.2024):

	```
	git clone https://github.com/ANL-CEEESA/powersas.m
	```
</details>
<details><summary><b><a href="https://github.com/OpenHybridSim/OpenHybridSim-code">OpenHybridSim</a></b> (🥉6 ·  ⭐ 7 · 💤) - Power system EMT-TS hybrid simulation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/OpenHybridSim/OpenHybridSim-code) (🔀 5 · ⏱️ 05.05.2020):

	```
	git clone https://github.com/OpenHybridSim/OpenHybridSim-code
	```
</details>
<details><summary><b><a href="https://www.epri.com/pages/sa/opendss">OpenDSS</a></b> (🥉2 · ➕) - Distribution system simulator. <code><a href="https://tldrlegal.com/search?q=BSD">❗️BSD</a></code></summary>

- _No project information available._</details>
<br>

## EMT

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Power System EMT Simulation._

<details><summary><b><a href="https://dpsim.fein-aachen.org/">DPsim</a></b> (🥇19 ·  ⭐ 60 · ➕) - Simulation for both EMT and phasor. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sogno-platform/dpsim) (👨‍💻 31 · 🔀 45 · 📦 6 · 📋 130 - 64% open · ⏱️ 25.01.2024):

	```
	git clone https://github.com/sogno-platform/dpsim
	```
- [PyPi](https://pypi.org/project/dpsim) (📥 80 / month · ⏱️ 10.12.2022):
	```
	pip install dpsim
	```
</details>
<details><summary><b><a href="https://github.com/NREL/ParaEMT_public">ParaEMT</a></b> (🥉9 ·  ⭐ 26) - Parallel EMT simulation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NREL/ParaEMT_public) (👨‍💻 3 · 🔀 8 · ⏱️ 15.12.2023):

	```
	git clone https://github.com/NREL/ParaEMT_public
	```
</details>
<br>

## Steady State

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Power System Steady State Simulation_

<details><summary><b><a href="https://www.pandapower.org/">pandapower</a></b> (🥇31 ·  ⭐ 720) - Convenient Power System Modelling and Analysis. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/e2nIEE/pandapower) (👨‍💻 130 · 🔀 430 · 📦 310 · 📋 900 - 19% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/e2nIEE/pandapower
	```
- [PyPi](https://pypi.org/project/pandapower) (📥 14K / month · 📦 28 · ⏱️ 02.01.2023):
	```
	pip install pandapower
	```
- [Conda](https://anaconda.org/conda-forge/pandapower) (📥 13K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pandapower
	```
- [Docker Hub](https://hub.docker.com/r/pauldepraz/pandapowerapi) (📥 89 · ⏱️ 09.02.2021):
	```
	docker pull pauldepraz/pandapowerapi
	```
</details>
<details><summary><b><a href="https://pypsa.org">PyPSA</a></b> (🥇29 ·  ⭐ 1K) - Simulating and optimising power and energy systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyPSA/PyPSA) (👨‍💻 69 · 🔀 400 · 📦 160 · 📋 320 - 28% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/PyPSA/PyPSA
	```
- [PyPi](https://pypi.org/project/pypsa) (📥 6.3K / month · 📦 24 · ⏱️ 25.01.2024):
	```
	pip install pypsa
	```
- [Conda](https://anaconda.org/conda-forge/pypsa) (📥 61K · ⏱️ 25.01.2024):
	```
	conda install -c conda-forge pypsa
	```
</details>
<details><summary><b><a href="https://www.advancedgridinsights.com/gridcal">GridCal</a></b> (🥇24 ·  ⭐ 370) - Cross-platform power systems software. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/SanPen/GridCal) (👨‍💻 38 · 🔀 78 · 📥 33 · 📦 7 · 📋 150 - 46% open · ⏱️ 29.01.2024):

	```
	git clone https://github.com/SanPen/GridCal
	```
- [PyPi](https://pypi.org/project/GridCal) (📥 800 / month · ⏱️ 04.01.2024):
	```
	pip install GridCal
	```
</details>
<details><summary><b><a href="https://github.com/PowerGridModel/power-grid-model">Power Grid Model</a></b> (🥇24 ·  ⭐ 110) - Steady-state distribution power system analysis. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PowerGridModel/power-grid-model) (👨‍💻 18 · 🔀 21 · 📥 560 · 📦 4 · 📋 110 - 39% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/PowerGridModel/power-grid-model
	```
- [PyPi](https://pypi.org/project/power-grid-model) (📥 20K / month · 📦 1 · ⏱️ 08.02.2024):
	```
	pip install power-grid-model
	```
- [Conda](https://anaconda.org/conda-forge/power-grid-model) (📥 110K · ⏱️ 05.02.2024):
	```
	conda install -c conda-forge power-grid-model
	```
</details>
<details><summary><b><a href="https://www.powsybl.org">PowSyBl Core</a></b> (🥈23 ·  ⭐ 110 · ➕) - Framework to build power system software. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/powsybl/powsybl-core) (👨‍💻 99 · 🔀 37 · 📥 95 · 📦 74 · 📋 530 - 44% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/powsybl/powsybl-core
	```
</details>
<details><summary><b><a href="https://matpower.org/">MATPOWER</a></b> (🥈22 ·  ⭐ 370 · ➕) - Steady state power flow simulation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/MATPOWER/matpower) (👨‍💻 15 · 🔀 150 · 📥 440K · 📋 180 - 19% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/MATPOWER/matpower
	```
- [Docker Hub](https://hub.docker.com/r/matpower/matpower) (📥 1.1K · ⏱️ 06.02.2024):
	```
	docker pull matpower/matpower
	```
</details>
<details><summary><b><a href="https://pypsa.org">PyPSA-Eur</a></b> (🥈22 ·  ⭐ 260) - Optimisation Model of the European Transmission System. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyPSA/pypsa-eur) (👨‍💻 61 · 🔀 170 · 📋 380 - 36% open · ⏱️ 07.02.2024):

	```
	git clone https://github.com/PyPSA/pypsa-eur
	```
- [Docker Hub](https://hub.docker.com/r/nimfetrisa/pypsa-eur) (📥 37 · ⏱️ 11.04.2022):
	```
	docker pull nimfetrisa/pypsa-eur
	```
</details>
<details><summary><b><a href="https://www.nrel.gov/analysis/sienna.html">PowerSimulations.jl</a></b> (🥈22 ·  ⭐ 250) - Power Systems optimization simulation and modeling;.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NREL-Sienna/PowerSimulations.jl) (👨‍💻 34 · 🔀 48 · 📋 290 - 11% open · ⏱️ 23.01.2024):

	```
	git clone https://github.com/NREL-Sienna/PowerSimulations.jl
	```
</details>
<details><summary><b><a href="https://github.com/lanl-ansi/PowerModels.jl">PowerModels.jl</a></b> (🥈19 ·  ⭐ 360) - Power Network Optimization. <code><a href="https://tldrlegal.com/search?q=BSD">❗️BSD</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lanl-ansi/PowerModels.jl) (👨‍💻 29 · 🔀 140 · 📋 470 - 18% open · ⏱️ 19.01.2024):

	```
	git clone https://github.com/lanl-ansi/PowerModels.jl
	```
</details>
<details><summary><b><a href="rwl.github.io/PYPOWER/api/">PYPOWER</a></b> (🥈19 ·  ⭐ 300) - Port of MATPOWER to Python. <code><a href="https://tldrlegal.com/search?q=BSD">❗️BSD</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwl/PYPOWER) (👨‍💻 20 · 🔀 110 · 📦 96 · 📋 41 - 73% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/rwl/PYPOWER
	```
- [PyPi](https://pypi.org/project/PYPOWER) (📥 2.8K / month · 📦 22 · ⏱️ 29.03.2023):
	```
	pip install PYPOWER
	```
- [Conda](https://anaconda.org/invenia/pypower) (📥 3.1K · ⏱️ 16.06.2023):
	```
	conda install -c invenia pypower
	```
- [Docker Hub](https://hub.docker.com/r/hwanghust/pypower) (📥 17 · ⏱️ 19.05.2019):
	```
	docker pull hwanghust/pypower
	```
</details>
<details><summary><b><a href="https://l2rpn.chalearn.org/">LightSim2Grid</a></b> (🥈19 ·  ⭐ 43) - A fast backend for the Grid2Op. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BDonnot/lightsim2grid) (👨‍💻 5 · 🔀 9 · 📥 100 · 📦 28 · 📋 42 - 38% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/BDonnot/lightsim2grid
	```
- [PyPi](https://pypi.org/project/LightSim2Grid) (📥 3.7K / month · 📦 7 · ⏱️ 27.10.2023):
	```
	pip install LightSim2Grid
	```
- [Docker Hub](https://hub.docker.com/r/bdonnot/lightsim2grid) (📥 190 · ⏱️ 01.02.2022):
	```
	docker pull bdonnot/lightsim2grid
	```
</details>
<details><summary><b><a href="https://www.gridpath.io/">GridPath</a></b> (🥉18 ·  ⭐ 82) - Power system planning and operations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blue-marble/gridpath) (👨‍💻 10 · 🔀 34 · 📥 740 · 📦 2 · 📋 320 - 21% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/blue-marble/gridpath
	```
</details>
<details><summary><b><a href="https://www.powsybl.org">PyPowSyBl</a></b> (🥉18 ·  ⭐ 40 · ➕) - A PowSyBl and Python integration. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/powsybl/pypowsybl) (👨‍💻 20 · 🔀 7 · 📋 170 - 26% open · ⏱️ 30.01.2024):

	```
	git clone https://github.com/powsybl/pypowsybl
	```
- [PyPi](https://pypi.org/project/pypowsybl) (📥 1.6K / month · 📦 2 · ⏱️ 30.01.2024):
	```
	pip install pypowsybl
	```
</details>
<details><summary><b><a href="https://groups.io/g/powergenome">PowerGenome</a></b> (🥉17 ·  ⭐ 180 · ➕) - Create inputs for power systems models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PowerGenome/PowerGenome) (👨‍💻 14 · 🔀 56 · 📋 130 - 48% open · ⏱️ 22.11.2023):

	```
	git clone https://github.com/PowerGenome/PowerGenome
	```
- [PyPi](https://pypi.org/project/PowerGenome) (📥 39 / month · ⏱️ 10.06.2023):
	```
	pip install PowerGenome
	```
- [Conda](https://anaconda.org/conda-forge/powergenome) (📥 66 · ⏱️ 02.01.2024):
	```
	conda install -c conda-forge powergenome
	```
</details>
<details><summary><b><a href="https://energy.mit.edu/genx/">GenX</a></b> (🥉16 ·  ⭐ 220) - Configurable capacity expansion model. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GenXProject/GenX) (👨‍💻 24 · 🔀 89 · 📋 220 - 22% open · ⏱️ 03.02.2024):

	```
	git clone https://github.com/GenXProject/GenX
	```
</details>
<details><summary><b><a href="https://github.com/grid-parity-exchange/Egret">EGRET</a></b> (🥉15 ·  ⭐ 120) - Tools for Power Systems Optimization Modeling. <code><a href="https://tldrlegal.com/search?q=BSD">❗️BSD</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/grid-parity-exchange/Egret) (👨‍💻 38 · 🔀 46 · 📦 6 · 📋 82 - 53% open · ⏱️ 14.11.2023):

	```
	git clone https://github.com/grid-parity-exchange/Egret
	```
</details>
<details><summary><b><a href="https://ltb.curent.org/">LTB AMS</a></b> (🥉15 ·  ⭐ 3) - Dispatch Modeling and Simulation; CURENT LTB. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ml-tooling/best-of-ml-python/main/config/images/jupyter.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/CURENT/ams) (👨‍💻 3 · 🔀 3 · 📋 2 - 50% open · ⏱️ 31.01.2024):

	```
	git clone https://github.com/CURENT/ams
	```
- [PyPi](https://pypi.org/project/ltbams) (📥 220 / month · ⏱️ 31.01.2024):
	```
	pip install ltbams
	```
</details>
<details><summary><b><a href="https://pypsa.org">PyPSA-Eur-Sec</a></b> (🥉13 ·  ⭐ 82) - Sector-Coupled Optimisation Model of the European Energy System. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyPSA/pypsa-eur-sec) (👨‍💻 22 · 🔀 48 · ⏱️ 18.03.2023):

	```
	git clone https://github.com/PyPSA/pypsa-eur-sec
	```
</details>
<details><summary><b><a href="https://matpower.org/">MOST</a></b> (🥉12 ·  ⭐ 30 · ➕) - MATPOWER Optimal Scheduling Tool. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/MATPOWER/most) (🔀 10 · 📋 34 - 32% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/MATPOWER/most
	```
</details>
<details><summary><b><a href="https://www.nrel.gov/analysis/reeds/">ReEDS-2.0</a></b> (🥉11 ·  ⭐ 100 · ➕) - Capacity planning and dispatch model. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NREL/ReEDS-2.0) (👨‍💻 13 · 🔀 8 · 📋 18 - 22% open · ⏱️ 11.01.2024):

	```
	git clone https://github.com/NREL/ReEDS-2.0
	```
</details>
<details><summary><b><a href="https://matpower.org/">matpower-pip</a></b> (🥉11 ·  ⭐ 15 · ➕) - Easy Python Access to MATPOWER. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yasirroni/matpower-pip) (📦 4 · ⏱️ 18.12.2023):

	```
	git clone https://github.com/yasirroni/matpower-pip
	```
- [PyPi](https://pypi.org/project/matpower) (📥 190 / month · 📦 1 · ⏱️ 25.03.2023):
	```
	pip install matpower
	```
</details>
<details><summary><b><a href="https://github.com/yasirroni/mypower">mypower</a></b> (🥉6 ·  ⭐ 6 · 💤) - Supplementary function of MATPOWER in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yasirroni/mypower) (🔀 1 · ⏱️ 26.11.2022):

	```
	git clone https://github.com/yasirroni/mypower
	```
</details>
<br>

## Interface

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://dss-extensions.org/">OpenDSSDirect.py</a></b> (🥇19 ·  ⭐ 76) - A direct library interface to OpenDSS. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dss-extensions/OpenDSSDirect.py) (👨‍💻 3 · 🔀 20 · 📦 44 · 📋 100 - 18% open · ⏱️ 02.07.2023):

	```
	git clone https://github.com/dss-extensions/OpenDSSDirect.py
	```
- [PyPi](https://pypi.org/project/OpenDSSDirect.py) (📥 3.6K / month · 📦 14 · ⏱️ 11.03.2021):
	```
	pip install OpenDSSDirect.py
	```
</details>
<details><summary><b><a href="https://github.com/mzy2240/ESA">Easy SimAuto</a></b> (🥈16 ·  ⭐ 40) - Python interface to PowerWorld. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mzy2240/ESA) (👨‍💻 11 · 🔀 9 · 📦 4 · 📋 99 - 16% open · ⏱️ 05.06.2023):

	```
	git clone https://github.com/mzy2240/ESA
	```
- [PyPi](https://pypi.org/project/esa) (📥 1.7K / month · 📦 1 · ⏱️ 21.05.2022):
	```
	pip install esa
	```
</details>
<details><summary><b><a href="https://www.nrel.gov/grid/pydss.html">PyDSS</a></b> (🥈16 ·  ⭐ 31) - A Python wrapper for OpenDSS. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NREL/PyDSS) (👨‍💻 24 · 🔀 18 · 📦 2 · 📋 32 - 50% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/NREL/PyDSS
	```
- [PyPi](https://pypi.org/project/pydss) (📥 21 / month · ⏱️ 17.08.2011):
	```
	pip install pydss
	```
</details>
<details><summary><b><a href="https://github.com/PauloRadatz/py_dss_interface">py-dss-interface</a></b> (🥈16 ·  ⭐ 22) - A package for access to direct dll version of OpenDSS. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PauloRadatz/py_dss_interface) (👨‍💻 6 · 🔀 8 · 📦 24 · 📋 54 - 61% open · ⏱️ 03.02.2024):

	```
	git clone https://github.com/PauloRadatz/py_dss_interface
	```
- [PyPi](https://pypi.org/project/py-dss-interface) (📥 430 / month · 📦 4 · ⏱️ 07.12.2021):
	```
	pip install py-dss-interface
	```
</details>
<details><summary><b><a href="https://github.com/felipemarkson/dssdata">DSSData</a></b> (🥉11 ·  ⭐ 14) - A micro-framework for simulation and data analysis of distribution.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/felipemarkson/dssdata) (👨‍💻 2 · 🔀 3 · 📥 30 · 📋 36 - 13% open · ⏱️ 10.04.2023):

	```
	git clone https://github.com/felipemarkson/dssdata
	```
- [PyPi](https://pypi.org/project/dssdata) (📥 51 / month · ⏱️ 24.01.2023):
	```
	pip install dssdata
	```
</details>
<details><summary><b><a href="https://www.epri.com/OpenDER">OpenDER interface</a></b> (🥉5 · 🐣) - Interface for OpenDER. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ml-tooling/best-of-ml-python/main/config/images/jupyter.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/epri-dev/OpenDER_interface) (👨‍💻 2 · ⏱️ 12.12.2023):

	```
	git clone https://github.com/epri-dev/OpenDER_interface
	```
</details>
<details><summary><b><a href="https://github.com/mzy2240/EasySimauto.jl">EasySimauto.jl</a></b> (🥉3 ·  ⭐ 4) - Julia interface for EasySimAuto and PowerWorld. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mzy2240/EasySimauto.jl) (👨‍💻 2 · ⏱️ 31.07.2023):

	```
	git clone https://github.com/mzy2240/EasySimauto.jl
	```
</details>
<br>

## Optimizer

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://osqp.org">OSQP</a></b> (🥇31 ·  ⭐ 1.5K · 📈) - Operator Splitting QP Solver. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/osqp/osqp) (👨‍💻 31 · 🔀 320 · 📥 56K · 📋 330 - 25% open · ⏱️ 22.09.2023):

	```
	git clone https://github.com/osqp/osqp
	```
- [PyPi](https://pypi.org/project/osqp) (📥 1.4M / month · 📦 61 · ⏱️ 05.02.2024):
	```
	pip install osqp
	```
- [Conda](https://anaconda.org/conda-forge/osqp) (📥 760K · ⏱️ 06.10.2023):
	```
	conda install -c conda-forge osqp
	```
</details>
<details><summary><b><a href="https://www.scipopt.org/">PySCIPOpt</a></b> (🥇30 ·  ⭐ 720) - Python interface for SCIP. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scipopt/PySCIPOpt) (👨‍💻 67 · 🔀 240 · 📦 140 · 📋 480 - 5% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/scipopt/PySCIPOpt
	```
- [PyPi](https://pypi.org/project/PySCIPOpt) (📥 12K / month · 📦 14 · ⏱️ 08.12.2023):
	```
	pip install PySCIPOpt
	```
- [Conda](https://anaconda.org/conda-forge/pyscipopt) (📥 210K · ⏱️ 15.12.2023):
	```
	conda install -c conda-forge pyscipopt
	```
</details>
<details><summary><b><a href="https://highs.dev/">HiGHS</a></b> (🥈29 ·  ⭐ 740) - Large-scale Sparse Linear Problem Optimizer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ERGO-Code/HiGHS) (👨‍💻 60 · 🔀 140 · 📦 60 · 📋 560 - 13% open · ⏱️ 29.01.2024):

	```
	git clone https://github.com/ERGO-Code/HiGHS
	```
- [PyPi](https://pypi.org/project/highspy) (📥 35K / month · 📦 5 · ⏱️ 15.12.2022):
	```
	pip install highspy
	```
- [Conda](https://anaconda.org/conda-forge/highs) (📥 2.7K · ⏱️ 29.09.2023):
	```
	conda install -c conda-forge highs
	```
</details>
<details><summary><b><a href="https://github.com/cvxgrp/scs">SCS</a></b> (🥈27 ·  ⭐ 510) - Splitting Conic Solver. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cvxgrp/scs) (👨‍💻 27 · 🔀 130 · 📋 170 - 20% open · ⏱️ 30.12.2023):

	```
	git clone https://github.com/cvxgrp/scs
	```
- [PyPi](https://pypi.org/project/scs) (📥 860K / month · 📦 77 · ⏱️ 22.11.2023):
	```
	pip install scs
	```
- [Conda](https://anaconda.org/conda-forge/scs) (📥 760K · ⏱️ 08.02.2024):
	```
	conda install -c conda-forge scs
	```
</details>
<details><summary><b><a href="https://github.com/coin-or/Ipopt">Ipopt</a></b> (🥈26 ·  ⭐ 1.2K · 📉) - COIN-OR Interior Point Optimizer. <code><a href="http://bit.ly/2M0xmjV">EPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/coin-or/Ipopt) (👨‍💻 30 · 🔀 250 · 📥 11K · 📋 570 - 0% open · ⏱️ 18.01.2024):

	```
	git clone https://github.com/coin-or/Ipopt
	```
- [PyPi](https://pypi.org/project/ipopt) (📥 1.5K / month · 📦 7 · ⏱️ 07.04.2021):
	```
	pip install ipopt
	```
- [Conda](https://anaconda.org/conda-forge/ipopt) (📥 1M · ⏱️ 19.01.2024):
	```
	conda install -c conda-forge ipopt
	```
</details>
<details><summary><b><a href="https://github.com/embotech/ecos">ECOS</a></b> (🥈26 ·  ⭐ 430 · 💤) - Conic solver for second-order cone programming. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/embotech/ecos) (👨‍💻 39 · 🔀 120 · 📋 160 - 40% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/embotech/ecos
	```
- [PyPi](https://pypi.org/project/ecos) (📥 660K / month · 📦 84 · ⏱️ 07.02.2024):
	```
	pip install ecos
	```
- [Conda](https://anaconda.org/conda-forge/ecos) (📥 680K · ⏱️ 07.02.2024):
	```
	conda install -c conda-forge ecos
	```
</details>
<details><summary><b><a href="https://github.com/coin-or/Cbc">CBC</a></b> (🥉24 ·  ⭐ 700 · 📈) - COIN-OR Branch-and-Cut solver. <code><a href="http://bit.ly/2M0xmjV">EPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/coin-or/Cbc) (👨‍💻 29 · 🔀 100 · 📥 18K · 📋 470 - 26% open · ⏱️ 21.01.2024):

	```
	git clone https://github.com/coin-or/Cbc
	```
- [Conda](https://anaconda.org/conda-forge/coincbc) (📥 920K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge coincbc
	```
</details>
<details><summary><b><a href="https://ampl.com/">AMPLPY</a></b> (🥉23 ·  ⭐ 60) - Python API for AMPL. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ampl/amplpy) (👨‍💻 8 · 🔀 19 · 📦 59 · 📋 46 - 2% open · ⏱️ 26.01.2024):

	```
	git clone https://github.com/ampl/amplpy
	```
- [PyPi](https://pypi.org/project/amplpy) (📥 13K / month · 📦 3 · ⏱️ 05.01.2024):
	```
	pip install amplpy
	```
- [Conda](https://anaconda.org/conda-forge/amplpy) (📥 200K · ⏱️ 29.12.2023):
	```
	conda install -c conda-forge amplpy
	```
</details>
<details><summary><b><a href="https://github.com/oxfordcontrol/Clarabel.rs">Clarabel.rs</a></b> (🥉21 ·  ⭐ 210) - Interior-point solver for convex conic optimisation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/oxfordcontrol/Clarabel.rs) (👨‍💻 5 · 🔀 15 · 📦 5 · 📋 18 - 55% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/oxfordcontrol/Clarabel.rs
	```
- [PyPi](https://pypi.org/project/clarabel) (📥 590K / month · 📦 11 · ⏱️ 20.09.2023):
	```
	pip install clarabel
	```
- [Conda](https://anaconda.org/conda-forge/clarabel) (📥 18K · ⏱️ 12.10.2023):
	```
	conda install -c conda-forge clarabel
	```
</details>
<details><summary><b><a href="https://github.com/PREDICT-EPFL/piqp">PIQP</a></b> (🥉16 ·  ⭐ 46) - Proximal Interior Point Quadratic Programming solver. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PREDICT-EPFL/piqp) (👨‍💻 1 · 🔀 6 · 📥 29 · 📦 5 · 📋 5 - 60% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/PREDICT-EPFL/piqp
	```
- [PyPi](https://pypi.org/project/piqp) (📥 5K / month · 📦 5 · ⏱️ 25.12.2023):
	```
	pip install piqp
	```
- [Conda](https://anaconda.org/conda-forge/piqp) (📥 9.3K · ⏱️ 25.12.2023):
	```
	conda install -c conda-forge piqp
	```
</details>
<details><summary><b><a href="https://github.com/oxfordcontrol/Clarabel.jl">Clarabel.jl</a></b> (🥉14 ·  ⭐ 140) - Interior-point solver for convex conic optimisation in Julia. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/oxfordcontrol/Clarabel.jl) (👨‍💻 11 · 🔀 15 · 📋 41 - 7% open · ⏱️ 03.10.2023):

	```
	git clone https://github.com/oxfordcontrol/Clarabel.jl
	```
</details>
<br>

## Optimization Modeling Language

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/cvxpy/cvxpy">CVXPY</a></b> (🥇37 ·  ⭐ 4.9K) - Convex optimization modeling language. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cvxpy/cvxpy) (👨‍💻 180 · 🔀 1K · 📥 310 · 📦 11K · 📋 1.4K - 13% open · ⏱️ 04.02.2024):

	```
	git clone https://github.com/cvxpy/cvxpy
	```
- [PyPi](https://pypi.org/project/cvxpy) (📥 860K / month · 📦 420 · ⏱️ 22.01.2024):
	```
	pip install cvxpy
	```
- [Conda](https://anaconda.org/conda-forge/cvxpy) (📥 930K · ⏱️ 20.01.2024):
	```
	conda install -c conda-forge cvxpy
	```
</details>
<details><summary><b><a href="https://www.pyomo.org">Pyomo</a></b> (🥈36 ·  ⭐ 1.8K) - Python-based Optimization Modeling Language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ml-tooling/best-of-ml-python/main/config/images/jupyter.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Pyomo/pyomo) (👨‍💻 140 · 🔀 460 · 📥 2K · 📦 1.7K · 📋 1.3K - 24% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/Pyomo/pyomo
	```
- [PyPi](https://pypi.org/project/Pyomo) (📥 330K / month · 📦 190 · ⏱️ 30.11.2023):
	```
	pip install Pyomo
	```
- [Conda](https://anaconda.org/conda-forge/pyomo) (📥 800K · ⏱️ 30.11.2023):
	```
	conda install -c conda-forge pyomo
	```
</details>
<details><summary><b><a href="https://jump.dev">JuMP</a></b> (🥈26 ·  ⭐ 2.1K) - Julia-based Optimization Modeling Language. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ml-tooling/best-of-ml-python/main/config/images/jupyter.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jump-dev/JuMP.jl) (👨‍💻 150 · 🔀 380 · 📋 1.5K - 5% open · ⏱️ 07.02.2024):

	```
	git clone https://github.com/jump-dev/JuMP.jl
	```
</details>
<details><summary><b><a href="https://cvxopt.org/">CVXOPT</a></b> (🥉25 ·  ⭐ 940) - Python Software for Convex Optimization. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cvxopt/cvxopt) (👨‍💻 8 · 🔀 200 · 📦 9K · 📋 180 - 20% open · ⏱️ 09.08.2023):

	```
	git clone https://github.com/cvxopt/cvxopt
	```
- [PyPi](https://pypi.org/project/cvxopt) (📥 340K / month · 📦 680 · ⏱️ 09.08.2023):
	```
	pip install cvxopt
	```
- [Conda](https://anaconda.org/conda-forge/cvxopt) (📥 910K · ⏱️ 23.09.2023):
	```
	conda install -c conda-forge cvxopt
	```
</details>
<details><summary><b><a href="https://github.com/XiongPengNUS/rsome">RSOME</a></b> (🥉17 ·  ⭐ 240 · ➕) - Robust Stochastic Optimization Made Easy. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/XiongPengNUS/rsome) (👨‍💻 3 · 🔀 50 · 📋 38 - 13% open · ⏱️ 19.01.2024):

	```
	git clone https://github.com/XiongPengNUS/rsome
	```
- [PyPi](https://pypi.org/project/rsome) (📥 820 / month · 📦 1 · ⏱️ 19.01.2024):
	```
	pip install rsome
	```
</details>
<details><summary><b><a href="https://github.com/sanurielf/kvxopt">KVXOPT</a></b> (🥉15 ·  ⭐ 10 · ➕) - CVXOPT with more wrappers suite-sparse. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sanurielf/kvxopt) (👨‍💻 18 · 🔀 1 · 📦 19 · 📋 7 - 14% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/sanurielf/kvxopt
	```
- [PyPi](https://pypi.org/project/kvxopt) (📥 6.1K / month · 📦 4 · ⏱️ 16.10.2023):
	```
	pip install kvxopt
	```
- [Conda](https://anaconda.org/conda-forge/kvxopt) (📥 96K · ⏱️ 05.02.2024):
	```
	conda install -c conda-forge kvxopt
	```
</details>
<br>

## Machine/Reinforcement Learning for Power Grid

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://l2rpn.chalearn.org/">Grid2Op</a></b> (🥇26 ·  ⭐ 250) - Modeling sequential decision making in power systems. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ml-tooling/best-of-ml-python/main/config/images/jupyter.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rte-france/Grid2Op) (👨‍💻 31 · 🔀 110 · 📋 330 - 11% open · ⏱️ 26.01.2024):

	```
	git clone https://github.com/rte-france/Grid2Op
	```
- [PyPi](https://pypi.org/project/Grid2Op) (📥 2.3K / month · 📦 10 · ⏱️ 26.01.2024):
	```
	pip install Grid2Op
	```
- [Docker Hub](https://hub.docker.com/r/bdonnot/grid2op) (📥 9.7K · ⭐ 1 · ⏱️ 05.07.2022):
	```
	docker pull bdonnot/grid2op
	```
</details>
<details><summary><b><a href="https://github.com/RLGC-Project/RLGC">RLGC</a></b> (🥉9 ·  ⭐ 100 · 💤) - RL for Grid Control (RLGC). <code><a href="https://tldrlegal.com/search?q=BSD">❗️BSD</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://raw.githubusercontent.com/ml-tooling/best-of-ml-python/main/config/images/jupyter.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RLGC-Project/RLGC) (👨‍💻 4 · 🔀 27 · 📋 15 - 33% open · ⏱️ 08.04.2022):

	```
	git clone https://github.com/RLGC-Project/RLGC
	```
</details>
<details><summary><b><a href="https://github.com/cuihantao/andes_gym">andes_gym</a></b> (🥉5 ·  ⭐ 7 · 💤) - ANDES RL Environment for OpenAI Gym. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cuihantao/andes_gym) (👨‍💻 2 · 🔀 4 · ⏱️ 28.01.2022):

	```
	git clone https://github.com/cuihantao/andes_gym
	```
</details>
<br>

## Co-Simulation Environment

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Co-Simulation Environment for Modeling and Simulation_

<details><summary><b><a href="https://openmodelica.org">OpenModelica</a></b> (🥇27 ·  ⭐ 700) - Modelica-based environment for modeling and simulation. <code><a href="https://modelica.org/licenses/ModelicaLicense2/">❗️Custom</a></code></summary>

- [GitHub](https://github.com/OpenModelica/OpenModelica) (👨‍💻 190 · 🔀 280 · 📥 360 · 📋 7.5K - 24% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/OpenModelica/OpenModelica
	```
- [Docker Hub](https://hub.docker.com/r/openmodelica/openmodelica) (📥 35K · ⭐ 5 · ⏱️ 15.12.2023):
	```
	docker pull openmodelica/openmodelica
	```
</details>
<details><summary><b><a href="https://precice.org/">precice</a></b> (🥉25 ·  ⭐ 640) - Precise Code Interaction Coupling Environment. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/precice/precice) (👨‍💻 55 · 🔀 160 · 📥 23K · 📋 820 - 24% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/precice/precice
	```
- [PyPi](https://pypi.org/project/pyprecice) (📥 520 / month · 📦 1 · ⏱️ 06.02.2024):
	```
	pip install pyprecice
	```
- [Conda](https://anaconda.org/conda-forge/pyprecice) (📥 17K · ⏱️ 07.02.2024):
	```
	conda install -c conda-forge pyprecice
	```
- [Docker Hub](https://hub.docker.com/r/precice/precice) (📥 15K · ⏱️ 08.02.2024):
	```
	docker pull precice/precice
	```
</details>
<br>

## Gas

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Gas Network Simulation_

<details><summary><b><a href="https://www.pandapipes.org/">pandapipes</a></b> (🥇23 ·  ⭐ 110) - Pipeflow Calculation Tool. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/e2nIEE/pandapipes) (👨‍💻 20 · 🔀 49 · 📦 18 · 📋 130 - 39% open · ⏱️ 22.12.2023):

	```
	git clone https://github.com/e2nIEE/pandapipes
	```
- [PyPi](https://pypi.org/project/pandapipes) (📥 2.3K / month · 📦 2 · ⏱️ 22.12.2023):
	```
	pip install pandapipes
	```
</details>
<details><summary><b><a href="https://github.com/lanl-ansi/GasModels.jl">GasModels.jl</a></b> (🥉15 ·  ⭐ 62) - Gas Network Optimization. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lanl-ansi/GasModels.jl) (👨‍💻 13 · 🔀 15 · 📋 150 - 32% open · ⏱️ 31.01.2024):

	```
	git clone https://github.com/lanl-ansi/GasModels.jl
	```
</details>
<br>

## Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://www.powsybl.org">PowSyBl Diagram</a></b> (🥇23 ·  ⭐ 110 · ➕) - single-line substation diagrams and network graph.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/powsybl/powsybl-core) (👨‍💻 99 · 🔀 37 · 📥 95 · 📦 74 · 📋 530 - 44% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/powsybl/powsybl-core
	```
</details>
<details><summary><b><a href="https://www.nrel.gov/analysis/sienna.html">PowerGraphics.jl</a></b> (🥉14 ·  ⭐ 23 · ➕) - Visualization for PowerSimulations; NREL Sienna. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NREL-Sienna/PowerGraphics.jl) (👨‍💻 9 · 🔀 9 · 📋 36 - 41% open · ⏱️ 16.09.2023):

	```
	git clone https://github.com/NREL-Sienna/powergraphics.jl
	```
</details>
<details><summary><b><a href="https://ltb.curent.org/">LTB AGVis</a></b> (🥉8 ·  ⭐ 5) - Geographical Visualization for Power Grid; CURENT LTB. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/CURENT/agvis) (👨‍💻 9 · 🔀 6 · 📥 9 · 📋 24 - 54% open · ⏱️ 20.01.2024):

	```
	git clone https://github.com/CURENT/agvis
	```
</details>
<br>

## Messaging Environment

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://helics.org/tools/">HELICS</a></b> (🥇23 ·  ⭐ 110 · 📈) - Data exchange among diverse simulators across platforms. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GMLC-TDC/HELICS) (👨‍💻 38 · 🔀 37 · 📥 20K · 📋 640 - 12% open · ⏱️ 07.02.2024):

	```
	git clone https://github.com/GMLC-TDC/HELICS
	```
- [PyPi](https://pypi.org/project/helics) (📥 3.2K / month · 📦 5 · ⏱️ 06.07.2022):
	```
	pip install helics
	```
- [Conda](https://anaconda.org/conda-forge/helics) (📥 20K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge helics
	```
</details>
<details><summary><b><a href="https://ltb.curent.org/">LTB DiME</a></b> (🥉8 ·  ⭐ 4) - Distributed Messaging Environment; CURENT LTB. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/CURENT/dime) (👨‍💻 4 · 🔀 3 · 📋 48 - 27% open · ⏱️ 31.07.2023):

	```
	git clone https://github.com/CURENT/dime
	```
</details>
<br>

## Power System Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://ourworldindata.org/energy">Data on Energy</a></b> ( ⭐ 240)  - Data on energy by Our World in Data. <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>

🔗&nbsp;<b><a href="https://github.com/tamu-engineering-research/COVID-EMDA">COVID-EMDA</a></b> ( ⭐ 57)  - Cross-Domain Data Hub with Data in USA. <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>

<details><summary><b><a href="https://pypsa.org">Atlite</a></b> (🥇24 ·  ⭐ 230) - Calculating Renewable Power Potentials. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyPSA/atlite) (👨‍💻 29 · 🔀 73 · 📦 47 · 📋 110 - 23% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/PyPSA/atlite
	```
- [PyPi](https://pypi.org/project/atlite) (📥 4K / month · ⏱️ 25.10.2023):
	```
	pip install atlite
	```
- [Conda](https://anaconda.org/conda-forge/atlite) (📥 41K · ⏱️ 25.10.2023):
	```
	conda install -c conda-forge atlite
	```
</details>
<details><summary><b><a href="https://pypsa.org">powerplantmatching</a></b> (🥈22 ·  ⭐ 130) - Tools to combine multiple power plant databases. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyPSA/powerplantmatching) (👨‍💻 22 · 🔀 47 · 📥 52 · 📦 38 · 📋 80 - 31% open · ⏱️ 07.02.2024):

	```
	git clone https://github.com/PyPSA/powerplantmatching
	```
- [PyPi](https://pypi.org/project/powerplantmatching) (📥 920 / month · ⏱️ 07.02.2024):
	```
	pip install powerplantmatching
	```
- [Conda](https://anaconda.org/conda-forge/powerplantmatching) (📥 30K · ⏱️ 07.02.2024):
	```
	conda install -c conda-forge powerplantmatching
	```
</details>
<details><summary><b><a href="https://www.gridstatus.io">GridStatus</a></b> (🥉21 ·  ⭐ 220 · ➕) - Extract data from ISOs and other sources. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kmax12/gridstatus) (👨‍💻 17 · 🔀 34 · 📦 6 · 📋 110 - 57% open · ⏱️ 07.02.2024):

	```
	git clone https://github.com/kmax12/gridstatus
	```
- [PyPi](https://pypi.org/project/gridstatus) (📥 4.6K / month · 📦 1 · ⏱️ 27.12.2023):
	```
	pip install gridstatus
	```
</details>
<details><summary><b><a href="https://deepsolar.web.app">DeepSolar</a></b> (🥉9 ·  ⭐ 240 · 💤) - Houseshold-level solar panel identification with deep learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/wangzhecheng/DeepSolar) (👨‍💻 2 · 🔀 65 · 📋 17 - 76% open · ⏱️ 26.03.2019):

	```
	git clone https://github.com/wangzhecheng/DeepSolar
	```
</details>
<details><summary><b><a href="https://github.com/enliten/ENLITEN-Grid-Econ-Data">WECC-and-NPCC-Electricity-Economic-Data</a></b> (🥉4 ·  ⭐ 5 · ➕) - Economic data on WECC and NPCC. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/enliten/ENLITEN-Grid-Econ-Data) (👨‍💻 3 · 🔀 2 · ⏱️ 06.09.2023):

	```
	git clone https://github.com/enliten/ENLITEN-Grid-Econ-Data
	```
</details>
<br>

## Power Electronics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/gseim/gseim">GSEIM</a></b> (🥇7 ·  ⭐ 8) - Interface Python to Ngspice and Xyce. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gseim/gseim) (👨‍💻 3 · 🔀 3 · 📋 6 - 33% open · ⏱️ 19.08.2023):

	```
	git clone https://github.com/gseim/gseim
	```
- [PyPi](https://pypi.org/project/GSEIM) (📥 9 / month · ⏱️ 16.07.2022):
	```
	pip install GSEIM
	```
</details>


---

## Project Popularity Score

- Has homepage link & description: `+ 1`
- Has an existing GitHub repository: `+ 1`
- Has a license: `+ 1`
- Has a commonly used license (e.g. MIT): `+ 1`
- Has multiple releases: `+ 1`
- Has stable releases based on semantic version: `+ 1`
- Has a release that is less than 6 months old: `+ 1`
- Repo was update in the last 3 months: `+ 1`
- Is older than 6 months: `+ 1`
- Metrics from GitHub & package mangers:
  - Number of stars: `+ log(COUNT / 2)`
  - Number of contributors: `+ log(COUNT / 2) - 1`
  - Number of commits: `+ log(COUNT / 2) - 1`
  - Number of forks: `+ log(COUNT / 2)`
  - Number of monthly downloads: `+ log(COUNT / 2) - 1`
  - Number of dependent projects: `+ log(COUNT / 1.5)`
  - Number of watchers: `+ log(COUNT / 2) - 1`
  - Number of closed issues: `+ log(COUNT / 2) - 1`

**NOTE**: This calculation is just chosen by ***EXPERIENCE***. There is ***NO*** scientific proof that this really reflects the ***QUALITY*** of a project.

## Project Data Collection

The data collection can be deficient for the projects that are not majorly hosted in GitHub.

## Related Resources

- [G-PST Tools Portal](https://g-pst.github.io/tools/): An open tools portal with a classification approach
- [Open Source Software (OSS) for Electricity Market Research, Teaching, and Training](https://www2.econ.iastate.edu/tesfatsi/ElectricOSS.htm)
- [Papers With Code](https://paperswithcode.com): Discover ML papers, code, and evaluation tables.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/jinningwang/best-of-ps/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/jinningwang/best-of-ps/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/jinningwang/best-of-ps/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/jinningwang/best-of-ps/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/jinningwang/best-of-ps/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
