# Hi, I'm Konstantin Nomerotski

I build software at the intersection of **computational chemistry, scientific computing, and data science**. My background is in chemistry with scientific computing, and my work ranges from spectroscopy and molecular simulation to distributed processing and full-stack applications.

I'm especially interested in turning scientific methods into practical tools: connecting calculations, managing their results, and making complex workflows easier to use.

## Ligand-X — computational drug discovery on your own hardware

My main project is **[Ligand-X](https://www.ligand-x.com)**, a self-hosted platform that brings molecular modeling, simulation, and drug-discovery workflows into one application. It connects structure preparation, screening, simulation, and molecular design through shared projects, a molecule library, interactive visualization, and workflow orchestration.

<a href="https://www.ligand-x.com">
  <img src="https://raw.githubusercontent.com/kon-218/ligand-x-launcher/main/docs/images/ligand-x-app-ui.png" alt="Ligand-X computational chemistry application" width="900" />
</a>

The platform spans:

- **Prepare and explore:** protein structure preparation, binding-pocket detection, molecule editing, structure alignment, and multiple sequence alignment.
- **Screen and evaluate:** molecular docking with AutoDock Vina, ADMET prediction, and Boltz-2 binding-affinity prediction.
- **Simulate and characterize:** molecular dynamics with OpenMM, absolute and relative binding free energy with OpenFE, and quantum chemistry with ORCA, including DFT and NEA UV–Vis spectroscopy.
- **Design:** generative molecular design with REINVENT4, connected to the wider modeling workflow.

Building Ligand-X brings together the scientific methods and the software around them: a Python/FastAPI backend, a TypeScript/Next.js interface, asynchronous execution with Celery, containerized scientific environments, and a Go/Wails desktop launcher that installs and manages the local runtime.

**[Website](https://www.ligand-x.com)** · **[Desktop launcher](https://github.com/kon-218/ligand-x-launcher)** · **[Downloads](https://github.com/kon-218/ligand-x-launcher/releases/latest)** · **[Support & discussions](https://github.com/kon-218/ligand-x-support)**

## Other projects

| Project | What I worked on |
| --- | --- |
| **[LaunchNEM](https://github.com/kon-218/LaunchNEM)** | Workflows for nuclear ensemble spectroscopy: launching ORCA calculations from sampled geometries, processing UV–Vis spectra, representative sampling, and postprocessing with SLURM support. |
| **[ATLAS cloud processing](https://github.com/kon-218/ATLAS-cloud-processing)** | Distributed processing of ATLAS public data using Docker Swarm, with RabbitMQ for communication and a web interface for results. |
| **[Accelerating the Lebwohl–Lasher model](https://github.com/kon-218/Accelerating_Lebwohl_Lasher)** | Exploring ways to accelerate a Python liquid-crystal simulation, including Cython, MPI, and SLURM batch execution. |
| **[Wine investigation](https://github.com/kon-218/wine_investigation)** | Applying logistic regression and Bayesian inference to wine classification and quality prediction. |

## Tools and interests

- **Scientific computing:** Python, molecular simulation, quantum chemistry, spectroscopy, and data analysis.
- **Application development:** TypeScript, React/Next.js, FastAPI, Go, and Wails.
- **Compute and infrastructure:** Docker, Celery, PostgreSQL, RabbitMQ, Cython, MPI, and SLURM.

You can find more about my work on my **[portfolio, blog, and CV](https://kon-218.github.io)**.
