# About

Physics simulation is a core topic in visual computing, with applications in
virtual prototyping, training simulators, robotics, visual effects for film,
and computer games.

This page collects **interactive examples** that explain the main methods
step by step. Each example runs directly in your browser, so there is nothing
to install, and comes with a short explanation of the underlying theory. You
can change parameters and watch how the simulation reacts.

The examples were written for my [lectures](https://animation.rwth-aachen.de/courses/)
at [RWTH Aachen University](https://www.rwth-aachen.de). They cover:

* **Numerical foundations:** finite differences, numerical and time integration, linear solvers and Newton's method
* **Particles and rigid bodies:** particle systems, quaternions and impulse-based collision handling
* **Deformable solids:** mass-spring systems, the Finite Element Method (FEM), and impulse- and position-based methods (IBDS, PBD, XPBD, shape matching)
* **Fluids:** Smoothed Particle Hydrodynamics (SPH)
* **Collision detection:** broad-phase methods, the Lin-Canny and GJK algorithms, and signed distance fields

**New to the topic?** Start with *Numerical Foundations*; the later sections
build on it.

**Teaching a course?** You are welcome to use the examples. The source code is
available on [GitHub](https://github.com/InteractiveComputerGraphics/physics-simulation)
under the [MIT license](https://github.com/InteractiveComputerGraphics/physics-simulation/blob/main/LICENSE).

## Tutorials

For a deeper introduction to specific topics, see our tutorials:

* [Position-Based Dynamics (PBD)](https://animation.rwth-aachen.de/publication/0553/)
* [Smoothed Particle Hydrodynamics (SPH)](https://sph-tutorial.physics-simulation.org)
* [Multiphysics simulation](https://multi.physics-simulation.org/)
* [Further tutorials](https://www.physicsbasedanimation.com/resources-courses/)

# Examples

## Numerical Foundations

### Basics

* [Barycentric coordinates](examples/barycentric_coordinates.html)
* [Finite differences](examples/finite_differences.html)
* [Numerical integration](examples/numerical_integration.html)
* [Quaternion rotation](examples/quaternion_rotation.html)
* [Heat equation](examples/heat_equation.html)

### Time Integration

* [Explicit time integration methods](examples/time_integration.html): comparison for a constant force
* [Explicit and implicit time integration methods](examples/spring_plot.html): comparison for a spring model
* [Energy conservation of a spring-damper model](examples/spring_damper.html)

### Linear Systems

* [LU decomposition](examples/LU_decomposition.html)
* [Jacobi, Gauss-Seidel and SOR methods](examples/Jacobi_GaussSeidel_SOR.html)

### Newton's Method

* [Newton's method](examples/Newton_solver.html)
* [Newton's method for minimization (1D)](examples/Newton_minimization.html)
* [Newton's method for minimization (2D)](examples/Newton_minimization_2D.html)
* [Newton's method with backtracking line search](examples/Newton_with_backtracking_line_search.html)
* [Newton's method: the saddle point problem](examples/Newton_saddle_3D.html)

## Particles and Rigid Bodies

* [Particle system](examples/particle_system.html): a simple particle system
* [Rigid body emitter](examples/particle_system_rb.html): an emitter that emits rigid bodies with rotation and angular velocity
* [Impulse-based collision handling for rigid bodies](examples/rigid_body_collision.html)

## Deformable Solids

### Force-Based Methods

* [Mass-spring system](examples/mass_spring_system.html)
* [Deformation gradient and strain tensor](examples/deformation_gradient_strain.html)
* [FEM: corotated linear elasticity](examples/FEM_Corot.html)
* [FEM: St. Venant-Kirchhoff model](examples/FEM_StVK.html)
* [FEM: Neo-Hookean model](examples/FEM_Neohookean.html)

### Constraint-Based Methods

* [Impulse-Based Dynamic Simulation (IBDS)](examples/ibds.html)
* [Position-Based Dynamics (PBD)](examples/pbd.html)
* [Extended Position-Based Dynamics (XPBD)](examples/xpbd.html)
* [Shape matching](examples/shape_matching.html)
* [Region-based shape matching](examples/region_based_shape_matching.html)

## Fluids (SPH)

### SPH Basics

* [Kernel functions and their derivatives](examples/sph_kernel.html)
* [SPH approximation of different functions](examples/sph_approximation.html): the benefit of a Shepard filter
* [SPH approximation of a user-defined function](examples/sph_approximation_user_fct.html): the benefit of a Shepard filter
* [SPH gradient approximation](examples/sph_gradient_approximation.html): a quadratic function and the benefit of a kernel gradient correction
* [Neighborhood search](examples/neighborhood_search.html)

### SPH Simulation Methods

* [Weakly Compressible SPH (WCSPH)](examples/wcsph.html)
* [Position-Based Fluids (PBF)](examples/pbf.html)
* [Implicit Incompressible SPH (IISPH)](examples/iisph.html)
* [Divergence-Free SPH (DFSPH)](examples/dfsph.html)

## Collision Detection

### Broad Phase

* [Bounding volumes](examples/bounding_volumes.html)
* [Sweep and prune for AABB overlap tests](examples/sweep_and_prune.html)
* [Bounding volume hierarchy (BVH)](examples/bvh.html)
* [Spatial hashing](examples/spatial_hashing.html)

### Narrow Phase: Rigid Bodies

* [Lin-Canny algorithm](examples/lin_canny.html)
* [GJK algorithm](examples/gjk.html)

### Signed Distance Fields (SDFs)

* Signed distance functions: [sphere](examples/sdf_sphere_plot.html), [box](examples/sdf_box_plot.html)
* [Signed distance field](examples/signed_distance_field.html)
