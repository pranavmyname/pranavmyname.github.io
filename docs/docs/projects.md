---
title: Projects
layout: default
nav_order: 2
---
{: .note }
> Click on the title of the project to read the project report

## [Master's Thesis:  Identification of Quasi-Normal Modes in Wavefield Imaging](files/Thesis.pdf)
Quasi-Normal Modes (QNMs) are a key concept in reduced-order models. In this thesis, we use Finite-Difference approach to create a discretized model of an open electromagnetic system in order to identify its QNMs and the Perfectly Matched Layer (PML) modes. We develop a structure of the QNMs and the PML modes and identify different regions of the eigenvalue distribution in our system. We validate the idea of dominant QNMs by using the identified QNMs to get the solution that was obtained using the Finite-Difference method. [Click here to access the thesis presentation](files/thesis_presentation.pdf)

{: .highlight  }
> Thesis presentation contains animation which only works on Adobe PDF and not in the web browser

## [Adaptive Optics System](files/adaptive_optics.pdf)
Used adaptive control strategies to dynamically focus a source of light which was phase aberrated using a rotating transparent disc. Control inputs were the voltages to a deformable-mirror with feedback from a Shack-Hartman wavefront sensor. It involved identification of the system parameters and controlling the voltages such that the error between phase of incoming light and deformable mirror is minimized to give a sharp focused image.

## [Magnetic Manipulator](files/magman.pdf)
Used system identification and non-linear control approach to track a reference trajectory in one dimension for a metallic ball controlled by four solenoids through magnetic forces.
- Developed a model for the system
- Identified system parameters and viscous friction coefficient in the developed model
- Implemented a Kalman filter state observer
- Used feedback linearization followed by three different approaches : pole placement, PID and Model Reference Adaptive Control (MRAC)
- Implemented Gain Scheduling controller: Linearization followed by pole placement at different operating points