# About

Physics simulation is an important research topic in visual computing. It has many applications ranging from such as virtual prototyping, training simulators, robotics, animation software for digital production including visual effects in film and animation movies, and computer games – just to mention a few.

At [RWTH Aachen university](https://animation.rwth-aachen.de) I offer [lectures](https://animation.rwth-aachen.de/courses/) which give an introduction to state-of-the-art simulation methods for rigid bodies, deformable solids and fluids in the area of visual computing (e.g, the Finite Element Method (FEM) and the [Smoothed Particle Hydrodynamics (SPH)](https://interactivecomputergraphics.github.io/SPH-Tutorial/) approach). For the lectures I programmed several simulation examples using JavaScript.  

Why JavaScript? Because everybody can directly run the examples in the browser. Moreover, I was able to add a short web page for each example which explains the method. 

I hope the examples and their documentation help you to learn something about the simulation methods. Feel free to use the examples in your own courses. 

# Particles

* [A simple particle system](examples/particle_system.html)
* [A simple particle system where each particle is represented by a rigid body with a rotation and an angular velocity](examples/particle_system_rb.html)

# Time Integration

* [Comparison of different explicit time integration methods for a constant force](examples/time_integration.html)
* [Comparison of different explicit and implicit time integration methods for a spring model](examples/spring_plot.html)
* [Energy conservation of a spring-damper model](examples/spring_damper.html)

# Deformable Solids

### Mass Spring System

* [Mass Spring System](examples/mass_spring_system.html)

### Continuum Mechanics

* [Computation of deformation gradient and strain tensor](examples/deformation_gradient_strain.html)
* [Finite Element Method (FEM) - Corotated Linear Elasticity Model](examples/FEM_Corot.html)
* [Finite Element Method (FEM) - St. Venant-Kirchhoff Model](examples/FEM_StVK.html)
* [Finite Element Method (FEM) - Neohookean Elasticity Model](examples/FEM_Neohookean.html)

### Position-Based Dynamics

* [Position-Based Dynamics (PBD)](examples/pbd.html)
* [eXtended Position-Based Dynamics (XPBD)](examples/xpbd.html)

# Fluids

### SPH Simulation Methods

* [Weakly Compressible SPH (WCSPH)](examples/wcsph.html)
* [Position Based Fluids (PBF)](examples/pbf.html)
* [Implicit Incompressible SPH (IISPH)](examples/iisph.html)
* [Divergence-Free SPH (DFSPH)](examples/dfsph.html)

### Neighborhood Search

* [Neighborhood search](examples/neighborhood_search.html)

### SPH Kernel

* [Different kernel functions and their derivatives](examples/sph_kernel.html)

### SPH Approximation

* [The SPH approximation of different functions and the benefit of a Shepard filter](examples/sph_approximation.html)
* [The SPH approximation of a user-defined function and the benefit of a Shepard filter](examples/sph_approximation_user_fct.html)
* [SPH approximation of the gradient of a quadratic function and the benefit of a kernel gradient correction](examples/sph_gradient_approximation.html)

# Collision Detection

### Signed Distance Fields (SDFs)

* [Signed distance function of a sphere](examples/sdf_sphere_plot.html)
* [Signed distance function of a box](examples/sdf_box_plot.html)