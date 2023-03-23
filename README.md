
# Aerospace Kinematics - Describing The Motions of Spacecraft.

#### **1)** Mapping Euler angles to the directional cosine matrix (DCM)
- Rudimentary mappings of the 12 pragmatic "yaw-pitch-roll" or Euler angles to their corresponding DCMs.
#### **2)** Quaternion (Euler parameter) attitude description.
- Mappings from sets of given Quaternion coordinates to the DCM.
- Inverse mappings from the DCM to the Quaternion set using Stanley's algorithm.
- Quaternion addition and subtraction.
- Solving the Quaternion kinematic differential equations utilising a Runge-Kutte 4 (RK4) integrator.
#### **3)** The Classial Rodrigues Parameters (CRPs).
- Mappings from a set of CRPs to the DCM.
- Inverse mappings from the DCM to the CRPs.
- Solving the CRP kinematic differential equations utilising and RK4 integrator.
#### **4)** The Modified Rodrigues Parameters (MRPs).
- Mappings from a set of MRPs to the DCM.
- Inverse mappings from the DCM to the MRPs.
- Solving the MRP kinematic differential equations utilising and RK4 integrator.
#### **5)** Methods for spacecraft attitude determination.
- The TRIAD method.
- Devenport's q method.
- QUEST method.
- Optimal Linear Attitude Estimator (OLAE)
