# Slider-Crank Linkage Mechanism

## 1. Project Overview

This project presents the design and 3D CAD assembly of a **Slider-Crank Linkage Mechanism** using Autodesk Inventor.

The slider-crank mechanism is a mechanical system designed to convert rotary motion into reciprocating linear motion, or vice versa. It consists of interconnected rigid links, rotational joints, and a sliding element that work together to produce controlled mechanical movement.

The assembly demonstrates fundamental mechanical engineering principles, including kinematics, motion transmission, mechanical constraints, and the interaction between rotating and translating components.

## 2. Purpose and Applications

The primary purpose of a slider-crank mechanism is to transform rotational movement into linear reciprocating movement.

It is commonly used in mechanical systems where continuous rotation must produce repetitive back-and-forth motion.

### Potential Applications

- **Internal combustion engines:** Converting the reciprocating motion of pistons into rotational motion at the crankshaft.
- **Reciprocating pumps:** Producing linear piston movement to move fluids.
- **Compressors:** Driving pistons to compress gases.
- **Mechanical presses:** Generating reciprocating movement for pressing operations.
- **Industrial machinery:** Transmitting motion between rotating and sliding components.
- **Automation systems:** Producing controlled linear movement from rotary actuators.

## 3. Mechanical Components

The assembly consists of four individually designed mechanical components and a complete assembly.

| Component | File | Function |
|---|---|---|
| Base | `base.ipt` | Provides structural support and the guide for the sliding component. |
| Arm Link | `arm_link.ipt` | Acts as the rotating crank or driving arm around the fixed pivot. |
| Connecting Link | `connecting_link.ipt` | Transfers movement and mechanical forces between the arm and slider. |
| Sliding Link | `sliding_link.ipt` | Provides linear reciprocating movement along the guide. |
| Main Assembly | `sliding_mechanism.iam` | Integrates all individual components into one mechanism. |
| Technical Drawing | `sliding_mechanism.idw` | Provides the engineering drawing representation of the assembly. |

## 4. Working Principle

The slider-crank mechanism operates through the interaction of rotational and linear movement.

Its operating principle can be described as follows:

1. **Rotational input:** The arm link rotates around its fixed pivot on the base.
2. **Motion transmission:** The connecting link transfers the movement from the rotating arm to the sliding component.
3. **Linear displacement:** The sliding link moves back and forth along the guide provided by the base.
4. **Continuous operation:** As the arm continues rotating, the connecting link drives the slider through repeated forward and backward movements.

The mechanism can also operate in reverse, where linear reciprocating movement drives the rotating arm.

## 5. Kinematic Principles

The mechanism demonstrates the relationship between angular and linear motion.

Its main mechanical joints include:

- **Revolute joints:** Allow rotational movement between connected links.
- **Prismatic joint:** Allows linear movement between the slider and its guide.
- **Fixed connection:** Establishes the stationary reference structure of the mechanism.

For an ideal slider-crank mechanism, the displacement of the slider depends on the crank angle, crank length, and connecting rod length.

The mechanism's motion is periodic, with one complete crank revolution producing one complete reciprocating cycle.

## 6. CAD Design and Assembly

The project was developed using **Autodesk Inventor**, following a component-based mechanical design approach.

The design workflow includes:

1. Creating the individual mechanical components as separate part files.
2. Modeling the base and its sliding guide.
3. Designing the rotating arm and connecting link.
4. Creating the sliding component.
5. Importing all components into the assembly environment.
6. Applying appropriate assembly constraints to establish the required mechanical relationships.
7. Integrating the components into the complete mechanism.
8. Preparing the technical drawing using Autodesk Inventor's drawing environment.

## 7. Engineering Concepts Demonstrated

This project demonstrates several fundamental mechanical engineering concepts:

- **Kinematics:** Analyzing the motion of interconnected mechanical components.
- **Motion conversion:** Transforming rotational movement into linear reciprocating movement.
- **Mechanical linkages:** Understanding the interaction between rigid links.
- **Revolute joints:** Modeling rotational connections between components.
- **Prismatic joints:** Modeling constrained linear movement.
- **Force transmission:** Understanding how mechanical forces pass through connected links.
- **CAD assembly constraints:** Defining component positions and permitted movements.
- **Technical drawing:** Representing mechanical designs through engineering drawings.

## 8. Software and Tools

| Software / Format | Purpose |
|---|---|
| Autodesk Inventor | 3D mechanical modeling and assembly design |
| IPT | Individual mechanical component files |
| IAM | Complete mechanical assembly |
| IDW | Engineering drawing documentation |

## 9. Project Objectives

The main objectives of this project are:

1. Design a functional slider-crank linkage using 3D CAD modeling.
2. Understand the relationship between rotary and reciprocating motion.
3. Develop individual mechanical components and integrate them into a complete assembly.
4. Apply mechanical joints and assembly constraints.
5. Explore the kinematic behavior of interconnected mechanical links.
6. Develop engineering drawing documentation for the designed mechanism.

## 10. Conclusion

The Slider-Crank Linkage Mechanism project demonstrates the application of mechanical design and kinematic principles in the development of a motion-conversion system.

By integrating a rotating arm, connecting link, sliding component, and supporting base, the project illustrates how mechanical linkages can convert rotational motion into controlled reciprocating linear movement.

The project provides practical experience in 3D mechanical modeling, assembly design, motion transmission, kinematic relationships, and technical drawing preparation.

## 11. Repository

**GitHub Repository:** [Slider-Crank Linkage Mechanism](https://github.com/CAD-Lawrenceak/Slider-Crank-Linkage-Mechanism)

**CAD Software:** Autodesk Inventor

**Project Type:** Mechanical Design, CAD Modeling, and Kinematic Assembly

**Date:** November 8, 2024

**Designed by:** Lawrence Abou Karroum

As a part of the CAD course at the university
